---
title: "Sep 7th. Mini Evaluation of Submitted Solvers"
---

The evaluation results are organized in the following structure.
- Total scores per tasks using normalized scores as shown in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)
- Link to the result output and logfiles.
- Solution and individual score per problem


# Total Scores

* Each cell shows avergae of the total score, the total score, and the total number of instancs.

## PR Task

| time (sec) | 20 | 1200 | 3600 |
|:--------|--------:|--------:|--------:|
| lbp-ihler-pr | -0.88 (-119.000/136) | -0.01 (-2.000/136) | -0.01 (-2.000/136) |
| uai14-ihler-pr | 0.44 (59.901/136) | 0.95 (129.739/136) | 0.95 (129.514/136) |

### Solvers
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-pr/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-pr)

## MAR Task
 
| time (sec) | 20 | 1200 | 3600 |
|:--------|--------:|--------:|--------:|
| lbp-ihler-mar | -0.87 (-114.687/132) | -0.02 (-3.000/132) | -0.01 (-1.000/132) |
| uai14-ihler-mar | 0.27 (35.554/132) | 0.98 (129.908/132) | 0.98 (129.979/132) |



### Solvers
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-mar/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mar)


## MPE Task

| time (sec) | 20 | 1200 | 3600 |
|:--------|--------:|--------:|--------:|
| dallouche | 0.70 (84.048/120) | 0.73 (87.374/120) | 0.75 (89.447/120) |
| daoopt | 0.95 (114.515/120) | 0.99 (118.655/120) | 1.00 (119.983/120) |
| daoopt-weak | 0.23 (27.055/120) | 0.45 (54.431/120) | 0.48 (57.671/120) |
| uai14-ihler-mpe | 0.11 (13.141/120) | 0.12 (14.818/120) | 0.13 (15.612/120) |


### Solvers
- dallouche: new submission this year
- daoopt: uai 2012, 2014, and 2016 participant by Lars Otten [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/daoopt-1hr-ib35)
- daoopt-weak: weaken the options in daoopt
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mpe)


## MMAP Task
 
