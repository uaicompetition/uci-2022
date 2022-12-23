---
title: "uai14-mmap"
date: 2022-12-23
permalink: /results/ongoing-leader-board/solver-scores/uai14-mmap-scores
---


### Description

The uai14 solvers are amalgam belief propagation based solvers created for the UAI-2014 competition by Alex Ihler.  They begin by reparameterizing the model using loopy BP, then build a series of generalized BP reparameterizations whose outer regions are selected via mini-bucket, eventually transitioning, when there is much more time than memory to cutset conditioning of GBP approximations.

### Authors

Alex Ihler


The results below are organized as follows:
- each table displays the solver's normalized score for individual problem instances (and, for PR, MPE, and MMAP, the associated log10 likelihood value) for the task under different time limits
- table values are normalized scores for each evaluated problem as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)


# MMAP

## overall

|         Problem          |      20sec      |     1200sec     |     3600sec     |
| ------------------------ | --------------- | --------------- | --------------- |
| 75-17-5.Q0.5.I4          | 0.0 (-inf)      | 54.2 (-12.6)    | 41.0 (-14.1)    |
| 75-19-5.Q0.5.I2          | 0.0 (-inf)      | 55.0 (-15.9)    | 55.0 (-15.9)    |
| 75-22-5.Q0.5.I2          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 75-23-5.Q0.5.I3          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 75-26-5.Q0.5.I4          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-22-5.Q0.5.I4          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-24-5.Q0.5.I2          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-25-5.Q0.5.I2          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-26-5.Q0.5.I1          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-30-5.Q0.5.I1          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-34-5.Q0.5.I2          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-38-5.Q0.5.I4          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-42-5.Q0.5.I4          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-46-5.Q0.5.I4          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| 90-50-5.Q0.5.I3          | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| Grids_20                 | 70.3 (4791.3)   | 0.0 (nan)       | 0.0 (nan)       |
| Grids_21                 | 38.5 (8207.2)   | 37.8 (8203.9)   | 41.7 (8222.4)   |
| Grids_22                 | 51.1 (2777.8)   | 56.2 (2783.7)   | 62.2 (2790.8)   |
| Grids_23                 | 65.8 (2755.4)   | 72.5 (2762.8)   | 74.5 (2765.0)   |
| Grids_24                 | 45.8 (8015.2)   | 62.1 (8082.1)   | 47.8 (8023.4)   |
| Grids_25                 | 86.4 (1203.6)   | 85.3 (1203.1)   | 98.0 (1209.0)   |
| Grids_26                 | 29.5 (1288.8)   | 45.8 (1297.5)   | 14.7 (1280.9)   |
| Grids_27                 | 31.3 (5371.7)   | 37.4 (5384.0)   | 34.7 (5378.4)   |
| Grids_28                 | 0.0 (1923.8)    | 0.0 (1940.8)    | 15.0 (1948.2)   |
| Grids_29                 | 38.3 (660.1)    | 35.2 (659.4)    | 67.8 (666.3)    |
| ImageAlignment_11        | 100.0 (-824.2)  | 100.0 (-824.2)  | 100.0 (-824.2)  |
| ImageAlignment_12        | 100.0 (-436.7)  | 100.0 (-436.7)  | 100.0 (-436.7)  |
| ImageAlignment_13        | 99.0 (-3004.4)  | 100.0 (-2998.9) | 100.0 (-2998.9) |
| ImageAlignment_14        | 100.0 (-1557.5) | 100.0 (-1557.5) | 100.0 (-1557.5) |
| ImageAlignment_15        | 100.0 (-1177.5) | 0.0 (nan)       | 0.0 (nan)       |
| ObjectDetection_13       | 0.0 (8569.1)    | 0.0 (8883.1)    | 0.0 (8883.1)    |
| ObjectDetection_14       | 64.6 (8638.2)   | 58.7 (8562.9)   | 58.7 (8562.9)   |
| ObjectDetection_15       | 68.9 (11916.6)  | 71.5 (11976.2)  | 71.5 (11976.2)  |
| ObjectDetection_16       | 83.5 (13900.5)  | 88.0 (14021.5)  | 88.0 (14021.5)  |
| ObjectDetection_17       | 66.4 (3992.8)   | 86.1 (4518.2)   | 86.1 (4518.2)   |
| ProteinFolding_11        | 16.6 (1452.8)   | 16.9 (1455.1)   | 29.0 (1528.7)   |
| ProteinFolding_12        | 99.3 (-1549.1)  | 0.0 (nan)       | 0.0 (nan)       |
| ProteinFolding_13        | 100.0 (-143.3)  | 100.0 (-143.3)  | 100.0 (-143.3)  |
| ProteinFolding_14        | 100.0 (-331.7)  | 100.0 (-331.7)  | 100.0 (-331.7)  |
| ProteinFolding_15        | 100.0 (-51.6)   | 100.0 (-51.6)   | 100.0 (-51.6)   |
| Segmentation_11          | 57.0 (-135.6)   | 84.5 (-133.4)   | 84.5 (-133.4)   |
| Segmentation_12          | 100.0 (-21.9)   | 100.0 (-21.9)   | 100.0 (-21.9)   |
| Segmentation_13          | 100.0 (-21.4)   | 100.0 (-21.4)   | 100.0 (-21.4)   |
| Segmentation_14          | 52.4 (-41.1)    | 84.9 (-39.8)    | 84.9 (-39.8)    |
| Segmentation_15          | 73.4 (-169.2)   | 75.1 (-168.8)   | 75.1 (-168.8)   |
| Segmentation_16          | 91.5 (-40.8)    | 91.5 (-40.8)    | 91.5 (-40.8)    |
| Segmentation_17          | 89.6 (-175.9)   | 90.0 (-175.9)   | 91.2 (-175.7)   |
| Segmentation_18          | 71.3 (-38.1)    | 100.0 (-34.0)   | 100.0 (-34.0)   |
| Segmentation_19          | 100.0 (-24.1)   | 100.0 (-24.1)   | 100.0 (-24.1)   |
| Segmentation_20          | 74.0 (-116.7)   | 92.0 (-113.5)   | 92.0 (-113.5)   |
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
| or_chain_16.fg.Q0.5.I3   | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
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
| pedigree1.Q0.5.I3        | 53.4 (-38.7)    | 68.1 (-37.8)    | 68.1 (-37.8)    |
| pedigree13.Q0.5.I1       | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| pedigree18.Q0.5.I1       | 0.0 (-inf)      | 91.5 (-116.4)   | 91.5 (-116.4)   |
| pedigree19.Q0.5.I4       | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| pedigree20.Q0.5.I2       | 0.0 (-inf)      | 38.8 (-72.8)    | 38.8 (-72.8)    |
| pedigree25.Q0.5.I2       | 0.0 (-inf)      | 37.4 (-175.7)   | 49.3 (-170.0)   |
| pedigree30.Q0.5.I2       | 0.0 (-inf)      | 72.1 (-140.8)   | 72.1 (-140.8)   |
| pedigree31.Q0.5.I2       | 59.7 (-147.7)   | 0.0 (-inf)      | 43.0 (-161.1)   |
| pedigree33.Q0.5.I2       | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| pedigree38.Q0.5.I2       | 0.0 (-inf)      | 72.2 (-90.5)    | 72.2 (-90.5)    |
| pedigree41.Q0.5.I2       | 0.0 (-inf)      | 21.0 (-160.7)   | 21.0 (-160.7)   |
| pedigree44.Q0.5.I4       | 0.0 (-inf)      | 0.0 (-inf)      | 0.0 (-inf)      |
| pedigree50.Q0.5.I1       | 64.0 (-63.2)    | 43.6 (-69.6)    | 43.6 (-69.6)    |
| pedigree7.Q0.5.I2        | 0.0 (-inf)      | 0.0 (-inf)      | 1.1 (-136.4)    |
| pedigree9.Q0.5.I3        | 0.0 (-inf)      | 29.3 (-159.0)   | 29.3 (-159.0)   |
| pomdp10-12_7_3_8_4.mmap  | 0.0 (nan)       | 100.0 (1.2)     | 100.0 (1.2)     |
| pomdp6-12_6_2_6_3.mmap   | 100.0 (1.0)     | 95.2 (1.0)      | 95.2 (1.0)      |
| pomdp7-20_10_2_10_3.mmap | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| pomdp8-14_9_3_12_4.mmap  | 0.0 (nan)       | 0.0 (nan)       | 91.5 (1.4)      |
| pomdp9-14_8_3_10_4.mmap  | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| wcsp_14                  | 0.0 (nan)       | 82.3 (-21.3)    | 82.6 (-20.9)    |
| wcsp_15                  | 0.0 (-409.1)    | 0.0 (-228.9)    | 0.0 (-193.8)    |
| wcsp_16                  | 76.3 (0.7)      | 74.3 (-1.3)     | 66.7 (-8.5)     |
| wcsp_17                  | 67.9 (-25.6)    | 0.0 (nan)       | 0.0 (nan)       |
| wcsp_18                  | 0.0 (-73.4)     | 70.6 (-16.9)    | 70.6 (-16.9)    |

