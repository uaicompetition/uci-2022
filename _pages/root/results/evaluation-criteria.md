---
title: "Evaluation Criteria"
usemathjax: true
permalink: /results/evaluation-criteria/
---

## PR Task
### computing errors from PR files
We compute the errors of the partition function to evaluate solvers.
The error of a solver \\(solver\\) on the \\(i^{th}\\) instance is computed as follows. <br>

$$ 
\begin{align*}
  Err^{(i)}_{solver} &= | \log \frac{Z^{*}}{Z_{solver}} |,
\end{align*}
$$

where $$ Z^{*} $$ 
is the true partition function and $$ Z_{solver} $$ is the approximate partition function computed by the solver.

### normalizing scores
We compute a score of a solver \\(solver\\) on the \\(i^{th}\\)  by normalizing error as follows. <br>

$$ 
\begin{align*}
  Score^{(i)}_{solver} &= 1 - \frac{Err^{(i)}_{solver}}{Maximum Err}.
\end{align*}
$$

* If solver returned the exact answer, the score will be +1.
* If a solver returned the worst answer, the score will be 0.
* If a solver didn't return any answer, the score will be -1.

### ranking solvers
the final ranking will be determined by the total score.

  
## MAR Task

### computing Hellinger errors from MAR files
  
For the \\(i^{th}\\) problem, the Hellinger error corresponding 
to a solver \\(M\\) is computed as follows. <br>

$$ 
\begin{align*}
 HErr_M^{(i)} &= \frac{1}{N} \sum_{j=1}^{N} Hell({\mathbf{P}}^{*}(V_j),{\mathbf{P}}(V_j)),
\end{align*}
$$

where $$N$$ is the total number of variables, 
$$Hell({\mathbf{P}}^{*}(V_j),{\mathbf{P}}(V_j))$$ is the Hellinger distance between 
the true probability distribution corresponding to the $$j^{th}$$ variable $$( \mathbf{P}^{*}(V_j) )$$ and 
the approximate one returned by the solver is $$({\mathbf{P}}(V_j))$$. <br>

### normalizing scores
We compute a score of a solver \\(solver\\) on the \\(i^{th}\\)  by normalizing error as follows. <br>

$$ 
\begin{align*}
  Score^{(i)}_{solver} &= 1 - \frac{HErr^{(i)}_{solver}}{Maximum HErr}.
\end{align*}
$$

* If solver returned the exact answer, the score will be +1.
* If a solver returned the worst answer, the score will be 0.
* If a solver didn't return any answer, the score will be -1.

### ranking solvers
the final ranking will be determined by the total score.
    
  
## MAP Task

### computing log MEP value from MPE files

For the \\(i^{th}\\) problem, we compute log MPE value. <br>

### normalizing scores
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

### ranking solvers
the final ranking will be determined by the total score.


## MMAP Task
For Evaluating the results produce by different MMAP solvers we 
use the same evaluation criteria used for MAP task.


## MLC Task
For Evaluating the results produce by different MLC submissions we 
use the same evaluation criteria used for MAP task.