| time (sec) | 20 | 1200 | 3600 |
|:--------|--------:|--------:|--------:|
| daoopt | 0.82(98.211/120) | 0.95(114.391/120) | 0.94(112.646/120) |
| lbp-ihler-mmap | -0.98(-118.000/120) | -0.02(-2.684/120) | 0.05(6.071/120) |
| uai14-ihler-mmap | -0.33(-39.969/120) | -0.25(-29.564/120) | -0.33(-39.315/120) |

  
### Solvers
- daoopt: take MPE solution from daoopt and truncate to MMAP solution
- lbp: loopy belief propagation [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/blob/main/docker/lbp-ihler-mmap/Dockerfile)
- uai14-ihler: uai 2014 participant by Alex Iher [Dockerfile](https://github.com/dechterlab/uai-competition-evaluations/tree/main/docker/uai14-ihler-mmap)


# Link to the results and logs

* The archive [Link](https://uaicompetition.github.io/uci-2022/leaderboard/leader_board_001.zip) for the all results and log files.


# Problem Scores

* Each cell shows the individual score and the returned solution.

## PR Task

| solver | problem | 20 sec | 1200 sec | 3600 sec |
|:--------|--------:|--------:|--------:|--------:|
| lbp-ihler-pr | Alchemy_11 | -1.00 (  nan) | 0.00 (606.265000) | 0.00 (606.265000) |
| lbp-ihler-pr | CSP_11 | -1.00 (  nan) | 0.00 (14.710500) | 0.00 (14.710500) |
| lbp-ihler-pr | CSP_12 | 0.00 (17.277600) | 0.00 (17.277600) | 0.00 (17.277600) |
| lbp-ihler-pr | CSP_13 | -1.00 (  nan) | 0.00 (16.969500) | 0.00 (16.969500) |
| lbp-ihler-pr | DBN_11 | -1.00 (  nan) | 0.00 (58.483700) | 0.00 (58.483700) |
| lbp-ihler-pr | DBN_12 | -1.00 (  nan) | 0.00 (63.112800) | 0.00 (63.112800) |
| lbp-ihler-pr | DBN_13 | -1.00 (  nan) | 0.00 (66.120100) | 0.00 (66.120100) |
| lbp-ihler-pr | DBN_14 | -1.00 (  nan) | 1.00 (151.155000) | 1.00 (151.155000) |
| lbp-ihler-pr | DBN_15 | -1.00 (  nan) | 0.00 (150.656000) | 0.00 (150.656000) |
| lbp-ihler-pr | DBN_16 | -1.00 (  nan) | 0.00 (166.103000) | 0.00 (166.103000) |
| lbp-ihler-pr | Grids_11 | 0.00 (184.906000) | 0.00 (184.906000) | 0.00 (184.906000) |
| lbp-ihler-pr | Grids_12 | 0.00 (349.656000) | 0.00 (349.656000) | 0.00 (349.656000) |
| lbp-ihler-pr | Grids_13 | 0.00 (364.240000) | 0.00 (364.240000) | 0.00 (364.240000) |
| lbp-ihler-pr | Grids_14 | 0.00 (522.174000) | 0.00 (522.174000) | 0.00 (522.174000) |
| lbp-ihler-pr | Grids_15 | -1.00 (  nan) | 0.00 (294.694000) | 0.00 (294.694000) |
| lbp-ihler-pr | Grids_16 | -1.00 (  nan) | 0.00 (719.348000) | 0.00 (719.348000) |
| lbp-ihler-pr | Grids_17 | -1.00 (  nan) | 0.00 (1471.120000) | 0.00 (1471.120000) |
| lbp-ihler-pr | Grids_18 | -1.00 (  nan) | 0.00 (2084.450000) | 0.00 (2084.450000) |
| lbp-ihler-pr | ObjectDetection_11 | -1.00 (  nan) | 0.00 (-75.037600) | 0.00 (-75.037600) |
| lbp-ihler-pr | ObjectDetection_12 | -1.00 (  nan) | 0.00 (-67.588400) | 0.00 (-67.588400) |
| lbp-ihler-pr | ObjectDetection_13 | -1.00 (  nan) | 0.00 (-70.599200) | 0.00 (-70.599200) |
| lbp-ihler-pr | ObjectDetection_14 | -1.00 (  nan) | 0.00 (-64.340800) | 0.00 (-64.340800) |
| lbp-ihler-pr | ObjectDetection_15 | -1.00 (  nan) | 0.00 (-51.889500) | 0.00 (-51.889500) |
| lbp-ihler-pr | ObjectDetection_16 | -1.00 (  nan) | 0.00 (-34.462400) | 0.00 (-34.462400) |
| lbp-ihler-pr | ObjectDetection_17 | -1.00 (  nan) | 0.00 (-29.870900) | 0.00 (-29.870900) |
| lbp-ihler-pr | ObjectDetection_18 | -1.00 (  nan) | 0.00 (-37.314900) | 0.00 (-37.314900) |
| lbp-ihler-pr | ObjectDetection_19 | -1.00 (  nan) | 0.00 (-39.231800) | 0.00 (-39.231800) |
| lbp-ihler-pr | ObjectDetection_20 | -1.00 (  nan) | 0.00 (-35.462900) | 0.00 (-35.462900) |
| lbp-ihler-pr | ObjectDetection_21 | -1.00 (  nan) | 0.00 (-24.496700) | 0.00 (-24.496700) |
| lbp-ihler-pr | ObjectDetection_22 | -1.00 (  nan) | 0.00 (-36.772200) | 0.00 (-36.772200) |
| lbp-ihler-pr | ObjectDetection_23 | -1.00 (  nan) | 0.00 (-31.714200) | 0.00 (-31.714200) |
| lbp-ihler-pr | ObjectDetection_24 | -1.00 (  nan) | 0.00 (-26.458300) | 0.00 (-26.458300) |
| lbp-ihler-pr | ObjectDetection_25 | -1.00 (  nan) | 0.00 (-18.700400) | 0.00 (-18.700400) |
| lbp-ihler-pr | ObjectDetection_26 | -1.00 (  nan) | 0.00 (-33.839200) | 0.00 (-33.839200) |
| lbp-ihler-pr | ObjectDetection_27 | -1.00 (  nan) | 0.00 (-29.912200) | 0.00 (-29.912200) |
| lbp-ihler-pr | ObjectDetection_28 | -1.00 (  nan) | 0.00 (-46.796700) | 0.00 (-46.796700) |
| lbp-ihler-pr | ObjectDetection_29 | -1.00 (  nan) | 0.00 (-50.872500) | 0.00 (-50.872500) |
| lbp-ihler-pr | ObjectDetection_30 | -1.00 (  nan) | 0.00 (-52.563200) | 0.00 (-52.563200) |
| lbp-ihler-pr | ObjectDetection_31 | -1.00 (  nan) | 0.00 (-44.162900) | 0.00 (-44.162900) |
| lbp-ihler-pr | ObjectDetection_32 | -1.00 (  nan) | 0.00 (-46.816700) | 0.00 (-46.816700) |
| lbp-ihler-pr | ObjectDetection_33 | -1.00 (  nan) | 0.00 (-44.217400) | 0.00 (-44.217400) |
| lbp-ihler-pr | ObjectDetection_34 | -1.00 (  nan) | 0.00 (-35.409200) | 0.00 (-35.409200) |
| lbp-ihler-pr | ObjectDetection_35 | -1.00 (  nan) | 0.00 (-37.562000) | 0.00 (-37.562000) |
| lbp-ihler-pr | ObjectDetection_36 | -1.00 (  nan) | 0.00 (-30.690200) | 0.00 (-30.690200) |
| lbp-ihler-pr | ObjectDetection_37 | -1.00 (  nan) | 0.00 (-29.968500) | 0.00 (-29.968500) |
| lbp-ihler-pr | ObjectDetection_38 | -1.00 (  nan) | 0.00 (-75.129300) | 0.00 (-75.129300) |
| lbp-ihler-pr | ObjectDetection_39 | -1.00 (  nan) | 0.00 (-70.264900) | 0.00 (-70.264900) |
| lbp-ihler-pr | ObjectDetection_40 | -1.00 (  nan) | 0.00 (-72.360100) | 0.00 (-72.360100) |
| lbp-ihler-pr | ObjectDetection_41 | -1.00 (  nan) | 0.00 (-73.744500) | 0.00 (-73.744500) |
| lbp-ihler-pr | ObjectDetection_42 | -1.00 (  nan) | 0.00 (-45.230700) | 0.00 (-45.230700) |
| lbp-ihler-pr | ObjectDetection_43 | -1.00 (  nan) | 0.00 (-39.478400) | 0.00 (-39.478400) |
| lbp-ihler-pr | ObjectDetection_44 | -1.00 (  nan) | 0.00 (-41.051700) | 0.00 (-41.051700) |
| lbp-ihler-pr | ObjectDetection_45 | -1.00 (  nan) | 0.00 (-38.960000) | 0.00 (-38.960000) |
| lbp-ihler-pr | ObjectDetection_46 | 0.00 (-43.015900) | 0.00 (-43.015900) | 0.00 (-43.015900) |
| lbp-ihler-pr | ObjectDetection_47 | -1.00 (  nan) | 0.00 (-45.809900) | 0.00 (-45.809900) |
| lbp-ihler-pr | ObjectDetection_48 | -1.00 (  nan) | 0.00 (-37.964900) | 0.00 (-37.964900) |
| lbp-ihler-pr | ObjectDetection_49 | -1.00 (  nan) | 0.00 (-40.052900) | 0.00 (-40.052900) |
| lbp-ihler-pr | ObjectDetection_50 | -1.00 (  nan) | 0.00 (-37.125400) | 0.00 (-37.125400) |
| lbp-ihler-pr | ObjectDetection_51 | -1.00 (  nan) | 0.00 (-53.426300) | 0.00 (-53.426300) |
| lbp-ihler-pr | ObjectDetection_52 | -1.00 (  nan) | 0.00 (-57.042200) | 0.00 (-57.042200) |
| lbp-ihler-pr | ObjectDetection_53 | -1.00 (  nan) | 0.00 (-47.769500) | 0.00 (-47.769500) |
| lbp-ihler-pr | ObjectDetection_54 | -1.00 (  nan) | 0.00 (-41.499400) | 0.00 (-41.499400) |
| lbp-ihler-pr | ObjectDetection_55 | -1.00 (  nan) | 0.00 (-34.131800) | 0.00 (-34.131800) |
| lbp-ihler-pr | ObjectDetection_56 | -1.00 (  nan) | 0.00 (-36.317100) | 0.00 (-36.317100) |
| lbp-ihler-pr | ObjectDetection_57 | -1.00 (  nan) | 0.00 (-33.446000) | 0.00 (-33.446000) |
| lbp-ihler-pr | ObjectDetection_58 | -1.00 (  nan) | 0.00 (-41.684100) | 0.00 (-41.684100) |
| lbp-ihler-pr | ObjectDetection_59 | -1.00 (  nan) | 0.00 (-35.899800) | 0.00 (-35.899800) |
| lbp-ihler-pr | ObjectDetection_60 | -1.00 (  nan) | 0.00 (-35.324100) | 0.00 (-35.324100) |
| lbp-ihler-pr | ObjectDetection_61 | -1.00 (  nan) | 0.00 (-23.154800) | 0.00 (-23.154800) |
| lbp-ihler-pr | ObjectDetection_62 | -1.00 (  nan) | 0.00 (-24.797500) | 0.00 (-24.797500) |
| lbp-ihler-pr | ObjectDetection_63 | -1.00 (  nan) | 0.00 (-19.913100) | 0.00 (-19.913100) |
| lbp-ihler-pr | ObjectDetection_64 | -1.00 (  nan) | 0.00 (-21.336400) | 0.00 (-21.336400) |
| lbp-ihler-pr | ObjectDetection_65 | -1.00 (  nan) | 0.00 (-19.708200) | 0.00 (-19.708200) |
| lbp-ihler-pr | ObjectDetection_66 | -1.00 (  nan) | 0.00 (-47.070000) | 0.00 (-47.070000) |
| lbp-ihler-pr | ObjectDetection_67 | -1.00 (  nan) | 0.00 (-40.650200) | 0.00 (-40.650200) |
| lbp-ihler-pr | ObjectDetection_68 | -1.00 (  nan) | 0.00 (-42.697300) | 0.00 (-42.697300) |
| lbp-ihler-pr | ObjectDetection_69 | -1.00 (  nan) | 0.00 (-40.300300) | 0.00 (-40.300300) |
| lbp-ihler-pr | ObjectDetection_70 | 0.00 (-31.256100) | 0.00 (-31.256100) | 0.00 (-31.256100) |
| lbp-ihler-pr | ObjectDetection_71 | -1.00 (  nan) | 0.00 (-33.655200) | 0.00 (-33.655200) |
| lbp-ihler-pr | ObjectDetection_72 | -1.00 (  nan) | 0.00 (-26.467900) | 0.00 (-26.467900) |
| lbp-ihler-pr | ObjectDetection_73 | -1.00 (  nan) | 0.00 (-25.726200) | 0.00 (-25.726200) |
| lbp-ihler-pr | ObjectDetection_74 | -1.00 (  nan) | 0.00 (-31.818400) | 0.00 (-31.818400) |
| lbp-ihler-pr | ObjectDetection_75 | -1.00 (  nan) | 0.00 (-33.778800) | 0.00 (-33.778800) |
| lbp-ihler-pr | Pedigree_11 | -1.00 (  nan) | 0.00 (-18.165400) | 0.00 (-18.165400) |
| lbp-ihler-pr | Pedigree_12 | -1.00 (  nan) | 0.00 (-12.083300) | 0.00 (-12.083300) |
| lbp-ihler-pr | Pedigree_13 | -1.00 (  nan) | 0.00 (-16.718500) | 0.00 (-16.718500) |
| lbp-ihler-pr | Promedus_11 | -1.00 (  nan) | 0.00 (-8.580990) | 0.00 (-8.580990) |
| lbp-ihler-pr | Promedus_12 | -1.00 (  nan) | 0.00 (-3.313830) | 0.00 (-3.313830) |
| lbp-ihler-pr | Promedus_13 | -1.00 (  nan) | 0.00 (-4.576000) | 0.00 (-4.576000) |
| lbp-ihler-pr | Promedus_14 | 0.00 (-8.016040) | 0.00 (-8.016040) | 0.00 (-8.016040) |
| lbp-ihler-pr | Promedus_15 | 0.00 (-3.816760) | 0.00 (-3.816760) | 0.00 (-3.816760) |
| lbp-ihler-pr | Promedus_16 | -1.00 (  nan) | 0.00 (-6.989680) | 0.00 (-6.989680) |
| lbp-ihler-pr | Promedus_17 | -1.00 (  nan) | 0.00 (-9.476830) | 0.00 (-9.476830) |
| lbp-ihler-pr | Promedus_18 | -1.00 (  nan) | 0.00 (-4.679630) | 0.00 (-4.679630) |
| lbp-ihler-pr | Promedus_19 | -1.00 (  nan) | 0.00 (-4.344960) | 0.00 (-4.344960) |
| lbp-ihler-pr | Promedus_20 | -1.00 (  nan) | 0.00 (-7.275560) | 0.00 (-7.275560) |
| lbp-ihler-pr | Promedus_21 | -1.00 (  nan) | 0.00 (-5.763760) | 0.00 (-5.763760) |
| lbp-ihler-pr | Promedus_22 | 0.00 (-2.637080) | 0.00 (-2.637080) | 0.00 (-2.637080) |
| lbp-ihler-pr | Promedus_23 | -1.00 (  nan) | 0.00 (-11.543100) | 0.00 (-11.543100) |
| lbp-ihler-pr | Promedus_24 | 0.00 (-5.862860) | 0.00 (-5.862860) | 0.00 (-5.862860) |
| lbp-ihler-pr | Promedus_25 | -1.00 (  nan) | 0.00 (-9.476080) | 0.00 (-9.476080) |
| lbp-ihler-pr | Promedus_26 | -1.00 (  nan) | 0.00 (-7.315150) | 0.00 (-7.315150) |
| lbp-ihler-pr | Promedus_27 | 0.00 (-8.365680) | 0.00 (-8.365680) | 0.00 (-8.365680) |
| lbp-ihler-pr | Promedus_28 | -1.00 (  nan) | 0.00 (-8.282150) | 0.00 (-8.282150) |
| lbp-ihler-pr | Promedus_29 | 0.00 (-10.465600) | 0.00 (-10.465600) | 0.00 (-10.465600) |
| lbp-ihler-pr | Promedus_30 | 0.00 (-22.225500) | 0.00 (-22.225500) | 0.00 (-22.225500) |
| lbp-ihler-pr | Promedus_31 | -1.00 (  nan) | 0.00 (-1.975210) | 0.00 (-1.975210) |
| lbp-ihler-pr | Promedus_32 | -1.00 (  nan) | 0.00 (-2.257180) | 0.00 (-2.257180) |
| lbp-ihler-pr | Promedus_33 | -1.00 (  nan) | 0.00 (-2.808880) | 0.00 (-2.808880) |
| lbp-ihler-pr | Promedus_34 | 0.00 (-3.321810) | 0.00 (-3.321810) | 0.00 (-3.321810) |
| lbp-ihler-pr | Promedus_35 | 0.00 (-1.930880) | 0.00 (-1.930880) | 0.00 (-1.930880) |
| lbp-ihler-pr | Promedus_36 | -1.00 (  nan) | 0.00 (-1.930140) | 0.00 (-1.930140) |
| lbp-ihler-pr | Promedus_37 | -1.00 (  nan) | 0.00 (-4.262200) | 0.00 (-4.262200) |
| lbp-ihler-pr | Promedus_38 | -1.00 (  nan) | 0.00 (-5.206710) | 0.00 (-5.206710) |
| lbp-ihler-pr | Segmentation_11 | -1.00 (  nan) | 0.00 (-25.920600) | 0.00 (-25.920600) |
| lbp-ihler-pr | Segmentation_12 | -1.00 (  nan) | 0.00 (-10.287400) | 0.00 (-10.287400) |
| lbp-ihler-pr | Segmentation_13 | -1.00 (  nan) | 0.00 (-34.362900) | 0.00 (-34.362900) |
| lbp-ihler-pr | Segmentation_14 | -1.00 (  nan) | 0.00 (-39.660500) | 0.00 (-39.660500) |
| lbp-ihler-pr | Segmentation_15 | -1.00 (  nan) | 0.00 (-31.595500) | 0.00 (-31.595500) |
| lbp-ihler-pr | Segmentation_16 | -1.00 (  nan) | 0.00 (-38.514200) | 0.00 (-38.514200) |
| lbp-ihler-pr | grid10x10.f10 | 0.00 (349.656000) | 0.00 (349.656000) | 0.00 (349.656000) |
| lbp-ihler-pr | linkage_12 | -1.00 (  nan) | 0.00 (-71.679500) | 0.00 (-71.679500) |
| lbp-ihler-pr | linkage_13 | -1.00 (  nan) | 0.00 (-77.346700) | 0.00 (-77.346700) |
| lbp-ihler-pr | linkage_14 | -1.00 (  nan) | 0.00 (-31.950700) | 0.00 (-31.950700) |
| lbp-ihler-pr | linkage_16 | -1.00 (  nan) | 0.00 (-41.295900) | 0.00 (-41.295900) |
| lbp-ihler-pr | linkage_18 | -1.00 (  nan) | 0.00 (-81.723800) | 0.00 (-81.723800) |
| lbp-ihler-pr | linkage_19 | -1.00 (  nan) | 0.00 (-62.552500) | 0.00 (-62.552500) |
| lbp-ihler-pr | linkage_21 | -1.00 (  nan) | 0.00 (-31.372400) | 0.00 (-31.372400) |
| lbp-ihler-pr | linkage_22 | -1.00 (  nan) | 0.00 (-57.163800) | 0.00 (-57.163800) |
| lbp-ihler-pr | linkage_23 | -1.00 (  nan) | 0.00 (-125.320000) | 0.00 (-125.320000) |
| lbp-ihler-pr | linkage_24 | -1.00 (  nan) | 0.00 (-87.045800) | 0.00 (-87.045800) |
| lbp-ihler-pr | linkage_26 | -1.00 (  nan) | 0.00 (-118.811000) | 0.00 (-118.811000) |
| lbp-ihler-pr | linkage_27 | -1.00 (  nan) | 0.00 (-67.653700) | 0.00 (-67.653700) |
| lbp-ihler-pr | relational_2 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-pr | relational_3 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-pr | relational_5 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-pr | Alchemy_11 | 1.00 (606.279000) | 1.00 (606.279000) | 1.00 (606.279000) |
| uai14-ihler-pr | CSP_11 | 0.00 (13.582700) | 1.00 (13.563000) | 1.00 (13.563000) |
| uai14-ihler-pr | CSP_12 | 1.00 (16.453600) | 1.00 (16.453600) | 1.00 (16.453600) |
| uai14-ihler-pr | CSP_13 | 1.00 (15.303700) | 1.00 (15.303700) | 1.00 (15.303700) |
| uai14-ihler-pr | DBN_11 | 1.00 (58.530700) | 1.00 (58.530700) | 1.00 (58.530700) |
| uai14-ihler-pr | DBN_12 | 1.00 (63.146700) | 1.00 (63.146700) | 1.00 (63.146700) |
| uai14-ihler-pr | DBN_13 | 0.00 (73.312300) | 1.00 (66.553800) | 1.00 (66.553800) |
| uai14-ihler-pr | DBN_14 | 1.00 (151.155000) | 1.00 (151.155000) | 1.00 (151.155000) |
| uai14-ihler-pr | DBN_15 | 1.00 (152.617000) | 1.00 (152.617000) | 1.00 (152.617000) |
| uai14-ihler-pr | DBN_16 | 1.00 (166.111000) | 1.00 (166.111000) | 1.00 (166.111000) |
| uai14-ihler-pr | Grids_11 | 1.00 (169.408000) | 1.00 (169.408000) | 1.00 (169.408000) |
| uai14-ihler-pr | Grids_12 | 1.00 (303.086000) | 1.00 (303.086000) | 1.00 (303.086000) |
| uai14-ihler-pr | Grids_13 | 1.00 (333.321000) | 1.00 (333.321000) | 1.00 (333.321000) |
| uai14-ihler-pr | Grids_14 | 1.00 (497.763000) | 1.00 (497.763000) | 1.00 (497.763000) |
| uai14-ihler-pr | Grids_15 | 0.00 (291.731000) | 1.00 (291.733000) | 1.00 (291.733000) |
| uai14-ihler-pr | Grids_16 | 0.00 (665.113000) | 1.00 (665.116000) | 1.00 (665.116000) |
| uai14-ihler-pr | Grids_17 | 0.00 (1311.990000) | 1.00 (1311.980000) | 1.00 (1311.980000) |
| uai14-ihler-pr | Grids_18 | 0.00 (1963.020000) | 1.00 (1962.980000) | 1.00 (1962.980000) |
| uai14-ihler-pr | ObjectDetection_11 | 0.00 (-74.882600) | 1.00 (-74.880400) | 1.00 (-74.880400) |
| uai14-ihler-pr | ObjectDetection_12 | 1.00 (-67.380300) | 1.00 (-67.380300) | 1.00 (-67.380300) |
| uai14-ihler-pr | ObjectDetection_13 | 0.00 (-70.407000) | 1.00 (-70.355700) | 1.00 (-70.355700) |
| uai14-ihler-pr | ObjectDetection_14 | 0.00 (-64.175200) | 1.00 (-64.090100) | 1.00 (-64.090100) |
| uai14-ihler-pr | ObjectDetection_15 | 0.00 (-51.866800) | 1.00 (-51.861300) | 1.00 (-51.861300) |
| uai14-ihler-pr | ObjectDetection_16 | 0.00 (-34.416100) | 1.00 (-34.403300) | 1.00 (-34.403300) |
| uai14-ihler-pr | ObjectDetection_17 | 0.00 (-29.835800) | 1.00 (-29.813400) | 1.00 (-29.813400) |
| uai14-ihler-pr | ObjectDetection_18 | 1.00 (-37.048100) | 1.00 (-37.048100) | 1.00 (-37.048100) |
| uai14-ihler-pr | ObjectDetection_19 | 0.00 (-39.046000) | 1.00 (-38.451500) | 1.00 (-38.451500) |
| uai14-ihler-pr | ObjectDetection_20 | 0.00 (-35.309400) | 1.00 (-34.838300) | 1.00 (-34.838300) |
| uai14-ihler-pr | ObjectDetection_21 | 0.00 (-24.424000) | 1.00 (-24.391800) | 1.00 (-24.391800) |
| uai14-ihler-pr | ObjectDetection_22 | 0.00 (-36.674300) | 1.00 (-36.674200) | 1.00 (-36.674200) |
| uai14-ihler-pr | ObjectDetection_23 | 0.00 (-31.633700) | 1.00 (-31.611600) | 1.00 (-31.611600) |
| uai14-ihler-pr | ObjectDetection_24 | 0.00 (-26.414800) | 1.00 (-26.379200) | 1.00 (-26.379200) |
| uai14-ihler-pr | ObjectDetection_25 | 0.00 (-18.694900) | 1.00 (-18.693200) | 1.00 (-18.693200) |
| uai14-ihler-pr | ObjectDetection_26 | 0.00 (-33.778800) | 1.00 (-33.753500) | 1.00 (-33.753500) |
| uai14-ihler-pr | ObjectDetection_27 | 0.00 (-29.885800) | 1.00 (-29.862500) | 1.00 (-29.862500) |
| uai14-ihler-pr | ObjectDetection_28 | 1.00 (-46.795800) | 1.00 (-46.795800) | 1.00 (-46.795800) |
| uai14-ihler-pr | ObjectDetection_29 | 0.00 (-50.802600) | 1.00 (-50.801400) | 1.00 (-50.801400) |
| uai14-ihler-pr | ObjectDetection_30 | 0.00 (-52.390200) | 1.00 (-52.371900) | 1.00 (-52.371900) |
| uai14-ihler-pr | ObjectDetection_31 | 0.00 (-44.096600) | 1.00 (-44.086900) | 1.00 (-44.086900) |
| uai14-ihler-pr | ObjectDetection_32 | 1.00 (-46.667800) | 1.00 (-46.667800) | 1.00 (-46.667800) |
| uai14-ihler-pr | ObjectDetection_33 | 0.00 (-44.087000) | 1.00 (-44.061000) | 1.00 (-44.061000) |
| uai14-ihler-pr | ObjectDetection_34 | 1.00 (-35.405600) | 1.00 (-35.405600) | 1.00 (-35.405600) |
| uai14-ihler-pr | ObjectDetection_35 | 0.00 (-37.551300) | 1.00 (-37.550800) | 1.00 (-37.550800) |
| uai14-ihler-pr | ObjectDetection_36 | 0.00 (-30.685000) | 1.00 (-30.684600) | 1.00 (-30.684600) |
| uai14-ihler-pr | ObjectDetection_37 | 0.00 (-29.953800) | 1.00 (-29.951800) | 1.00 (-29.951800) |
| uai14-ihler-pr | ObjectDetection_38 | 0.00 (-75.070600) | 1.00 (-75.070000) | 1.00 (-75.070000) |
| uai14-ihler-pr | ObjectDetection_39 | 0.00 (-70.201500) | 1.00 (-70.199700) | 1.00 (-70.199700) |
| uai14-ihler-pr | ObjectDetection_40 | 1.00 (-72.274400) | 1.00 (-72.274400) | 1.00 (-72.274400) |
| uai14-ihler-pr | ObjectDetection_41 | 0.00 (-73.632200) | 1.00 (-71.094500) | 1.00 (-71.094500) |
| uai14-ihler-pr | ObjectDetection_42 | 0.00 (-45.217900) | 1.00 (-45.217800) | 1.00 (-45.217800) |
| uai14-ihler-pr | ObjectDetection_43 | 0.00 (-39.464900) | 1.00 (-39.464700) | 1.00 (-39.464700) |
| uai14-ihler-pr | ObjectDetection_44 | 1.00 (-41.028100) | 1.00 (-41.028100) | 1.00 (-41.028100) |
| uai14-ihler-pr | ObjectDetection_45 | 0.00 (-38.931700) | 1.00 (-38.928500) | 1.00 (-38.928500) |
| uai14-ihler-pr | ObjectDetection_46 | 1.00 (-41.971600) | 1.00 (-41.971600) | 1.00 (-41.971600) |
| uai14-ihler-pr | ObjectDetection_47 | 0.00 (-44.653900) | 1.00 (-44.653500) | 1.00 (-44.653500) |
| uai14-ihler-pr | ObjectDetection_48 | 0.00 (-36.592500) | 1.00 (-36.592200) | 1.00 (-36.592200) |
| uai14-ihler-pr | ObjectDetection_49 | 1.00 (-38.681500) | 1.00 (-38.681500) | 1.00 (-38.681500) |
| uai14-ihler-pr | ObjectDetection_50 | 0.00 (-37.105700) | 1.00 (-36.051300) | 1.00 (-36.051300) |
| uai14-ihler-pr | ObjectDetection_51 | 1.00 (-53.401300) | 1.00 (-53.401300) | 1.00 (-53.401300) |
| uai14-ihler-pr | ObjectDetection_52 | 0.00 (-56.998400) | 1.00 (-56.998000) | 1.00 (-56.998000) |
| uai14-ihler-pr | ObjectDetection_53 | 0.00 (-47.733400) | 1.00 (-47.732100) | 1.00 (-47.732100) |
| uai14-ihler-pr | ObjectDetection_54 | 0.00 (-41.478200) | 1.00 (-41.477600) | 1.00 (-41.477600) |
| uai14-ihler-pr | ObjectDetection_55 | 0.00 (-34.118200) | 1.00 (-34.117600) | 1.00 (-34.117600) |
| uai14-ihler-pr | ObjectDetection_56 | 1.00 (-36.292100) | 1.00 (-36.292100) | 1.00 (-36.292100) |
| uai14-ihler-pr | ObjectDetection_57 | 0.00 (-33.423000) | 1.00 (-33.414100) | 1.00 (-33.414100) |
| uai14-ihler-pr | ObjectDetection_58 | 0.00 (-41.653500) | 1.00 (-41.653300) | 1.00 (-41.653300) |
| uai14-ihler-pr | ObjectDetection_59 | 0.00 (-35.873000) | 1.00 (-35.872900) | 1.00 (-35.872900) |
| uai14-ihler-pr | ObjectDetection_60 | 0.00 (-35.293100) | 1.00 (-35.272100) | 1.00 (-35.272100) |
| uai14-ihler-pr | ObjectDetection_61 | 1.00 (-23.151900) | 1.00 (-23.151900) | 1.00 (-23.151900) |
| uai14-ihler-pr | ObjectDetection_62 | 0.00 (-24.793000) | 1.00 (-24.792900) | 1.00 (-24.792900) |
| uai14-ihler-pr | ObjectDetection_63 | 0.00 (-19.907300) | 1.00 (-19.907100) | 1.00 (-19.907100) |
| uai14-ihler-pr | ObjectDetection_64 | 1.00 (-21.328100) | 1.00 (-21.328100) | 1.00 (-21.328100) |
| uai14-ihler-pr | ObjectDetection_65 | 0.00 (-19.698800) | 1.00 (-19.696600) | 1.00 (-19.696600) |
| uai14-ihler-pr | ObjectDetection_66 | 0.00 (-47.040900) | 1.00 (-47.040800) | 1.00 (-47.040800) |
| uai14-ihler-pr | ObjectDetection_67 | 0.00 (-40.624800) | 1.00 (-40.624600) | 1.00 (-40.624600) |
| uai14-ihler-pr | ObjectDetection_68 | 1.00 (-42.661700) | 1.00 (-42.661700) | 1.00 (-42.661700) |
| uai14-ihler-pr | ObjectDetection_69 | 0.00 (-40.257300) | 1.00 (-40.251600) | 1.00 (-40.251600) |
| uai14-ihler-pr | ObjectDetection_70 | 1.00 (-31.243900) | 1.00 (-31.243900) | 1.00 (-31.243900) |
| uai14-ihler-pr | ObjectDetection_71 | 0.00 (-33.641400) | 1.00 (-33.641100) | 1.00 (-33.641100) |
| uai14-ihler-pr | ObjectDetection_72 | 0.00 (-26.412800) | 1.00 (-26.412500) | 1.00 (-26.412500) |
| uai14-ihler-pr | ObjectDetection_73 | 0.00 (-25.706400) | 1.00 (-25.639100) | 1.00 (-25.639100) |
| uai14-ihler-pr | ObjectDetection_74 | 1.00 (-31.815600) | 1.00 (-31.815600) | 1.00 (-31.815600) |
| uai14-ihler-pr | ObjectDetection_75 | 0.00 (-33.772500) | 1.00 (-33.772300) | 1.00 (-33.772300) |
| uai14-ihler-pr | Pedigree_11 | 1.00 (-17.215500) | 1.00 (-17.215500) | 1.00 (-17.215500) |
| uai14-ihler-pr | Pedigree_12 | 1.00 (-11.455400) | 1.00 (-11.455400) | 1.00 (-11.455400) |
| uai14-ihler-pr | Pedigree_13 | 1.00 (-15.212900) | 1.00 (-15.212900) | 1.00 (-15.212900) |
| uai14-ihler-pr | Promedus_11 | 1.00 (-8.391450) | 1.00 (-8.391450) | 1.00 (-8.391450) |
| uai14-ihler-pr | Promedus_12 | 1.00 (-3.164620) | 1.00 (-3.164620) | 1.00 (-3.164620) |
| uai14-ihler-pr | Promedus_13 | 1.00 (-4.507030) | 1.00 (-4.507030) | 1.00 (-4.507030) |
| uai14-ihler-pr | Promedus_14 | 0.90 (-7.827450) | 1.00 (-7.806750) | 1.00 (-7.806750) |
| uai14-ihler-pr | Promedus_15 | 1.00 (-3.636670) | 1.00 (-3.636670) | 1.00 (-3.636670) |
| uai14-ihler-pr | Promedus_16 | 1.00 (-6.975220) | 1.00 (-6.975220) | 1.00 (-6.975220) |
| uai14-ihler-pr | Promedus_17 | 1.00 (-9.459200) | 1.00 (-9.459200) | 1.00 (-9.459200) |
| uai14-ihler-pr | Promedus_18 | 0.00 (-4.672300) | 1.00 (-4.672280) | 1.00 (-4.672280) |
| uai14-ihler-pr | Promedus_19 | 0.00 (-4.344860) | 1.00 (-4.344640) | 1.00 (-4.344640) |
| uai14-ihler-pr | Promedus_20 | 1.00 (-7.060650) | 1.00 (-7.060650) | 1.00 (-7.060650) |
| uai14-ihler-pr | Promedus_21 | 1.00 (-5.580120) | 1.00 (-5.580120) | 1.00 (-5.580120) |
| uai14-ihler-pr | Promedus_22 | 1.00 (-2.494740) | 1.00 (-2.494740) | 1.00 (-2.494740) |
| uai14-ihler-pr | Promedus_23 | 1.00 (-11.315100) | 1.00 (-11.315100) | 1.00 (-11.315100) |
| uai14-ihler-pr | Promedus_24 | 1.00 (-5.861810) | 1.00 (-5.861810) | 1.00 (-5.861810) |
| uai14-ihler-pr | Promedus_25 | 1.00 (-9.417910) | 1.00 (-9.417910) | 1.00 (-9.417910) |
| uai14-ihler-pr | Promedus_26 | 1.00 (-7.304890) | 1.00 (-7.304890) | 1.00 (-7.304890) |
| uai14-ihler-pr | Promedus_27 | 1.00 (-8.135760) | 1.00 (-8.135760) | 1.00 (-8.135760) |
| uai14-ihler-pr | Promedus_28 | 1.00 (-8.131520) | 1.00 (-8.131520) | 1.00 (-8.131520) |
| uai14-ihler-pr | Promedus_29 | 1.00 (-10.452700) | 1.00 (-10.452700) | 1.00 (-10.452700) |
| uai14-ihler-pr | Promedus_30 | 1.00 (-22.100500) | 1.00 (-22.100500) | 1.00 (-22.100500) |
| uai14-ihler-pr | Promedus_31 | 1.00 (-1.799790) | 1.00 (-1.799790) | 1.00 (-1.799790) |
| uai14-ihler-pr | Promedus_32 | 1.00 (-2.201930) | 1.00 (-2.201930) | 1.00 (-2.201930) |
| uai14-ihler-pr | Promedus_33 | 1.00 (-2.808660) | 1.00 (-2.808660) | 1.00 (-2.808660) |
| uai14-ihler-pr | Promedus_34 | 1.00 (-3.079960) | 1.00 (-3.079960) | 1.00 (-3.079960) |
| uai14-ihler-pr | Promedus_35 | 1.00 (-1.742950) | 1.00 (-1.742950) | 1.00 (-1.742950) |
| uai14-ihler-pr | Promedus_36 | 1.00 (-1.742700) | 1.00 (-1.742700) | 1.00 (-1.742700) |
| uai14-ihler-pr | Promedus_37 | 1.00 (-4.171100) | 1.00 (-4.171100) | 1.00 (-4.171100) |
| uai14-ihler-pr | Promedus_38 | 1.00 (-4.982350) | 1.00 (-4.982350) | 1.00 (-4.982350) |
| uai14-ihler-pr | Segmentation_11 | 1.00 (-23.996100) | 1.00 (-23.996100) | 1.00 (-23.996100) |
| uai14-ihler-pr | Segmentation_12 | -1.00 (  nan) | 1.00 (-10.287200) | 1.00 (-10.287200) |
| uai14-ihler-pr | Segmentation_13 | 1.00 (-33.368800) | 1.00 (-33.368800) | 1.00 (-33.368800) |
| uai14-ihler-pr | Segmentation_14 | 1.00 (-39.496500) | 1.00 (-39.496500) | 1.00 (-39.496500) |
| uai14-ihler-pr | Segmentation_15 | 1.00 (-26.244100) | 1.00 (-26.244100) | 1.00 (-26.244100) |
| uai14-ihler-pr | Segmentation_16 | 1.00 (-38.128300) | 1.00 (-38.128300) | 1.00 (-38.128300) |
| uai14-ihler-pr | grid10x10.f10 | 1.00 (303.086000) | 1.00 (303.086000) | 1.00 (303.086000) |
| uai14-ihler-pr | linkage_12 | 0.00 (-69.591800) | 0.99 (-69.713400) | 0.99 (-69.723800) |
| uai14-ihler-pr | linkage_13 | 0.00 (-75.900500) | 0.89 (-76.185600) | 0.82 (-76.272300) |
| uai14-ihler-pr | linkage_14 | 0.00 (-31.047800) | 1.00 (-30.761400) | 1.00 (-30.761400) |
| uai14-ihler-pr | linkage_16 | 0.00 (-38.546900) | 1.00 (-38.555600) | 1.00 (-38.555600) |
| uai14-ihler-pr | linkage_18 | 0.00 (-78.516800) | 1.00 (-78.522200) | 1.00 (-78.522200) |
| uai14-ihler-pr | linkage_19 | 0.00 (-58.661900) | 0.98 (-58.938500) | 1.00 (-59.024900) |
| uai14-ihler-pr | linkage_21 | 0.00 (-29.785400) | 1.00 (-29.630400) | 1.00 (-29.630400) |
| uai14-ihler-pr | linkage_22 | 0.00 (-54.829500) | 0.98 (-54.335800) | 0.72 (-53.478300) |
| uai14-ihler-pr | linkage_23 | 0.00 (-116.784000) | 0.90 (-115.722000) | 0.98 (-116.750000) |
| uai14-ihler-pr | linkage_24 | 1.00 (-83.733100) | 1.00 (-83.733100) | 1.00 (-83.733100) |
| uai14-ihler-pr | linkage_26 | 0.00 (-115.788000) | 1.00 (-115.772000) | 1.00 (-115.772000) |
| uai14-ihler-pr | linkage_27 | 0.00 (-63.489100) | 1.00 (-63.473500) | 1.00 (-63.473500) |
| uai14-ihler-pr | relational_2 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-pr | relational_3 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-pr | relational_5 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |



## MAR Task

| solver | problem | 20 sec | 1200 sec | 3600 sec |
|:--------|--------:|--------:|--------:|--------:|
| lbp-ihler-mar | Alchemy_11 | -1.00 (  nan) | 0.00 (0.112756) | 0.00 (0.112756) |
| lbp-ihler-mar | CSP_11 | -1.00 (  nan) | 0.00 (2.425222) | 0.00 (2.425222) |
| lbp-ihler-mar | CSP_12 | 0.00 (1.702130) | 0.00 (1.702130) | 0.00 (1.702130) |
| lbp-ihler-mar | CSP_13 | -1.00 (  nan) | 0.00 (4.213548) | 0.00 (4.213548) |
| lbp-ihler-mar | DBN_11 | -1.00 (  nan) | 0.00 (8.120593) | 0.00 (8.120593) |
| lbp-ihler-mar | DBN_12 | -1.00 (  nan) | 0.00 (2.462202) | 0.00 (2.462202) |
| lbp-ihler-mar | DBN_13 | -1.00 (  nan) | 0.00 (13.737831) | 0.00 (13.737831) |
| lbp-ihler-mar | DBN_14 | -1.00 (  nan) | 0.00 (0.000015) | 0.00 (0.000015) |
| lbp-ihler-mar | DBN_15 | -1.00 (  nan) | 0.00 (39.741700) | 0.00 (39.741700) |
| lbp-ihler-mar | DBN_16 | -1.00 (  nan) | 0.00 (4.156808) | 0.00 (4.156808) |
| lbp-ihler-mar | Grids_11 | 0.07 (34.978468) | 0.00 (34.978468) | 0.00 (34.978468) |
| lbp-ihler-mar | Grids_12 | 0.00 (24.663208) | 0.00 (24.663208) | 0.00 (24.663208) |
| lbp-ihler-mar | Grids_13 | 0.24 (34.078287) | 0.00 (34.078287) | 0.00 (34.078287) |
| lbp-ihler-mar | Grids_14 | 0.00 (67.755344) | 0.00 (67.755344) | 0.00 (67.755344) |
| lbp-ihler-mar | Grids_15 | -1.00 (  nan) | 0.00 (47.719345) | 0.00 (47.719345) |
| lbp-ihler-mar | Grids_16 | -1.00 (  nan) | 0.00 (125.660755) | 0.00 (125.660755) |
| lbp-ihler-mar | Grids_17 | -1.00 (  nan) | 0.00 (142.250592) | 0.00 (142.250592) |
| lbp-ihler-mar | Grids_18 | -1.00 (  nan) | 0.00 (200.584453) | 0.00 (200.584453) |
| lbp-ihler-mar | ObjectDetection_11 | -1.00 (  nan) | 0.00 (1.081384) | 0.00 (1.081384) |
| lbp-ihler-mar | ObjectDetection_12 | -1.00 (  nan) | 0.00 (1.258411) | 0.00 (1.258411) |
| lbp-ihler-mar | ObjectDetection_13 | -1.00 (  nan) | 0.00 (1.535864) | 0.00 (1.535864) |
| lbp-ihler-mar | ObjectDetection_14 | -1.00 (  nan) | 0.00 (1.532797) | 0.00 (1.532797) |
| lbp-ihler-mar | ObjectDetection_15 | -1.00 (  nan) | 0.00 (0.094888) | 0.00 (0.094888) |
| lbp-ihler-mar | ObjectDetection_16 | -1.00 (  nan) | 0.00 (0.323424) | 0.00 (0.323424) |
| lbp-ihler-mar | ObjectDetection_17 | -1.00 (  nan) | 0.00 (0.247676) | 0.00 (0.247676) |
| lbp-ihler-mar | ObjectDetection_18 | -1.00 (  nan) | 0.00 (3.488473) | 0.00 (3.488473) |
| lbp-ihler-mar | ObjectDetection_19 | -1.00 (  nan) | 0.00 (8.276058) | 0.00 (8.276058) |
| lbp-ihler-mar | ObjectDetection_20 | -1.00 (  nan) | 0.00 (6.376711) | 0.00 (6.376711) |
| lbp-ihler-mar | ObjectDetection_21 | -1.00 (  nan) | 0.00 (0.395452) | 0.00 (0.395452) |
| lbp-ihler-mar | ObjectDetection_22 | -1.00 (  nan) | 0.00 (0.389485) | 0.00 (0.389485) |
| lbp-ihler-mar | ObjectDetection_23 | -1.00 (  nan) | 0.00 (0.534954) | 0.00 (0.534954) |
| lbp-ihler-mar | ObjectDetection_24 | -1.00 (  nan) | 0.00 (0.370045) | 0.00 (0.370045) |
| lbp-ihler-mar | ObjectDetection_25 | -1.00 (  nan) | 0.00 (0.023526) | 0.00 (0.023526) |
| lbp-ihler-mar | ObjectDetection_26 | -1.00 (  nan) | 0.00 (0.258247) | 0.00 (0.258247) |
| lbp-ihler-mar | ObjectDetection_27 | -1.00 (  nan) | 0.00 (0.170791) | 0.00 (0.170791) |
| lbp-ihler-mar | ObjectDetection_28 | -1.00 (  nan) | 0.00 (0.002992) | 0.00 (0.002992) |
| lbp-ihler-mar | ObjectDetection_29 | -1.00 (  nan) | 0.00 (0.261015) | 0.00 (0.261015) |
| lbp-ihler-mar | ObjectDetection_30 | -1.00 (  nan) | 0.00 (0.801288) | 0.00 (0.801288) |
| lbp-ihler-mar | ObjectDetection_31 | -1.00 (  nan) | 0.00 (0.225147) | 0.00 (0.225147) |
| lbp-ihler-mar | ObjectDetection_32 | -1.00 (  nan) | 0.00 (0.480498) | 0.00 (0.480498) |
| lbp-ihler-mar | ObjectDetection_33 | -1.00 (  nan) | 0.00 (0.528286) | 0.00 (0.528286) |
| lbp-ihler-mar | ObjectDetection_34 | -1.00 (  nan) | 0.00 (0.011306) | 0.00 (0.011306) |
| lbp-ihler-mar | ObjectDetection_35 | -1.00 (  nan) | 0.00 (0.037988) | 0.00 (0.037988) |
| lbp-ihler-mar | ObjectDetection_36 | -1.00 (  nan) | 0.00 (0.017982) | 0.00 (0.017982) |
| lbp-ihler-mar | ObjectDetection_37 | -1.00 (  nan) | 0.00 (0.055393) | 0.00 (0.055393) |
| lbp-ihler-mar | ObjectDetection_38 | -1.00 (  nan) | 0.00 (0.379263) | 0.00 (0.379263) |
| lbp-ihler-mar | ObjectDetection_39 | -1.00 (  nan) | 0.00 (0.429416) | 0.00 (0.429416) |
| lbp-ihler-mar | ObjectDetection_40 | -1.00 (  nan) | 0.00 (0.603158) | 0.00 (0.603158) |
| lbp-ihler-mar | ObjectDetection_41 | -1.00 (  nan) | 0.00 (10.566045) | 0.00 (10.566045) |
| lbp-ihler-mar | ObjectDetection_42 | -1.00 (  nan) | 0.00 (0.073422) | 0.00 (0.073422) |
| lbp-ihler-mar | ObjectDetection_43 | -1.00 (  nan) | 0.00 (0.062385) | 0.00 (0.062385) |
| lbp-ihler-mar | ObjectDetection_44 | -1.00 (  nan) | 0.00 (0.119369) | 0.00 (0.119369) |
| lbp-ihler-mar | ObjectDetection_45 | -1.00 (  nan) | 0.00 (0.163430) | 0.00 (0.163430) |
| lbp-ihler-mar | ObjectDetection_46 | 0.00 (7.184664) | 0.00 (7.184664) | 0.00 (7.184664) |
| lbp-ihler-mar | ObjectDetection_47 | -1.00 (  nan) | 0.00 (8.559423) | 0.00 (8.559423) |
| lbp-ihler-mar | ObjectDetection_48 | -1.00 (  nan) | 0.00 (7.611619) | 0.00 (7.611619) |
| lbp-ihler-mar | ObjectDetection_49 | -1.00 (  nan) | 0.00 (8.473924) | 0.00 (8.473924) |
| lbp-ihler-mar | ObjectDetection_50 | -1.00 (  nan) | 0.00 (8.036239) | 0.00 (8.036239) |
| lbp-ihler-mar | ObjectDetection_51 | -1.00 (  nan) | 0.00 (0.103407) | 0.00 (0.103407) |
| lbp-ihler-mar | ObjectDetection_52 | -1.00 (  nan) | 0.00 (0.215145) | 0.00 (0.215145) |
| lbp-ihler-mar | ObjectDetection_53 | -1.00 (  nan) | 0.00 (0.174417) | 0.00 (0.174417) |
| lbp-ihler-mar | ObjectDetection_54 | -1.00 (  nan) | 0.00 (0.082538) | 0.00 (0.082538) |
| lbp-ihler-mar | ObjectDetection_55 | -1.00 (  nan) | 0.00 (0.062563) | 0.00 (0.062563) |
| lbp-ihler-mar | ObjectDetection_56 | -1.00 (  nan) | 0.00 (0.102589) | 0.00 (0.102589) |
| lbp-ihler-mar | ObjectDetection_57 | -1.00 (  nan) | 0.00 (0.139598) | 0.00 (0.139598) |
| lbp-ihler-mar | ObjectDetection_58 | -1.00 (  nan) | 0.00 (0.171506) | 0.00 (0.171506) |
| lbp-ihler-mar | ObjectDetection_59 | -1.00 (  nan) | 0.00 (0.126857) | 0.00 (0.126857) |
| lbp-ihler-mar | ObjectDetection_60 | -1.00 (  nan) | 0.00 (0.244974) | 0.00 (0.244974) |
| lbp-ihler-mar | ObjectDetection_61 | -1.00 (  nan) | 0.00 (0.021595) | 0.00 (0.021595) |
| lbp-ihler-mar | ObjectDetection_62 | -1.00 (  nan) | 0.00 (0.027772) | 0.00 (0.027772) |
| lbp-ihler-mar | ObjectDetection_63 | -1.00 (  nan) | 0.00 (0.039141) | 0.00 (0.039141) |
| lbp-ihler-mar | ObjectDetection_64 | -1.00 (  nan) | 0.00 (0.053110) | 0.00 (0.053110) |
| lbp-ihler-mar | ObjectDetection_65 | -1.00 (  nan) | 0.00 (0.069706) | 0.00 (0.069706) |
| lbp-ihler-mar | ObjectDetection_66 | -1.00 (  nan) | 0.00 (0.152654) | 0.00 (0.152654) |
| lbp-ihler-mar | ObjectDetection_67 | -1.00 (  nan) | 0.00 (0.140935) | 0.00 (0.140935) |
| lbp-ihler-mar | ObjectDetection_68 | -1.00 (  nan) | 0.00 (0.195314) | 0.00 (0.195314) |
| lbp-ihler-mar | ObjectDetection_69 | -1.00 (  nan) | 0.00 (0.253570) | 0.00 (0.253570) |
| lbp-ihler-mar | ObjectDetection_70 | 0.00 (0.591936) | 0.00 (0.591936) | 0.00 (0.591936) |
| lbp-ihler-mar | ObjectDetection_71 | -1.00 (  nan) | 0.00 (0.494683) | 0.00 (0.494683) |
| lbp-ihler-mar | ObjectDetection_72 | -1.00 (  nan) | 0.00 (1.576998) | 0.00 (1.576998) |
| lbp-ihler-mar | ObjectDetection_73 | -1.00 (  nan) | 0.00 (2.261983) | 0.00 (2.261983) |
| lbp-ihler-mar | ObjectDetection_74 | -1.00 (  nan) | 0.00 (0.017963) | 0.00 (0.017963) |
| lbp-ihler-mar | ObjectDetection_75 | 0.00 (0.022690) | 0.00 (0.022690) | 0.00 (0.022690) |
| lbp-ihler-mar | Pedigree_11 | -1.00 (  nan) | 0.00 (24.788239) | 0.00 (24.788239) |
| lbp-ihler-mar | Pedigree_12 | -1.00 (  nan) | 0.00 (18.433931) | 0.00 (18.433931) |
| lbp-ihler-mar | Pedigree_13 | -1.00 (  nan) | 0.00 (51.318459) | 0.00 (51.318459) |
| lbp-ihler-mar | Promedus_11 | -1.00 (  nan) | 0.00 (15.139754) | 0.00 (15.139754) |
| lbp-ihler-mar | Promedus_12 | -1.00 (  nan) | 0.00 (9.426388) | 0.00 (9.426388) |
| lbp-ihler-mar | Promedus_13 | -1.00 (  nan) | 0.00 (13.568409) | 0.00 (13.568409) |
| lbp-ihler-mar | Promedus_14 | 0.00 (39.474434) | 0.00 (39.474434) | 0.00 (39.474434) |
| lbp-ihler-mar | Promedus_15 | 0.00 (9.594813) | 0.00 (9.594813) | 0.00 (9.594813) |
| lbp-ihler-mar | Promedus_16 | -1.00 (  nan) | 0.00 (2.186896) | 0.00 (2.186896) |
| lbp-ihler-mar | Promedus_17 | -1.00 (  nan) | 0.00 (28.632196) | 0.00 (28.632196) |
| lbp-ihler-mar | Promedus_18 | -1.00 (  nan) | 0.00 (2.648261) | 0.00 (2.648261) |
| lbp-ihler-mar | Promedus_19 | -1.00 (  nan) | 0.00 (0.231400) | 0.00 (0.231400) |
| lbp-ihler-mar | Promedus_20 | -1.00 (  nan) | 0.00 (10.229795) | 0.00 (10.229795) |
| lbp-ihler-mar | Promedus_21 | -1.00 (  nan) | 0.00 (11.189675) | 0.00 (11.189675) |
| lbp-ihler-mar | Promedus_22 | 0.00 (22.030258) | 0.00 (22.030258) | 0.00 (22.030258) |
| lbp-ihler-mar | Promedus_23 | -1.00 (  nan) | 0.00 (14.356360) | 0.00 (14.356360) |
| lbp-ihler-mar | Promedus_24 | 0.00 (0.023373) | 0.00 (0.023373) | 0.00 (0.023373) |
| lbp-ihler-mar | Promedus_25 | -1.00 (  nan) | 0.00 (9.237966) | 0.00 (9.237966) |
| lbp-ihler-mar | Promedus_26 | -1.00 (  nan) | 0.00 (1.070627) | 0.00 (1.070627) |
| lbp-ihler-mar | Promedus_27 | 0.00 (16.468724) | 0.00 (16.468724) | 0.00 (16.468724) |
| lbp-ihler-mar | Promedus_28 | -1.00 (  nan) | 0.00 (10.622322) | 0.00 (10.622322) |
| lbp-ihler-mar | Promedus_29 | 0.00 (0.931036) | 0.00 (0.931036) | 0.00 (0.931036) |
| lbp-ihler-mar | Promedus_30 | 0.00 (4.311323) | 0.00 (4.311323) | 0.00 (4.311323) |
| lbp-ihler-mar | Promedus_31 | -1.00 (  nan) | 0.00 (10.879302) | 0.00 (10.879302) |
| lbp-ihler-mar | Promedus_32 | -1.00 (  nan) | 0.00 (12.275480) | 0.00 (12.275480) |
| lbp-ihler-mar | Promedus_33 | -1.00 (  nan) | 0.00 (0.011687) | 0.00 (0.011687) |
| lbp-ihler-mar | Promedus_34 | 0.00 (10.293006) | 0.00 (10.293006) | 0.00 (10.293006) |
| lbp-ihler-mar | Promedus_35 | 0.00 (11.897043) | 0.00 (11.897043) | 0.00 (11.897043) |
| lbp-ihler-mar | Promedus_36 | -1.00 (  nan) | 0.00 (11.819390) | 0.00 (11.819390) |
| lbp-ihler-mar | Promedus_37 | -1.00 (  nan) | 0.00 (20.416939) | 0.00 (20.416939) |
| lbp-ihler-mar | Promedus_38 | -1.00 (  nan) | 0.00 (12.313805) | 0.00 (12.313805) |
| lbp-ihler-mar | Segmentation_11 | -1.00 (  nan) | 0.00 (38.950036) | 0.00 (38.950036) |
| lbp-ihler-mar | Segmentation_12 | -1.00 (  nan) | 0.00 (0.007858) | 0.00 (0.007858) |
| lbp-ihler-mar | Segmentation_13 | -1.00 (  nan) | 0.00 (27.078116) | 0.00 (27.078116) |
| lbp-ihler-mar | Segmentation_14 | -1.00 (  nan) | 0.00 (2.403654) | 0.00 (2.403654) |
| lbp-ihler-mar | Segmentation_15 | -1.00 (  nan) | 0.00 (18.037887) | 0.00 (18.037887) |
| lbp-ihler-mar | Segmentation_16 | -1.00 (  nan) | 0.00 (7.900034) | 0.00 (7.900034) |
| lbp-ihler-mar | linkage_14 | -1.00 (  nan) | 0.00 (2.633082) | 0.00 (2.633082) |
| lbp-ihler-mar | linkage_16 | -1.00 (  nan) | 0.00 (39.841829) | 0.00 (39.841829) |
| lbp-ihler-mar | linkage_18 | -1.00 (  nan) | 0.00 (98.520626) | 0.00 (98.520626) |
| lbp-ihler-mar | linkage_19 | -1.00 (  nan) | 0.00 (106.939826) | 0.00 (106.939826) |
| lbp-ihler-mar | linkage_21 | -1.00 (  nan) | 0.00 (25.945491) | 0.00 (25.945491) |
| lbp-ihler-mar | linkage_24 | -1.00 (  nan) | 0.00 (120.472588) | 0.00 (120.472588) |
| lbp-ihler-mar | linkage_26 | -1.00 (  nan) | 0.00 (143.357585) | 0.00 (143.357585) |
| lbp-ihler-mar | linkage_27 | -1.00 (  nan) | 0.00 (90.796742) | 0.00 (90.796742) |
| lbp-ihler-mar | relational_2 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (1387.056206) |
| lbp-ihler-mar | relational_3 | -1.00 (  nan) | 0.00 (88.103435) | 0.00 (88.103435) |
| lbp-ihler-mar | relational_4 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mar | relational_5 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (584.853399) |
| uai14-ihler-mar | Alchemy_11 | 0.00 (139.656915) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | CSP_11 | 0.00 (20.648811) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | CSP_12 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | CSP_13 | 0.00 (30.098498) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_11 | 0.00 (8.029898) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_12 | 0.00 (2.253323) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_13 | 0.00 (18.003967) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_14 | 0.00 (0.000015) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_15 | 0.00 (39.741700) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | DBN_16 | 0.00 (4.156808) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_11 | 0.00 (37.650721) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_12 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_13 | 0.00 (44.965027) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_14 | 0.32 (45.802663) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_15 | 0.00 (22.018801) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_16 | 0.00 (90.925852) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_17 | 0.00 (123.348616) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Grids_18 | 0.00 (164.915015) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_11 | 0.00 (0.020229) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_12 | 0.00 (0.058083) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_13 | 0.00 (0.417356) | 0.98 (0.037382) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_14 | 0.00 (0.610031) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_15 | 0.00 (0.021626) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_16 | 0.00 (0.083479) | 1.00 (0.000263) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_17 | 0.00 (0.101160) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_18 | 0.00 (1.144442) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_19 | 0.00 (4.100598) | 1.00 (0.000053) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_20 | 0.00 (4.219567) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_21 | 0.00 (0.116501) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_22 | 0.00 (0.000112) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_23 | 0.00 (0.142168) | 1.00 (0.000341) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_24 | 0.00 (0.176674) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_25 | 0.00 (0.005033) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_26 | 0.00 (0.079642) | 1.00 (0.000331) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_27 | 0.00 (0.081881) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_28 | 0.00 (0.000019) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_29 | 0.00 (0.004195) | 0.99 (0.002481) | 0.99 (0.002481) |
| uai14-ihler-mar | ObjectDetection_30 | 0.00 (0.180342) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_31 | 0.00 (0.028300) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_32 | 0.00 (0.025532) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_33 | 0.00 (0.103281) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_34 | 0.00 (0.000109) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_35 | 0.00 (0.001460) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_36 | 0.00 (0.000973) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_37 | 0.00 (0.006852) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_38 | 0.00 (0.006541) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_39 | 0.00 (0.012057) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_40 | 0.00 (0.001154) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_41 | 0.00 (6.134988) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_42 | 0.00 (0.000589) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_43 | 0.00 (0.001170) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_44 | 0.00 (0.000684) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_45 | 0.00 (0.014226) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_46 | 1.00 (0.000046) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_47 | 0.00 (0.001397) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_48 | 0.00 (0.001071) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_49 | 0.00 (0.000383) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_50 | 0.00 (7.421027) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_51 | 0.00 (0.000111) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_52 | 0.00 (0.001584) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_53 | 0.00 (0.006445) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_54 | 0.00 (0.002508) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_55 | 0.00 (0.002522) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_56 | 0.00 (0.001881) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_57 | 0.00 (0.032507) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_58 | 0.00 (0.000569) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_59 | 0.00 (0.000713) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_60 | 0.00 (0.095768) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_61 | 0.00 (0.000046) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_62 | 0.00 (0.000391) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_63 | 0.00 (0.000628) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_64 | 0.00 (0.000212) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_65 | 0.00 (0.016176) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_66 | 0.00 (0.000489) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_67 | 0.00 (0.001166) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_68 | 0.00 (0.000334) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_69 | 0.00 (0.028159) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_70 | 1.00 (0.000107) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_71 | 0.00 (0.001190) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_72 | -1.00 (  nan) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_73 | 0.00 (2.115225) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_74 | 0.00 (0.000086) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | ObjectDetection_75 | 0.98 (0.000468) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Pedigree_11 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Pedigree_12 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Pedigree_13 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_11 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_12 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_13 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_14 | 0.35 (25.712141) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_15 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_16 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_17 | 0.00 (23.963121) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_18 | 0.00 (0.029803) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_19 | 0.00 (0.088920) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_20 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_21 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_22 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_23 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_24 | 0.90 (0.002285) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_25 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_26 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_27 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_28 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_29 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_30 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_31 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_32 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_33 | 0.00 (0.002122) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_34 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_35 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_36 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_37 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Promedus_38 | 0.00 (19.074911) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_11 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_12 | 0.00 (0.000006) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_13 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_14 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_15 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | Segmentation_16 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_14 | 0.00 (1.476124) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_16 | 0.00 (4.900779) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_18 | 0.00 (5.302832) | 0.99 (0.509541) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_19 | 0.00 (20.917889) | 0.95 (5.210216) | 0.99 (1.277669) |
| uai14-ihler-mar | linkage_21 | 0.00 (2.513209) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_24 | 0.00 (68.647435) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_26 | 0.00 (85.231023) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | linkage_27 | 0.00 (0.892615) | 1.00 (0.111155) | 1.00 (0.000002) |
| uai14-ihler-mar | relational_2 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | relational_3 | 1.00 (0.000000) | 1.00 (0.000000) | 1.00 (0.000000) |
| uai14-ihler-mar | relational_4 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mar | relational_5 | 0.00 (84.349839) | 1.00 (0.000000) | 1.00 (0.000000) |


## MPE Task

| solver | problem | 20 sec | 1200 sec | 3600 sec |
|:--------|--------:|--------:|--------:|--------:|
| dallouche | Grids_18 | 0.87 (5558.352973) | 0.92 (5605.126468) | 0.92 (5606.398846) |
| dallouche | Grids_19 | 0.91 (1166.299722) | 0.94 (1170.620308) | 0.94 (1171.215005) |
| dallouche | Grids_20 | 0.85 (4590.401621) | 0.92 (4633.980474) | 0.93 (4638.015846) |
| dallouche | Grids_21 | 0.90 (8363.488180) | 0.93 (8405.957451) | 0.93 (8405.957451) |
| dallouche | Grids_22 | 0.86 (2762.702719) | 0.88 (2771.729454) | 0.88 (2771.729454) |
| dallouche | Grids_23 | 0.90 (2743.946068) | 0.91 (2748.890379) | 0.92 (2750.615532) |
| dallouche | Grids_24 | 0.85 (8047.945312) | 0.88 (8094.933158) | 0.89 (8098.965043) |
| dallouche | Grids_25 | 0.88 (1156.276580) | 0.90 (1158.168136) | 0.94 (1162.300460) |
| dallouche | Grids_26 | 0.93 (1311.917780) | 0.98 (1321.204177) | 0.98 (1321.204177) |
| dallouche | Grids_27 | 0.89 (5414.196292) | 0.90 (5424.149511) | 0.91 (5432.601464) |
| dallouche | Grids_28 | 0.83 (1938.980877) | 0.91 (1959.905518) | 0.92 (1960.647009) |
| dallouche | Grids_29 | 0.88 (660.228406) | 0.96 (666.453745) | 0.99 (668.770921) |
| dallouche | Grids_30 | 0.91 (1294.618403) | 0.95 (1301.900652) | 0.95 (1301.900652) |
| dallouche | ImageAlignment_11 | 1.00 (-824.234024) | 1.00 (-824.234024) | 1.00 (-824.234024) |
| dallouche | ImageAlignment_12 | 1.00 (-436.669411) | 1.00 (-436.669411) | 1.00 (-436.669411) |
| dallouche | ImageAlignment_13 | 1.00 (-2999.933955) | 1.00 (-2999.933955) | 1.00 (-2999.933955) |
| dallouche | ImageAlignment_14 | 1.00 (-1557.513069) | 1.00 (-1557.513069) | 1.00 (-1557.513069) |
| dallouche | ImageAlignment_15 | 1.00 (-1177.484737) | 1.00 (-1177.484737) | 1.00 (-1177.484737) |
| dallouche | ObjectDetection_11 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_12 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_13 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_14 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_15 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_16 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_17 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ObjectDetection_18 | -1.00 (  nan) | 0.74 (7181.731782) | 0.81 (7613.576590) |
| dallouche | Promedas_11 | 1.00 (-20.995503) | 1.00 (-20.995503) | 1.00 (-20.995503) |
| dallouche | Promedas_12 | 1.00 (-15.286451) | 1.00 (-15.286451) | 1.00 (-15.286451) |
| dallouche | Promedas_13 | 1.00 (-27.090597) | 1.00 (-27.090597) | 1.00 (-27.090597) |
| dallouche | Promedas_14 | 1.00 (-18.599675) | 1.00 (-18.599675) | 1.00 (-18.599675) |
| dallouche | Promedas_15 | 1.00 (-24.538854) | 1.00 (-24.538854) | 1.00 (-24.538854) |
| dallouche | Promedas_16 | 1.00 (-19.714956) | 1.00 (-19.714956) | 1.00 (-19.714956) |
| dallouche | Promedas_17 | 1.00 (-19.790235) | 1.00 (-19.790235) | 1.00 (-19.790235) |
| dallouche | Promedas_18 | 1.00 (-24.405720) | 1.00 (-24.405720) | 1.00 (-24.405720) |
| dallouche | Promedas_19 | 1.00 (-26.144218) | 1.00 (-26.144218) | 1.00 (-26.144218) |
| dallouche | Promedas_20 | 1.00 (-12.225969) | 1.00 (-12.225969) | 1.00 (-12.225969) |
| dallouche | Promedas_21 | 1.00 (-17.442462) | 1.00 (-17.442462) | 1.00 (-17.442462) |
| dallouche | Promedas_22 | 1.00 (-16.112633) | 1.00 (-16.112633) | 1.00 (-16.112633) |
| dallouche | Promedas_23 | 1.00 (-23.458485) | 1.00 (-23.458485) | 1.00 (-23.458485) |
| dallouche | Promedas_24 | 1.00 (-12.542312) | 1.00 (-12.542312) | 1.00 (-12.542312) |
| dallouche | Promedas_25 | 1.00 (-14.672095) | 1.00 (-14.672095) | 1.00 (-14.672095) |
| dallouche | Promedas_26 | 1.00 (-19.245086) | 1.00 (-19.245086) | 1.00 (-19.245086) |
| dallouche | Promedas_27 | 1.00 (-10.023281) | 1.00 (-10.023281) | 1.00 (-10.023281) |
| dallouche | Promedas_28 | 1.00 (-5.976281) | 1.00 (-5.976281) | 1.00 (-5.976281) |
| dallouche | Promedas_29 | 1.00 (-19.761113) | 1.00 (-19.761113) | 1.00 (-19.761113) |
| dallouche | Promedas_30 | 1.00 (-10.439065) | 1.00 (-10.439065) | 1.00 (-10.439065) |
| dallouche | Promedas_31 | 1.00 (-12.199562) | 1.00 (-12.199562) | 1.00 (-12.199562) |
| dallouche | Promedas_32 | 1.00 (-13.875033) | 1.00 (-13.875033) | 1.00 (-13.875033) |
| dallouche | Promedas_33 | 1.00 (-14.028949) | 1.00 (-14.028949) | 1.00 (-14.028949) |
| dallouche | Promedas_34 | 1.00 (-17.022867) | 1.00 (-17.022867) | 1.00 (-17.022867) |
| dallouche | Promedas_35 | 1.00 (-11.255544) | 1.00 (-11.255544) | 1.00 (-11.255544) |
| dallouche | Promedas_36 | 1.00 (-8.179996) | 1.00 (-8.179996) | 1.00 (-8.179996) |
| dallouche | Promedas_37 | 1.00 (-15.413972) | 1.00 (-15.413972) | 1.00 (-15.413972) |
| dallouche | Promedas_38 | 1.00 (-12.080001) | 1.00 (-12.080001) | 1.00 (-12.080001) |
| dallouche | Promedas_39 | 1.00 (-20.690628) | 1.00 (-20.690628) | 1.00 (-20.690628) |
| dallouche | Promedas_40 | 1.00 (-7.288980) | 1.00 (-7.288980) | 1.00 (-7.288980) |
| dallouche | Promedas_41 | 1.00 (-9.678987) | 1.00 (-9.678987) | 1.00 (-9.678987) |
| dallouche | Promedas_42 | 1.00 (-12.762584) | 1.00 (-12.762584) | 1.00 (-12.762584) |
| dallouche | Promedas_43 | 1.00 (-7.536269) | 1.00 (-7.536269) | 1.00 (-7.536269) |
| dallouche | Promedas_44 | 1.00 (-9.265009) | 1.00 (-9.265009) | 1.00 (-9.265009) |
| dallouche | Promedas_45 | 1.00 (-7.500451) | 1.00 (-7.500451) | 1.00 (-7.500451) |
| dallouche | Promedas_46 | 1.00 (-12.801987) | 1.00 (-12.801987) | 1.00 (-12.801987) |
| dallouche | Promedas_47 | 1.00 (-14.013809) | 1.00 (-14.013809) | 1.00 (-14.013809) |
| dallouche | Promedas_48 | 1.00 (-10.778584) | 1.00 (-10.778584) | 1.00 (-10.778584) |
| dallouche | Promedas_49 | 1.00 (-8.372280) | 1.00 (-8.372280) | 1.00 (-8.372280) |
| dallouche | Promedas_50 | 1.00 (-8.995057) | 1.00 (-8.995057) | 1.00 (-8.995057) |
| dallouche | Promedas_51 | 1.00 (-12.294454) | 1.00 (-12.294454) | 1.00 (-12.294454) |
| dallouche | Promedas_52 | 1.00 (-10.784241) | 1.00 (-10.784241) | 1.00 (-10.784241) |
| dallouche | Promedas_53 | 1.00 (-9.085503) | 1.00 (-9.085503) | 1.00 (-9.085503) |
| dallouche | Promedas_54 | 1.00 (-10.324254) | 1.00 (-10.324254) | 1.00 (-10.324254) |
| dallouche | Promedas_55 | 1.00 (-12.715439) | 1.00 (-12.715439) | 1.00 (-12.715439) |
| dallouche | Promedas_56 | 1.00 (-10.844023) | 1.00 (-10.844023) | 1.00 (-10.844023) |
| dallouche | Promedas_57 | 1.00 (-10.432162) | 1.00 (-10.432162) | 1.00 (-10.432162) |
| dallouche | Promedas_58 | 1.00 (-19.946604) | 1.00 (-19.946604) | 1.00 (-19.946604) |
| dallouche | Promedas_59 | 1.00 (-10.555197) | 1.00 (-10.555197) | 1.00 (-10.555197) |
| dallouche | Promedas_60 | 1.00 (-10.036466) | 1.00 (-10.036466) | 1.00 (-10.036466) |
| dallouche | Promedas_61 | 1.00 (-6.882303) | 1.00 (-6.882303) | 1.00 (-6.882303) |
| dallouche | Promedas_62 | 1.00 (-4.665399) | 1.00 (-4.665399) | 1.00 (-4.665399) |
| dallouche | Promedas_63 | 1.00 (-6.093362) | 1.00 (-6.093362) | 1.00 (-6.093362) |
| dallouche | Promedas_64 | 1.00 (-11.469786) | 1.00 (-11.469786) | 1.00 (-11.469786) |
| dallouche | Promedas_65 | 1.00 (-5.156746) | 1.00 (-5.156746) | 1.00 (-5.156746) |
| dallouche | Promedas_66 | 1.00 (-10.392104) | 1.00 (-10.392104) | 1.00 (-10.392104) |
| dallouche | Promedas_67 | 1.00 (-13.361078) | 1.00 (-13.361078) | 1.00 (-13.361078) |
| dallouche | Promedas_68 | 1.00 (-18.940748) | 1.00 (-18.940748) | 1.00 (-18.940748) |
| dallouche | Promedas_69 | 1.00 (-11.192360) | 1.00 (-11.192360) | 1.00 (-11.192360) |
| dallouche | Promedas_70 | 1.00 (-4.121582) | 1.00 (-4.121582) | 1.00 (-4.121582) |
| dallouche | Promedas_71 | 1.00 (-6.014154) | 1.00 (-6.014154) | 1.00 (-6.014154) |
| dallouche | ProteinFolding_11 | 0.91 (1938.523709) | 0.94 (1946.493071) | 0.96 (1952.952337) |
| dallouche | ProteinFolding_12 | 1.00 (-1547.125248) | 1.00 (-1547.125248) | 1.00 (-1547.125248) |
| dallouche | ProteinFolding_13 | 1.00 (-143.321762) | 1.00 (-143.321762) | 1.00 (-143.321762) |
| dallouche | ProteinFolding_14 | 1.00 (-331.734776) | 1.00 (-331.734776) | 1.00 (-331.734776) |
| dallouche | ProteinFolding_15 | 1.00 (-51.551640) | 1.00 (-51.551640) | 1.00 (-51.551640) |
| dallouche | ProteinFolding_16 | 1.00 (-855.521914) | 1.00 (-855.521914) | 1.00 (-855.521914) |
| dallouche | ProteinFolding_17 | - (-) | 0.63 (13098.191267) | 0.63 (13098.491520) |
| dallouche | ProteinFolding_18 | 0.00 (12238.305256) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ProteinFolding_19 | -1.00 (  nan) | -1.00 (  nan) | 0.90 (2438.353645) |
| dallouche | ProteinFolding_20 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ProteinFolding_21 | 0.85 (7543.798197) | 0.99 (7905.301980) | 0.99 (7905.301980) |
| dallouche | ProteinFolding_22 | -1.00 (  nan) | 0.99 (10507.137958) | 0.99 (10507.137958) |
| dallouche | ProteinFolding_23 | 0.68 (3968.428791) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ProteinFolding_24 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | ProteinFolding_25 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | Segmentation_11 | 1.00 (-135.829797) | 1.00 (-135.829797) | 1.00 (-135.829797) |
| dallouche | Segmentation_12 | 1.00 (-22.214446) | 1.00 (-22.214446) | 1.00 (-22.214446) |
| dallouche | Segmentation_13 | 1.00 (-21.653378) | 1.00 (-21.653378) | 1.00 (-21.653378) |
| dallouche | Segmentation_14 | 1.00 (-40.099954) | 1.00 (-40.099954) | 1.00 (-40.099954) |
| dallouche | Segmentation_15 | 1.00 (-165.202647) | 1.00 (-165.202647) | 1.00 (-165.202647) |
| dallouche | Segmentation_16 | 1.00 (-41.257946) | 1.00 (-41.257946) | 1.00 (-41.257946) |
| dallouche | Segmentation_17 | 1.00 (-176.786122) | 1.00 (-176.786122) | 1.00 (-176.786122) |
| dallouche | Segmentation_18 | 1.00 (-35.902911) | 1.00 (-35.902911) | 1.00 (-35.902911) |
| dallouche | Segmentation_19 | 1.00 (-25.494906) | 1.00 (-25.494906) | 1.00 (-25.494906) |
| dallouche | Segmentation_20 | 1.00 (-113.878796) | 1.00 (-113.878796) | 1.00 (-113.878796) |
| dallouche | wcsp_11 | 0.87 (-3.337084) | 0.85 (-3.337084) | 0.85 (-3.337084) |
| dallouche | wcsp_12 | 1.00 (-2.577032) | 1.00 (-2.576279) | 1.00 (-2.576279) |
| dallouche | wcsp_13 | 0.33 (-8.070790) | 0.33 (-8.070790) | 0.33 (-8.070790) |
| dallouche | wcsp_14 | 0.43 (-16.086970) | 0.43 (-16.054910) | 0.43 (-16.054910) |
| dallouche | wcsp_15 | 0.50 (-132.000000) | 0.48 (-128.000000) | 0.46 (-128.000000) |
| dallouche | wcsp_16 | 1.00 (-16.492000) | 1.00 (-16.492000) | 1.00 (-16.492000) |
| dallouche | wcsp_17 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| dallouche | wcsp_18 | 0.00 (-32.066761) | 0.00 (-32.035844) | 0.00 (-32.035844) |
| daoopt-1hr-ib35 | Grids_18 | - (-) | - (-) | 1.00 (5674.431752) |
| daoopt-1hr-ib35 | Grids_19 | - (-) | - (-) | 1.00 (1179.244443) |
| daoopt-1hr-ib35 | Grids_20 | - (-) | - (-) | 1.00 (4677.643924) |
| daoopt-1hr-ib35 | Grids_21 | - (-) | - (-) | 1.00 (8496.672906) |
| daoopt-1hr-ib35 | Grids_22 | - (-) | - (-) | 1.00 (2825.476587) |
| daoopt-1hr-ib35 | Grids_23 | - (-) | - (-) | 1.00 (2781.641450) |
| daoopt-1hr-ib35 | Grids_24 | - (-) | - (-) | 1.00 (8234.260906) |
| daoopt-1hr-ib35 | Grids_25 | - (-) | - (-) | 1.00 (1167.819057) |
| daoopt-1hr-ib35 | Grids_26 | - (-) | - (-) | 1.00 (1325.038005) |
| daoopt-1hr-ib35 | Grids_27 | - (-) | - (-) | 1.00 (5504.384331) |
| daoopt-1hr-ib35 | Grids_28 | - (-) | - (-) | 1.00 (1981.759980) |
| daoopt-1hr-ib35 | Grids_29 | - (-) | - (-) | 1.00 (669.970751) |
| daoopt-1hr-ib35 | Grids_30 | - (-) | - (-) | 1.00 (1309.721293) |
| daoopt-1hr-ib35 | ImageAlignment_11 | - (-) | - (-) | 1.00 (-824.234024) |
| daoopt-1hr-ib35 | ImageAlignment_12 | - (-) | - (-) | 1.00 (-436.669411) |
| daoopt-1hr-ib35 | ImageAlignment_13 | - (-) | - (-) | 1.00 (-2999.933955) |
| daoopt-1hr-ib35 | ImageAlignment_14 | - (-) | - (-) | 1.00 (-1557.513069) |
| daoopt-1hr-ib35 | ImageAlignment_15 | - (-) | - (-) | 1.00 (-1177.484737) |
| daoopt-1hr-ib35 | ObjectDetection_11 | - (-) | - (-) | 1.00 (4237.893984) |
| daoopt-1hr-ib35 | ObjectDetection_12 | - (-) | - (-) | 1.00 (6684.994818) |
| daoopt-1hr-ib35 | ObjectDetection_13 | - (-) | - (-) | 1.00 (9854.221704) |
| daoopt-1hr-ib35 | ObjectDetection_14 | - (-) | - (-) | 1.00 (9020.782273) |
| daoopt-1hr-ib35 | ObjectDetection_15 | - (-) | - (-) | 1.00 (12478.579551) |
| daoopt-1hr-ib35 | ObjectDetection_16 | - (-) | - (-) | 0.99 (13536.214904) |
| daoopt-1hr-ib35 | ObjectDetection_17 | - (-) | - (-) | 1.00 (4816.027439) |
| daoopt-1hr-ib35 | ObjectDetection_18 | - (-) | - (-) | 1.00 (8849.451213) |
| daoopt-1hr-ib35 | Promedas_11 | - (-) | - (-) | 1.00 (-20.995503) |
| daoopt-1hr-ib35 | Promedas_12 | - (-) | - (-) | 0.99 (-15.436749) |
| daoopt-1hr-ib35 | Promedas_13 | - (-) | - (-) | 1.00 (-27.090597) |
| daoopt-1hr-ib35 | Promedas_14 | - (-) | - (-) | 1.00 (-18.599675) |
| daoopt-1hr-ib35 | Promedas_15 | - (-) | - (-) | 1.00 (-24.538854) |
| daoopt-1hr-ib35 | Promedas_16 | - (-) | - (-) | 1.00 (-19.714956) |
| daoopt-1hr-ib35 | Promedas_17 | - (-) | - (-) | 1.00 (-19.790235) |
| daoopt-1hr-ib35 | Promedas_18 | - (-) | - (-) | 1.00 (-24.405720) |
| daoopt-1hr-ib35 | Promedas_19 | - (-) | - (-) | 1.00 (-26.144218) |
| daoopt-1hr-ib35 | Promedas_20 | - (-) | - (-) | 1.00 (-12.225969) |
| daoopt-1hr-ib35 | Promedas_21 | - (-) | - (-) | 1.00 (-17.442462) |
| daoopt-1hr-ib35 | Promedas_22 | - (-) | - (-) | 1.00 (-16.112633) |
| daoopt-1hr-ib35 | Promedas_23 | - (-) | - (-) | 1.00 (-23.458485) |
| daoopt-1hr-ib35 | Promedas_24 | - (-) | - (-) | 1.00 (-12.542312) |
| daoopt-1hr-ib35 | Promedas_25 | - (-) | - (-) | 1.00 (-14.672095) |
| daoopt-1hr-ib35 | Promedas_26 | - (-) | - (-) | 1.00 (-19.245086) |
| daoopt-1hr-ib35 | Promedas_27 | - (-) | - (-) | 1.00 (-10.023281) |
| daoopt-1hr-ib35 | Promedas_28 | - (-) | - (-) | 1.00 (-5.976281) |
| daoopt-1hr-ib35 | Promedas_29 | - (-) | - (-) | 1.00 (-19.761113) |
| daoopt-1hr-ib35 | Promedas_30 | - (-) | - (-) | 1.00 (-10.439065) |
| daoopt-1hr-ib35 | Promedas_31 | - (-) | - (-) | 1.00 (-12.199562) |
| daoopt-1hr-ib35 | Promedas_32 | - (-) | - (-) | 1.00 (-13.875033) |
| daoopt-1hr-ib35 | Promedas_33 | - (-) | - (-) | 1.00 (-14.028949) |
| daoopt-1hr-ib35 | Promedas_34 | - (-) | - (-) | 1.00 (-17.022867) |
| daoopt-1hr-ib35 | Promedas_35 | - (-) | - (-) | 1.00 (-11.255544) |
| daoopt-1hr-ib35 | Promedas_36 | - (-) | - (-) | 1.00 (-8.179996) |
| daoopt-1hr-ib35 | Promedas_37 | - (-) | - (-) | 1.00 (-15.413972) |
| daoopt-1hr-ib35 | Promedas_38 | - (-) | - (-) | 1.00 (-12.080001) |
| daoopt-1hr-ib35 | Promedas_39 | - (-) | - (-) | 1.00 (-20.690628) |
| daoopt-1hr-ib35 | Promedas_40 | - (-) | - (-) | 1.00 (-7.288980) |
| daoopt-1hr-ib35 | Promedas_41 | - (-) | - (-) | 1.00 (-9.678987) |
| daoopt-1hr-ib35 | Promedas_42 | - (-) | - (-) | 1.00 (-12.762584) |
| daoopt-1hr-ib35 | Promedas_43 | - (-) | - (-) | 1.00 (-7.536269) |
| daoopt-1hr-ib35 | Promedas_44 | - (-) | - (-) | 1.00 (-9.265009) |
| daoopt-1hr-ib35 | Promedas_45 | - (-) | - (-) | 1.00 (-7.500451) |
| daoopt-1hr-ib35 | Promedas_46 | - (-) | - (-) | 1.00 (-12.801987) |
| daoopt-1hr-ib35 | Promedas_47 | - (-) | - (-) | 1.00 (-14.013809) |
| daoopt-1hr-ib35 | Promedas_48 | - (-) | - (-) | 1.00 (-10.778584) |
| daoopt-1hr-ib35 | Promedas_49 | - (-) | - (-) | 1.00 (-8.372280) |
| daoopt-1hr-ib35 | Promedas_50 | - (-) | - (-) | 1.00 (-8.995057) |
| daoopt-1hr-ib35 | Promedas_51 | - (-) | - (-) | 1.00 (-12.294454) |
| daoopt-1hr-ib35 | Promedas_52 | - (-) | - (-) | 1.00 (-10.784241) |
| daoopt-1hr-ib35 | Promedas_53 | - (-) | - (-) | 1.00 (-9.085503) |
| daoopt-1hr-ib35 | Promedas_54 | - (-) | - (-) | 1.00 (-10.324254) |
| daoopt-1hr-ib35 | Promedas_55 | - (-) | - (-) | 1.00 (-12.715439) |
| daoopt-1hr-ib35 | Promedas_56 | - (-) | - (-) | 1.00 (-10.844023) |
| daoopt-1hr-ib35 | Promedas_57 | - (-) | - (-) | 1.00 (-10.432162) |
| daoopt-1hr-ib35 | Promedas_58 | - (-) | - (-) | 1.00 (-19.946604) |
| daoopt-1hr-ib35 | Promedas_59 | - (-) | - (-) | 1.00 (-10.555197) |
| daoopt-1hr-ib35 | Promedas_60 | - (-) | - (-) | 1.00 (-10.036466) |
| daoopt-1hr-ib35 | Promedas_61 | - (-) | - (-) | 1.00 (-6.882303) |
| daoopt-1hr-ib35 | Promedas_62 | - (-) | - (-) | 1.00 (-4.665399) |
| daoopt-1hr-ib35 | Promedas_63 | - (-) | - (-) | 1.00 (-6.093362) |
| daoopt-1hr-ib35 | Promedas_64 | - (-) | - (-) | 1.00 (-11.469786) |
| daoopt-1hr-ib35 | Promedas_65 | - (-) | - (-) | 1.00 (-5.156746) |
| daoopt-1hr-ib35 | Promedas_66 | - (-) | - (-) | 1.00 (-10.392104) |
| daoopt-1hr-ib35 | Promedas_67 | - (-) | - (-) | 1.00 (-13.361078) |
| daoopt-1hr-ib35 | Promedas_68 | - (-) | - (-) | 1.00 (-18.940748) |
| daoopt-1hr-ib35 | Promedas_69 | - (-) | - (-) | 1.00 (-11.192360) |
| daoopt-1hr-ib35 | Promedas_70 | - (-) | - (-) | 1.00 (-4.121582) |
| daoopt-1hr-ib35 | Promedas_71 | - (-) | - (-) | 1.00 (-6.014154) |
| daoopt-1hr-ib35 | ProteinFolding_11 | - (-) | - (-) | 1.00 (1961.845320) |
| daoopt-1hr-ib35 | ProteinFolding_12 | - (-) | - (-) | 1.00 (-1547.125248) |
| daoopt-1hr-ib35 | ProteinFolding_13 | - (-) | - (-) | 1.00 (-143.321762) |
| daoopt-1hr-ib35 | ProteinFolding_14 | - (-) | - (-) | 1.00 (-331.734776) |
| daoopt-1hr-ib35 | ProteinFolding_15 | - (-) | - (-) | 1.00 (-51.551640) |
| daoopt-1hr-ib35 | ProteinFolding_16 | - (-) | - (-) | 1.00 (-855.521914) |
| daoopt-1hr-ib35 | ProteinFolding_17 | - (-) | - (-) | 1.00 (16544.169748) |
| daoopt-1hr-ib35 | ProteinFolding_18 | - (-) | - (-) | 1.00 (18606.266173) |
| daoopt-1hr-ib35 | ProteinFolding_19 | - (-) | - (-) | 1.00 (2448.664503) |
| daoopt-1hr-ib35 | ProteinFolding_20 | - (-) | - (-) | 1.00 (5577.253167) |
| daoopt-1hr-ib35 | ProteinFolding_21 | - (-) | - (-) | 1.00 (7958.719664) |
| daoopt-1hr-ib35 | ProteinFolding_22 | - (-) | - (-) | 1.00 (10547.218187) |
| daoopt-1hr-ib35 | ProteinFolding_23 | - (-) | - (-) | 1.00 (4215.114527) |
| daoopt-1hr-ib35 | ProteinFolding_24 | - (-) | - (-) | 1.00 (5868.771956) |
| daoopt-1hr-ib35 | ProteinFolding_25 | - (-) | - (-) | 1.00 (8656.260558) |
| daoopt-1hr-ib35 | Segmentation_11 | - (-) | - (-) | 1.00 (-135.829797) |
| daoopt-1hr-ib35 | Segmentation_12 | - (-) | - (-) | 1.00 (-22.214446) |
| daoopt-1hr-ib35 | Segmentation_13 | - (-) | - (-) | 1.00 (-21.653378) |
| daoopt-1hr-ib35 | Segmentation_14 | - (-) | - (-) | 1.00 (-40.099954) |
| daoopt-1hr-ib35 | Segmentation_15 | - (-) | - (-) | 1.00 (-165.202647) |
| daoopt-1hr-ib35 | Segmentation_16 | - (-) | - (-) | 1.00 (-41.257946) |
| daoopt-1hr-ib35 | Segmentation_17 | - (-) | - (-) | 1.00 (-176.786122) |
| daoopt-1hr-ib35 | Segmentation_18 | - (-) | - (-) | 1.00 (-35.902911) |
| daoopt-1hr-ib35 | Segmentation_19 | - (-) | - (-) | 1.00 (-25.494906) |
| daoopt-1hr-ib35 | Segmentation_20 | - (-) | - (-) | 1.00 (-113.878796) |
| daoopt-1hr-ib35 | wcsp_11 | - (-) | - (-) | 1.00 (-3.312556) |
| daoopt-1hr-ib35 | wcsp_12 | - (-) | - (-) | 1.00 (-2.576843) |
| daoopt-1hr-ib35 | wcsp_13 | - (-) | - (-) | 1.00 (-0.212371) |
| daoopt-1hr-ib35 | wcsp_14 | - (-) | - (-) | 1.00 (-0.137105) |
| daoopt-1hr-ib35 | wcsp_15 | - (-) | - (-) | 1.00 (-76.000000) |
| daoopt-1hr-ib35 | wcsp_16 | - (-) | - (-) | 1.00 (-16.492000) |
| daoopt-1hr-ib35 | wcsp_17 | - (-) | - (-) | 1.00 (-13.156000) |
| daoopt-1hr-ib35 | wcsp_18 | - (-) | - (-) | 1.00 (-0.082510) |
| daoopt-1hr-weak | Grids_18 | - (-) | - (-) | 0.89 (5576.225030) |
| daoopt-1hr-weak | Grids_19 | - (-) | - (-) | 0.99 (1177.579046) |
| daoopt-1hr-weak | Grids_20 | - (-) | - (-) | 0.93 (4637.780301) |
| daoopt-1hr-weak | Grids_21 | - (-) | - (-) | 0.87 (8332.770157) |
| daoopt-1hr-weak | Grids_22 | - (-) | - (-) | 0.97 (2810.655170) |
| daoopt-1hr-weak | Grids_23 | - (-) | - (-) | 0.98 (2773.013164) |
| daoopt-1hr-weak | Grids_24 | - (-) | - (-) | 0.96 (8191.689966) |
| daoopt-1hr-weak | Grids_25 | - (-) | - (-) | 0.99 (1167.321501) |
| daoopt-1hr-weak | Grids_26 | - (-) | - (-) | 0.97 (1319.689331) |
| daoopt-1hr-weak | Grids_27 | - (-) | - (-) | 0.98 (5492.211518) |
| daoopt-1hr-weak | Grids_28 | - (-) | - (-) | 0.96 (1970.738194) |
| daoopt-1hr-weak | Grids_29 | - (-) | - (-) | 1.00 (669.970751) |
| daoopt-1hr-weak | Grids_30 | - (-) | - (-) | 1.00 (1309.721293) |
| daoopt-1hr-weak | ImageAlignment_11 | - (-) | - (-) | 1.00 (-824.234024) |
| daoopt-1hr-weak | ImageAlignment_12 | - (-) | - (-) | 1.00 (-436.669411) |
| daoopt-1hr-weak | ImageAlignment_13 | - (-) | - (-) | 1.00 (-2999.933955) |
| daoopt-1hr-weak | ImageAlignment_14 | - (-) | - (-) | 1.00 (-1557.513069) |
| daoopt-1hr-weak | ImageAlignment_15 | - (-) | - (-) | 1.00 (-1177.484737) |
| daoopt-1hr-weak | ObjectDetection_11 | - (-) | - (-) | 0.00 (2667.219086) |
| daoopt-1hr-weak | ObjectDetection_12 | - (-) | - (-) | 0.33 (4223.315708) |
| daoopt-1hr-weak | ObjectDetection_13 | - (-) | - (-) | 0.72 (8572.308957) |
| daoopt-1hr-weak | ObjectDetection_14 | - (-) | - (-) | 0.63 (6845.342448) |
| daoopt-1hr-weak | ObjectDetection_15 | - (-) | - (-) | 0.82 (10958.130858) |
| daoopt-1hr-weak | ObjectDetection_16 | - (-) | - (-) | 0.64 (11789.543522) |
| daoopt-1hr-weak | ObjectDetection_17 | - (-) | - (-) | 0.79 (4485.481124) |
| daoopt-1hr-weak | ObjectDetection_18 | - (-) | - (-) | 0.75 (7246.903476) |
| daoopt-1hr-weak | Promedas_11 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_12 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_13 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_14 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_15 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_16 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_17 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_18 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_19 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_20 | - (-) | - (-) | 0.31 (-36.293188) |
| daoopt-1hr-weak | Promedas_21 | - (-) | - (-) | 0.49 (-40.240063) |
| daoopt-1hr-weak | Promedas_22 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_23 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_24 | - (-) | - (-) | 0.82 (-14.819664) |
| daoopt-1hr-weak | Promedas_25 | - (-) | - (-) | 0.57 (-23.109702) |
| daoopt-1hr-weak | Promedas_26 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_27 | - (-) | - (-) | 0.54 (-16.848511) |
| daoopt-1hr-weak | Promedas_28 | - (-) | - (-) | 0.00 (-15.824628) |
| daoopt-1hr-weak | Promedas_29 | - (-) | - (-) | 0.80 (-23.700105) |
| daoopt-1hr-weak | Promedas_30 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_31 | - (-) | - (-) | 0.32 (-17.995495) |
| daoopt-1hr-weak | Promedas_32 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_33 | - (-) | - (-) | 0.88 (-15.949212) |
| daoopt-1hr-weak | Promedas_34 | - (-) | - (-) | 0.78 (-21.249767) |
| daoopt-1hr-weak | Promedas_35 | - (-) | - (-) | 0.95 (-12.095702) |
| daoopt-1hr-weak | Promedas_36 | - (-) | - (-) | 0.57 (-17.476618) |
| daoopt-1hr-weak | Promedas_37 | - (-) | - (-) | 0.82 (-20.289642) |
| daoopt-1hr-weak | Promedas_38 | - (-) | - (-) | 0.98 (-12.354055) |
| daoopt-1hr-weak | Promedas_39 | - (-) | - (-) | 0.68 (-24.056085) |
| daoopt-1hr-weak | Promedas_40 | - (-) | - (-) | 0.70 (-10.860499) |
| daoopt-1hr-weak | Promedas_41 | - (-) | - (-) | 0.93 (-10.376741) |
| daoopt-1hr-weak | Promedas_42 | - (-) | - (-) | 0.94 (-14.337668) |
| daoopt-1hr-weak | Promedas_43 | - (-) | - (-) | 0.88 (-9.156753) |
| daoopt-1hr-weak | Promedas_44 | - (-) | - (-) | 0.00 (-21.880269) |
| daoopt-1hr-weak | Promedas_45 | - (-) | - (-) | 0.82 (-7.975272) |
| daoopt-1hr-weak | Promedas_46 | - (-) | - (-) | 0.77 (-16.086453) |
| daoopt-1hr-weak | Promedas_47 | - (-) | - (-) | 0.91 (-14.235484) |
| daoopt-1hr-weak | Promedas_48 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_49 | - (-) | - (-) | 0.02 (-15.590516) |
| daoopt-1hr-weak | Promedas_50 | - (-) | - (-) | 0.99 (-9.167522) |
| daoopt-1hr-weak | Promedas_51 | - (-) | - (-) | 0.88 (-12.914615) |
| daoopt-1hr-weak | Promedas_52 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_53 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_54 | - (-) | - (-) | 1.00 (-10.324254) |
| daoopt-1hr-weak | Promedas_55 | - (-) | - (-) | 1.00 (-12.715439) |
| daoopt-1hr-weak | Promedas_56 | - (-) | - (-) | 1.00 (-10.844023) |
| daoopt-1hr-weak | Promedas_57 | - (-) | - (-) | 0.97 (-10.588895) |
| daoopt-1hr-weak | Promedas_58 | - (-) | - (-) | 1.00 (-19.946604) |
| daoopt-1hr-weak | Promedas_59 | - (-) | - (-) | 0.92 (-11.640076) |
| daoopt-1hr-weak | Promedas_60 | - (-) | - (-) | 1.00 (-10.036466) |
| daoopt-1hr-weak | Promedas_61 | - (-) | - (-) | 1.00 (-6.882303) |
| daoopt-1hr-weak | Promedas_62 | - (-) | - (-) | 1.00 (-4.665399) |
| daoopt-1hr-weak | Promedas_63 | - (-) | - (-) | 0.00 (-12.768625) |
| daoopt-1hr-weak | Promedas_64 | - (-) | - (-) | 0.00 (-14.999074) |
| daoopt-1hr-weak | Promedas_65 | - (-) | - (-) | 1.00 (-5.156746) |
| daoopt-1hr-weak | Promedas_66 | - (-) | - (-) | 1.00 (-10.392104) |
| daoopt-1hr-weak | Promedas_67 | - (-) | - (-) | -1.00 (  nan) |
| daoopt-1hr-weak | Promedas_68 | - (-) | - (-) | 0.94 (-20.441459) |
| daoopt-1hr-weak | Promedas_69 | - (-) | - (-) | 1.00 (-11.192360) |
| daoopt-1hr-weak | Promedas_70 | - (-) | - (-) | 0.00 (-8.894208) |
| daoopt-1hr-weak | Promedas_71 | - (-) | - (-) | 0.33 (-7.516743) |
| daoopt-1hr-weak | ProteinFolding_11 | - (-) | - (-) | 1.00 (1961.845320) |
| daoopt-1hr-weak | ProteinFolding_12 | - (-) | - (-) | 1.00 (-1547.125248) |
| daoopt-1hr-weak | ProteinFolding_13 | - (-) | - (-) | 1.00 (-143.321762) |
| daoopt-1hr-weak | ProteinFolding_14 | - (-) | - (-) | 1.00 (-331.734776) |
| daoopt-1hr-weak | ProteinFolding_15 | - (-) | - (-) | 1.00 (-51.551640) |
| daoopt-1hr-weak | ProteinFolding_16 | - (-) | - (-) | 1.00 (-855.521914) |
| daoopt-1hr-weak | ProteinFolding_17 | - (-) | - (-) | 0.20 (9024.023568) |
| daoopt-1hr-weak | ProteinFolding_18 | - (-) | - (-) | 0.78 (16705.130233) |
| daoopt-1hr-weak | ProteinFolding_19 | - (-) | - (-) | 0.00 (2350.116854) |
| daoopt-1hr-weak | ProteinFolding_20 | - (-) | - (-) | 0.41 (4484.075807) |
| daoopt-1hr-weak | ProteinFolding_21 | - (-) | - (-) | 0.82 (7101.018802) |
| daoopt-1hr-weak | ProteinFolding_22 | - (-) | - (-) | 0.96 (10346.272253) |
| daoopt-1hr-weak | ProteinFolding_23 | - (-) | - (-) | 0.00 (3455.840945) |
| daoopt-1hr-weak | ProteinFolding_24 | - (-) | - (-) | 0.38 (4866.525356) |
| daoopt-1hr-weak | ProteinFolding_25 | - (-) | - (-) | 0.63 (6887.604905) |
| daoopt-1hr-weak | Segmentation_11 | - (-) | - (-) | 1.00 (-135.829797) |
| daoopt-1hr-weak | Segmentation_12 | - (-) | - (-) | 1.00 (-22.214446) |
| daoopt-1hr-weak | Segmentation_13 | - (-) | - (-) | 1.00 (-21.653378) |
| daoopt-1hr-weak | Segmentation_14 | - (-) | - (-) | 1.00 (-40.099954) |
| daoopt-1hr-weak | Segmentation_15 | - (-) | - (-) | 1.00 (-165.202647) |
| daoopt-1hr-weak | Segmentation_16 | - (-) | - (-) | 1.00 (-41.257946) |
| daoopt-1hr-weak | Segmentation_17 | - (-) | - (-) | 1.00 (-176.786122) |
| daoopt-1hr-weak | Segmentation_18 | - (-) | - (-) | 1.00 (-35.902911) |
| daoopt-1hr-weak | Segmentation_19 | - (-) | - (-) | 1.00 (-25.494906) |
| daoopt-1hr-weak | Segmentation_20 | - (-) | - (-) | 1.00 (-113.878796) |
| daoopt-1hr-weak | wcsp_11 | - (-) | - (-) | 0.46 (-3.398404) |
| daoopt-1hr-weak | wcsp_12 | - (-) | - (-) | 0.00 (-2.861268) |
| daoopt-1hr-weak | wcsp_13 | - (-) | - (-) | 1.00 (-0.212371) |
| daoopt-1hr-weak | wcsp_14 | - (-) | - (-) | 0.43 (-16.049453) |
| daoopt-1hr-weak | wcsp_15 | - (-) | - (-) | 0.00 (-172.000000) |
| daoopt-1hr-weak | wcsp_16 | - (-) | - (-) | 0.42 (-21.084000) |
| daoopt-1hr-weak | wcsp_17 | - (-) | - (-) | 0.00 (-59.788000) |
| daoopt-1hr-weak | wcsp_18 | - (-) | - (-) | 0.50 (-16.000386) |
| daoopt-20min-ib25 | Grids_18 | - (-) | 1.00 (5674.431752) | - (-) |
| daoopt-20min-ib25 | Grids_19 | - (-) | 1.00 (1179.244443) | - (-) |
| daoopt-20min-ib25 | Grids_20 | - (-) | 1.00 (4677.734173) | - (-) |
| daoopt-20min-ib25 | Grids_21 | - (-) | 1.00 (8496.672906) | - (-) |
| daoopt-20min-ib25 | Grids_22 | - (-) | 1.00 (2825.476587) | - (-) |
| daoopt-20min-ib25 | Grids_23 | - (-) | 1.00 (2781.641450) | - (-) |
| daoopt-20min-ib25 | Grids_24 | - (-) | 1.00 (8234.260906) | - (-) |
| daoopt-20min-ib25 | Grids_25 | - (-) | 1.00 (1167.819057) | - (-) |
| daoopt-20min-ib25 | Grids_26 | - (-) | 1.00 (1325.038005) | - (-) |
| daoopt-20min-ib25 | Grids_27 | - (-) | 1.00 (5504.384331) | - (-) |
| daoopt-20min-ib25 | Grids_28 | - (-) | 1.00 (1981.759980) | - (-) |
| daoopt-20min-ib25 | Grids_29 | - (-) | 1.00 (669.970751) | - (-) |
| daoopt-20min-ib25 | Grids_30 | - (-) | 1.00 (1309.721293) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_11 | - (-) | 1.00 (-824.234024) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_12 | - (-) | 1.00 (-436.669411) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_13 | - (-) | 1.00 (-2999.933955) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_14 | - (-) | 1.00 (-1557.513069) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_15 | - (-) | 1.00 (-1177.484737) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_11 | - (-) | 1.00 (4237.893984) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_12 | - (-) | 1.00 (6684.994818) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_13 | - (-) | 1.00 (9854.221704) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_14 | - (-) | 1.00 (9020.782273) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_15 | - (-) | 1.00 (12478.579551) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_16 | - (-) | 0.99 (13536.214904) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_17 | - (-) | 1.00 (4816.027439) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_18 | - (-) | 1.00 (8849.451213) | - (-) |
| daoopt-20min-ib25 | Promedas_11 | - (-) | 0.98 (-21.457977) | - (-) |
| daoopt-20min-ib25 | Promedas_12 | - (-) | 1.00 (-15.286451) | - (-) |
| daoopt-20min-ib25 | Promedas_13 | - (-) | 1.00 (-27.090597) | - (-) |
| daoopt-20min-ib25 | Promedas_14 | - (-) | 1.00 (-18.599675) | - (-) |
| daoopt-20min-ib25 | Promedas_15 | - (-) | 1.00 (-24.538854) | - (-) |
| daoopt-20min-ib25 | Promedas_16 | - (-) | 1.00 (-19.714956) | - (-) |
| daoopt-20min-ib25 | Promedas_17 | - (-) | 1.00 (-19.790235) | - (-) |
| daoopt-20min-ib25 | Promedas_18 | - (-) | 1.00 (-24.405720) | - (-) |
| daoopt-20min-ib25 | Promedas_19 | - (-) | 1.00 (-26.144218) | - (-) |
| daoopt-20min-ib25 | Promedas_20 | - (-) | 1.00 (-12.225969) | - (-) |
| daoopt-20min-ib25 | Promedas_21 | - (-) | 1.00 (-17.442462) | - (-) |
| daoopt-20min-ib25 | Promedas_22 | - (-) | 1.00 (-16.112633) | - (-) |
| daoopt-20min-ib25 | Promedas_23 | - (-) | 1.00 (-23.458485) | - (-) |
| daoopt-20min-ib25 | Promedas_24 | - (-) | 1.00 (-12.542312) | - (-) |
| daoopt-20min-ib25 | Promedas_25 | - (-) | 1.00 (-14.672095) | - (-) |
| daoopt-20min-ib25 | Promedas_26 | - (-) | 1.00 (-19.245086) | - (-) |
| daoopt-20min-ib25 | Promedas_27 | - (-) | 1.00 (-10.023281) | - (-) |
| daoopt-20min-ib25 | Promedas_28 | - (-) | 1.00 (-5.976281) | - (-) |
| daoopt-20min-ib25 | Promedas_29 | - (-) | 1.00 (-19.761113) | - (-) |
| daoopt-20min-ib25 | Promedas_30 | - (-) | 1.00 (-10.439065) | - (-) |
| daoopt-20min-ib25 | Promedas_31 | - (-) | 1.00 (-12.199562) | - (-) |
| daoopt-20min-ib25 | Promedas_32 | - (-) | 0.00 (-13.890450) | - (-) |
| daoopt-20min-ib25 | Promedas_33 | - (-) | 1.00 (-14.028949) | - (-) |
| daoopt-20min-ib25 | Promedas_34 | - (-) | 1.00 (-17.022867) | - (-) |
| daoopt-20min-ib25 | Promedas_35 | - (-) | 1.00 (-11.255544) | - (-) |
| daoopt-20min-ib25 | Promedas_36 | - (-) | 1.00 (-8.179996) | - (-) |
| daoopt-20min-ib25 | Promedas_37 | - (-) | 1.00 (-15.413972) | - (-) |
| daoopt-20min-ib25 | Promedas_38 | - (-) | 1.00 (-12.080001) | - (-) |
| daoopt-20min-ib25 | Promedas_39 | - (-) | 1.00 (-20.690628) | - (-) |
| daoopt-20min-ib25 | Promedas_40 | - (-) | 1.00 (-7.288980) | - (-) |
| daoopt-20min-ib25 | Promedas_41 | - (-) | 1.00 (-9.678987) | - (-) |
| daoopt-20min-ib25 | Promedas_42 | - (-) | 1.00 (-12.762584) | - (-) |
| daoopt-20min-ib25 | Promedas_43 | - (-) | 1.00 (-7.536269) | - (-) |
| daoopt-20min-ib25 | Promedas_44 | - (-) | 1.00 (-9.265009) | - (-) |
| daoopt-20min-ib25 | Promedas_45 | - (-) | 1.00 (-7.500451) | - (-) |
| daoopt-20min-ib25 | Promedas_46 | - (-) | 1.00 (-12.801987) | - (-) |
| daoopt-20min-ib25 | Promedas_47 | - (-) | 1.00 (-14.013809) | - (-) |
| daoopt-20min-ib25 | Promedas_48 | - (-) | 1.00 (-10.778584) | - (-) |
| daoopt-20min-ib25 | Promedas_49 | - (-) | 1.00 (-8.372280) | - (-) |
| daoopt-20min-ib25 | Promedas_50 | - (-) | 1.00 (-8.995057) | - (-) |
| daoopt-20min-ib25 | Promedas_51 | - (-) | 1.00 (-12.294454) | - (-) |
| daoopt-20min-ib25 | Promedas_52 | - (-) | 1.00 (-10.784241) | - (-) |
| daoopt-20min-ib25 | Promedas_53 | - (-) | 1.00 (-9.085503) | - (-) |
| daoopt-20min-ib25 | Promedas_54 | - (-) | 1.00 (-10.324254) | - (-) |
| daoopt-20min-ib25 | Promedas_55 | - (-) | 1.00 (-12.715439) | - (-) |
| daoopt-20min-ib25 | Promedas_56 | - (-) | 1.00 (-10.844023) | - (-) |
| daoopt-20min-ib25 | Promedas_57 | - (-) | 1.00 (-10.432162) | - (-) |
| daoopt-20min-ib25 | Promedas_58 | - (-) | 1.00 (-19.946604) | - (-) |
| daoopt-20min-ib25 | Promedas_59 | - (-) | 1.00 (-10.555197) | - (-) |
| daoopt-20min-ib25 | Promedas_60 | - (-) | 1.00 (-10.036466) | - (-) |
| daoopt-20min-ib25 | Promedas_61 | - (-) | 1.00 (-6.882303) | - (-) |
| daoopt-20min-ib25 | Promedas_62 | - (-) | 1.00 (-4.665399) | - (-) |
| daoopt-20min-ib25 | Promedas_63 | - (-) | 1.00 (-6.093362) | - (-) |
| daoopt-20min-ib25 | Promedas_64 | - (-) | 1.00 (-11.469786) | - (-) |
| daoopt-20min-ib25 | Promedas_65 | - (-) | 1.00 (-5.156746) | - (-) |
| daoopt-20min-ib25 | Promedas_66 | - (-) | 1.00 (-10.392104) | - (-) |
| daoopt-20min-ib25 | Promedas_67 | - (-) | 1.00 (-13.361078) | - (-) |
| daoopt-20min-ib25 | Promedas_68 | - (-) | 1.00 (-18.940748) | - (-) |
| daoopt-20min-ib25 | Promedas_69 | - (-) | 1.00 (-11.192360) | - (-) |
| daoopt-20min-ib25 | Promedas_70 | - (-) | 1.00 (-4.121582) | - (-) |
| daoopt-20min-ib25 | Promedas_71 | - (-) | 1.00 (-6.014154) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_11 | - (-) | 1.00 (1961.845320) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_12 | - (-) | 1.00 (-1547.125248) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_13 | - (-) | 1.00 (-143.321762) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_14 | - (-) | 1.00 (-331.734776) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_15 | - (-) | 1.00 (-51.551640) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_16 | - (-) | 1.00 (-855.521914) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_17 | - (-) | 1.00 (16544.169748) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_18 | - (-) | 1.00 (18606.266173) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_19 | - (-) | 1.00 (2448.664503) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_20 | - (-) | 1.00 (5577.253167) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_21 | - (-) | 1.00 (7958.719664) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_22 | - (-) | 1.00 (10547.218187) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_23 | - (-) | 0.99 (4210.150115) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_24 | - (-) | 1.00 (5868.771956) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_25 | - (-) | 1.00 (8656.260558) | - (-) |
| daoopt-20min-ib25 | Segmentation_11 | - (-) | 1.00 (-135.829797) | - (-) |
| daoopt-20min-ib25 | Segmentation_12 | - (-) | 1.00 (-22.214446) | - (-) |
| daoopt-20min-ib25 | Segmentation_13 | - (-) | 1.00 (-21.653378) | - (-) |
| daoopt-20min-ib25 | Segmentation_14 | - (-) | 1.00 (-40.099954) | - (-) |
| daoopt-20min-ib25 | Segmentation_15 | - (-) | 1.00 (-165.202647) | - (-) |
| daoopt-20min-ib25 | Segmentation_16 | - (-) | 1.00 (-41.257946) | - (-) |
| daoopt-20min-ib25 | Segmentation_17 | - (-) | 1.00 (-176.786122) | - (-) |
| daoopt-20min-ib25 | Segmentation_18 | - (-) | 1.00 (-35.902911) | - (-) |
| daoopt-20min-ib25 | Segmentation_19 | - (-) | 1.00 (-25.494906) | - (-) |
| daoopt-20min-ib25 | Segmentation_20 | - (-) | 1.00 (-113.878796) | - (-) |
| daoopt-20min-ib25 | wcsp_11 | - (-) | 0.69 (-3.361612) | - (-) |
| daoopt-20min-ib25 | wcsp_12 | - (-) | 1.00 (-2.577408) | - (-) |
| daoopt-20min-ib25 | wcsp_13 | - (-) | 1.00 (-0.212371) | - (-) |
| daoopt-20min-ib25 | wcsp_14 | - (-) | 1.00 (-0.137105) | - (-) |
| daoopt-20min-ib25 | wcsp_15 | - (-) | 1.00 (-76.000000) | - (-) |
| daoopt-20min-ib25 | wcsp_16 | - (-) | 1.00 (-16.492000) | - (-) |
| daoopt-20min-ib25 | wcsp_17 | - (-) | 1.00 (-13.156000) | - (-) |
| daoopt-20min-ib25 | wcsp_18 | - (-) | 1.00 (-0.082510) | - (-) |
| daoopt-20min-weak | Grids_18 | - (-) | 0.89 (5576.225030) | - (-) |
| daoopt-20min-weak | Grids_19 | - (-) | 0.99 (1177.579046) | - (-) |
| daoopt-20min-weak | Grids_20 | - (-) | 0.92 (4631.479565) | - (-) |
| daoopt-20min-weak | Grids_21 | - (-) | 0.87 (8332.770157) | - (-) |
| daoopt-20min-weak | Grids_22 | - (-) | 0.97 (2810.655170) | - (-) |
| daoopt-20min-weak | Grids_23 | - (-) | 0.98 (2773.013164) | - (-) |
| daoopt-20min-weak | Grids_24 | - (-) | 0.96 (8191.689966) | - (-) |
| daoopt-20min-weak | Grids_25 | - (-) | 0.99 (1167.321501) | - (-) |
| daoopt-20min-weak | Grids_26 | - (-) | 0.95 (1315.693261) | - (-) |
| daoopt-20min-weak | Grids_27 | - (-) | 0.98 (5492.211518) | - (-) |
| daoopt-20min-weak | Grids_28 | - (-) | 0.96 (1970.738194) | - (-) |
| daoopt-20min-weak | Grids_29 | - (-) | 1.00 (669.970751) | - (-) |
| daoopt-20min-weak | Grids_30 | - (-) | 1.00 (1309.721293) | - (-) |
| daoopt-20min-weak | ImageAlignment_11 | - (-) | 1.00 (-824.234024) | - (-) |
| daoopt-20min-weak | ImageAlignment_12 | - (-) | 1.00 (-436.669411) | - (-) |
| daoopt-20min-weak | ImageAlignment_13 | - (-) | 1.00 (-2999.933955) | - (-) |
| daoopt-20min-weak | ImageAlignment_14 | - (-) | 1.00 (-1557.513069) | - (-) |
| daoopt-20min-weak | ImageAlignment_15 | - (-) | 1.00 (-1177.484737) | - (-) |
| daoopt-20min-weak | ObjectDetection_11 | - (-) | 0.00 (2667.219086) | - (-) |
| daoopt-20min-weak | ObjectDetection_12 | - (-) | 0.33 (4223.315708) | - (-) |
| daoopt-20min-weak | ObjectDetection_13 | - (-) | 0.69 (8572.308957) | - (-) |
| daoopt-20min-weak | ObjectDetection_14 | - (-) | 0.63 (6845.342448) | - (-) |
| daoopt-20min-weak | ObjectDetection_15 | - (-) | 0.82 (10958.130858) | - (-) |
| daoopt-20min-weak | ObjectDetection_16 | - (-) | 0.70 (11789.543522) | - (-) |
| daoopt-20min-weak | ObjectDetection_17 | - (-) | 0.79 (4485.481124) | - (-) |
| daoopt-20min-weak | ObjectDetection_18 | - (-) | 0.75 (7246.903476) | - (-) |
| daoopt-20min-weak | Promedas_11 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_12 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_13 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_14 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_15 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_16 | - (-) | 0.00 (-33.066412) | - (-) |
| daoopt-20min-weak | Promedas_17 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_18 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_19 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_20 | - (-) | 0.00 (-36.293188) | - (-) |
| daoopt-20min-weak | Promedas_21 | - (-) | 0.50 (-40.240063) | - (-) |
| daoopt-20min-weak | Promedas_22 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_23 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_24 | - (-) | 0.86 (-14.819664) | - (-) |
| daoopt-20min-weak | Promedas_25 | - (-) | 0.45 (-25.403281) | - (-) |
| daoopt-20min-weak | Promedas_26 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_27 | - (-) | 0.72 (-15.860253) | - (-) |
| daoopt-20min-weak | Promedas_28 | - (-) | 0.00 (-15.824628) | - (-) |
| daoopt-20min-weak | Promedas_29 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_30 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_31 | - (-) | 0.03 (-20.541148) | - (-) |
| daoopt-20min-weak | Promedas_32 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_33 | - (-) | 1.00 (-14.028949) | - (-) |
| daoopt-20min-weak | Promedas_34 | - (-) | 0.44 (-27.837824) | - (-) |
| daoopt-20min-weak | Promedas_35 | - (-) | 0.95 (-12.095702) | - (-) |
| daoopt-20min-weak | Promedas_36 | - (-) | 0.48 (-17.096528) | - (-) |
| daoopt-20min-weak | Promedas_37 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_38 | - (-) | 0.92 (-13.365855) | - (-) |
| daoopt-20min-weak | Promedas_39 | - (-) | 0.75 (-24.056085) | - (-) |
| daoopt-20min-weak | Promedas_40 | - (-) | 0.15 (-18.334682) | - (-) |
| daoopt-20min-weak | Promedas_41 | - (-) | 0.93 (-10.376741) | - (-) |
| daoopt-20min-weak | Promedas_42 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_43 | - (-) | 0.88 (-9.156753) | - (-) |
| daoopt-20min-weak | Promedas_44 | - (-) | 0.00 (-21.880269) | - (-) |
| daoopt-20min-weak | Promedas_45 | - (-) | 0.82 (-7.975272) | - (-) |
| daoopt-20min-weak | Promedas_46 | - (-) | 1.00 (-12.801987) | - (-) |
| daoopt-20min-weak | Promedas_47 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_48 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_49 | - (-) | 0.02 (-15.590516) | - (-) |
| daoopt-20min-weak | Promedas_50 | - (-) | 0.99 (-9.167522) | - (-) |
| daoopt-20min-weak | Promedas_51 | - (-) | 0.93 (-12.914615) | - (-) |
| daoopt-20min-weak | Promedas_52 | - (-) | 1.00 (-10.784241) | - (-) |
| daoopt-20min-weak | Promedas_53 | - (-) | 0.99 (-9.257969) | - (-) |
| daoopt-20min-weak | Promedas_54 | - (-) | 0.69 (-11.703378) | - (-) |
| daoopt-20min-weak | Promedas_55 | - (-) | 0.97 (-13.225606) | - (-) |
| daoopt-20min-weak | Promedas_56 | - (-) | 1.00 (-10.844023) | - (-) |
| daoopt-20min-weak | Promedas_57 | - (-) | 0.97 (-10.588895) | - (-) |
| daoopt-20min-weak | Promedas_58 | - (-) | 1.00 (-19.946604) | - (-) |
| daoopt-20min-weak | Promedas_59 | - (-) | 0.93 (-11.640076) | - (-) |
| daoopt-20min-weak | Promedas_60 | - (-) | 1.00 (-10.036466) | - (-) |
| daoopt-20min-weak | Promedas_61 | - (-) | 1.00 (-6.882303) | - (-) |
| daoopt-20min-weak | Promedas_62 | - (-) | 1.00 (-4.665399) | - (-) |
| daoopt-20min-weak | Promedas_63 | - (-) | 0.00 (-15.926594) | - (-) |
| daoopt-20min-weak | Promedas_64 | - (-) | 0.00 (-14.999074) | - (-) |
| daoopt-20min-weak | Promedas_65 | - (-) | 1.00 (-5.156746) | - (-) |
| daoopt-20min-weak | Promedas_66 | - (-) | 1.00 (-10.392104) | - (-) |
| daoopt-20min-weak | Promedas_67 | - (-) | -1.00 (  nan) | - (-) |
| daoopt-20min-weak | Promedas_68 | - (-) | 0.94 (-20.441459) | - (-) |
| daoopt-20min-weak | Promedas_69 | - (-) | 1.00 (-11.192360) | - (-) |
| daoopt-20min-weak | Promedas_70 | - (-) | 0.00 (-8.894208) | - (-) |
| daoopt-20min-weak | Promedas_71 | - (-) | 0.88 (-7.516743) | - (-) |
| daoopt-20min-weak | ProteinFolding_11 | - (-) | 1.00 (1961.845320) | - (-) |
| daoopt-20min-weak | ProteinFolding_12 | - (-) | 1.00 (-1547.125248) | - (-) |
| daoopt-20min-weak | ProteinFolding_13 | - (-) | 1.00 (-143.321762) | - (-) |
| daoopt-20min-weak | ProteinFolding_14 | - (-) | 1.00 (-331.734776) | - (-) |
| daoopt-20min-weak | ProteinFolding_15 | - (-) | 1.00 (-51.551640) | - (-) |
| daoopt-20min-weak | ProteinFolding_16 | - (-) | 1.00 (-855.521914) | - (-) |
| daoopt-20min-weak | ProteinFolding_17 | - (-) | 0.20 (8984.225201) | - (-) |
| daoopt-20min-weak | ProteinFolding_18 | - (-) | 0.77 (16619.019078) | - (-) |
| daoopt-20min-weak | ProteinFolding_19 | - (-) | 0.00 (2350.116854) | - (-) |
| daoopt-20min-weak | ProteinFolding_20 | - (-) | 0.41 (4484.075807) | - (-) |
| daoopt-20min-weak | ProteinFolding_21 | - (-) | 0.80 (7101.018802) | - (-) |
| daoopt-20min-weak | ProteinFolding_22 | - (-) | 0.95 (10346.272253) | - (-) |
| daoopt-20min-weak | ProteinFolding_23 | - (-) | 0.00 (3436.356305) | - (-) |
| daoopt-20min-weak | ProteinFolding_24 | - (-) | 0.30 (4728.460394) | - (-) |
| daoopt-20min-weak | ProteinFolding_25 | - (-) | 0.64 (6887.604905) | - (-) |
| daoopt-20min-weak | Segmentation_11 | - (-) | 1.00 (-135.829797) | - (-) |
| daoopt-20min-weak | Segmentation_12 | - (-) | 1.00 (-22.214446) | - (-) |
| daoopt-20min-weak | Segmentation_13 | - (-) | 1.00 (-21.653378) | - (-) |
| daoopt-20min-weak | Segmentation_14 | - (-) | 1.00 (-40.099954) | - (-) |
| daoopt-20min-weak | Segmentation_15 | - (-) | 1.00 (-165.202647) | - (-) |
| daoopt-20min-weak | Segmentation_16 | - (-) | 1.00 (-41.257946) | - (-) |
| daoopt-20min-weak | Segmentation_17 | - (-) | 1.00 (-176.786122) | - (-) |
| daoopt-20min-weak | Segmentation_18 | - (-) | 1.00 (-35.902911) | - (-) |
| daoopt-20min-weak | Segmentation_19 | - (-) | 1.00 (-25.494906) | - (-) |
| daoopt-20min-weak | Segmentation_20 | - (-) | 1.00 (-113.878796) | - (-) |
| daoopt-20min-weak | wcsp_11 | - (-) | 0.46 (-3.398404) | - (-) |
| daoopt-20min-weak | wcsp_12 | - (-) | 0.00 (-2.861268) | - (-) |
| daoopt-20min-weak | wcsp_13 | - (-) | 1.00 (-0.212371) | - (-) |
| daoopt-20min-weak | wcsp_14 | - (-) | 0.43 (-16.049453) | - (-) |
| daoopt-20min-weak | wcsp_15 | - (-) | 0.04 (-172.000000) | - (-) |
| daoopt-20min-weak | wcsp_16 | - (-) | 0.60 (-21.084000) | - (-) |
| daoopt-20min-weak | wcsp_17 | - (-) | 0.00 (-60.240000) | - (-) |
| daoopt-20min-weak | wcsp_18 | - (-) | 0.50 (-16.000386) | - (-) |
| daoopt-20sec-ib15 | Grids_18 | 1.00 (5673.973975) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_19 | 1.00 (1179.125941) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_20 | 0.85 (4588.378008) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_21 | 1.00 (8495.223983) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_22 | 0.98 (2817.844201) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_23 | 1.00 (2781.641450) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_24 | 0.99 (8227.603059) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_25 | 1.00 (1167.819057) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_26 | 1.00 (1325.038005) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_27 | 1.00 (5504.384331) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_28 | 1.00 (1981.759980) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_29 | 1.00 (669.970751) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_30 | 1.00 (1309.721293) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_11 | 1.00 (-824.234024) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_12 | 1.00 (-436.669411) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_13 | 1.00 (-2999.933955) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_14 | 1.00 (-1557.513069) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_15 | 1.00 (-1177.484737) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_11 | 1.00 (4237.893984) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_12 | 1.00 (6684.994818) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_13 | 1.00 (9854.221704) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_14 | 1.00 (9020.782273) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_15 | 1.00 (12478.579551) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_16 | 0.95 (13326.139044) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_17 | 1.00 (4816.027439) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_18 | 1.00 (8849.451213) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_11 | 0.73 (-27.702224) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_12 | 0.98 (-15.909344) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_13 | 0.86 (-32.865447) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_14 | 0.77 (-22.900765) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_15 | 0.88 (-26.804624) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_16 | 0.00 (-20.899196) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_17 | 0.99 (-20.015118) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_18 | 0.96 (-25.099399) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_19 | 1.00 (-26.144218) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_20 | 0.77 (-17.395426) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_21 | 1.00 (-17.442462) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_22 | 0.98 (-16.633451) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_23 | 1.00 (-23.458485) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_24 | 1.00 (-12.542312) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_25 | 1.00 (-14.672095) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_26 | 0.00 (-19.614788) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_27 | 0.99 (-10.173299) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_28 | 1.00 (-5.976281) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_29 | 0.97 (-20.318457) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_30 | 1.00 (-10.439065) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_31 | 1.00 (-12.199562) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_32 | 1.00 (-13.875033) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_33 | 1.00 (-14.028949) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_34 | 1.00 (-17.022867) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_35 | 1.00 (-11.255544) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_36 | 1.00 (-8.179996) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_37 | 1.00 (-15.413972) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_38 | 1.00 (-12.080001) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_39 | 0.98 (-20.991679) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_40 | 1.00 (-7.288980) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_41 | 1.00 (-9.678987) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_42 | 1.00 (-12.762584) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_43 | 1.00 (-7.536269) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_44 | 1.00 (-9.265009) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_45 | 1.00 (-7.500451) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_46 | 1.00 (-12.801987) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_47 | 1.00 (-14.013809) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_48 | 1.00 (-10.778584) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_49 | 1.00 (-8.372280) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_50 | 1.00 (-8.995057) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_51 | 1.00 (-12.294454) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_52 | 1.00 (-10.784241) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_53 | 1.00 (-9.085503) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_54 | 1.00 (-10.324254) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_55 | 1.00 (-12.715439) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_56 | 1.00 (-10.844023) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_57 | 1.00 (-10.432162) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_58 | 1.00 (-19.946604) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_59 | 1.00 (-10.555197) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_60 | 1.00 (-10.036466) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_61 | 1.00 (-6.882303) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_62 | 1.00 (-4.665399) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_63 | 1.00 (-6.093362) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_64 | 1.00 (-11.469786) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_65 | 1.00 (-5.156746) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_66 | 1.00 (-10.392104) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_67 | 1.00 (-13.361078) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_68 | 1.00 (-18.940748) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_69 | 1.00 (-11.192360) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_70 | 1.00 (-4.121582) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_71 | 1.00 (-6.014154) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_11 | 1.00 (1961.845320) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_12 | 1.00 (-1547.125248) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_13 | 1.00 (-143.321762) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_14 | 1.00 (-331.734776) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_15 | 1.00 (-51.551640) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_16 | 1.00 (-855.521914) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_17 | 1.00 (16544.169748) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_18 | 1.00 (18606.266173) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_19 | 1.00 (2448.664503) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_20 | 1.00 (5577.253167) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_21 | 1.00 (7958.719664) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_22 | 1.00 (10547.218187) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_23 | 0.78 (4049.793085) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_24 | 1.00 (5868.771956) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_25 | 1.00 (8656.260558) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_11 | 1.00 (-135.829797) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_12 | 1.00 (-22.214446) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_13 | 1.00 (-21.653378) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_14 | 1.00 (-40.099954) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_15 | 1.00 (-165.202647) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_16 | 1.00 (-41.257946) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_17 | 1.00 (-176.786122) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_18 | 1.00 (-35.902911) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_19 | 1.00 (-25.494906) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_20 | 1.00 (-113.878796) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_11 | 0.73 (-3.361612) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_12 | 0.99 (-2.580324) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_13 | 1.00 (-0.212371) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_14 | 0.14 (-24.064119) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_15 | 1.00 (-76.000000) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_16 | 0.97 (-18.288000) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_17 | 0.89 (-25.456000) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_18 | 0.38 (-20.000386) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_18 | 0.84 (5528.731059) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_19 | 0.92 (1167.639742) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_20 | 0.81 (4563.199085) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_21 | 0.85 (8305.187056) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_22 | 0.86 (2763.150091) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_23 | 0.87 (2730.327596) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_24 | 0.84 (8033.286179) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_25 | 0.91 (1158.803484) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_26 | 0.85 (1295.640518) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_27 | 0.85 (5376.926423) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_28 | 0.84 (1941.580866) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_29 | 0.90 (661.607810) | - (-) | - (-) |
| daoopt-20sec-weak | Grids_30 | 0.98 (1305.589194) | - (-) | - (-) |
| daoopt-20sec-weak | ImageAlignment_11 | 1.00 (-824.234024) | - (-) | - (-) |
| daoopt-20sec-weak | ImageAlignment_12 | 1.00 (-436.669411) | - (-) | - (-) |
| daoopt-20sec-weak | ImageAlignment_13 | 1.00 (-2999.933955) | - (-) | - (-) |
| daoopt-20sec-weak | ImageAlignment_14 | 1.00 (-1557.513069) | - (-) | - (-) |
| daoopt-20sec-weak | ImageAlignment_15 | 1.00 (-1177.484737) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_11 | 0.41 (3001.270456) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_12 | 0.76 (5412.799893) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_13 | 0.91 (9440.683557) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_14 | 0.21 (6048.188077) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_15 | 0.56 (10691.610130) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_16 | 1.00 (13584.377571) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_17 | 0.55 (3647.994846) | - (-) | - (-) |
| daoopt-20sec-weak | ObjectDetection_18 | 0.92 (8491.203139) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_11 | 0.30 (-38.369912) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_12 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_13 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_14 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_15 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_16 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_17 | 0.28 (-34.716734) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_18 | 0.00 (-43.908610) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_19 | 0.52 (-49.650420) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_20 | 0.30 (-28.080133) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_21 | 0.38 (-45.730322) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_22 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_23 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_24 | 0.60 (-19.096995) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_25 | 0.59 (-22.612157) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_26 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_27 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_28 | 0.00 (-14.161851) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_29 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_30 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_31 | 0.36 (-26.904973) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_32 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_33 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_34 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_35 | 0.22 (-16.954384) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_36 | 0.77 (-12.192010) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_37 | 0.54 (-26.555954) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_38 | 0.75 (-15.947832) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_39 | 0.79 (-23.402886) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_40 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_41 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_42 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_43 | 0.52 (-13.917089) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_44 | 0.00 (-19.149819) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_45 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_46 | 0.73 (-16.069789) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_47 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_48 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_49 | 0.26 (-15.614501) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_50 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_51 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_52 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_53 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_54 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_55 | 0.96 (-13.378390) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_56 | 0.27 (-22.198789) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_57 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_58 | 0.66 (-33.098446) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_59 | 0.95 (-11.523543) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_60 | 0.91 (-11.456162) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_61 | 0.60 (-17.359098) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_62 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_63 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_64 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_65 | 0.90 (-6.475288) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_66 | 0.77 (-14.655538) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_67 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_68 | 0.94 (-20.441459) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_69 | 0.77 (-14.756405) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_70 | 0.67 (-6.815244) | - (-) | - (-) |
| daoopt-20sec-weak | Promedas_71 | -1.00 (  nan) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_11 | 0.98 (1956.193320) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_12 | 1.00 (-1547.125248) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_13 | 1.00 (-143.321762) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_14 | 1.00 (-331.734776) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_15 | 1.00 (-51.551640) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_16 | 1.00 (-855.521914) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_17 | 0.54 (12680.143262) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_18 | 0.33 (14316.463796) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_19 | 0.11 (1679.144598) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_20 | 0.72 (4396.762651) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_21 | 0.68 (7087.662636) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_22 | 0.97 (10373.860160) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_23 | 0.64 (3940.468323) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_24 | 0.91 (5566.588815) | - (-) | - (-) |
| daoopt-20sec-weak | ProteinFolding_25 | 0.75 (7587.665040) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_11 | 0.00 (-138.431612) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_12 | 1.00 (-22.214446) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_13 | 1.00 (-21.653378) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_14 | 1.00 (-40.099954) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_15 | 0.00 (-167.135262) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_16 | 1.00 (-41.257946) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_17 | 0.18 (-177.217830) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_18 | 1.00 (-35.902911) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_19 | 1.00 (-25.494906) | - (-) | - (-) |
| daoopt-20sec-weak | Segmentation_20 | 0.00 (-114.123739) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_11 | 0.53 (-3.398404) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_12 | 0.33 (-2.767682) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_13 | 0.67 (-4.141580) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_14 | 0.29 (-20.038540) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_15 | 0.00 (-188.000000) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_16 | 0.00 (-73.980000) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_17 | 0.00 (-125.552000) | - (-) | - (-) |
| daoopt-20sec-weak | wcsp_18 | 0.50 (-16.023574) | - (-) | - (-) |
| uai14-ihler-mpe | Grids_18 | 0.00 (4770.552583) | 0.00 (4770.552583) | 0.00 (4770.552583) |
| uai14-ihler-mpe | Grids_19 | 0.00 (1033.416960) | 0.00 (1033.416960) | 0.00 (1033.416960) |
| uai14-ihler-mpe | Grids_20 | 0.00 (4077.814520) | 0.00 (4130.722586) | 0.00 (4130.722586) |
| uai14-ihler-mpe | Grids_21 | 0.00 (7226.487585) | 0.00 (7226.487585) | 0.00 (7226.487585) |
| uai14-ihler-mpe | Grids_22 | 0.00 (2375.115233) | 0.00 (2376.359002) | 0.00 (2376.359002) |
| uai14-ihler-mpe | Grids_23 | 0.00 (2394.707549) | 0.00 (2412.834159) | 0.00 (2412.834159) |
| uai14-ihler-mpe | Grids_24 | 0.00 (6950.581208) | 0.00 (7049.258626) | 0.00 (7049.258626) |
| uai14-ihler-mpe | Grids_25 | 0.00 (1068.532515) | 0.00 (1068.532515) | 0.00 (1068.532515) |
| uai14-ihler-mpe | Grids_26 | 0.00 (1125.104807) | 0.00 (1125.104807) | 0.00 (1125.104807) |
| uai14-ihler-mpe | Grids_27 | 0.00 (4647.067456) | 0.00 (4727.754754) | 0.00 (4727.754754) |
| uai14-ihler-mpe | Grids_28 | 0.00 (1724.750220) | 0.00 (1724.750220) | 0.00 (1724.750220) |
| uai14-ihler-mpe | Grids_29 | 0.00 (586.551954) | 0.00 (586.551954) | 0.00 (586.551954) |
| uai14-ihler-mpe | Grids_30 | 0.00 (1138.746734) | 0.00 (1138.746734) | 0.00 (1138.746734) |
| uai14-ihler-mpe | ImageAlignment_11 | 1.00 (-824.234024) | 1.00 (-824.234024) | 1.00 (-824.234024) |
| uai14-ihler-mpe | ImageAlignment_12 | 1.00 (-436.669411) | 1.00 (-436.669411) | 1.00 (-436.669411) |
| uai14-ihler-mpe | ImageAlignment_13 | 1.00 (-2999.933955) | 1.00 (-2999.933955) | 1.00 (-2999.933955) |
| uai14-ihler-mpe | ImageAlignment_14 | 1.00 (-1557.513069) | 1.00 (-1557.513069) | 1.00 (-1557.513069) |
| uai14-ihler-mpe | ImageAlignment_15 | 1.00 (-1177.484737) | 1.00 (-1177.484737) | 1.00 (-1177.484737) |
| uai14-ihler-mpe | ObjectDetection_11 | 0.00 (2153.836931) | 0.27 (3083.786731) | 0.58 (3571.265896) |
| uai14-ihler-mpe | ObjectDetection_12 | 0.00 (1299.951380) | 0.00 (2984.002565) | 0.00 (2984.002565) |
| uai14-ihler-mpe | ObjectDetection_13 | 0.00 (5128.190783) | 0.00 (5777.295683) | 0.00 (5280.856076) |
| uai14-ihler-mpe | ObjectDetection_14 | 0.00 (5273.403379) | 0.00 (3204.421266) | 0.00 (3204.421266) |
| uai14-ihler-mpe | ObjectDetection_15 | 0.00 (8378.951637) | 0.00 (3970.818209) | 0.00 (4258.775893) |
| uai14-ihler-mpe | ObjectDetection_16 | 0.00 (8554.937219) | 0.00 (7589.867444) | 0.00 (8533.049966) |
| uai14-ihler-mpe | ObjectDetection_17 | 0.00 (2223.022314) | 0.00 (3248.448473) | 0.00 (3248.448473) |
| uai14-ihler-mpe | ObjectDetection_18 | 0.00 (4200.883831) | 0.00 (2413.395202) | 0.00 (2413.395202) |
| uai14-ihler-mpe | Promedas_11 | 0.00 (-45.859335) | 0.00 (-45.859335) | 0.00 (-45.164730) |
| uai14-ihler-mpe | Promedas_12 | 0.00 (-44.447694) | 0.00 (-40.937540) | 0.00 (-41.693458) |
| uai14-ihler-mpe | Promedas_13 | 0.00 (-67.900922) | 0.00 (-62.469415) | 0.00 (-67.480491) |
| uai14-ihler-mpe | Promedas_14 | 0.00 (-37.199730) | 0.00 (-37.199730) | 0.00 (-37.199730) |
| uai14-ihler-mpe | Promedas_15 | 0.00 (-43.262319) | 0.00 (-42.961267) | 0.00 (-42.303690) |
| uai14-ihler-mpe | Promedas_16 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_17 | 0.00 (-40.606840) | 0.00 (-26.309579) | 0.00 (-25.623769) |
| uai14-ihler-mpe | Promedas_18 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_19 | 0.00 (-74.669950) | 0.00 (-73.585503) | 0.00 (-74.688183) |
| uai14-ihler-mpe | Promedas_20 | 0.00 (-34.787190) | 0.26 (-29.953739) | 0.00 (-47.076506) |
| uai14-ihler-mpe | Promedas_21 | 0.00 (-62.943400) | 0.00 (-62.943400) | 0.00 (-62.438059) |
| uai14-ihler-mpe | Promedas_22 | 0.00 (-40.370270) | 0.00 (-39.877589) | 0.00 (-42.956749) |
| uai14-ihler-mpe | Promedas_23 | 0.00 (-58.160034) | 0.00 (-55.050234) | 0.00 (-56.609244) |
| uai14-ihler-mpe | Promedas_24 | 0.00 (-28.834112) | 0.00 (-28.834112) | 0.00 (-25.387333) |
| uai14-ihler-mpe | Promedas_25 | 0.00 (-33.945408) | 0.00 (-34.121521) | 0.00 (-34.121521) |
| uai14-ihler-mpe | Promedas_26 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_27 | 0.00 (-32.096648) | 0.00 (-30.671568) | 0.00 (-24.843855) |
| uai14-ihler-mpe | Promedas_28 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_29 | 0.00 (-39.906424) | 0.00 (-39.906424) | 0.00 (-39.941596) |
| uai14-ihler-mpe | Promedas_30 | 0.00 (-35.650073) | 0.00 (-35.826186) | 0.00 (-35.826186) |
| uai14-ihler-mpe | Promedas_31 | 0.00 (-35.276433) | 0.00 (-20.758112) | 0.00 (-20.758112) |
| uai14-ihler-mpe | Promedas_32 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_33 | 0.00 (-42.951613) | 0.00 (-38.173470) | 0.00 (-29.714407) |
| uai14-ihler-mpe | Promedas_34 | 0.00 (-35.460176) | 0.00 (-36.287246) | 0.00 (-36.031851) |
| uai14-ihler-mpe | Promedas_35 | 0.00 (-18.562661) | 0.00 (-29.789348) | 0.00 (-27.657714) |
| uai14-ihler-mpe | Promedas_36 | 0.00 (-25.369169) | 0.00 (-25.193056) | 0.00 (-29.747113) |
| uai14-ihler-mpe | Promedas_37 | 0.00 (-39.503934) | 0.00 (-40.029071) | 0.00 (-43.157190) |
| uai14-ihler-mpe | Promedas_38 | 0.00 (-27.252358) | 0.00 (-27.252358) | 0.00 (-26.817834) |
| uai14-ihler-mpe | Promedas_39 | 0.00 (-33.562758) | 0.00 (-34.067973) | 0.00 (-31.071349) |
| uai14-ihler-mpe | Promedas_40 | 0.00 (-19.885293) | 0.00 (-20.311410) | 0.00 (-19.338285) |
| uai14-ihler-mpe | Promedas_41 | 0.00 (-29.904478) | 0.00 (-19.358134) | 0.00 (-19.358134) |
| uai14-ihler-mpe | Promedas_42 | 0.00 (-37.969048) | 0.00 (-38.295570) | 0.00 (-37.524150) |
| uai14-ihler-mpe | Promedas_43 | 0.00 (-20.934609) | 0.00 (-20.934609) | 0.00 (-21.382855) |
| uai14-ihler-mpe | Promedas_44 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_45 | 0.00 (-15.446607) | 0.00 (-10.101981) | 0.00 (-10.101981) |
| uai14-ihler-mpe | Promedas_46 | 0.00 (-25.042667) | 0.00 (-26.937759) | 0.00 (-26.937759) |
| uai14-ihler-mpe | Promedas_47 | 0.00 (-36.757324) | 0.00 (-16.463511) | 0.00 (-16.463511) |
| uai14-ihler-mpe | Promedas_48 | 0.00 (-29.892581) | 0.00 (-28.494537) | 0.00 (-28.318424) |
| uai14-ihler-mpe | Promedas_49 | 0.00 (-18.130758) | 0.00 (-15.717190) | 0.00 (-15.717190) |
| uai14-ihler-mpe | Promedas_50 | 0.00 (-23.757505) | 0.00 (-23.513923) | 0.00 (-23.581392) |
| uai14-ihler-mpe | Promedas_51 | 0.00 (-21.385796) | 0.00 (-21.385796) | 0.00 (-17.591918) |
| uai14-ihler-mpe | Promedas_52 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_53 | 0.00 (-28.398710) | 0.00 (-27.097472) | 0.00 (-27.979015) |
| uai14-ihler-mpe | Promedas_54 | 0.00 (-14.767499) | 0.00 (-14.767499) | 0.00 (-14.767499) |
| uai14-ihler-mpe | Promedas_55 | 0.00 (-27.619120) | 0.00 (-30.312888) | 0.00 (-26.534137) |
| uai14-ihler-mpe | Promedas_56 | 0.00 (-26.391174) | 0.00 (-23.605471) | 0.00 (-12.724997) |
| uai14-ihler-mpe | Promedas_57 | 0.00 (-19.030466) | 0.00 (-15.452801) | 0.00 (-15.452801) |
| uai14-ihler-mpe | Promedas_58 | 0.00 (-59.040181) | 0.00 (-54.294552) | 0.00 (-59.955347) |
| uai14-ihler-mpe | Promedas_59 | 0.00 (-30.746229) | 0.00 (-26.098866) | 0.00 (-23.537591) |
| uai14-ihler-mpe | Promedas_60 | 0.00 (-25.285292) | 0.00 (-19.887352) | 0.00 (-19.076607) |
| uai14-ihler-mpe | Promedas_61 | 0.00 (-33.035853) | 0.00 (-10.838238) | 0.00 (-10.838238) |
| uai14-ihler-mpe | Promedas_62 | 0.00 (-10.852143) | 0.00 (-8.228506) | 0.00 (-6.342788) |
| uai14-ihler-mpe | Promedas_63 | 0.00 (-15.428159) | 0.05 (-15.428159) | 0.32 (-10.661529) |
| uai14-ihler-mpe | Promedas_64 | 0.00 (-27.966189) | 0.34 (-13.807262) | 0.44 (-13.459996) |
| uai14-ihler-mpe | Promedas_65 | 0.00 (-18.697488) | 0.00 (-15.010184) | 0.00 (-15.010184) |
| uai14-ihler-mpe | Promedas_66 | 0.00 (-28.858299) | 0.00 (-14.541729) | 0.00 (-14.541729) |
| uai14-ihler-mpe | Promedas_67 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mpe | Promedas_68 | 0.00 (-44.163656) | 0.00 (-44.754982) | 0.00 (-44.690961) |
| uai14-ihler-mpe | Promedas_69 | 0.00 (-26.613977) | 0.00 (-23.309174) | 0.00 (-23.309174) |
| uai14-ihler-mpe | Promedas_70 | 0.00 (-12.246395) | 0.21 (-7.909059) | 0.21 (-7.909059) |
| uai14-ihler-mpe | Promedas_71 | 0.00 (-18.671725) | 0.00 (-18.674200) | 0.00 (-8.265583) |
| uai14-ihler-mpe | ProteinFolding_11 | 0.00 (1709.389899) | 0.00 (1709.389899) | 0.00 (1709.389899) |
| uai14-ihler-mpe | ProteinFolding_12 | 1.00 (-1547.125248) | 1.00 (-1547.125248) | 1.00 (-1547.125248) |
| uai14-ihler-mpe | ProteinFolding_13 | 1.00 (-143.321762) | 1.00 (-143.321762) | 1.00 (-143.321762) |
| uai14-ihler-mpe | ProteinFolding_14 | 1.00 (-331.734776) | 1.00 (-331.734776) | 1.00 (-331.734776) |
| uai14-ihler-mpe | ProteinFolding_15 | 1.00 (-51.551640) | 1.00 (-51.551640) | 1.00 (-51.551640) |
| uai14-ihler-mpe | ProteinFolding_16 | 1.00 (-855.521914) | 1.00 (-855.521914) | 1.00 (-855.521914) |
| uai14-ihler-mpe | ProteinFolding_17 | 0.00 (8114.869548) | 0.00 (7107.890294) | 0.00 (7141.452960) |
| uai14-ihler-mpe | ProteinFolding_18 | 0.03 (12444.363985) | 0.00 (10028.154696) | 0.00 (10102.612265) |
| uai14-ihler-mpe | ProteinFolding_19 | 0.00 (1580.704476) | 0.16 (2365.741511) | 0.16 (2365.741511) |
| uai14-ihler-mpe | ProteinFolding_20 | 0.00 (1399.807379) | 0.00 (3729.873681) | 0.00 (3729.873681) |
| uai14-ihler-mpe | ProteinFolding_21 | 0.00 (5232.223727) | 0.00 (3673.992811) | 0.00 (3190.331941) |
| uai14-ihler-mpe | ProteinFolding_22 | 0.00 (5525.894610) | 0.00 (6737.076334) | 0.00 (5678.465056) |
| uai14-ihler-mpe | ProteinFolding_23 | 0.00 (3454.333748) | 0.88 (4117.936608) | 0.87 (4117.936608) |
| uai14-ihler-mpe | ProteinFolding_24 | 0.00 (2652.485663) | 0.00 (4241.252898) | 0.00 (4241.252898) |
| uai14-ihler-mpe | ProteinFolding_25 | 0.00 (4459.649565) | 0.00 (3769.168983) | 0.00 (3879.131349) |
| uai14-ihler-mpe | Segmentation_11 | 1.00 (-135.829797) | 1.00 (-135.829797) | 1.00 (-135.829797) |
| uai14-ihler-mpe | Segmentation_12 | 1.00 (-22.214446) | 1.00 (-22.214446) | 1.00 (-22.214446) |
| uai14-ihler-mpe | Segmentation_13 | 1.00 (-21.653378) | 1.00 (-21.653378) | 1.00 (-21.653378) |
| uai14-ihler-mpe | Segmentation_14 | 1.00 (-40.099954) | 1.00 (-40.099954) | 1.00 (-40.099954) |
| uai14-ihler-mpe | Segmentation_15 | 1.00 (-165.202647) | 1.00 (-165.202647) | 1.00 (-165.202647) |
| uai14-ihler-mpe | Segmentation_16 | 1.00 (-41.257946) | 1.00 (-41.257946) | 1.00 (-41.257946) |
| uai14-ihler-mpe | Segmentation_17 | 0.00 (-177.312073) | 1.00 (-176.786122) | 1.00 (-176.786122) |
| uai14-ihler-mpe | Segmentation_18 | 1.00 (-35.902911) | 1.00 (-35.902911) | 1.00 (-35.902911) |
| uai14-ihler-mpe | Segmentation_19 | 1.00 (-25.494906) | 1.00 (-25.494906) | 1.00 (-25.494906) |
| uai14-ihler-mpe | Segmentation_20 | 1.00 (-113.878796) | 1.00 (-113.878796) | 1.00 (-113.878796) |
| uai14-ihler-mpe | wcsp_11 | 0.00 (-3.496577) | 0.00 (-3.471988) | 0.00 (-3.471988) |
| uai14-ihler-mpe | wcsp_12 | 0.00 (-2.863337) | 0.65 (-2.674850) | 0.65 (-2.674850) |
| uai14-ihler-mpe | wcsp_13 | 0.00 (-12.000000) | 0.00 (-12.000000) | 0.00 (-12.000000) |
| uai14-ihler-mpe | wcsp_14 | 0.00 (-28.000000) | 0.00 (-28.000000) | 0.00 (-28.000000) |
| uai14-ihler-mpe | wcsp_15 | 0.11 (-176.000000) | 0.00 (-176.000000) | 0.04 (-168.000000) |
| uai14-ihler-mpe | wcsp_16 | 1.00 (-16.492000) | 0.00 (-27.900000) | 0.00 (-24.396000) |
| uai14-ihler-mpe | wcsp_17 | 1.00 (-13.196000) | 0.01 (-60.000000) | 0.35 (-43.436000) |
| uai14-ihler-mpe | wcsp_18 | 0.00 (-32.000000) | 0.00 (-32.000000) | 0.00 (-32.000000) |


## MMAP Task
| solver | problem | 20 sec | 1200 sec | 3600 sec |
|:--------|--------:|--------:|--------:|--------:|
| daoopt-1hr-ib35 | Grids_18 | - (-) | - (-) | 1.00 (5678.697565) |
| daoopt-1hr-ib35 | Grids_19 | - (-) | - (-) | 1.00 (1221.632914) |
| daoopt-1hr-ib35 | Grids_20 | - (-) | - (-) | 1.00 (4839.034649) |
| daoopt-1hr-ib35 | Grids_21 | - (-) | - (-) | 1.00 (8499.735835) |
| daoopt-1hr-ib35 | Grids_22 | - (-) | - (-) | 1.00 (2835.156886) |
| daoopt-1hr-ib35 | Grids_23 | - (-) | - (-) | 1.00 (2793.029489) |
| daoopt-1hr-ib35 | Grids_24 | - (-) | - (-) | 1.00 (8237.320599) |
| daoopt-1hr-ib35 | Grids_25 | - (-) | - (-) | 1.00 (1209.298030) |
| daoopt-1hr-ib35 | Grids_26 | - (-) | - (-) | 1.00 (1326.301730) |
| daoopt-1hr-ib35 | Grids_27 | - (-) | - (-) | 1.00 (5508.870617) |
| daoopt-1hr-ib35 | Grids_28 | - (-) | - (-) | 1.00 (1982.514133) |
| daoopt-1hr-ib35 | Grids_29 | - (-) | - (-) | 1.00 (673.009931) |
| daoopt-1hr-ib35 | Grids_30 | - (-) | - (-) | 1.00 (1311.489968) |
| daoopt-1hr-ib35 | ImageAlignment_11 | - (-) | - (-) | 1.00 (-824.234005) |
| daoopt-1hr-ib35 | ImageAlignment_12 | - (-) | - (-) | 1.00 (-436.669411) |
| daoopt-1hr-ib35 | ImageAlignment_13 | - (-) | - (-) | 0.10 (-2999.826395) |
| daoopt-1hr-ib35 | ImageAlignment_14 | - (-) | - (-) | 1.00 (-1557.493793) |
| daoopt-1hr-ib35 | ImageAlignment_15 | - (-) | - (-) | 1.00 (-1177.469334) |
| daoopt-1hr-ib35 | ObjectDetection_11 | - (-) | - (-) | 1.00 (4237.893988) |
| daoopt-1hr-ib35 | ObjectDetection_12 | - (-) | - (-) | 0.99 (6684.994818) |
| daoopt-1hr-ib35 | ObjectDetection_13 | - (-) | - (-) | 1.00 (9854.221704) |
| daoopt-1hr-ib35 | ObjectDetection_14 | - (-) | - (-) | 1.00 (9020.782274) |
| daoopt-1hr-ib35 | ObjectDetection_15 | - (-) | - (-) | 1.00 (12478.594616) |
| daoopt-1hr-ib35 | ObjectDetection_16 | - (-) | - (-) | 0.00 (13536.214904) |
| daoopt-1hr-ib35 | ObjectDetection_17 | - (-) | - (-) | 1.00 (4816.027443) |
| daoopt-1hr-ib35 | ObjectDetection_18 | - (-) | - (-) | 0.51 (8849.451213) |
| daoopt-1hr-ib35 | Promedas_11 | - (-) | - (-) | 1.00 (-13.360050) |
| daoopt-1hr-ib35 | Promedas_12 | - (-) | - (-) | 0.87 (-10.846450) |
| daoopt-1hr-ib35 | Promedas_13 | - (-) | - (-) | 1.00 (-20.973674) |
| daoopt-1hr-ib35 | Promedas_14 | - (-) | - (-) | 1.00 (-14.013563) |
| daoopt-1hr-ib35 | Promedas_15 | - (-) | - (-) | 1.00 (-21.178305) |
| daoopt-1hr-ib35 | Promedas_16 | - (-) | - (-) | 0.99 (-15.113236) |
| daoopt-1hr-ib35 | Promedas_17 | - (-) | - (-) | 1.00 (-16.479777) |
| daoopt-1hr-ib35 | Promedas_18 | - (-) | - (-) | 0.05 (-21.319489) |
| daoopt-1hr-ib35 | Promedas_19 | - (-) | - (-) | 1.00 (-23.074125) |
| daoopt-1hr-ib35 | Promedas_20 | - (-) | - (-) | 1.00 (-10.679914) |
| daoopt-1hr-ib35 | Promedas_21 | - (-) | - (-) | 1.00 (-14.378231) |
| daoopt-1hr-ib35 | Promedas_22 | - (-) | - (-) | 1.00 (-14.492451) |
| daoopt-1hr-ib35 | Promedas_23 | - (-) | - (-) | 1.00 (-18.482181) |
| daoopt-1hr-ib35 | Promedas_24 | - (-) | - (-) | 1.00 (-9.464359) |
| daoopt-1hr-ib35 | Promedas_25 | - (-) | - (-) | 1.00 (-11.602464) |
| daoopt-1hr-ib35 | Promedas_26 | - (-) | - (-) | 0.85 (-16.086208) |
| daoopt-1hr-ib35 | Promedas_27 | - (-) | - (-) | 1.00 (-10.007080) |
| daoopt-1hr-ib35 | Promedas_28 | - (-) | - (-) | 1.00 (-4.434689) |
| daoopt-1hr-ib35 | Promedas_29 | - (-) | - (-) | 1.00 (-13.642516) |
| daoopt-1hr-ib35 | Promedas_30 | - (-) | - (-) | 1.00 (-10.417678) |
| daoopt-1hr-ib35 | Promedas_31 | - (-) | - (-) | 1.00 (-10.663967) |
| daoopt-1hr-ib35 | Promedas_32 | - (-) | - (-) | 1.00 (-10.814157) |
| daoopt-1hr-ib35 | Promedas_33 | - (-) | - (-) | 1.00 (-12.487801) |
| daoopt-1hr-ib35 | Promedas_34 | - (-) | - (-) | 1.00 (-13.960330) |
| daoopt-1hr-ib35 | Promedas_35 | - (-) | - (-) | 1.00 (-9.715347) |
| daoopt-1hr-ib35 | Promedas_36 | - (-) | - (-) | 1.00 (-8.162267) |
| daoopt-1hr-ib35 | Promedas_37 | - (-) | - (-) | 1.00 (-10.832623) |
| daoopt-1hr-ib35 | Promedas_38 | - (-) | - (-) | 1.00 (-12.060074) |
| daoopt-1hr-ib35 | Promedas_39 | - (-) | - (-) | 1.00 (-17.602875) |
| daoopt-1hr-ib35 | Promedas_40 | - (-) | - (-) | 1.00 (-7.271882) |
| daoopt-1hr-ib35 | Promedas_41 | - (-) | - (-) | 1.00 (-8.137140) |
| daoopt-1hr-ib35 | Promedas_42 | - (-) | - (-) | 0.00 (-11.212486) |
| daoopt-1hr-ib35 | Promedas_43 | - (-) | - (-) | 1.00 (-7.518561) |
| daoopt-1hr-ib35 | Promedas_44 | - (-) | - (-) | 1.00 (-6.160980) |
| daoopt-1hr-ib35 | Promedas_45 | - (-) | - (-) | 1.00 (-5.966508) |
| daoopt-1hr-ib35 | Promedas_46 | - (-) | - (-) | 1.00 (-8.218067) |
| daoopt-1hr-ib35 | Promedas_47 | - (-) | - (-) | 1.00 (-6.381001) |
| daoopt-1hr-ib35 | Promedas_48 | - (-) | - (-) | 1.00 (-10.682423) |
| daoopt-1hr-ib35 | Promedas_49 | - (-) | - (-) | 1.00 (-6.839290) |
| daoopt-1hr-ib35 | Promedas_50 | - (-) | - (-) | 1.00 (-7.436286) |
| daoopt-1hr-ib35 | Promedas_51 | - (-) | - (-) | 1.00 (-7.713349) |
| daoopt-1hr-ib35 | Promedas_52 | - (-) | - (-) | 1.00 (-10.655784) |
| daoopt-1hr-ib35 | Promedas_53 | - (-) | - (-) | 1.00 (-9.070205) |
| daoopt-1hr-ib35 | Promedas_54 | - (-) | - (-) | 1.00 (-8.763556) |
| daoopt-1hr-ib35 | Promedas_55 | - (-) | - (-) | 1.00 (-11.181493) |
| daoopt-1hr-ib35 | Promedas_56 | - (-) | - (-) | 1.00 (-7.787217) |
| daoopt-1hr-ib35 | Promedas_57 | - (-) | - (-) | 1.00 (-10.295119) |
| daoopt-1hr-ib35 | Promedas_58 | - (-) | - (-) | 1.00 (-15.349332) |
| daoopt-1hr-ib35 | Promedas_59 | - (-) | - (-) | 1.00 (-10.541072) |
| daoopt-1hr-ib35 | Promedas_60 | - (-) | - (-) | 1.00 (-10.017980) |
| daoopt-1hr-ib35 | Promedas_61 | - (-) | - (-) | 1.00 (-5.351968) |
| daoopt-1hr-ib35 | Promedas_62 | - (-) | - (-) | 1.00 (-4.653217) |
| daoopt-1hr-ib35 | Promedas_63 | - (-) | - (-) | 1.00 (-4.561249) |
| daoopt-1hr-ib35 | Promedas_64 | - (-) | - (-) | 1.00 (-9.938811) |
| daoopt-1hr-ib35 | Promedas_65 | - (-) | - (-) | 1.00 (-5.141839) |
| daoopt-1hr-ib35 | Promedas_66 | - (-) | - (-) | 1.00 (-10.363194) |
| daoopt-1hr-ib35 | Promedas_67 | - (-) | - (-) | 0.88 (-11.818985) |
| daoopt-1hr-ib35 | Promedas_68 | - (-) | - (-) | 1.00 (-18.819387) |
| daoopt-1hr-ib35 | Promedas_69 | - (-) | - (-) | 1.00 (-9.655585) |
| daoopt-1hr-ib35 | Promedas_70 | - (-) | - (-) | 1.00 (-4.106543) |
| daoopt-1hr-ib35 | Promedas_71 | - (-) | - (-) | 1.00 (-6.000856) |
| daoopt-1hr-ib35 | ProteinFolding_11 | - (-) | - (-) | 1.00 (1962.312184) |
| daoopt-1hr-ib35 | ProteinFolding_12 | - (-) | - (-) | 1.00 (-1547.035521) |
| daoopt-1hr-ib35 | ProteinFolding_13 | - (-) | - (-) | 1.00 (-143.321762) |
| daoopt-1hr-ib35 | ProteinFolding_14 | - (-) | - (-) | 1.00 (-331.734776) |
| daoopt-1hr-ib35 | ProteinFolding_15 | - (-) | - (-) | 1.00 (-51.551640) |
| daoopt-1hr-ib35 | ProteinFolding_16 | - (-) | - (-) | 1.00 (-855.521914) |
| daoopt-1hr-ib35 | ProteinFolding_17 | - (-) | - (-) | 1.00 (16544.169748) |
| daoopt-1hr-ib35 | ProteinFolding_18 | - (-) | - (-) | 1.00 (18606.266186) |
| daoopt-1hr-ib35 | ProteinFolding_19 | - (-) | - (-) | 1.00 (2448.665183) |
| daoopt-1hr-ib35 | ProteinFolding_20 | - (-) | - (-) | 1.00 (5577.253215) |
| daoopt-1hr-ib35 | ProteinFolding_21 | - (-) | - (-) | 1.00 (7958.719664) |
| daoopt-1hr-ib35 | ProteinFolding_22 | - (-) | - (-) | 1.00 (10547.218187) |
| daoopt-1hr-ib35 | ProteinFolding_23 | - (-) | - (-) | 0.00 (4215.114528) |
| daoopt-1hr-ib35 | ProteinFolding_24 | - (-) | - (-) | 0.46 (5868.771957) |
| daoopt-1hr-ib35 | ProteinFolding_25 | - (-) | - (-) | 1.00 (8656.260558) |
| daoopt-1hr-ib35 | Segmentation_11 | - (-) | - (-) | 1.00 (-132.269023) |
| daoopt-1hr-ib35 | Segmentation_12 | - (-) | - (-) | 1.00 (-21.924367) |
| daoopt-1hr-ib35 | Segmentation_13 | - (-) | - (-) | 1.00 (-21.370458) |
| daoopt-1hr-ib35 | Segmentation_14 | - (-) | - (-) | 1.00 (-39.278931) |
| daoopt-1hr-ib35 | Segmentation_15 | - (-) | - (-) | 1.00 (-163.791869) |
| daoopt-1hr-ib35 | Segmentation_16 | - (-) | - (-) | 1.00 (-40.444530) |
| daoopt-1hr-ib35 | Segmentation_17 | - (-) | - (-) | 1.00 (-174.322694) |
| daoopt-1hr-ib35 | Segmentation_18 | - (-) | - (-) | 1.00 (-33.984056) |
| daoopt-1hr-ib35 | Segmentation_19 | - (-) | - (-) | 1.00 (-24.075016) |
| daoopt-1hr-ib35 | Segmentation_20 | - (-) | - (-) | 1.00 (-112.006849) |
| daoopt-1hr-ib35 | wcsp_11 | - (-) | - (-) | 0.99 (6.764898) |
| daoopt-1hr-ib35 | wcsp_12 | - (-) | - (-) | 0.95 (13.347903) |
| daoopt-1hr-ib35 | wcsp_13 | - (-) | - (-) | 1.00 (0.682731) |
| daoopt-1hr-ib35 | wcsp_14 | - (-) | - (-) | 1.00 (1.523865) |
| daoopt-1hr-ib35 | wcsp_15 | - (-) | - (-) | 1.00 (-74.619072) |
| daoopt-1hr-ib35 | wcsp_16 | - (-) | - (-) | 0.99 (23.233682) |
| daoopt-1hr-ib35 | wcsp_17 | - (-) | - (-) | 0.00 (33.310152) |
| daoopt-1hr-ib35 | wcsp_18 | - (-) | - (-) | 1.00 (0.213908) |
| daoopt-20min-ib25 | Grids_18 | - (-) | 1.00 (5678.697565) | - (-) |
| daoopt-20min-ib25 | Grids_19 | - (-) | 1.00 (1221.632914) | - (-) |
| daoopt-20min-ib25 | Grids_20 | - (-) | 0.98 (4838.379300) | - (-) |
| daoopt-20min-ib25 | Grids_21 | - (-) | 1.00 (8499.735835) | - (-) |
| daoopt-20min-ib25 | Grids_22 | - (-) | 1.00 (2835.156886) | - (-) |
| daoopt-20min-ib25 | Grids_23 | - (-) | 1.00 (2793.029489) | - (-) |
| daoopt-20min-ib25 | Grids_24 | - (-) | 1.00 (8237.320599) | - (-) |
| daoopt-20min-ib25 | Grids_25 | - (-) | 1.00 (1209.298030) | - (-) |
| daoopt-20min-ib25 | Grids_26 | - (-) | 1.00 (1326.301730) | - (-) |
| daoopt-20min-ib25 | Grids_27 | - (-) | 1.00 (5508.870617) | - (-) |
| daoopt-20min-ib25 | Grids_28 | - (-) | 1.00 (1982.514133) | - (-) |
| daoopt-20min-ib25 | Grids_29 | - (-) | 1.00 (673.009931) | - (-) |
| daoopt-20min-ib25 | Grids_30 | - (-) | 1.00 (1311.489968) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_11 | - (-) | 1.00 (-824.234005) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_12 | - (-) | 1.00 (-436.669411) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_13 | - (-) | 0.00 (-2999.826395) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_14 | - (-) | 1.00 (-1557.493793) | - (-) |
| daoopt-20min-ib25 | ImageAlignment_15 | - (-) | 1.00 (-1177.469334) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_11 | - (-) | 1.00 (4237.893988) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_12 | - (-) | 0.99 (6684.994818) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_13 | - (-) | 1.00 (9854.221704) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_14 | - (-) | 1.00 (9020.782274) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_15 | - (-) | 1.00 (12478.594616) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_16 | - (-) | 0.00 (13536.214904) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_17 | - (-) | 1.00 (4816.027443) | - (-) |
| daoopt-20min-ib25 | ObjectDetection_18 | - (-) | 0.54 (8849.451213) | - (-) |
| daoopt-20min-ib25 | Promedas_11 | - (-) | 0.98 (-13.824143) | - (-) |
| daoopt-20min-ib25 | Promedas_12 | - (-) | 1.00 (-7.649550) | - (-) |
| daoopt-20min-ib25 | Promedas_13 | - (-) | 1.00 (-20.973674) | - (-) |
| daoopt-20min-ib25 | Promedas_14 | - (-) | 1.00 (-14.013563) | - (-) |
| daoopt-20min-ib25 | Promedas_15 | - (-) | 1.00 (-21.178305) | - (-) |
| daoopt-20min-ib25 | Promedas_16 | - (-) | 0.99 (-15.113236) | - (-) |
| daoopt-20min-ib25 | Promedas_17 | - (-) | 1.00 (-16.479777) | - (-) |
| daoopt-20min-ib25 | Promedas_18 | - (-) | 0.05 (-21.319489) | - (-) |
| daoopt-20min-ib25 | Promedas_19 | - (-) | 1.00 (-23.074125) | - (-) |
| daoopt-20min-ib25 | Promedas_20 | - (-) | 1.00 (-10.679914) | - (-) |
| daoopt-20min-ib25 | Promedas_21 | - (-) | 1.00 (-14.378231) | - (-) |
| daoopt-20min-ib25 | Promedas_22 | - (-) | 1.00 (-14.492451) | - (-) |
| daoopt-20min-ib25 | Promedas_23 | - (-) | 1.00 (-18.482181) | - (-) |
| daoopt-20min-ib25 | Promedas_24 | - (-) | 1.00 (-9.464359) | - (-) |
| daoopt-20min-ib25 | Promedas_25 | - (-) | 1.00 (-11.602464) | - (-) |
| daoopt-20min-ib25 | Promedas_26 | - (-) | 0.85 (-16.086208) | - (-) |
| daoopt-20min-ib25 | Promedas_27 | - (-) | 1.00 (-10.007080) | - (-) |
| daoopt-20min-ib25 | Promedas_28 | - (-) | 1.00 (-4.434689) | - (-) |
| daoopt-20min-ib25 | Promedas_29 | - (-) | 1.00 (-13.642516) | - (-) |
| daoopt-20min-ib25 | Promedas_30 | - (-) | 1.00 (-10.417678) | - (-) |
| daoopt-20min-ib25 | Promedas_31 | - (-) | 1.00 (-10.663967) | - (-) |
| daoopt-20min-ib25 | Promedas_32 | - (-) | 0.89 (-13.871537) | - (-) |
| daoopt-20min-ib25 | Promedas_33 | - (-) | 1.00 (-12.487801) | - (-) |
| daoopt-20min-ib25 | Promedas_34 | - (-) | 1.00 (-13.960330) | - (-) |
| daoopt-20min-ib25 | Promedas_35 | - (-) | 1.00 (-9.715347) | - (-) |
| daoopt-20min-ib25 | Promedas_36 | - (-) | 1.00 (-8.162267) | - (-) |
| daoopt-20min-ib25 | Promedas_37 | - (-) | 1.00 (-10.832623) | - (-) |
| daoopt-20min-ib25 | Promedas_38 | - (-) | 1.00 (-12.060074) | - (-) |
| daoopt-20min-ib25 | Promedas_39 | - (-) | 1.00 (-17.602875) | - (-) |
| daoopt-20min-ib25 | Promedas_40 | - (-) | 1.00 (-7.271882) | - (-) |
| daoopt-20min-ib25 | Promedas_41 | - (-) | 1.00 (-8.137140) | - (-) |
| daoopt-20min-ib25 | Promedas_42 | - (-) | 0.00 (-11.212486) | - (-) |
| daoopt-20min-ib25 | Promedas_43 | - (-) | 1.00 (-7.518561) | - (-) |
| daoopt-20min-ib25 | Promedas_44 | - (-) | 1.00 (-6.160980) | - (-) |
| daoopt-20min-ib25 | Promedas_45 | - (-) | 1.00 (-5.966508) | - (-) |
| daoopt-20min-ib25 | Promedas_46 | - (-) | 1.00 (-8.218067) | - (-) |
| daoopt-20min-ib25 | Promedas_47 | - (-) | 1.00 (-6.381001) | - (-) |
| daoopt-20min-ib25 | Promedas_48 | - (-) | 1.00 (-10.682423) | - (-) |
| daoopt-20min-ib25 | Promedas_49 | - (-) | 1.00 (-6.839290) | - (-) |
| daoopt-20min-ib25 | Promedas_50 | - (-) | 1.00 (-7.436286) | - (-) |
| daoopt-20min-ib25 | Promedas_51 | - (-) | 1.00 (-7.713349) | - (-) |
| daoopt-20min-ib25 | Promedas_52 | - (-) | 1.00 (-10.655784) | - (-) |
| daoopt-20min-ib25 | Promedas_53 | - (-) | 1.00 (-9.070205) | - (-) |
| daoopt-20min-ib25 | Promedas_54 | - (-) | 1.00 (-8.763556) | - (-) |
| daoopt-20min-ib25 | Promedas_55 | - (-) | 1.00 (-11.181493) | - (-) |
| daoopt-20min-ib25 | Promedas_56 | - (-) | 1.00 (-7.787217) | - (-) |
| daoopt-20min-ib25 | Promedas_57 | - (-) | 1.00 (-10.295119) | - (-) |
| daoopt-20min-ib25 | Promedas_58 | - (-) | 1.00 (-15.349332) | - (-) |
| daoopt-20min-ib25 | Promedas_59 | - (-) | 1.00 (-10.541072) | - (-) |
| daoopt-20min-ib25 | Promedas_60 | - (-) | 1.00 (-10.017980) | - (-) |
| daoopt-20min-ib25 | Promedas_61 | - (-) | 1.00 (-5.351968) | - (-) |
| daoopt-20min-ib25 | Promedas_62 | - (-) | 1.00 (-4.653217) | - (-) |
| daoopt-20min-ib25 | Promedas_63 | - (-) | 1.00 (-4.561249) | - (-) |
| daoopt-20min-ib25 | Promedas_64 | - (-) | 1.00 (-9.938811) | - (-) |
| daoopt-20min-ib25 | Promedas_65 | - (-) | 1.00 (-5.141839) | - (-) |
| daoopt-20min-ib25 | Promedas_66 | - (-) | 1.00 (-10.363194) | - (-) |
| daoopt-20min-ib25 | Promedas_67 | - (-) | 0.88 (-11.818985) | - (-) |
| daoopt-20min-ib25 | Promedas_68 | - (-) | 1.00 (-18.819387) | - (-) |
| daoopt-20min-ib25 | Promedas_69 | - (-) | 1.00 (-9.655585) | - (-) |
| daoopt-20min-ib25 | Promedas_70 | - (-) | 1.00 (-4.106543) | - (-) |
| daoopt-20min-ib25 | Promedas_71 | - (-) | 1.00 (-6.000856) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_11 | - (-) | 1.00 (1962.312184) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_12 | - (-) | 1.00 (-1547.035521) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_13 | - (-) | 1.00 (-143.321762) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_14 | - (-) | 1.00 (-331.734776) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_15 | - (-) | 1.00 (-51.551640) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_16 | - (-) | 1.00 (-855.521914) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_17 | - (-) | 1.00 (16544.169748) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_18 | - (-) | 1.00 (18606.266186) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_19 | - (-) | 1.00 (2448.665183) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_20 | - (-) | 1.00 (5577.253215) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_21 | - (-) | 1.00 (7958.719664) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_22 | - (-) | 1.00 (10547.218187) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_23 | - (-) | 0.85 (4210.150125) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_24 | - (-) | 0.46 (5868.771957) | - (-) |
| daoopt-20min-ib25 | ProteinFolding_25 | - (-) | 1.00 (8656.260558) | - (-) |
| daoopt-20min-ib25 | Segmentation_11 | - (-) | 1.00 (-132.269023) | - (-) |
| daoopt-20min-ib25 | Segmentation_12 | - (-) | 1.00 (-21.924367) | - (-) |
| daoopt-20min-ib25 | Segmentation_13 | - (-) | 1.00 (-21.370458) | - (-) |
| daoopt-20min-ib25 | Segmentation_14 | - (-) | 1.00 (-39.278931) | - (-) |
| daoopt-20min-ib25 | Segmentation_15 | - (-) | 1.00 (-163.791869) | - (-) |
| daoopt-20min-ib25 | Segmentation_16 | - (-) | 1.00 (-40.444530) | - (-) |
| daoopt-20min-ib25 | Segmentation_17 | - (-) | 1.00 (-174.322694) | - (-) |
| daoopt-20min-ib25 | Segmentation_18 | - (-) | 1.00 (-33.984056) | - (-) |
| daoopt-20min-ib25 | Segmentation_19 | - (-) | 1.00 (-24.075016) | - (-) |
| daoopt-20min-ib25 | Segmentation_20 | - (-) | 1.00 (-112.006849) | - (-) |
| daoopt-20min-ib25 | wcsp_11 | - (-) | 0.99 (5.583539) | - (-) |
| daoopt-20min-ib25 | wcsp_12 | - (-) | 0.95 (13.390244) | - (-) |
| daoopt-20min-ib25 | wcsp_13 | - (-) | 1.00 (0.682731) | - (-) |
| daoopt-20min-ib25 | wcsp_14 | - (-) | 0.98 (1.067379) | - (-) |
| daoopt-20min-ib25 | wcsp_15 | - (-) | 1.00 (-74.619072) | - (-) |
| daoopt-20min-ib25 | wcsp_16 | - (-) | 1.00 (23.406038) | - (-) |
| daoopt-20min-ib25 | wcsp_17 | - (-) | 1.00 (33.431466) | - (-) |
| daoopt-20min-ib25 | wcsp_18 | - (-) | 1.00 (0.213908) | - (-) |
| daoopt-20sec-ib15 | Grids_18 | 1.00 (5678.096015) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_19 | 0.81 (1221.262472) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_20 | 0.47 (4813.424045) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_21 | 1.00 (8498.307750) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_22 | 0.97 (2833.344271) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_23 | 1.00 (2793.029489) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_24 | 0.97 (8231.124396) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_25 | 1.00 (1209.298030) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_26 | 1.00 (1326.301730) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_27 | 1.00 (5508.870617) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_28 | 1.00 (1982.514133) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_29 | 1.00 (673.009931) | - (-) | - (-) |
| daoopt-20sec-ib15 | Grids_30 | 1.00 (1311.489968) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_11 | 1.00 (-824.234005) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_12 | 1.00 (-436.669411) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_13 | 0.82 (-2999.826395) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_14 | 1.00 (-1557.493793) | - (-) | - (-) |
| daoopt-20sec-ib15 | ImageAlignment_15 | 1.00 (-1177.469334) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_11 | 1.00 (4237.893988) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_12 | 0.99 (6684.994818) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_13 | 1.00 (9854.221704) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_14 | 1.00 (9020.782274) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_15 | 1.00 (12478.594616) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_16 | 0.00 (13326.147592) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_17 | 1.00 (4816.027443) | - (-) | - (-) |
| daoopt-20sec-ib15 | ObjectDetection_18 | 0.00 (8849.451213) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_11 | 0.00 (-19.967223) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_12 | 0.00 (-11.302391) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_13 | 0.00 (-25.229122) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_14 | 0.00 (-19.837051) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_15 | 0.00 (-23.441173) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_16 | 1.00 (-14.774520) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_17 | 0.00 (-16.704783) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_18 | 0.00 (-22.013065) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_19 | 1.00 (-23.074125) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_20 | 0.00 (-15.849873) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_21 | 1.00 (-14.378231) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_22 | 0.00 (-15.016419) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_23 | 1.00 (-18.482181) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_24 | 1.00 (-9.464359) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_25 | 1.00 (-11.602464) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_26 | 1.00 (-11.887696) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_27 | 0.00 (-10.154574) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_28 | 1.00 (-4.434689) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_29 | 0.00 (-17.243662) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_30 | 1.00 (-10.417678) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_31 | 1.00 (-10.663967) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_32 | 1.00 (-10.814157) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_33 | 1.00 (-12.487801) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_34 | 1.00 (-13.960330) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_35 | 1.00 (-9.715347) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_36 | 1.00 (-8.162267) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_37 | 1.00 (-10.832623) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_38 | 1.00 (-12.060074) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_39 | 0.00 (-17.904470) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_40 | 1.00 (-7.271882) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_41 | 1.00 (-8.137140) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_42 | 0.00 (-11.212486) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_43 | 1.00 (-7.518561) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_44 | 1.00 (-6.160980) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_45 | 1.00 (-5.966508) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_46 | 1.00 (-8.218067) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_47 | 1.00 (-6.381001) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_48 | 1.00 (-10.682423) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_49 | 1.00 (-6.839290) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_50 | 1.00 (-7.436286) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_51 | 1.00 (-7.713349) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_52 | 1.00 (-10.655784) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_53 | 1.00 (-9.070205) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_54 | 1.00 (-8.763556) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_55 | 1.00 (-11.181493) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_56 | 1.00 (-7.787217) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_57 | 1.00 (-10.295119) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_58 | 1.00 (-15.349332) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_59 | 1.00 (-10.541072) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_60 | 1.00 (-10.017980) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_61 | 1.00 (-5.351968) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_62 | 1.00 (-4.653217) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_63 | 1.00 (-4.561249) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_64 | 1.00 (-9.938811) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_65 | 1.00 (-5.141839) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_66 | 1.00 (-10.363194) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_67 | 0.00 (-11.818985) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_68 | 1.00 (-18.819387) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_69 | 1.00 (-9.655585) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_70 | 1.00 (-4.106543) | - (-) | - (-) |
| daoopt-20sec-ib15 | Promedas_71 | 1.00 (-6.000856) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_11 | 1.00 (1962.312184) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_12 | 1.00 (-1547.035521) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_13 | 1.00 (-143.321762) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_14 | 1.00 (-331.734776) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_15 | 1.00 (-51.551640) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_16 | 1.00 (-855.521914) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_17 | 1.00 (16544.169748) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_18 | 1.00 (18606.266186) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_19 | 1.00 (2448.665183) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_20 | 1.00 (5577.253215) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_21 | 1.00 (7958.719664) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_22 | 1.00 (10547.218187) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_23 | 0.00 (4049.957920) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_24 | 0.60 (5868.771957) | - (-) | - (-) |
| daoopt-20sec-ib15 | ProteinFolding_25 | 1.00 (8656.260558) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_11 | 1.00 (-132.269023) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_12 | 1.00 (-21.924367) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_13 | 1.00 (-21.370458) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_14 | 1.00 (-39.278931) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_15 | 1.00 (-163.791869) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_16 | 1.00 (-40.444530) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_17 | 1.00 (-174.322694) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_18 | 1.00 (-33.984056) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_19 | 1.00 (-24.075016) | - (-) | - (-) |
| daoopt-20sec-ib15 | Segmentation_20 | 1.00 (-112.006849) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_11 | 0.00 (5.742455) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_12 | 0.00 (13.179315) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_13 | 1.00 (0.682731) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_14 | 0.00 (-21.961143) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_15 | 1.00 (-75.095933) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_16 | 0.97 (22.782394) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_17 | 0.80 (20.623201) | - (-) | - (-) |
| daoopt-20sec-ib15 | wcsp_18 | 0.80 (-14.201833) | - (-) | - (-) |
| lbp-ihler-mmap | Grids_18 | -1.00 (  nan) | 0.54 (5587.975338) | 0.45 (5587.975338) |
| lbp-ihler-mmap | Grids_19 | -1.00 (  nan) | 0.00 (1212.808886) | 0.00 (1212.808886) |
| lbp-ihler-mmap | Grids_20 | -1.00 (  nan) | 0.00 (4804.896239) | 0.00 (4804.896239) |
| lbp-ihler-mmap | Grids_21 | -1.00 (  nan) | 0.00 (8322.925678) | 0.40 (8322.925678) |
| lbp-ihler-mmap | Grids_22 | -1.00 (  nan) | 0.00 (2763.435628) | 0.00 (2763.435628) |
| lbp-ihler-mmap | Grids_23 | -1.00 (  nan) | 0.00 (2739.232161) | 0.00 (2739.232161) |
| lbp-ihler-mmap | Grids_24 | -1.00 (  nan) | 0.34 (8106.534473) | 0.44 (8106.534473) |
| lbp-ihler-mmap | Grids_25 | -1.00 (  nan) | 0.31 (1204.599070) | 0.00 (1204.599070) |
| lbp-ihler-mmap | Grids_26 | -1.00 (  nan) | 0.20 (1300.445822) | 0.38 (1300.445822) |
| lbp-ihler-mmap | Grids_27 | -1.00 (  nan) | 0.00 (5383.058541) | 0.29 (5383.058541) |
| lbp-ihler-mmap | Grids_28 | -1.00 (  nan) | 0.00 (1924.662896) | 0.00 (1924.662896) |
| lbp-ihler-mmap | Grids_29 | -1.00 (  nan) | 0.07 (662.624459) | 0.00 (662.624459) |
| lbp-ihler-mmap | Grids_30 | -1.00 (  nan) | 0.90 (1309.118379) | 0.92 (1309.118379) |
| lbp-ihler-mmap | ImageAlignment_11 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mmap | ImageAlignment_12 | -1.00 (  nan) | 1.00 (-436.669411) | 1.00 (-436.669411) |
| lbp-ihler-mmap | ImageAlignment_13 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mmap | ImageAlignment_14 | -1.00 (  nan) | -1.00 (  nan) | 1.00 (-1557.493793) |
| lbp-ihler-mmap | ImageAlignment_15 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mmap | ObjectDetection_11 | -1.00 (  nan) | 0.34 (3537.240465) | 0.34 (3537.240465) |
| lbp-ihler-mmap | ObjectDetection_12 | -1.00 (  nan) | 1.00 (6694.675344) | 1.00 (6694.675344) |
| lbp-ihler-mmap | ObjectDetection_13 | -1.00 (  nan) | 0.00 (8826.505758) | 0.00 (8826.505758) |
| lbp-ihler-mmap | ObjectDetection_14 | -1.00 (  nan) | 0.00 (8341.855648) | 0.00 (8341.855648) |
| lbp-ihler-mmap | ObjectDetection_15 | -1.00 (  nan) | 0.00 (11543.730821) | 0.00 (11543.730821) |
| lbp-ihler-mmap | ObjectDetection_16 | -1.00 (  nan) | 0.02 (13547.593812) | 0.02 (13547.593812) |
| lbp-ihler-mmap | ObjectDetection_17 | -1.00 (  nan) | 0.00 (3794.885387) | 0.00 (3794.885387) |
| lbp-ihler-mmap | ObjectDetection_18 | -1.00 (  nan) | 1.00 (9017.105088) | 1.00 (9017.105088) |
| lbp-ihler-mmap | Promedas_11 | -1.00 (  nan) | 0.00 (-39.907246) | 0.00 (-39.907246) |
| lbp-ihler-mmap | Promedas_12 | -1.00 (  nan) | 0.00 (-32.434919) | 0.00 (-32.434919) |
| lbp-ihler-mmap | Promedas_13 | -1.00 (  nan) | 0.00 (-61.163029) | 0.00 (-61.163029) |
| lbp-ihler-mmap | Promedas_14 | -1.00 (  nan) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_15 | -1.00 (  nan) | 0.00 (-52.043972) | 0.00 (-52.043972) |
| lbp-ihler-mmap | Promedas_16 | -1.00 (  nan) | 0.00 (-41.673860) | 0.00 (-41.673860) |
| lbp-ihler-mmap | Promedas_17 | -1.00 (  nan) | 0.00 (-32.469040) | 0.00 (-32.469040) |
| lbp-ihler-mmap | Promedas_18 | -1.00 (  nan) | 0.00 (-44.692090) | 0.00 (-44.692090) |
| lbp-ihler-mmap | Promedas_19 | -1.00 (  nan) | 0.00 (-58.771413) | 0.00 (-58.771413) |
| lbp-ihler-mmap | Promedas_20 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_21 | -1.00 (  nan) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_22 | -1.00 (  nan) | 0.00 (-39.876154) | 0.00 (-39.876154) |
| lbp-ihler-mmap | Promedas_23 | -1.00 (  nan) | 0.00 (-43.411642) | 0.00 (-43.411642) |
| lbp-ihler-mmap | Promedas_24 | -1.00 (  nan) | 0.00 (-18.981118) | 0.00 (-18.981118) |
| lbp-ihler-mmap | Promedas_25 | -1.00 (  nan) | 0.00 (-29.102407) | 0.00 (-29.102407) |
| lbp-ihler-mmap | Promedas_26 | -1.00 (  nan) | 0.00 (-39.434979) | 0.00 (-39.434979) |
| lbp-ihler-mmap | Promedas_27 | -1.00 (  nan) | 0.00 (-26.161445) | 0.00 (-26.161445) |
| lbp-ihler-mmap | Promedas_28 | -1.00 (  nan) | 0.00 (-12.171562) | 0.00 (-12.171562) |
| lbp-ihler-mmap | Promedas_29 | -1.00 (  nan) | 0.00 (-28.499439) | 0.00 (-28.499439) |
| lbp-ihler-mmap | Promedas_30 | -1.00 (  nan) | 0.00 (-32.049505) | 0.00 (-32.049505) |
| lbp-ihler-mmap | Promedas_31 | -1.00 (  nan) | 0.00 (-29.126358) | 0.00 (-29.126358) |
| lbp-ihler-mmap | Promedas_32 | -1.00 (  nan) | 0.00 (-38.202173) | 0.00 (-38.202173) |
| lbp-ihler-mmap | Promedas_33 | -1.00 (  nan) | 0.00 (-26.660457) | 0.00 (-26.660457) |
| lbp-ihler-mmap | Promedas_34 | -1.00 (  nan) | 0.00 (-30.426368) | 0.00 (-30.426368) |
| lbp-ihler-mmap | Promedas_35 | -1.00 (  nan) | 0.00 (-24.749306) | 0.00 (-24.749306) |
| lbp-ihler-mmap | Promedas_36 | -1.00 (  nan) | 0.00 (-24.782347) | 0.00 (-24.782347) |
| lbp-ihler-mmap | Promedas_37 | -1.00 (  nan) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_38 | -1.00 (  nan) | 0.00 (-20.966840) | 0.00 (-20.966840) |
| lbp-ihler-mmap | Promedas_39 | -1.00 (  nan) | 0.00 (-33.266733) | 0.00 (-33.266733) |
| lbp-ihler-mmap | Promedas_40 | -1.00 (  nan) | 0.00 (-18.333485) | 0.00 (-18.333485) |
| lbp-ihler-mmap | Promedas_41 | -1.00 (  nan) | 0.00 (-23.554030) | 0.00 (-23.554030) |
| lbp-ihler-mmap | Promedas_42 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_43 | -1.00 (  nan) | 0.00 (-17.559924) | 0.00 (-17.559924) |
| lbp-ihler-mmap | Promedas_44 | -1.00 (  nan) | 0.00 (-16.292326) | 0.00 (-16.292326) |
| lbp-ihler-mmap | Promedas_45 | -1.00 (  nan) | 0.00 (-17.901387) | 0.00 (-17.901387) |
| lbp-ihler-mmap | Promedas_46 | -1.00 (  nan) | 0.00 (-24.147514) | 0.00 (-24.147514) |
| lbp-ihler-mmap | Promedas_47 | -1.00 (  nan) | 0.00 (-21.320742) | 0.00 (-21.320742) |
| lbp-ihler-mmap | Promedas_48 | -1.00 (  nan) | 0.00 (-23.319616) | 0.00 (-23.319616) |
| lbp-ihler-mmap | Promedas_49 | -1.00 (  nan) | 0.00 (-15.932015) | 0.00 (-15.932015) |
| lbp-ihler-mmap | Promedas_50 | -1.00 (  nan) | 0.00 (-20.311262) | 0.00 (-20.311262) |
| lbp-ihler-mmap | Promedas_51 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_52 | -1.00 (  nan) | 0.00 (-18.689748) | 0.95 (-18.689748) |
| lbp-ihler-mmap | Promedas_53 | -1.00 (  nan) | 0.00 (-13.223952) | 0.00 (-13.223952) |
| lbp-ihler-mmap | Promedas_54 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_55 | -1.00 (  nan) | 0.00 (-21.782118) | 0.00 (-21.782118) |
| lbp-ihler-mmap | Promedas_56 | -1.00 (  nan) | 0.00 (-19.600428) | 0.00 (-19.600428) |
| lbp-ihler-mmap | Promedas_57 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | Promedas_58 | -1.00 (  nan) | 0.00 (-31.303710) | 0.00 (-31.303710) |
| lbp-ihler-mmap | Promedas_59 | -1.00 (  nan) | 0.00 (-17.031503) | 0.00 (-17.031503) |
| lbp-ihler-mmap | Promedas_60 | -1.00 (  nan) | 0.00 (-16.797206) | 0.00 (-16.797206) |
| lbp-ihler-mmap | Promedas_61 | -1.00 (  nan) | 0.00 (-18.894793) | 0.00 (-18.894793) |
| lbp-ihler-mmap | Promedas_62 | -1.00 (  nan) | 0.00 (-22.058409) | 0.00 (-22.058409) |
| lbp-ihler-mmap | Promedas_63 | -1.00 (  nan) | 0.00 (-17.513972) | 0.00 (-17.513972) |
| lbp-ihler-mmap | Promedas_64 | -1.00 (  nan) | 0.00 (-24.292181) | 0.00 (-24.292181) |
| lbp-ihler-mmap | Promedas_65 | -1.00 (  nan) | 0.00 (-10.090911) | 0.00 (-10.090911) |
| lbp-ihler-mmap | Promedas_66 | -1.00 (  nan) | 0.00 (-26.660189) | 0.00 (-26.660189) |
| lbp-ihler-mmap | Promedas_67 | -1.00 (  nan) | 0.00 (-20.792767) | 0.00 (-20.792767) |
| lbp-ihler-mmap | Promedas_68 | -1.00 (  nan) | 0.00 (-29.472772) | 0.00 (-29.472772) |
| lbp-ihler-mmap | Promedas_69 | 0.00 (-20.326362) | 0.00 (-20.326362) | 0.00 (-20.326362) |
| lbp-ihler-mmap | Promedas_70 | 0.00 (-8.273126) | 0.00 (-8.273126) | 0.00 (-8.273126) |
| lbp-ihler-mmap | Promedas_71 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| lbp-ihler-mmap | ProteinFolding_11 | -1.00 (  nan) | 0.77 (1839.413425) | 0.76 (1839.413425) |
| lbp-ihler-mmap | ProteinFolding_12 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (-1555.528623) |
| lbp-ihler-mmap | ProteinFolding_13 | -1.00 (  nan) | -1.00 (  nan) | 1.00 (-143.321762) |
| lbp-ihler-mmap | ProteinFolding_14 | -1.00 (  nan) | 1.00 (-331.734776) | 1.00 (-331.734776) |
| lbp-ihler-mmap | ProteinFolding_15 | -1.00 (  nan) | 1.00 (-51.551640) | 0.00 (-4506.345917) |
| lbp-ihler-mmap | ProteinFolding_16 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (-11925.739157) |
| lbp-ihler-mmap | ProteinFolding_17 | -1.00 (  nan) | 0.00 (9043.884037) | 0.00 (9043.884037) |
| lbp-ihler-mmap | ProteinFolding_18 | -1.00 (  nan) | 0.00 (8158.379759) | 0.00 (8158.379759) |
| lbp-ihler-mmap | ProteinFolding_19 | -1.00 (  nan) | 0.49 (1865.564979) | 0.49 (1865.564979) |
| lbp-ihler-mmap | ProteinFolding_20 | -1.00 (  nan) | 0.35 (4680.306043) | 0.35 (4680.306043) |
| lbp-ihler-mmap | ProteinFolding_21 | -1.00 (  nan) | 0.56 (7402.598288) | 0.00 (7402.598288) |
| lbp-ihler-mmap | ProteinFolding_22 | -1.00 (  nan) | 0.39 (10531.284365) | 1.00 (10531.284365) |
| lbp-ihler-mmap | ProteinFolding_23 | -1.00 (  nan) | 1.00 (4230.192111) | 1.00 (4230.192111) |
| lbp-ihler-mmap | ProteinFolding_24 | -1.00 (  nan) | 1.00 (5900.367999) | 1.00 (5900.367999) |
| lbp-ihler-mmap | ProteinFolding_25 | -1.00 (  nan) | 1.00 (8656.260558) | 1.00 (8656.260558) |
| lbp-ihler-mmap | Segmentation_11 | -1.00 (  nan) | 0.08 (-133.273521) | 0.08 (-133.273521) |
| lbp-ihler-mmap | Segmentation_12 | -1.00 (  nan) | 0.00 (-30.138669) | 0.00 (-30.138669) |
| lbp-ihler-mmap | Segmentation_13 | -1.00 (  nan) | 1.00 (-21.370458) | 1.00 (-21.370458) |
| lbp-ihler-mmap | Segmentation_14 | -1.00 (  nan) | 0.00 (-40.167339) | 0.00 (-40.167339) |
| lbp-ihler-mmap | Segmentation_15 | -1.00 (  nan) | 0.06 (-168.529002) | 0.06 (-168.529002) |
| lbp-ihler-mmap | Segmentation_16 | -1.00 (  nan) | 1.00 (-40.444530) | 1.00 (-40.444530) |
| lbp-ihler-mmap | Segmentation_17 | -1.00 (  nan) | 0.28 (-175.304059) | 0.37 (-175.304059) |
| lbp-ihler-mmap | Segmentation_18 | -1.00 (  nan) | 0.00 (-35.862337) | 0.00 (-35.862337) |
| lbp-ihler-mmap | Segmentation_19 | -1.00 (  nan) | 0.00 (-25.403010) | 0.00 (-25.403010) |
| lbp-ihler-mmap | Segmentation_20 | -1.00 (  nan) | 0.75 (-112.368088) | 1.00 (-112.368088) |
| lbp-ihler-mmap | wcsp_11 | -1.00 (  nan) | 0.00 (-1206.607463) | 0.00 (-1206.607463) |
| lbp-ihler-mmap | wcsp_12 | -1.00 (  nan) | 0.00 (-227.060582) | 0.00 (-227.060582) |
| lbp-ihler-mmap | wcsp_13 | -1.00 (  nan) | 0.85 (-2.464254) | 0.78 (-2.464254) |
| lbp-ihler-mmap | wcsp_14 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (-402.446334) |
| lbp-ihler-mmap | wcsp_15 | -1.00 (  nan) | 0.00 (-1503.079072) | 0.00 (-1503.079072) |
| lbp-ihler-mmap | wcsp_16 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mmap | wcsp_17 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| lbp-ihler-mmap | wcsp_18 | -1.00 (  nan) | -1.00 (  nan) | 0.00 (-15.978071) |
| uai14-ihler-mmap | Grids_18 | 0.00 (5538.279462) | 0.00 (5481.730742) | 0.00 (5513.942234) |
| uai14-ihler-mmap | Grids_19 | 0.00 (1219.644598) | 0.34 (1215.818866) | -1.00 (  nan) |
| uai14-ihler-mmap | Grids_20 | 0.00 (4790.546052) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | Grids_21 | 0.00 (8185.388711) | -1.00 (  nan) | 0.00 (8204.607908) |
| uai14-ihler-mmap | Grids_22 | 0.00 (2777.785975) | 0.51 (2799.859535) | 0.11 (2771.319948) |
| uai14-ihler-mmap | Grids_23 | 0.00 (2750.784484) | 0.33 (2757.190085) | 0.27 (2753.517701) |
| uai14-ihler-mmap | Grids_24 | 0.00 (8021.241608) | 0.00 (8038.081207) | 0.00 (8004.970134) |
| uai14-ihler-mmap | Grids_25 | 0.00 (1204.242888) | 0.00 (1202.512181) | 0.99 (1209.268061) |
| uai14-ihler-mmap | Grids_26 | 0.00 (1279.053124) | 0.00 (1294.129540) | 0.00 (1284.488045) |
| uai14-ihler-mmap | Grids_27 | 0.00 (5378.168323) | 0.10 (5395.837669) | 0.00 (5331.241565) |
| uai14-ihler-mmap | Grids_28 | 0.00 (1926.972403) | 0.31 (1942.644399) | 0.39 (1947.432295) |
| uai14-ihler-mmap | Grids_29 | 0.00 (659.445657) | 0.00 (661.816275) | 0.82 (671.173636) |
| uai14-ihler-mmap | Grids_30 | 0.00 (1304.888257) | 0.00 (1287.057497) | 0.00 (1281.840665) |
| uai14-ihler-mmap | ImageAlignment_11 | 1.00 (-824.234005) | 1.00 (-824.234005) | -1.00 (  nan) |
| uai14-ihler-mmap | ImageAlignment_12 | 1.00 (-436.669411) | 1.00 (-436.669411) | 0.00 (-4065.730987) |
| uai14-ihler-mmap | ImageAlignment_13 | 0.00 (-3004.395560) | 1.00 (-2998.853760) | 0.00 (-2999.933955) |
| uai14-ihler-mmap | ImageAlignment_14 | 1.00 (-1557.493793) | 1.00 (-1557.493793) | 1.00 (-1557.493793) |
| uai14-ihler-mmap | ImageAlignment_15 | 1.00 (-1177.469334) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | ObjectDetection_11 | 0.00 (3383.173587) | 0.00 (3176.142154) | 0.00 (3176.142154) |
| uai14-ihler-mmap | ObjectDetection_12 | 0.00 (5342.855471) | 0.00 (5503.105728) | 0.00 (5503.105728) |
| uai14-ihler-mmap | ObjectDetection_13 | 0.00 (8569.110112) | 0.06 (8883.109816) | -1.00 (  nan) |
| uai14-ihler-mmap | ObjectDetection_14 | 0.00 (8638.242094) | 0.33 (8562.922848) | 0.33 (8562.922848) |
| uai14-ihler-mmap | ObjectDetection_15 | 0.00 (11916.599233) | 0.49 (12004.064106) | -1.00 ( -inf) |
| uai14-ihler-mmap | ObjectDetection_16 | 0.83 (13900.526538) | 1.00 (14021.532955) | -1.00 (  nan) |
| uai14-ihler-mmap | ObjectDetection_17 | 0.00 (3992.786004) | 0.71 (4518.212029) | 0.71 (4518.212029) |
| uai14-ihler-mmap | ObjectDetection_18 | 0.39 (8914.203124) | 0.00 (8650.938542) | 0.00 (8673.111418) |
| uai14-ihler-mmap | Promedas_11 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_12 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_13 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_14 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_15 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_16 | 0.00 (-15.248533) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | Promedas_17 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_18 | -1.00 ( -inf) | -1.00 ( -inf) | 1.00 (394.616676) |
| uai14-ihler-mmap | Promedas_19 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_20 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_21 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_22 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_23 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_24 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_25 | -1.00 ( -inf) | 0.45 (-21.292960) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_26 | 0.00 (-13.740220) | 0.93 (-13.740220) | 0.93 (-13.740220) |
| uai14-ihler-mmap | Promedas_27 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_28 | 0.00 (-4.604382) | 0.98 (-4.604382) | -1.00 (  nan) |
| uai14-ihler-mmap | Promedas_29 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_30 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_31 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_32 | 0.00 (-12.218119) | 0.95 (-12.218119) | 0.95 (-12.218119) |
| uai14-ihler-mmap | Promedas_33 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_34 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_35 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_36 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_37 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_38 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_39 | -1.00 ( -inf) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | Promedas_40 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_41 | 0.00 (-17.288701) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_42 | -1.00 ( -inf) | -1.00 ( -inf) | 1.00 (-10.910887) |
| uai14-ihler-mmap | Promedas_43 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_44 | 0.00 (-7.612956) | 0.86 (-7.612956) | 0.86 (-7.612956) |
| uai14-ihler-mmap | Promedas_45 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_46 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_47 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_48 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_49 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_50 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_51 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_52 | 0.00 (-12.953431) | 0.71 (-12.953431) | 0.00 (-168.000000) |
| uai14-ihler-mmap | Promedas_53 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_54 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_55 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_56 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_57 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_58 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_59 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_60 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_61 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_62 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_63 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_64 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_65 | -1.00 ( -inf) | 0.01 (-10.038214) | 0.01 (-10.038214) |
| uai14-ihler-mmap | Promedas_66 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | Promedas_67 | 1.00 (-10.650942) | 1.00 (-10.650942) | 1.00 (-10.650942) |
| uai14-ihler-mmap | Promedas_68 | 1.00 (-18.819387) | 1.00 (-18.819387) | 1.00 (-18.819387) |
| uai14-ihler-mmap | Promedas_69 | -1.00 ( -inf) | 0.19 (-18.345889) | 0.19 (-18.345889) |
| uai14-ihler-mmap | Promedas_70 | -1.00 ( -inf) | 0.75 (-5.139961) | 0.75 (-5.139961) |
| uai14-ihler-mmap | Promedas_71 | -1.00 ( -inf) | -1.00 ( -inf) | -1.00 ( -inf) |
| uai14-ihler-mmap | ProteinFolding_11 | 0.00 (1260.937569) | 0.00 (1423.325732) | 0.00 (1451.993074) |
| uai14-ihler-mmap | ProteinFolding_12 | 0.00 (-1549.086071) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | ProteinFolding_13 | 1.00 (-143.321762) | 1.00 (-143.321762) | 1.00 (-143.321762) |
| uai14-ihler-mmap | ProteinFolding_14 | 1.00 (-331.734776) | 1.00 (-331.734776) | 1.00 (-331.734776) |
| uai14-ihler-mmap | ProteinFolding_15 | 1.00 (-51.551640) | 1.00 (-51.551640) | 1.00 (-51.551640) |
| uai14-ihler-mmap | ProteinFolding_16 | 1.00 (-855.521914) | 1.00 (-855.521914) | 1.00 (-855.521914) |
| uai14-ihler-mmap | ProteinFolding_17 | 0.00 (12517.251997) | 0.62 (13693.622075) | 0.62 (13697.201265) |
| uai14-ihler-mmap | ProteinFolding_18 | 0.00 (12289.209209) | 0.54 (13772.491084) | 0.54 (13772.491084) |
| uai14-ihler-mmap | ProteinFolding_19 | 0.00 (1540.366288) | 0.00 (1298.739804) | 0.00 (1298.739804) |
| uai14-ihler-mmap | ProteinFolding_20 | 0.00 (4301.603353) | 0.00 (4187.503070) | 0.00 (4204.275659) |
| uai14-ihler-mmap | ProteinFolding_21 | 0.00 (4209.722487) | 0.00 (6687.131143) | -1.00 (  nan) |
| uai14-ihler-mmap | ProteinFolding_22 | 0.00 (9753.150441) | 0.00 (10521.213892) | 0.00 (5723.783636) |
| uai14-ihler-mmap | ProteinFolding_23 | 0.82 (4197.537553) | 0.00 (4099.412028) | -1.00 ( -inf) |
| uai14-ihler-mmap | ProteinFolding_24 | 0.00 (5821.078747) | 0.00 (5841.748294) | 0.00 (5841.748294) |
| uai14-ihler-mmap | ProteinFolding_25 | 0.00 (8607.182602) | 1.00 (8656.260558) | 1.00 (8656.260558) |
| uai14-ihler-mmap | Segmentation_11 | 0.00 (-135.618405) | 0.00 (-133.359641) | 0.00 (-133.359641) |
| uai14-ihler-mmap | Segmentation_12 | 1.00 (-21.924367) | 1.00 (-21.924367) | 1.00 (-21.924367) |
| uai14-ihler-mmap | Segmentation_13 | 1.00 (-21.370458) | 1.00 (-21.370458) | 1.00 (-21.370458) |
| uai14-ihler-mmap | Segmentation_14 | 0.00 (-41.070251) | 0.36 (-39.846326) | 0.36 (-39.846326) |
| uai14-ihler-mmap | Segmentation_15 | 0.00 (-169.183076) | 0.00 (-168.837968) | 0.00 (-168.837968) |
| uai14-ihler-mmap | Segmentation_16 | 0.00 (-40.799852) | 0.00 (-40.799852) | 0.00 (-40.799852) |
| uai14-ihler-mmap | Segmentation_17 | 0.00 (-175.939579) | 0.00 (-175.679841) | 0.00 (-175.874072) |
| uai14-ihler-mmap | Segmentation_18 | 0.00 (-38.083549) | 1.00 (-33.984056) | 1.00 (-33.984056) |
| uai14-ihler-mmap | Segmentation_19 | 1.00 (-24.075016) | 1.00 (-24.075016) | 1.00 (-24.075016) |
| uai14-ihler-mmap | Segmentation_20 | 0.00 (-116.721260) | 0.00 (-113.453250) | 0.00 (-620.974418) |
| uai14-ihler-mmap | wcsp_11 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | wcsp_12 | -1.00 (  nan) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | wcsp_13 | 0.00 (-91.148587) | 0.00 (-20.864587) | 0.00 (-13.315616) |
| uai14-ihler-mmap | wcsp_14 | -1.00 (  nan) | 0.00 (-21.887984) | 0.94 (-21.286055) |
| uai14-ihler-mmap | wcsp_15 | 0.00 (-409.301984) | 0.92 (-194.493482) | 0.92 (-193.788958) |
| uai14-ihler-mmap | wcsp_16 | 0.00 (-0.689955) | 0.00 (-0.845938) | 0.00 (1.493282) |
| uai14-ihler-mmap | wcsp_17 | 0.00 (-30.361099) | -1.00 (  nan) | -1.00 (  nan) |
| uai14-ihler-mmap | wcsp_18 | 0.00 (-73.384806) | 0.00 (-15.500621) | -1.00 (  nan) |


