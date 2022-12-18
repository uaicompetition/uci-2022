---
title: "Shadow Leader Board"
date: 2022-12-18
permalink: /results/shadow-leader-board-2022-12-18
---



The results below are organized as follows:
- each table displays the cumulative results for the given task under different time limits
- table values are average normalized scores across all evaluated problems as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- clicking on a solver name links to the results of the solver on the individual problem instances 


# PR

|                               Solver                               | 20sec | 1200sec | 3600sec |
| ------------------------------------------------------------------ | ----: | ------: | ------: |
| [lbp-pr](solver-scores/lbp-pr-scores.md)                           |  90.3 |    89.9 |    90.2 |
| [uai14-pr](solver-scores/uai14-pr-scores.md)                       |  61.7 |    96.8 |    96.7 |
| [ibia-pr](solver-scores/ibia-pr-scores.md)                         |  53.6 |    96.6 |    97.1 |
| [AbstractionSampling](solver-scores/AbstractionSampling-scores.md) |  75.2 |    31.8 |    38.9 |
| [wmbsearch-aobfs-pr](solver-scores/wmbsearch-aobfs-pr-scores.md)   |  36.1 |    11.6 |    11.6 |
| [baseline](solver-scores/baseline-scores.md)                       |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/PR-scores-comparison.md)

### Solvers

- lbp-pr: loopy belief propagation
- uai14-pr: PR solver submission from UAI 2014
- ibia-pr: PR solver submission
- AbstractionSampling: Importance Sampling scheme in AND/OR trees
- wmbsearch-aobfs-pr: AND/OR best-first search scheme using the weighted mini-bucket guiding heuristic
- baseline: weak baseline

# MAR

|                     Solver                     | 20sec | 1200sec | 3600sec |
| ---------------------------------------------- | ----: | ------: | ------: |
| [uai14-mar](solver-scores/uai14-mar-scores.md) |  58.4 |    80.5 |    81.9 |
| [ibia-mar](solver-scores/ibia-mar-scores.md)   |  46.5 |    78.2 |    78.6 |
| [lbp-mar](solver-scores/lbp-mar-scores.md)     |  58.6 |    58.4 |    58.4 |
| [baseline](solver-scores/baseline-scores.md)   |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/MAR-scores-comparison.md)

### Solvers

- uai14-mar: MAR solver submission from UAI 2014
- ibia-mar: MAR solver submission
- lbp-mar: loopy belief propogation
- baseline: weak baseline

# MPE

|                               Solver                               | 20sec | 1200sec | 3600sec |
| ------------------------------------------------------------------ | ----: | ------: | ------: |
| [toulbar2-vns-mpe](solver-scores/toulbar2-vns-mpe-scores.md)       |  81.2 |    86.2 |    86.4 |
| [toulbar2-vacint-mpe](solver-scores/toulbar2-vacint-mpe-scores.md) |  76.2 |    86.8 |    88.6 |
| [daoopt-mpe](solver-scores/daoopt-mpe-scores.md)                   |  72.2 |    87.1 |    89.6 |
| [toulbar2-ipr-mpe](solver-scores/toulbar2-ipr-mpe-scores.md)       |  60.4 |    86.0 |    86.1 |
| [daoopt-lh-mpe](solver-scores/daoopt-lh-mpe-scores.md)             |  17.5 |    31.1 |    32.0 |
| [baseline](solver-scores/baseline-scores.md)                       |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/MPE-scores-comparison.md)

### Solvers

- toulbar2-vns-mpe: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vacint-mpe: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-mpe: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-ipr-mpe: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-lh-mpe: DAOOPT scheme with lookahead by William Lam
- baseline: weak baseline

# MMAP

|                                Solver                                | 20sec | 1200sec | 3600sec |
| -------------------------------------------------------------------- | ----: | ------: | ------: |
| [toulbar2-vns-mmap](solver-scores/toulbar2-vns-mmap-scores.md)       |  70.5 |    72.2 |    72.3 |
| [toulbar2-ipr-mmap](solver-scores/toulbar2-ipr-mmap-scores.md)       |  67.8 |    72.7 |    73.4 |
| [daoopt-mmap](solver-scores/daoopt-mmap-scores.md)                   |  68.5 |    72.1 |    71.8 |
| [toulbar2-vacint-mmap](solver-scores/toulbar2-vacint-mmap-scores.md) |  69.0 |    71.4 |    71.5 |
| [daoopt-lh-mmap](solver-scores/daoopt-lh-mmap-scores.md)             |  17.5 |    36.1 |    47.2 |
| [uai14-mmap](solver-scores/uai14-mmap-scores.md)                     |  28.9 |    33.8 |    35.4 |
| [lbp-mmap](solver-scores/lbp-mmap-scores.md)                         |  28.3 |    29.4 |    29.6 |
| [merlin-mmap](solver-scores/merlin-mmap-scores.md)                   |  14.5 |    15.1 |    20.2 |
| [baseline](solver-scores/baseline-scores.md)                         |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/MMAP-scores-comparison.md)

### Solvers

- toulbar2-vns-mmap: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mmap: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-mmap: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-vacint-mmap: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-lh-mmap: DAOOPT scheme with lookahead by William Lam
- uai14-mmap: MMAP solver submission from UAI 2014
- lbp-mmap: loopy belief propagation modified for solving MMAP
- merlin-mmap: Breadth rotating depth-first AND/OR branch and bound based scheme for MMAP
- baseline: weak baseline

