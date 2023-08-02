---
title: "Tasks"
usemathjax: true
permalink: /competition-entry/tasks/
---

## Probabilistic Inference Tasks

Tasks are each with respect to a graphical model $$ \mathcal{M} = < X, D, F> $$, where:
* $$ X = \{ X_1, X_2, ..., X_N \} $$ is the set of the model's variables
* $$ D = \{ D_{X_1}, D_{X_2}, ..., D_{X_N} \} $$ is the set of discrete domains for each variable
* $$ F = \{ f_1, f_2, ..., f_M \} $$ is the set of the model's functions

$$ X $$ can be further partitioned into two sets, 
evidence variables $$ E $$ and the rest $$ X'= X \setminus E  $$.


**PR :** 
&nbsp; computing the partition function (ie. normalizing constant)
$$ 
\begin{align*}
  PR(E=e) = \sum_{X'} \prod_{F} f(x',e)
\end{align*}
$$


**MAR :** 
&nbsp; computing the marginal probability distribution over all variables given evidence
$$ 
\begin{align*}
  MAR(X_i|E=e) = \frac{ \sum_{X'' = X' \setminus X_i} \prod_{F} f(x'',e) }{ PR(E=e) }
\end{align*}
$$

**MPE :** 
&nbsp; computing the most likely assignment to all variables given evidence
$$ 
\begin{align*}
  MPE(X_i|E=e) = \arg \max_{X'} \prod_{F} f(x',e)
\end{align*}
$$

**MMAP :**
&nbsp; computing the most likely assignment to the query variables, $$ X_M \subset X' $$ 
after marginalizing out when marganlizing the remaining variables $$ X_S = X' \setminus X_M $$.

$$ 
\begin{align*}
  MMAP(X_i|E=e) = \arg \max_{X_M} \sum_{X_S} \prod_{F} f(x_M, x_S, e)
\end{align*}
$$

### All inference tasks will be given one CPU and 8GB of ram and will be tested in three different time categories:
* 20 seconds
* 20 minutes
* 1 hour


## Multi-Label Classification Task

**MLC** *(new!)* **:** 
&nbsp; multi-label classification of a subset of variables of given a model and observed evidence (through learning, inference, or any other method of your choice).
* Please see the [detailed description](./new-mlc-challenge.md) for more information.
