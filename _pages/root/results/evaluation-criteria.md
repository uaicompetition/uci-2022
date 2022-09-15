---
title: "Evaluation Criteria"
usemathjax: true
permalink: /results/evaluation-criteria/
---

## PR Task
### Computing PR errors
For each partition function problem instance tested, we compute solver errors in the following way: <br>

$$ 
\begin{align*}
  Err &= | \log \frac{Z^{*}}{\hat{Z}} |,
\end{align*}
$$

where $$ Z^{*} $$ 
is the true partition function value for the problem instance and $$ \hat{Z} $$ is the approximate partition function value as computed by the solver.

### Normalizing errors
In order to assign final scores to each solver that equally consider all problems tested on, we first compute a per-instance score by normalizing the afformentioned errors on each problem instance.  We compute this per-instance score in the following way: <br>

$$ 
\begin{align*}
  Score &= max( 0,  100 (1 - \frac{Err}{MaxErr}) ).
\end{align*}
$$

where $$ MaxErr $$ 
is the error of the solution returned by a trivial solver.

* If the evaluated solver returns the true partition function value, its score will be 100.
* If the evaluated solver returns an answer worst than the trivial solver, the score will be 0.

### Final solver scores
The final rankings will be according to an aggregation of solver scores computed by averaging the per-instance scores across all problems tested on.

  
## MAR Task

### Computing MAR Hellinger errors
  
For the MAR task, which asks for the marginal probability distributions of ***all*** unobserved variables, a method is needed to to account for the nature of the task as producing many distinct distributions of varying accuracy.  For each marginal distribution, we use [Hellinger distance](https://en.wikipedia.org/wiki/Hellinger_distance) as error between approximated and true distributions.  The overall error is computed by taking the average of the error over all marginal distributions.

Namely, for each MAR problem instance tested, we compute a per-instance average Hellinger error in the following way: <br>

$$ 
\begin{align*}
 HErr &= \frac{1}{N} \sum_{i=1}^{N} Hell({\mathbf{P}}^{*}(V_i),{\mathbf{\hat{P}}}(V_i)),
\end{align*}
$$

where $$N$$ is the total number of unobserved variables for the problem instance, $$\mathbf{P}^{*}(V_i)$$ is the true probability distribution of unobserved variable $$i$$, $$\mathbf{\hat{P}}(V_i)$$ is the approximated probability distribution of unobserved variable $$i$$ as computed by the solver, and $$Hell({\mathbf{P}}^{*}(V_i),{\mathbf{\hat{P}}}(V_i))$$ is the Hellinger distance between the two. <br>

### Normalizing errors
In order to assign final scores to each solver that equally consider all problems tested on, we first compute a per-instance score by normalizing the afformentioned average Hellinger errors on each problem instance.  We compute this per-instance score in the following way: <br>

$$ 
\begin{align*}
  Score &= max( 0,  100 (1 - \frac{HErr}{MaxHErr}) ).
\end{align*}
$$

where $$ MaxHErr $$ 
is the average Hellinger error of the solution returned by a trivial solver.

* If the evaluated solver returns the true probability distributions for all unobserved variables, its score will be 100.
* If the evaluated solver returns an answer worst than the trivial solver, the score will be 0.

### Ranking solvers
The final rankings will be according to an aggregation of solver scores computed by averaging the per-instance scores across all problems tested on.
    
  
## MAP Task

### Computing MPE relative errors

The quality of a solution for the MAP task, which asks for the most probable explanation (or MPE) - ie. the most likely joint assignment to all unobserved variables, can be determined by computing the likelihood $$\mathcal{L}(.)$$ of a returned assignment $$\widehat{MPE}$$ based on the functions associated with the problem network. However, since finding the MPE is intractible for many of the problems, we compute errors relative to the best known solution out of all solvers in the competition to date, $$\widehat{MPE}^{best}$$ in the following way: <br>

$$ 
\begin{align*}
 Err &= log(  \frac{\mathcal{L}(\widehat{MPE}^{best})}{\mathcal{L}(\widehat{MPE})} ),
\end{align*}
$$

(Note that, based on this method, errors for the same solver on the same problems can change as better solutions become available). <br>

### Normalizing scores
In order to assign final scores to each solver that equally consider all problems tested on, we first compute a per-instance score by normalizing the afformentioned errors on each problem instance.  We compute this per-instance score in the following way: <br>

$$ 
\begin{align*}
  Score &= max( 0,  100 (1 - \frac{Err}{MaxErr}) ).
\end{align*}
$$

where $$ MaxErr $$ 
is the relative error of the solution returned by a trivial solver \[still with respect to the best solution available\].

* If the likelihood of the evaluated solver's solution is the same as the best solution available, its score will be 100.
* If the evaluated solver returns an answer worst than the trivial solver, the score will be 0.

(Note that, based on this method, scores for the same solver on the same problems can change as better solutions become available). <br>

### Ranking solvers
The final rankings will be according to an aggregation of solver scores computed by averaging the per-instance scores across all problems tested on.


## MMAP Task
For Evaluating the results produce by different MMAP solvers we 
use the same evaluation criteria used for MAP task.


## MLC Task
For Evaluating the results produce by different MLC submissions we 
use the same evaluation criteria used for MAP task.
