---
title: "toulbar2-vns-mmap"
date: 2022-12-22
permalink: /results/shadow-trial4-w-1,4,5-leader-board-2022-12-22/solver-scores/toulbar2-vns-mmap-scores
---


### Description

Toulbar2-VNS is a metaheuristic called variable neighborhood search that uses (partial) tree search inside its local neighborhood exploration. The approach consists of several neighborhood explorations of increasing search complexity, by controlling two parameters, the discrepancy limit, and the neighborhood size. Thus, the optimality of the obtained solutions can be proven when the neighborhood size is maximal and with an unbounded tree search. The tree decomposition uses a minimum fill-in ordering. Leaf clusters are merged with their fathers if the number of proper variables is too small. [Toulbar2](https://github.com/toulbar2/toulbar2)

### Authors

David Allouche, Simon de Givry, Samir Loudni, and Abdelkader Ouali


The results below are organized as follows:
- each table displays the solver's performance for individual problem instances for the given task under different time limits
- table values are normalized scores for each evaluated problem as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)


# MMAP

## overall

|         Problem          |      20sec      |     1200sec     |     3600sec     |
| ------------------------ | --------------- | --------------- | --------------- |
| 75-17-5.Q0.5.I4          | 97.9 (-7.7)     | 97.9 (-7.7)     | 97.9 (-7.7)     |
| 75-19-5.Q0.5.I2          | 100.0 (-9.6)    | 100.0 (-9.6)    | 100.0 (-9.6)    |
| 75-22-5.Q0.5.I2          | 98.3 (-11.7)    | 98.3 (-11.7)    | 98.3 (-11.7)    |
| 75-23-5.Q0.5.I3          | 100.0 (-12.5)   | 100.0 (-12.5)   | 100.0 (-12.5)   |
| 75-26-5.Q0.5.I4          | 98.3 (-18.6)    | 100.0 (-18.1)   | 100.0 (-18.1)   |
| 90-22-5.Q0.5.I4          | 100.0 (-5.6)    | 100.0 (-5.6)    | 100.0 (-5.6)    |
| 90-24-5.Q0.5.I2          | 99.4 (-5.7)     | 99.4 (-5.7)     | 99.4 (-5.7)     |
| 90-25-5.Q0.5.I2          | 100.0 (-7.7)    | 100.0 (-7.7)    | 100.0 (-7.7)    |
| 90-26-5.Q0.5.I1          | 99.5 (-8.7)     | 99.5 (-8.7)     | 99.5 (-8.7)     |
| 90-30-5.Q0.5.I1          | 100.0 (-10.9)   | 100.0 (-10.9)   | 100.0 (-10.9)   |
| 90-34-5.Q0.5.I2          | 100.0 (-12.2)   | 100.0 (-12.2)   | 100.0 (-12.2)   |
| 90-38-5.Q0.5.I4          | 97.3 (-17.4)    | 100.0 (-16.8)   | 100.0 (-16.8)   |
| 90-42-5.Q0.5.I4          | 97.7 (-17.7)    | 100.0 (-17.0)   | 100.0 (-17.0)   |
| 90-46-5.Q0.5.I4          | 99.1 (-24.8)    | 98.4 (-25.0)    | 100.0 (-24.5)   |
| 90-50-5.Q0.5.I3          | 100.0 (-25.7)   | 100.0 (-25.7)   | 100.0 (-25.7)   |
| Grids_20                 | 73.2 (4796.0)   | 98.4 (4836.5)   | 98.4 (4836.5)   |
| Grids_21                 | 83.3 (8420.1)   | 87.0 (8438.1)   | 87.0 (8438.1)   |
| Grids_22                 | 71.0 (2801.1)   | 90.0 (2823.4)   | 90.0 (2823.4)   |
| Grids_23                 | 88.3 (2780.3)   | 88.3 (2780.3)   | 88.3 (2780.3)   |
| Grids_24                 | 80.1 (8155.9)   | 84.8 (8175.2)   | 84.8 (8175.2)   |
| Grids_25                 | 98.4 (1209.1)   | 98.4 (1209.1)   | 98.4 (1209.1)   |
| Grids_26                 | 87.3 (1319.6)   | 87.3 (1319.6)   | 92.4 (1322.2)   |
| Grids_27                 | 84.3 (5477.6)   | 90.4 (5489.7)   | 90.4 (5489.7)   |
| Grids_28                 | 75.5 (1972.6)   | 75.5 (1972.6)   | 75.5 (1972.6)   |
| Grids_29                 | 87.7 (670.4)    | 87.7 (670.4)    | 87.7 (670.4)    |
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
| ProteinFolding_11        | 97.1 (1944.8)   | 97.1 (1944.8)   | 97.1 (1944.8)   |
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
| or_chain_16.fg.Q0.5.I3   | 99.7 (-23.6)    | 100.0 (-23.4)   | 100.0 (-23.4)   |
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
| pedigree1.Q0.5.I3        | 94.0 (-36.1)    | 94.0 (-36.1)    | 94.0 (-36.1)    |
| pedigree13.Q0.5.I1       | 99.7 (-62.5)    | 99.7 (-62.5)    | 99.7 (-62.5)    |
| pedigree18.Q0.5.I1       | 96.7 (-113.5)   | 96.7 (-113.5)   | 96.7 (-113.5)   |
| pedigree19.Q0.5.I4       | 93.9 (-90.9)    | 94.8 (-90.2)    | 95.7 (-89.6)    |
| pedigree20.Q0.5.I2       | 100.0 (-46.1)   | 100.0 (-46.1)   | 100.0 (-46.1)   |
| pedigree25.Q0.5.I2       | 100.0 (-145.6)  | 95.4 (-147.8)   | 95.4 (-147.8)   |
| pedigree30.Q0.5.I2       | 98.8 (-123.9)   | 98.2 (-124.3)   | 98.2 (-124.3)   |
| pedigree31.Q0.5.I2       | 100.0 (-115.4)  | 99.8 (-115.6)   | 99.8 (-115.6)   |
| pedigree33.Q0.5.I2       | 94.4 (-71.1)    | 94.4 (-71.1)    | 94.4 (-71.1)    |
| pedigree38.Q0.5.I2       | 99.2 (-77.8)    | 99.2 (-77.8)    | 99.2 (-77.8)    |
| pedigree41.Q0.5.I2       | 98.4 (-106.7)   | 96.3 (-108.2)   | 96.3 (-108.2)   |
| pedigree44.Q0.5.I4       | 100.0 (-87.7)   | 96.5 (-89.3)    | 95.6 (-89.7)    |
| pedigree50.Q0.5.I1       | 100.0 (-52.0)   | 100.0 (-52.0)   | 100.0 (-52.0)   |
| pedigree7.Q0.5.I2        | 97.9 (-98.3)    | 97.9 (-98.3)    | 97.9 (-98.3)    |
| pedigree9.Q0.5.I3        | 95.9 (-115.4)   | 98.0 (-114.0)   | 98.0 (-114.0)   |
| pomdp10-12_7_3_8_4.mmap  | 0.0 (nan)       | 100.0 (1.2)     | 100.0 (1.2)     |
| pomdp6-12_6_2_6_3.mmap   | 93.8 (1.0)      | 93.8 (1.0)      | 93.8 (1.0)      |
| pomdp7-20_10_2_10_3.mmap | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| pomdp8-14_9_3_12_4.mmap  | 88.3 (1.4)      | 89.3 (1.4)      | 89.3 (1.4)      |
| pomdp9-14_8_3_10_4.mmap  | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| wcsp_14                  | 100.0 (1.1)     | 100.0 (1.1)     | 100.0 (1.1)     |
| wcsp_15                  | 78.3 (-98.4)    | 92.0 (-83.4)    | 92.0 (-83.4)    |
| wcsp_16                  | 100.0 (23.2)    | 100.0 (23.2)    | 100.0 (23.2)    |
| wcsp_17                  | 99.9 (34.8)     | 99.9 (34.8)     | 99.9 (34.8)     |
| wcsp_18                  | 100.0 (0.2)     | 100.0 (0.2)     | 100.0 (0.2)     |

