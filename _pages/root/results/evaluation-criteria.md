---
title: "Evaluation Criteria"
usemathjax: true
permalink: /results/evaluation-criteria/
---

## PR Task

For evaluating the results of different PR solvers,
we compute the errors of the partition function.

The error of a solver \\(solver\\) on the \\(i^{th}\\) instance is computed as follows. <br>

<p>

$$ 
\begin{align*}
  Err^{(i)}_{solver} &= | \log \frac{Z^{*}}{Z_{solver}} |,
\end{align*}
$$

where  
$$ Z^{*} $$ 
is the true partition function and 
$$ Z_{solver} $$  
is the approximate partition function computed by the solver.<br>

  
The final error for a solver is given by 
$$ Err_{solver} = sum_{i}Err_{solver}^{(i)}, $$
and 
the solver with least final error is decided as a winner.
<\p>

  
  
## MAR Task
  
For Evaluating the results produce by different MAR solvers we have used the following two metrics.
  
#### Hellinger Error
For the \\(i^{th}\\) problem the Hellinger error corresponding 
to a solver \\(M\\) is computed as follows. <br>

<p>
$$ 
\begin{align*}
 HErr_M^{(i)} &= frac{1}{N} sum_{j=1}^{N} Hell({bf P}^{*}(V_j),{bf P}(V_j)),
\end{align*}
$$
<\p>
where \\(N\\) is the total number of variables, 
\\(Hell({bf P}^{*}(V_j),{bf P}(V_j))\\) is the Hellinger distance between 
the true probability distribution corresponding to the 
\\(j^{th}\\) variable 
\\(({bf P}^{*}(V_j))\\) and 
the approximate one returned by the solver \\(({bf P}(V_j))\\). <br>

The final error for a solver \\(M\\) is given by 
\\(Err_M = sum_{i}HErr_M^{(i)}\\).
  
#### Max-Absolute Error
For the \\(i^{th}\\) problem 
the max absolute error corresponding to a solver \\(M\\) is computed as follows. <br>


<p>
$$ 
\begin{align*}
AErr_M{(i)} &= frac{1}{N} sum_{j=1}^{N} max_k |P^{*}(V_j = k)-P(V_j = k)|.
\end{align*}
$$
<\p>
where the true probability distribution corresponding to the 
\\(j^{th}\\) variable is 
\\(({bf P}^{*}(V_j))\\) and the approximate one returned by the solver is 
\\(({bf P}(V_j))\\). <br>

The final error for a solver \\(M \\) is given by 
\\(AErr_M = sum_{i}AErr_M^{(i)}\\).
  
  
## MAP Task
For Evaluating the results produce by different MAP solvers we have used following two metrics.

#### Relative Gap From the Leader


For each problem and for a solver \\( solver \\), 
the score \\( S(solver) \\) is computed as follows. <br>

<p>
$$ 
\begin{align*}
S(solver) &= \frac{M_{leader} - M_{solver}}{M_{leader}},
\end{align*}
$$
where \\(M_{solver}\\) is the \\(\log MAP\\) value of the result 
returned by \\(solver\\) and \\(M_{leader}\\) is the same for the best solver for this
problem instance, i.e., solver with the highest MAP value.

**Note**: For deciding the winner we have not used this metric as it gives higher importance to problem instances with smaller MAP value.
</p>

#### Rank
For each problem, 
each solver is ranked in terms of its solution quality, 
i.e.– solvers with higher MAP value gets smaller rank and the winner(s) 
for that problem gets the rank 1. 
Finally we add all the ranks of a solver in all the problems. 
The winner of the competition is selected using this metric. 
The solver which has lowest cumulative score is decided as a winner.


## MMAP Task
For Evaluating the results produce by different MMAP solvers we 
use the same evaluation criteria used for MAP task.


## MLC Task
For Evaluating the results produce by different MLC submissions we 
use the same evaluation criteria used for MAP task.
