---
title: "New Learned Multi-Label Classification Challenge!"
usemathjax: true
permalink: /competition-entry/new-mlc-challenge/
---

This year we are excited to include a new challenge of learning **multi-label classification**.  In summary, a solver's task will be to predict optimal assignments to a subset of query variables given evidence that maximize a marginalization over the rest of the variables (similar to the [MMAP task](../competition-entry/tasks.md)).  In other words, the task is to *find the most-probable assignment to the query variables given an assignment of values to the evidence variables* for several Markov networks (separately) known ahead of time. <br/>

This challenge will have two phases: 
* an offline learning phase (for which you will use your own hardware)
* an online prediction phase (for which we will use our hardware to evaluate your solvers).


## Offline Training Phase

For the offline training phase, you will be provided with the following:
1. Several Markov networks in the UAI format
2. For each, a data set that contains:
    * A partition of the model's variables \\(X\\) into the following exclusive subsets:
        * observed or evidence variables \\(E\\)
        * query variables \\(Q\\) 
        * hidden variables \\(H\\)
    * 10,000 data lines, each containing:
        * an evidence assignment (ie. observation)
        * a corresponding query assignment
        * a value measuring the goodness of the query assignment given the evidence (ie. observation)
            * this value correpsponds to the log10 likelihood of the joint evidence-query assignment marginalizing over the hidden variables

During the training phase, you can use your own computational resources to compile each Markov
network and data to a relevant representation such that the prediction to the query variables given evidence
can be provided efficiently and maximizes the marginal likelihood as described above. 
Example representations include but are not limited to neural networks, graph neural networks,
auto-regressive models, junction trees, arithmetic circuits, AND/OR graphs, sum-product networks,
cutset networks, and probabilistic circuits. Note that you can use the Markov network
or the data or both to learn a *new representation*.

Technically, given a Markov network M, this task is equivalent to the marginal maximum-aposteriori
(MMAP) task when the subset \\(H\\) is not empty. When \\(H\\) is empty, the task is equivalent to the MAP task. 
Thus approaches that forgo the compilation phase and solve the prediction
task at test time using a MMAP solver can also participate in this task, however, speed will be an
integral part of the scores recieved as alluded to below.


## Online Prediction Phase

During the Prediction (or evaluation) phase, for each time limit being evaluated we will run your solver \\(k\\) times, where \\(k\\) is the number of Markov network models provided.  During each run, we will pass as input (1) the [model file](../file-formats/model-format.md) to your solver, (2) a [test file](../file-formats/test-format.md) that will provide a series of evidence assignments (ie. observations), and (3) a path to the expected result file. For each observation in the test file, your program should output the most-probable assignment to all of the query variables for as many of the given evidence assignments as possible ***in order*** and store the results in the [result file](../file-formats/result-format.md).
