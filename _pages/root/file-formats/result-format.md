---
title: "File Formats"
permalink: /file-formats/result-format/
---

## Result File Format

The rest of the file will contain the solution for the task. 
The first line must contain one of the tasks (PR, MPE, MAR, MMAP, or MLC) solved. 

Solvers could write more then one solution by writing -BEGIN- at the head of the new solution. 
We will only consider the last solution in the file. 
In the example below the task we choose is PR. 
We have two solutions.<br/>
The format of the &lt;SOLUTION&gt; part will be described below.

```
PR
<SOLUTION>
-BEGIN-
<SOLUTION>
```

The solution format are as follows depending on the task

* **Partition function, PR**: Line with the value of the log10 of the partition function. 
  * For example, an approximation log10 Pr(e) = -0.2008 which is known to be an upper bound may have a solution line:
```
-0.2008
```

* **Marginals, MAR**: A space separated line that includes:
    * The number of variables in the model.
    * A list of marginal approximations of all the variables. For each variable its cardinality is first stated, then the probability of each state is stated. The order of the variables is the same as in the model, all data is space separated.
    * For example, a model with 3 variables, with cardinalities of 2, 2, 3 respectively. The solution might look like this:
```
3 2 0.1 0.9 2 0.3 0.7 3 0.2 0.2 0.6
```

* **Marginal MAP, MMAP**: A space separated line that includes:
    * The number _q_ of query variables
    * the most probable instantiation, a list of variable value pairs for all _q_ variables.
    * For example, if the solution is an assignment of 0, 1 and 0 to three query variables indexed by 2 3 and 4 respectively, the solution will look as follows
```
3 2 0 3 1 4 0
```

* **Multi label classfication, MLC**: This format is similar as MMAP result format described above with the exception that multiple outputs appear in a single file. Each line is a prediction result on the query variables formatted as a space separated line that includes:
    * The number _q_ of (possibly non-binary) properties or query variables
    * the predicted label for each query variable, a list of variable value pairs for all _q_ variables.
    * For example, suppose that we have three query variables Q={2, 4, 7} and based on two different evidence inputs two predictions are made to the assignments to the query variables: q1={0, 2, 0} and q2={2, 0, 1}.
```
3 2 0 4 2 7 0
3 2 2 4 0 7 1
```
