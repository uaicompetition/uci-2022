---
title: "Evaluation Criteria"
usemathjax: true
permalink: /results/evaluation-criteria/
---

## PR Task

## MAR Task


## MAP Task
For Evaluating the results produce by different MAP solvers we have used following two metrics:

#### **Relative Gap From the Leader**

<p>
For each problem and for a solver \\( solver \\), 
the score \\( S(solver) \\) is computed by <br>

$$ 
\begin{aligned}
S(solver) &= \frac{M_{leader} - M_{solver}}{M_{leader}},
\end{aligned}
$$
where \\(M_{solver}\\) is the \\(log MAP\\) value of the result 
returned by \\(solver\\) and \\(M_{leader}\\) is the same for the best solver for this
problem instance, i.e., solver with the highest MAP value.

**Note**: For deciding the winner we have not used this metric as it gives higher importance to problem instances with smaller MAP value.
</p>

#### **Rank**
For each problem, 
each solver is ranked in terms of its solution quality, 
i.e.– solvers with higher MAP value gets smaller rank and the winner(s) 
for that problem gets the rank 1. 
Finally we add all the ranks of a solver in all the problems. 
The winner of the competition is selected using this metric. 
The solver which has lowest cumulative score is decided as a winner.


## MMAP Task

## MLC Task
