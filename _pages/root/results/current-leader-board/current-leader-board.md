---
title: "Leader Board"
date: 2022-12-09
permalink: /results/current-leader-board
---



The results below are organized as follows:
- each table displays the cumulative results for the given task under different time limits
- table values are average normalized scores across all evaluated problems as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- clicking on a solver name links to the results of the solver on the individual problem instances 


# PR

|                                Solver                                | 20sec | 1200sec | 3600sec |
| -------------------------------------------------------------------- | ----: | ------: | ------: |
| [ibia-pr](solver-scores/ibia-pr-scores.md)                           |  99.9 |   100.0 |   100.0 |
| [uai14-pr](solver-scores/uai14-pr-scores.md)                         |  97.2 |   100.0 |   100.0 |
| [lbp](solver-scores/lbp-scores.md)                                   |   8.6 |    88.0 |    88.0 |
| [wmbsearch-aobfs-pr](solver-scores/wmbsearch-aobfs-pr-scores.md)     |  29.3 |    57.1 |    57.1 |
| [Abstraction-Sampling](solver-scores/Abstraction-Sampling-scores.md) |  60.1 |    21.1 |    20.3 |

[Side-by-Side Comparisons](solver-scores/PR-scores-comparison.md)

### Solvers

- ibia-pr: PR solver submission
- uai14-pr: PR solver submission from UAI 2014
- lbp: loopy belief propogation
- wmbsearch-aobfs-pr: AND/OR best-first search scheme using the weighted mini-bucket guiding heuristic
- Abstraction-Sampling: Importance Sampling scheme in AND/OR trees

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

|                               Solver                               | 20sec | 1200sec | 3600sec |
| ------------------------------------------------------------------ | ----: | ------: | ------: |
| [toulbar2-vacint-mpe](solver-scores/toulbar2-vacint-mpe-scores.md) |  84.7 |    85.2 |    85.2 |
| [daoopt](solver-scores/daoopt-scores.md)                           |  83.6 |    84.8 |    85.2 |
| [toulbar2-vns-mpe](solver-scores/toulbar2-vns-mpe-scores.md)       |  69.8 |    72.9 |    72.9 |
| [toulbar2-ipr-mpe](solver-scores/toulbar2-ipr-mpe-scores.md)       |  68.4 |    61.9 |    61.9 |
| [daoopt-test](solver-scores/daoopt-test-scores.md)                 |  49.2 |    56.7 |    57.9 |
| [daoopt-lh-mpe](solver-scores/daoopt-lh-mpe-scores.md)             |  27.5 |    55.8 |    65.0 |
| [uai14-mpe](solver-scores/uai14-mpe-scores.md)                     |  40.0 |    44.7 |    46.2 |

[Side-by-Side Comparisons](solver-scores/MPE-scores-comparison.md)

### Solvers

- toulbar2-vacint-mpe: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-vns-mpe: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mpe: An incremental precision-based incremental search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-test: daoopt with less competitive settings
- daoopt-lh-mpe: daoopt with look ahead heuristic
- uai14-mpe: MPE solver submission from UAI 2014

# MMAP

|                              Solver                              | 20sec | 1200sec | 3600sec |
| ---------------------------------------------------------------- | ----: | ------: | ------: |
| [toulbar2-rahs-mmap](solver-scores/toulbar2-rahs-mmap-scores.md) |  98.0 |    97.9 |    97.9 |
| [toulbar2-vns-mmap](solver-scores/toulbar2-vns-mmap-scores.md)   |  97.5 |    98.0 |    98.1 |
| [daoopt](solver-scores/daoopt-scores.md)                         |  96.4 |    97.4 |    97.5 |
| [toulbar2-ipr-mmap](solver-scores/toulbar2-ipr-mmap-scores.md)   |   0.8 |    98.2 |    98.2 |
| [daoopt-lh-mmap](solver-scores/daoopt-lh-mmap-scores.md)         |  29.0 |    52.6 |    57.6 |
| [uai14-mmap](solver-scores/uai14-mmap-scores.md)                 |  40.8 |    41.2 |    41.4 |
| [lbp-mmap](solver-scores/lbp-mmap-scores.md)                     |   0.5 |    50.3 |    54.2 |
| [uai16-mmap](solver-scores/uai16-mmap-scores.md)                 |   2.5 |    35.4 |    22.0 |

[Side-by-Side Comparisons](solver-scores/MMAP-scores-comparison.md)

### Solvers

- toulbar2-rahs-mmap: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vns-mmap: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-ipr-mmap: An incremental precision-based incremental search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-lh-mmap: daoopt with look ahead heuristic
- uai14-mmap: MMAP solver submission from UAI 2014
- lbp-mmap: loopy belief propagation modified for solving MMAP
- uai16-mmap: Breadth rotating depth-first AND/OR branch and bound based scheme for MMAP

