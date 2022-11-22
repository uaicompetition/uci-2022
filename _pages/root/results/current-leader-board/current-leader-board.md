---
title: "Leader Board"
date: 2022-11-22
permalink: /results/current-leader-board
---



The results below are organized as follows:
- each table displays the cumulative results for the given task under different time limits
- table values are average normalized scores across all evaluated problems as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- clicking on a solver name links to the results of the solver on the individual problem instances 


# PR

|                                Solver                                | 20sec | 1200sec | 3600sec |
| -------------------------------------------------------------------- | ----: | ------: | ------: |
| [ibia-pr](solver-scores/ibia-pr-scores.md)                           |  99.9 |     100 |   100.0 |
| [uai14-pr](solver-scores/uai14-pr-scores.md)                         |  97.2 |     100 |   100.0 |
| [Abstraction-Sampling](solver-scores/Abstraction-Sampling-scores.md) |  48.1 |      97 |    96.2 |
| [lbp](solver-scores/lbp-scores.md)                                   |   8.6 |      88 |    88.0 |

[Side-by-Side Comparisons](solver-scores/PR-scores-comparison.md)

### Solvers

- ibia-pr: PR solver submission
- uai14-pr: PR solver submission from UAI 2014
- Abstraction-Sampling: Importance Sampling scheme in AND/OR trees
- lbp: loopy belief propogation

# MAR

|                     Solver                     | 20sec | 1200sec | 3600sec |
| ---------------------------------------------- | ----: | ------: | ------: |
| [ibia-mar](solver-scores/ibia-mar-scores.md)   |  71.1 |    76.4 |    76.4 |
| [uai14-mar](solver-scores/uai14-mar-scores.md) |  61.6 |    76.5 |    76.5 |
| [lbp](solver-scores/lbp-scores.md)             |   3.3 |    54.2 |    54.2 |

[Side-by-Side Comparisons](solver-scores/MAR-scores-comparison.md)

### Solvers

- ibia-mar: MAR solver submission
- uai14-mar: MAR solver submission from UAI 2014
- lbp: loopy belief propogation

# MPE

|                           Solver                           | 20sec | 1200sec | 3600sec |
| ---------------------------------------------------------- | ----: | ------: | ------: |
| [daoopt](solver-scores/daoopt-scores.md)                   |  98.3 |    99.6 |   100.0 |
| [toulbar2-vacint](solver-scores/toulbar2-vacint-scores.md) |  97.4 |    97.6 |    97.6 |
| [toulbar2-ipr](solver-scores/toulbar2-ipr-scores.md)       |  96.1 |    97.3 |    97.3 |
| [toulbar2-vns](solver-scores/toulbar2-vns-scores.md)       |  83.3 |    86.4 |    86.4 |
| [daoopt-test](solver-scores/daoopt-test-scores.md)         |  54.9 |    65.9 |    67.6 |
| [uai14-mpe](solver-scores/uai14-mpe-scores.md)             |  43.7 |    50.1 |    52.1 |

[Side-by-Side Comparisons](solver-scores/MPE-scores-comparison.md)

### Solvers

- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-vacint: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr: An incremental precision-based incremental search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vns: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-test: daoopt with less competitive settings
- uai14-mpe: MPE solver submission from UAI 2014

# MMAP

|                      Solver                      | 20sec | 1200sec | 3600sec |
| ------------------------------------------------ | ----: | ------: | ------: |
| [daoopt](solver-scores/daoopt-scores.md)         |  97.0 |    98.0 |    98.1 |
| [uai14-mmap](solver-scores/uai14-mmap-scores.md) |  41.1 |    41.6 |    41.8 |
| [lbp-mmap](solver-scores/lbp-mmap-scores.md)     |   0.6 |    50.6 |    54.6 |
| [uai16-mmap](solver-scores/uai16-mmap-scores.md) |   2.5 |    35.8 |    22.2 |

[Side-by-Side Comparisons](solver-scores/MMAP-scores-comparison.md)

### Solvers

- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- uai14-mmap: MMAP solver submission from UAI 2014
- lbp-mmap: loopy belief propagation modified for solving MMAP
- uai16-mmap: Breadth rotating depth-first AND/OR branch and bound based scheme for MMAP

# MLC

|                  Solver                  | 60sec | 300sec |
| ---------------------------------------- | ----: | -----: |
| [RF_d-8](solver-scores/RF_d-8-scores.md) |  73.0 |   73.0 |
| [RF_d-4](solver-scores/RF_d-4-scores.md) |  53.8 |   53.8 |

[Side-by-Side Comparisons](solver-scores/MLC-scores-comparison.md)

### Solvers

- RF_d-8: scikit-learn random-forest learner using a depth of 8
- RF_d-4: scikit-learn random-forest learner using a depth of 4

