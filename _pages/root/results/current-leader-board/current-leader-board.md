---
title: "Leader Board"
date: 2022-12-12
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
| [Abstraction-Sampling](solver-scores/Abstraction-Sampling-scores.md) |  99.7 |    97.0 |    97.7 |
| [lbp](solver-scores/lbp-scores.md)                                   |   8.6 |    88.0 |    88.0 |
| [wmbsearch-aobfs-pr](solver-scores/wmbsearch-aobfs-pr-scores.md)     |  29.3 |    57.1 |    57.1 |

[Side-by-Side Comparisons](solver-scores/PR-scores-comparison.md)

### Solvers

- ibia-pr: PR solver submission
- uai14-pr: PR solver submission from UAI 2014
- Abstraction-Sampling: Importance Sampling scheme in AND/OR trees
- lbp: loopy belief propogation
- wmbsearch-aobfs-pr: AND/OR best-first search scheme using the weighted mini-bucket guiding heuristic

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
| [toulbar2-vns-mpe](solver-scores/toulbar2-vns-mpe-scores.md)       |  98.5 |    99.2 |    99.3 |
| [toulbar2-ipr-mpe](solver-scores/toulbar2-ipr-mpe-scores.md)       |  97.2 |    99.4 |    99.5 |
| [toulbar2-vacint-mpe](solver-scores/toulbar2-vacint-mpe-scores.md) |  98.3 |    98.8 |    98.9 |
| [daoopt](solver-scores/daoopt-scores.md)                           |  97.3 |    98.5 |    98.9 |
| [daoopt-lh-mpe](solver-scores/daoopt-lh-mpe-scores.md)             |  94.1 |    96.3 |    96.2 |
| [daoopt-test](solver-scores/daoopt-test-scores.md)                 |  54.5 |    65.6 |    67.3 |
| [uai14-mpe](solver-scores/uai14-mpe-scores.md)                     |  43.7 |    49.8 |    51.8 |

[Side-by-Side Comparisons](solver-scores/MPE-scores-comparison.md)

### Solvers

- toulbar2-vns-mpe: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mpe: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vacint-mpe: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- daoopt-lh-mpe: daoopt with look ahead heuristic
- daoopt-test: daoopt with less competitive settings
- uai14-mpe: MPE solver submission from UAI 2014

# MMAP

|                                Solver                                | 20sec | 1200sec | 3600sec |
| -------------------------------------------------------------------- | ----: | ------: | ------: |
| [toulbar2-vacint-mmap](solver-scores/toulbar2-vacint-mmap-scores.md) |  98.5 |    98.4 |    98.4 |
| [toulbar2-vns-mmap](solver-scores/toulbar2-vns-mmap-scores.md)       |  98.0 |    98.5 |    98.6 |
| [toulbar2-ipr-mmap](solver-scores/toulbar2-ipr-mmap-scores.md)       |  97.5 |    98.7 |    98.7 |
| [daoopt](solver-scores/daoopt-scores.md)                             |  96.9 |    97.9 |    98.0 |
| [daoopt-lh-mmap](solver-scores/daoopt-lh-mmap-scores.md)             |  95.5 |    96.3 |    97.1 |
| [merlin-mmap](solver-scores/merlin-mmap-scores.md)                   |  35.5 |    45.0 |    52.0 |
| [uai14-mmap](solver-scores/uai14-mmap-scores.md)                     |  40.9 |    41.4 |    41.5 |
| [lbp-mmap](solver-scores/lbp-mmap-scores.md)                         |   0.6 |    50.6 |    54.5 |

[Side-by-Side Comparisons](solver-scores/MMAP-scores-comparison.md)

### Solvers

- toulbar2-vacint-mmap: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vns-mmap: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mmap: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten
- daoopt-lh-mmap: daoopt with look ahead heuristic
- merlin-mmap: Breadth rotating depth-first AND/OR branch and bound based scheme for MMAP
- uai14-mmap: MMAP solver submission from UAI 2014
- lbp-mmap: loopy belief propagation modified for solving MMAP

