---
title: "Sep 7th. Mini Evaluation of Submitted Solvers"
---

The evaluation results are organized in the following structure.
- Total scores per tasks using normalized scores as shown in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- Solution and individual score per problem
- Lastly, link to the result output and logfiles.


# Total Scores

## PR Task

  | time | 20 sec | 20 min | 1 hr |
  |:------|--------:|--------:|------:|
  | lbp  | -119.000 | -2.000   | -2.000 | 
  | uai14-ihler | 59.901 | 129.739 | 129.514 |

### Solvers
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-pr/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-pr)

## MAR Task
 
  | time | 20 sec | 20 min | 1 hr |
  |:------|--------:|--------:|------:|
  | lbp  | -124.000 | -4.000   | -1.000 | 
  | uai14-ihler | 35.554 | 129.908 | 129.978 |

### Solvers
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-mar/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mar)


## MPE Task

  | time | 20 sec | 20 min | 1 hr |
  |:------|--------:|--------:|------:|
  |dallouche| 84.0479 |  87.374 | 89.447 |
  |daoopt |114.515    | 118.655        | 119.982  |
  |daoopt-weak | 27.055 | 54.431 | 57.671  |
  |uai14-ihler| 13.141 | 14.817 | 15.611 |  

### Solvers
- dallouche: new submission this year
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/daoopt-1hr-ib35)
- daoopt-weak: weaken the options in daoopt
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mpe)


## MMAP Task
 
  | time | 20 sec | 20 min | 1 hr |
  |:------|--------:|--------:|------:|
  | daoopt | 98.211 | 114.391 | 112.646 |
  |lbp | -118.000 | -2.683 |6.078 |
  |uai14-ihler | -39.968 | -29.564 |-39.314|
  
### Solvers
- daoopt: take MPE solution from daoopt and truncate to MMAP solution
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-mmap/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mmap)

