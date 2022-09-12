---
title: "Evaluation Criteria"
usemathjax: true
permalink: /results/evaluation-criteria/
---

## PR Task
### Computing PR errors
For each partition function problem instance \\(i\\) tested, we compute solver errors in the following way: <br>

$$ 
\begin{align*}
  Err^{(i)}_{solver} &= | \log \frac{Z^{*(i)}}{Z^{(i)}_{solver}} |,
\end{align*}
$$

where $$ Z^{*(i)} $$ 
is the true partition function value for problem instance \\(i\\) and $$ Z^{(i)}_{solver} $$ is the approximate partition function value as computed by the solver.

### Normalizing errors
In order to assign final scores to each solver that consider all problems tested on, we first normalize the errors computed on each problem instance so that they can be aggregated in a way that each contributes equally to the final score.  We compute this normalized error in the following way: <br>

$$ 
\begin{align*}
  ErrNorm^{(i)}_{solver} &= max(0, 1 - \frac{Err^{(i)}_{solver}}{MaxErr^{(i)}}).
\end{align*}
$$

where $$ MaxErr^{(i)} $$ 
is the error that results from the solution produced by a trivial solver on problem instance \\(i\\).

* If solver returned the exact answer, the score will be +1.
* If a solver returned an answer worst than the trivial solver, the score will be 0.
* In the case that a solver doesn't produce any answer, we assign a score of -1.

### Final solver scores
The final ranking will be according to solver scores determined by averaging the normalized errors across all problems tested on.

  
## MAR Task

### Computing Hellinger errors from MAR files
  
For the \\(i^{th}\\) problem, the Hellinger error corresponding 
to a solver \\(solver\\) is computed as follows. <br>

$$ 
\begin{align*}
 HErr_{solver}^{(i)} &= \frac{1}{N} \sum_{j=1}^{N} Hell({\mathbf{P}}^{*}(V_j),{\mathbf{P}}(V_j)),
\end{align*}
$$

where $$N$$ is the total number of variables, 
$$Hell({\mathbf{P}}^{*}(V_j),{\mathbf{P}}(V_j))$$ is the Hellinger distance between 
the true probability distribution corresponding to the $$j^{th}$$ variable $$( \mathbf{P}^{*}(V_j) )$$ and 
the approximate one returned by the solver is $$({\mathbf{P}}(V_j))$$. <br>

### Normalizing scores
We compute a score of a solver \\(solver\\) on the \\(i^{th}\\)  by normalizing error as follows. <br>

$$ 
\begin{align*}
  Score^{(i)}_{solver} &= 1 - \frac{HErr^{(i)}_{solver}}{\text{Max HErr}}.
\end{align*}
$$

* If solver returned the exact answer, the score will be +1.
* If a solver returned the worst answer, the score will be 0.
* If a solver didn't return any answer, the score will be -1.

### Ranking solvers
The final ranking will be determined by the total score.
    
  
## MAP Task

### Computing log MEP value from MPE files

For the \\(i^{th}\\) problem, we compute log MPE value. <br>

### Normalizing scores
We compute a score of a solver \\(solver\\) on the \\(i^{th}\\)  by normalizing log MPE values as follows. <br>


$$ 
\begin{align*}
  Score^{(i)}_{solver} &= \frac{log(MPE)^{(i)}_{solver} - log(MPE)^{(i)}_{worst}}{log(MPE)^{(i)}_{best} - log(MPE)^{(i)}_{worst}},
\end{align*}
$$

where 
where $$ log(MPE)^{(i)}_{solver} $$  is the log MPE value from the solver,
$$ log(MPE)^{(i)}_{best} $$ is the best known log MPE value, and
$$ log(MPE)^{(i)}_{worst} $$ is the worst log MPE value.

* If solver returned the exact or best known answer, the score will be +1.
* If a solver returned the worst answer, the score will be 0.
* If a solver didn't return any answer, the score will be -1.

### Ranking solvers
The final ranking will be determined by the total score.


## MMAP Task
For Evaluating the results produce by different MMAP solvers we 
use the same evaluation criteria used for MAP task.


## MLC Task
For Evaluating the results produce by different MLC submissions we 
use the same evaluation criteria used for MAP task.
