---
title: "Leader Board"
date: 2022-12-12
permalink: /results/shadow-leader-board
---



The results below are organized as follows:
- each table displays the cumulative results for the given task under different time limits
- table values are average normalized scores across all evaluated problems as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- clicking on a solver name links to the results of the solver on the individual problem instances 


# PR

|                               Solver                               | 20sec | 1200sec | 3600sec |
| ------------------------------------------------------------------ | ----: | ------: | ------: |
| [uai14-pr](solver-scores/uai14-pr-scores.md)                       |  61.7 |    96.9 |    96.6 |
| [ibia-pr](solver-scores/ibia-pr-scores.md)                         |  53.6 |    96.6 |    96.6 |
| [AbstractionSampling](solver-scores/AbstractionSampling-scores.md) |  74.7 |    33.3 |    36.9 |
| [wmbsearch-aobfs-pr](solver-scores/wmbsearch-aobfs-pr-scores.md)   |  36.2 |    11.6 |    11.6 |
| [lbp-pr](solver-scores/lbp-pr-scores.md)                           |   5.8 |     2.0 |     2.0 |
| [baseline](solver-scores/baseline-scores.md)                       |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/PR-scores-comparison.md)

### Solvers

- uai14-pr: PR solver submission from UAI 2014
- ibia-pr: PR solver submission
- AbstractionSampling: Importance Sampling scheme in AND/OR trees
- wmbsearch-aobfs-pr: AND/OR best-first search scheme using the weighted mini-bucket guiding heuristic
- lbp-pr: loopy belief propagation
- baseline: weak baseline

# MAR

|                     Solver                     | 20sec | 1200sec | 3600sec |
| ---------------------------------------------- | ----: | ------: | ------: |
| [uai14-mar](solver-scores/uai14-mar-scores.md) |  59.1 |    80.5 |    81.8 |
| [ibia-mar](solver-scores/ibia-mar-scores.md)   |  46.5 |    77.8 |    78.6 |
| [lbp-mar](solver-scores/lbp-mar-scores.md)     |   8.9 |    41.0 |    58.4 |
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
| [daoopt-mpe](solver-scores/daoopt-mpe-scores.md)                   |  71.8 |    84.7 |    84.5 |
| [daoopt-lh-mpe](solver-scores/daoopt-lh-mpe-scores.md)             |  69.8 |    80.9 |    85.7 |
| [toulbar2-vns-mpe](solver-scores/toulbar2-vns-mpe-scores.md)       |  70.1 |    74.0 |    74.1 |
| [toulbar2-vacint-mpe](solver-scores/toulbar2-vacint-mpe-scores.md) |  65.4 |    71.9 |    72.0 |
| [toulbar2-ipr-mpe](solver-scores/toulbar2-ipr-mpe-scores.md)       |  49.3 |    74.6 |    74.7 |
| [baseline](solver-scores/baseline-scores.md)                       |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/MPE-scores-comparison.md)

### Solvers

- daoopt-mpe: uai 2012, 2014, and 2016 participant by Lars Otten
- daoopt-lh-mpe: DAOOPT scheme with lookahead by William Lam
- toulbar2-vns-mpe: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-vacint-mpe: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mpe: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- baseline: weak baseline

# MMAP

|                                Solver                                | 20sec | 1200sec | 3600sec |
| -------------------------------------------------------------------- | ----: | ------: | ------: |
| [daoopt-mmap](solver-scores/daoopt-mmap-scores.md)                   |  68.5 |    71.8 |    71.8 |
| [toulbar2-vns-mmap](solver-scores/toulbar2-vns-mmap-scores.md)       |  66.7 |    67.5 |    67.6 |
| [toulbar2-ipr-mmap](solver-scores/toulbar2-ipr-mmap-scores.md)       |  62.9 |    67.7 |    68.4 |
| [daoopt-lh-mmap](solver-scores/daoopt-lh-mmap-scores.md)             |  64.4 |    66.3 |    67.5 |
| [toulbar2-vacint-mmap](solver-scores/toulbar2-vacint-mmap-scores.md) |  63.3 |    65.7 |    65.8 |
| [merlin-mmap](solver-scores/merlin-mmap-scores.md)                   |  14.5 |    15.0 |    20.2 |
| [uai14-mmap](solver-scores/uai14-mmap-scores.md)                     |   2.2 |     7.8 |     9.2 |
| [baseline](solver-scores/baseline-scores.md)                         |   0.0 |     0.0 |     0.0 |

[Side-by-Side Comparisons](solver-scores/MMAP-scores-comparison.md)

### Solvers

- daoopt-mmap: uai 2012, 2014, and 2016 participant by Lars Otten
- toulbar2-vns-mmap: A variable neighborhood search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- toulbar2-ipr-mmap: An incremental precision-based search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- daoopt-lh-mmap: DAOOPT scheme with lookahead by William Lam
- toulbar2-vacint-mmap: A heuristic search method of former UAI competition winner [Toulbar2](https://github.com/toulbar2/toulbar2)
- merlin-mmap: Breadth rotating depth-first AND/OR branch and bound based scheme for MMAP
- uai14-mmap: MMAP solver submission from UAI 2014
- baseline: weak baseline

