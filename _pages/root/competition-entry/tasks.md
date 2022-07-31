---
title: "Tasks"
permalink: /competition-entry/tasks/
---

Tasks are each with respect to a graphical model $$ \mathcal{M} = < X, D, F> $$, where:
* $$ X = \{ X_1, X_2, ..., X_N \} $$ is the set of the model's variables
* $$ D = \{ D_{X_1}, D_{X_2}, ..., D_{X_N} \} is the set of discrete domains for each variable
* $$ F = \{ f_1, f_2, ..., f_M \} is the set of functions defined over the model

$$ X $$ can be further partitioned into two sets, $$ E $$ and $$ X' $$, where:
* $$ E $$ are the evidence variables for which assignments are observed (ie. given)
* $$ X' = X \setminus E $$ are the unknown variables


**PR :** 
&nbsp; computing the partition function (ie. normalizing constant) or probability of evidence
$$ 
\begin{align*}
  PR(X'|E=e) = \sum_{X'} \prod_{F} f(x',e)
\end{align*}
$$


**MAR :** 
&nbsp; computing the marginal probability distribution over all variables given evidence
$$ 
\begin{align*}
  MAR(X_i|E=e) = \frac{ \sum_{X'' = X' \setminus X_i} \prod_{F} f(x'',e) }{ PR(X'|E=e) }
\end{align*}
$$

**MAP :** 
&nbsp; computing the most likely assignment to all variables given evidence
$$ 
\begin{align*}
  MAP(X_i|E=e) = \argmax_{X'} \prod_{F} f(x',e)
\end{align*}
$$

**MMAP :**
&nbsp; computing the most likely assignment to a subset of variables that maximizes the marginals on the remaining variables
* $$ X_M \subset X' $$
* $$ X_S = X' \setminus X_M $$
$$ 
\begin{align*}
  MMAP(X_i|E=e) = \argmax_{X_M} \sum_{X_S} \prod_{F} f(x_M, x_S, e)
\end{align*}
$$

All inference tasks (above) will be given one CPU and 8GB of ram and will be tested in three different time categories:
* 20 sec
* 100 sec
* 2o min (1200 sec)

**MLC** *(new!)* **:** 
&nbsp; multi-label classification of a subset of variables of given a model and observed evidence (through learning, inference, or any other method of your choice).
* Please see the [detailed description](./new-mlc-challenge.md) for more information.
