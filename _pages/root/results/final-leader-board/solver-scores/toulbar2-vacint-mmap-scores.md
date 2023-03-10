---
title: "toulbar2-vacint-mmap"
date: 2023-03-10
permalink: /results/final-leader-board/solver-scores/toulbar2-vacint-mmap-scores
---


### Description

Toulbar2-VACINT uses an initial upper bound solution found by INCOP local search. Next, the solver enforces Virtual Arc Consistency in preprocessing. A hybrid best-first search method is performed, restarting from the root after a given backtrack number and following VAC-integrality/Full-EAC variable ordering heuristic. The solver also applies a VAC-based upper bound probing heuristic to find good solutions in preprocessing. [Toulbar2](https://github.com/toulbar2/toulbar2)

### Authors

David Allouche, Simon de Givry, George Katsirelos, Thomas Schiex, and Fulya Trösser


The results below are organized as follows:
- each table displays the solver's normalized score for individual problem instances (and the associated log10 likelihood value) for the given task under different time limits
- table values are normalized scores for each evaluated problem as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)


# MMAP

## overall

|         Problem          |      20sec      |     1200sec     |     3600sec     |
| ------------------------ | --------------- | --------------- | --------------- |
| 75-17-5.Q0.5.I4          | 97.9 (-7.7)     | 97.9 (-7.7)     | 97.9 (-7.7)     |
| 75-19-5.Q0.5.I2          | 100.0 (-9.6)    | 100.0 (-9.6)    | 100.0 (-9.6)    |
| 75-22-5.Q0.5.I2          | 98.3 (-11.7)    | 98.3 (-11.7)    | 98.3 (-11.7)    |
| 75-23-5.Q0.5.I3          | 100.0 (-12.5)   | 100.0 (-12.5)   | 100.0 (-12.5)   |
| 75-26-5.Q0.5.I4          | 99.5 (-18.2)    | 100.0 (-18.1)   | 100.0 (-18.1)   |
| 90-22-5.Q0.5.I4          | 100.0 (-5.6)    | 100.0 (-5.6)    | 100.0 (-5.6)    |
| 90-24-5.Q0.5.I2          | 99.4 (-5.7)     | 99.4 (-5.7)     | 99.4 (-5.7)     |
| 90-25-5.Q0.5.I2          | 100.0 (-7.7)    | 100.0 (-7.7)    | 100.0 (-7.7)    |
| 90-26-5.Q0.5.I1          | 99.5 (-8.7)     | 99.5 (-8.7)     | 99.5 (-8.7)     |
| 90-30-5.Q0.5.I1          | 100.0 (-10.9)   | 100.0 (-10.9)   | 100.0 (-10.9)   |
| 90-34-5.Q0.5.I2          | 100.0 (-12.2)   | 100.0 (-12.2)   | 100.0 (-12.2)   |
| 90-38-5.Q0.5.I4          | 100.0 (-16.8)   | 100.0 (-16.8)   | 100.0 (-16.8)   |
| 90-42-5.Q0.5.I4          | 100.0 (-17.0)   | 100.0 (-17.0)   | 100.0 (-17.0)   |
| 90-46-5.Q0.5.I4          | 99.0 (-24.8)    | 98.7 (-24.9)    | 98.7 (-24.9)    |
| 90-50-5.Q0.5.I3          | 98.7 (-26.4)    | 100.0 (-25.7)   | 100.0 (-25.7)   |
| Grids_20                 | 51.7 (4761.5)   | 82.7 (4811.2)   | 86.1 (4816.7)   |
| Grids_21                 | 69.2 (8353.4)   | 70.2 (8357.8)   | 70.2 (8357.8)   |
| Grids_22                 | 59.9 (2788.1)   | 66.9 (2796.2)   | 67.6 (2797.1)   |
| Grids_23                 | 84.5 (2776.2)   | 86.8 (2778.7)   | 86.8 (2778.7)   |
| Grids_24                 | 80.6 (8157.8)   | 81.4 (8160.9)   | 81.4 (8160.9)   |
| Grids_25                 | 77.7 (1199.5)   | 77.7 (1199.5)   | 77.7 (1199.5)   |
| Grids_26                 | 89.1 (1320.5)   | 90.8 (1321.4)   | 90.8 (1321.4)   |
| Grids_27                 | 49.4 (5407.8)   | 49.5 (5408.1)   | 56.7 (5422.5)   |
| Grids_28                 | 65.6 (1968.6)   | 88.1 (1977.7)   | 89.4 (1978.2)   |
| Grids_29                 | 53.1 (663.2)    | 96.6 (672.3)    | 96.6 (672.3)    |
| ImageAlignment_11        | 100.0 (-824.2)  | 100.0 (-824.2)  | 100.0 (-824.2)  |
| ImageAlignment_12        | 100.0 (-436.7)  | 100.0 (-436.7)  | 100.0 (-436.7)  |
| ImageAlignment_13        | 99.8 (-2999.8)  | 99.8 (-2999.8)  | 99.8 (-2999.8)  |
| ImageAlignment_14        | 100.0 (-1557.5) | 100.0 (-1557.5) | 100.0 (-1557.5) |
| ImageAlignment_15        | 100.0 (-1177.5) | 100.0 (-1177.5) | 100.0 (-1177.5) |
| ObjectDetection_13       | 100.0 (9970.6)  | 100.0 (9970.6)  | 100.0 (9970.6)  |
| ObjectDetection_14       | 100.0 (9093.7)  | 100.0 (9093.7)  | 100.0 (9093.7)  |
| ObjectDetection_15       | 100.0 (12633.3) | 100.0 (12633.3) | 100.0 (12633.3) |
| ObjectDetection_16       | 100.0 (14347.1) | 100.0 (14347.1) | 100.0 (14347.1) |
| ObjectDetection_17       | 100.0 (4887.4)  | 100.0 (4887.4)  | 100.0 (4887.4)  |
| ProteinFolding_11        | 98.4 (1952.7)   | 99.6 (1959.7)   | 99.6 (1959.7)   |
| ProteinFolding_12        | 100.0 (-1547.0) | 100.0 (-1547.0) | 100.0 (-1547.0) |
| ProteinFolding_13        | 100.0 (-143.3)  | 100.0 (-143.3)  | 100.0 (-143.3)  |
| ProteinFolding_14        | 100.0 (-331.7)  | 100.0 (-331.7)  | 100.0 (-331.7)  |
| ProteinFolding_15        | 100.0 (-51.6)   | 100.0 (-51.6)   | 100.0 (-51.6)   |
| Segmentation_11          | 97.8 (-132.3)   | 97.8 (-132.3)   | 97.8 (-132.3)   |
| Segmentation_12          | 100.0 (-21.9)   | 100.0 (-21.9)   | 100.0 (-21.9)   |
| Segmentation_13          | 100.0 (-21.4)   | 100.0 (-21.4)   | 100.0 (-21.4)   |
| Segmentation_14          | 100.0 (-39.3)   | 100.0 (-39.3)   | 100.0 (-39.3)   |
| Segmentation_15          | 100.0 (-163.8)  | 100.0 (-163.8)  | 100.0 (-163.8)  |
| Segmentation_16          | 100.0 (-40.4)   | 100.0 (-40.4)   | 100.0 (-40.4)   |
| Segmentation_17          | 100.0 (-174.3)  | 100.0 (-174.3)  | 100.0 (-174.3)  |
| Segmentation_18          | 100.0 (-34.0)   | 100.0 (-34.0)   | 100.0 (-34.0)   |
| Segmentation_19          | 100.0 (-24.1)   | 100.0 (-24.1)   | 100.0 (-24.1)   |
| Segmentation_20          | 100.0 (-112.0)  | 100.0 (-112.0)  | 100.0 (-112.0)  |
| bw_p24_16                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p24_20                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p34_15                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p34_20                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p44_15                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p44_19                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p54_10                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| bw_p54_16                | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| comm_p01_16              | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| comm_p01_20              | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_11.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_16.fg.Q0.5.I3   | 100.0 (-23.4)   | 100.0 (-23.4)   | 100.0 (-23.4)   |
| or_chain_22.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_24.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_25.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_32.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_36.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_39.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_40.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_41.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_43.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_6.fg.Q0.5.I3    | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_60.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_63.fg.Q0.5.I3   | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| or_chain_8.fg.Q0.5.I3    | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| pedigree1.Q0.5.I3        | 100.0 (-35.7)   | 100.0 (-35.7)   | 100.0 (-35.7)   |
| pedigree13.Q0.5.I1       | 99.2 (-62.7)    | 99.2 (-62.7)    | 99.2 (-62.7)    |
| pedigree18.Q0.5.I1       | 97.2 (-113.2)   | 96.8 (-113.4)   | 97.7 (-112.9)   |
| pedigree19.Q0.5.I4       | 93.0 (-91.5)    | 94.6 (-90.4)    | 95.8 (-89.5)    |
| pedigree20.Q0.5.I2       | 100.0 (-46.1)   | 100.0 (-46.1)   | 100.0 (-46.1)   |
| pedigree25.Q0.5.I2       | 96.4 (-147.3)   | 96.4 (-147.3)   | 96.4 (-147.3)   |
| pedigree30.Q0.5.I2       | 97.6 (-124.6)   | 100.0 (-123.1)  | 100.0 (-123.1)  |
| pedigree31.Q0.5.I2       | 97.2 (-117.6)   | 97.2 (-117.6)   | 97.2 (-117.6)   |
| pedigree33.Q0.5.I2       | 95.6 (-70.4)    | 95.6 (-70.4)    | 95.6 (-70.4)    |
| pedigree38.Q0.5.I2       | 99.6 (-77.6)    | 99.6 (-77.6)    | 99.6 (-77.6)    |
| pedigree41.Q0.5.I2       | 96.4 (-108.1)   | 97.0 (-107.7)   | 97.0 (-107.7)   |
| pedigree44.Q0.5.I4       | 97.8 (-88.7)    | 96.3 (-89.4)    | 96.3 (-89.4)    |
| pedigree50.Q0.5.I1       | 96.5 (-53.1)    | 96.5 (-53.1)    | 96.5 (-53.1)    |
| pedigree7.Q0.5.I2        | 98.9 (-98.0)    | 98.9 (-98.0)    | 98.9 (-98.0)    |
| pedigree9.Q0.5.I3        | 99.8 (-112.8)   | 100.0 (-112.7)  | 100.0 (-112.7)  |
| pomdp10-12_7_3_8_4.mmap  | 0.0 (nan)       | 100.0 (1.2)     | 100.0 (1.2)     |
| pomdp6-12_6_2_6_3.mmap   | 72.0 (1.0)      | 93.8 (1.0)      | 93.8 (1.0)      |
| pomdp7-20_10_2_10_3.mmap | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| pomdp8-14_9_3_12_4.mmap  | 89.6 (1.4)      | 89.6 (1.4)      | 89.6 (1.4)      |
| pomdp9-14_8_3_10_4.mmap  | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| wcsp_14                  | 100.0 (1.1)     | 100.0 (1.1)     | 100.0 (1.1)     |
| wcsp_15                  | 96.4 (-78.6)    | 96.4 (-78.6)    | 96.4 (-78.6)    |
| wcsp_16                  | 99.6 (22.8)     | 99.6 (22.8)     | 99.6 (22.8)     |
| wcsp_17                  | 99.1 (33.4)     | 100.0 (35.0)    | 100.0 (35.0)    |
| wcsp_18                  | 100.0 (0.2)     | 100.0 (0.2)     | 100.0 (0.2)     |

