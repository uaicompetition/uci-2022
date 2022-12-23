---
title: "uai14-mar"
date: 2022-12-22
permalink: /results/shadow-final-pt3-ongoing-evaluations-leader-board-2022-12-22/solver-scores/uai14-mar-scores
---


### Description

The uai14 solvers are amalgam belief propagation based solvers created for the UAI-2014 competition by Alex Ihler.  They begin by reparameterizing the model using loopy BP, then build a series of generalized BP reparameterizations whose outer regions are selected via mini-bucket, eventually transitioning, when there is much more time than memory to cutset conditioning of GBP approximations.

### Authors

Alex Ihler


The results below are organized as follows:
- each table displays the solver's normalized score for individual problem instances (and, for PR, MPE, and MMAP, the associated log10 likelihood value) for the task under different time limits
- table values are normalized scores for each evaluated problem as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)


# MAR

## overall

|         Problem          | 20sec | 1200sec | 3600sec |
| ------------------------ | ----: | ------: | ------: |
| 1aie                     | 100.0 |   100.0 |   100.0 |
| 1bxv                     | 100.0 |   100.0 |   100.0 |
| 1g6x                     | 100.0 |   100.0 |   100.0 |
| 1jer                     | 100.0 |   100.0 |   100.0 |
| 1npl                     | 100.0 |   100.0 |   100.0 |
| 1qt9                     |  98.0 |    99.9 |    99.9 |
| 1rfs                     | 100.0 |   100.0 |   100.0 |
| 2rta                     | 100.0 |   100.0 |   100.0 |
| BN_12                    |   0.0 |    99.6 |    99.6 |
| BN_13                    |   0.0 |    99.7 |    99.7 |
| BN_15                    |  99.4 |     0.0 |     0.0 |
| BN_31                    |  99.3 |    99.9 |   100.0 |
| blockmap_10_01-0009      |   0.0 |     0.0 |     0.0 |
| blockmap_10_02-0009      |   0.0 |     0.0 |     0.0 |
| blockmap_10_03-0009      |   0.0 |     0.0 |   100.0 |
| blockmap_10_03-0010      |   0.0 |     0.0 |     0.0 |
| blockmap_15_01-0008      |   0.0 |     0.0 |     0.0 |
| blockmap_15_02-0008      |   0.0 |   100.0 |   100.0 |
| blockmap_15_03-0010      |   0.0 |   100.0 |   100.0 |
| blockmap_20_01-0009      |   0.0 |    99.8 |    99.8 |
| bwt3ac.wcsp              |   0.0 |    72.0 |    64.0 |
| fs-07                    |   0.0 |   100.0 |   100.0 |
| mastermind_03_08_04-0000 |  74.7 |    98.9 |    99.8 |
| mastermind_03_08_04-0001 |  99.1 |    99.2 |    99.2 |
| mastermind_03_08_04-0002 |  99.6 |    99.6 |    99.6 |
| mastermind_03_08_04-0003 |  98.2 |    98.1 |    98.1 |
| mastermind_03_08_04-0007 |   0.0 |   100.0 |   100.0 |
| mastermind_03_08_04-0008 |   0.0 |   100.0 |   100.0 |
| mastermind_03_08_04-0010 |   0.0 |     0.0 |     0.0 |
| mastermind_03_08_04-0012 |  55.3 |    42.3 |    61.5 |
| mastermind_03_08_04-0013 |  63.2 |    14.0 |    74.3 |
| mastermind_03_08_04-0014 |  56.0 |    42.2 |    66.0 |
| mastermind_03_08_04-0015 |  64.7 |    88.7 |    95.4 |
| mastermind_03_08_05-0001 |   0.0 |    98.5 |    78.1 |
| mastermind_03_08_05-0003 |   0.0 |    99.4 |    81.7 |
| mastermind_03_08_05-0009 |  55.2 |     0.0 |     0.0 |
| mastermind_04_08_03-0000 |  99.6 |    99.3 |    99.3 |
| mastermind_04_08_03-0011 |  47.0 |   100.0 |   100.0 |
| mastermind_04_08_03-0012 |  62.6 |   100.0 |   100.0 |
| mastermind_04_08_03-0013 |  62.2 |   100.0 |   100.0 |
| mastermind_04_08_03-0014 |  34.3 |   100.0 |   100.0 |
| mastermind_04_08_03-0015 |  41.4 |   100.0 |   100.0 |
| mastermind_04_08_04-0001 |  98.1 |    97.7 |    74.3 |
| mastermind_04_08_04-0002 |  75.6 |    99.5 |    68.3 |
| mastermind_04_08_04-0003 |  77.7 |    99.6 |    99.9 |
| mastermind_04_08_04-0004 |  75.0 |    99.6 |    99.9 |
| mastermind_04_08_04-0005 |  99.0 |    99.1 |    83.4 |
| mastermind_05_08_03-0001 |  99.6 |    99.8 |    99.9 |
| mastermind_05_08_03-0002 |  99.4 |    99.5 |    99.5 |
| mastermind_05_08_03-0003 |  99.2 |    99.0 |    99.0 |
| mastermind_05_08_03-0004 |  99.6 |    99.6 |    99.6 |
| mastermind_05_08_03-0009 |   0.0 |    73.5 |    73.5 |
| mastermind_05_08_03-0011 |  74.8 |    97.3 |    54.6 |
| mastermind_05_08_03-0012 |  73.8 |    97.6 |    99.5 |
| mastermind_05_08_03-0013 |  67.5 |    94.1 |    80.6 |
| mastermind_05_08_03-0015 |   0.0 |    97.6 |    59.3 |
| mastermind_06_08_03-0002 |  99.4 |    99.3 |    86.6 |
| mastermind_06_08_03-0003 |  99.8 |    99.7 |    89.1 |
| mastermind_06_08_03-0005 | 100.0 |   100.0 |   100.0 |
| mastermind_06_08_03-0009 |   0.0 |    72.7 |    73.8 |
| mastermind_10_08_03-0008 |  30.5 |     0.0 |     0.0 |
| mastermind_10_08_03-0009 |  77.6 |    77.7 |    77.7 |
| myciel5g_3.wcsp          | 100.0 |   100.0 |   100.0 |
| or_chain_102.fg          |  13.3 |    54.5 |    64.2 |
| or_chain_106.fg          |  88.8 |    72.5 |    92.8 |
| or_chain_107.fg          |  57.2 |    55.7 |    63.6 |
| or_chain_12.fg           |  17.7 |    90.2 |   100.0 |
| or_chain_128.fg          |  45.5 |    77.3 |    94.7 |
| or_chain_132.fg          |  97.5 |    97.6 |    99.1 |
| or_chain_138.fg          |  96.1 |    99.2 |    99.9 |
| or_chain_140.fg          |  66.6 |     0.0 |     5.0 |
| or_chain_149.fg          |  97.9 |   100.0 |    97.9 |
| or_chain_15.fg           |  84.7 |    85.0 |    59.2 |
| or_chain_150.fg          |  50.1 |    54.2 |    55.3 |
| or_chain_153.fg          |  12.6 |    89.2 |   100.0 |
| or_chain_155.fg          |  93.9 |    93.9 |    98.7 |
| or_chain_161.fg          |  32.2 |    76.4 |    97.7 |
| or_chain_186.fg          |  67.2 |    63.6 |   100.0 |
| or_chain_188.fg          |  71.8 |   100.0 |   100.0 |
| or_chain_198.fg          |  99.2 |    99.2 |    99.6 |
| or_chain_209.fg          |  87.5 |    99.9 |    99.9 |
| or_chain_242.fg          |  58.0 |    78.5 |    95.5 |
| or_chain_4.fg            |  24.3 |    57.0 |    61.2 |
| or_chain_53.fg           |  99.7 |    99.7 |    99.7 |
| or_chain_61.fg           |  82.9 |    86.6 |    84.5 |
| or_chain_64.fg           |   0.0 |    96.9 |   100.0 |
| or_chain_90.fg           |  35.9 |   100.0 |   100.0 |
| queen5_5_3.wcsp          | 100.0 |   100.0 |   100.0 |

