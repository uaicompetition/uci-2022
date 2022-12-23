---
title: "toulbar2-ipr-mpe"
date: 2022-12-23
permalink: /results/ongoing-leader-board/solver-scores/toulbar2-ipr-mpe-scores
---


### Description

Toulbar2-ipr is inspired by an energy landscape-flattering approach coming from physics.  The procedure is an iterative approach based on VNS with an increasing precision followed by VACINT approach with full precision.  Each iteration uses a time contract and the best solution previously found.  The initial solution is provided by a VNS local search with low precision. During the first half time, the upper bound solution from the previous precision is the starting point of the next VNS search, performed with a larger duration and increased precision. Starting from the best solution known so far, the remaining half-time is dedicated to the optimality proof using the VACINT approach at full precision and enforcing virtual pairwise consistency during search on a binary encoding of the problem. Incop local search solver followed by a partition crossover combined with an iterative local search are performed to find good initial upper bound solutions. [Toulbar2](https://github.com/toulbar2/toulbar2)

### Authors

David Allouche, Simon de Givry, George Katsirelos, Samir Loudni, Pierre Montalbano, Abdelkader Ouali, Thomas Schiex,  David Simoncini, and Fulya Trösser


The results below are organized as follows:
- each table displays the solver's normalized score for individual problem instances (and, for PR, MPE, and MMAP, the associated log10 likelihood value) for the task under different time limits
- table values are normalized scores for each evaluated problem as outlined in [Evaluation Criteria](https://uaicompetition.github.io/uci-2022/results/evaluation-criteria/)


# MPE

## overall

|                        Problem                         |      20sec      |     1200sec     |     3600sec     |
| ------------------------------------------------------ | --------------- | --------------- | --------------- |
| 1CKK                                                   | 0.0 (nan)       | 100.0 (5520.9)  | 100.0 (5520.9)  |
| 1CM1                                                   | 0.0 (nan)       | 100.0 (5414.6)  | 100.0 (5414.6)  |
| 1SY9                                                   | 0.0 (nan)       | 100.0 (3985.1)  | 100.0 (3985.1)  |
| 2BBN                                                   | 0.0 (nan)       | 100.0 (5328.6)  | 100.0 (5328.6)  |
| 2BCX                                                   | 0.0 (nan)       | 100.0 (6002.2)  | 100.0 (6002.2)  |
| BN-d-10000-4-2                                         | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| BN-d-200-5-10                                          | 95.3 (-46.9)    | 100.0 (-46.5)   | 100.0 (-46.5)   |
| BN-d-20000-4-2                                         | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| BN-d-250-5-10                                          | 0.0 (nan)       | 100.0 (-56.6)   | 100.0 (-56.6)   |
| BN-d-500-5-10                                          | 0.0 (nan)       | 99.7 (-117.1)   | 99.7 (-117.1)   |
| BN-nd-10000-4-2                                        | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| BN-nd-200-5-10                                         | 0.0 (nan)       | 100.0 (-54.5)   | 100.0 (-54.5)   |
| BN-nd-20000-4-2                                        | 0.0 (nan)       | 0.0 (nan)       | 0.0 (nan)       |
| BN-nd-250-5-10                                         | 0.0 (nan)       | 91.7 (-65.8)    | 91.7 (-65.8)    |
| BN-nd-500-5-10                                         | 0.0 (nan)       | 100.0 (-134.9)  | 100.0 (-134.9)  |
| Maxsat_aes_64_1_keyfind_1                              | 61.5 (1845.2)   | 99.5 (1869.3)   | 99.5 (1869.3)   |
| Maxsat_gss-25-s100                                     | 0.0 (nan)       | 0.2 (63026.1)   | 0.2 (63026.1)   |
| Maxsat_mod2c-rand3bip-sat-240-3.shuffled-as.sat05-2520 | 79.0 (1626.9)   | 96.6 (1637.4)   | 100.0 (1639.4)  |
| Maxsat_mod2c-rand3bip-sat-250-3.shuffled-as.sat05-2535 | 85.0 (1684.2)   | 98.6 (1692.1)   | 100.0 (1692.9)  |
| Maxsat_mod4block_2vars_10gates_u2_autoenc              | 0.0 (nan)       | 99.0 (81310.6)  | 100.0 (81315.1) |
| Promedas_60                                            | 100.0 (-10.0)   | 100.0 (-10.0)   | 100.0 (-10.0)   |
| Promedas_61                                            | 100.0 (-6.9)    | 100.0 (-6.9)    | 100.0 (-6.9)    |
| Promedas_62                                            | 100.0 (-4.7)    | 100.0 (-4.7)    | 100.0 (-4.7)    |
| Promedas_63                                            | 100.0 (-6.1)    | 100.0 (-6.1)    | 100.0 (-6.1)    |
| Promedas_64                                            | 100.0 (-11.5)   | 100.0 (-11.5)   | 100.0 (-11.5)   |
| Promedas_65                                            | 100.0 (-5.2)    | 100.0 (-5.2)    | 100.0 (-5.2)    |
| Promedas_66                                            | 100.0 (-10.4)   | 100.0 (-10.4)   | 100.0 (-10.4)   |
| Promedas_67                                            | 100.0 (-13.4)   | 100.0 (-13.4)   | 100.0 (-13.4)   |
| Promedas_68                                            | 100.0 (-18.9)   | 100.0 (-18.9)   | 100.0 (-18.9)   |
| Promedas_69                                            | 100.0 (-11.2)   | 100.0 (-11.2)   | 100.0 (-11.2)   |
| driverlog04ac.wcsp                                     | 100.0 (-0.2)    | 100.0 (-0.2)    | 100.0 (-0.2)    |
| driverlog05ac.wcsp                                     | 88.0 (-12.0)    | 100.0 (-0.1)    | 100.0 (-0.1)    |
| driverlog08ac.wcsp                                     | 88.9 (-12.1)    | 100.0 (-0.1)    | 100.0 (-0.1)    |
| grid20x20.f10                                          | 100.0 (1309.7)  | 100.0 (1309.7)  | 100.0 (1309.7)  |
| grid20x20.f10.wrap                                     | 100.0 (1325.0)  | 100.0 (1325.0)  | 100.0 (1325.0)  |
| grid20x20.f15                                          | 100.0 (1961.8)  | 100.0 (1961.8)  | 100.0 (1961.8)  |
| grid20x20.f15.wrap                                     | 100.0 (1981.8)  | 100.0 (1981.8)  | 100.0 (1981.8)  |
| grid20x20.f5.wrap                                      | 100.0 (670.0)   | 100.0 (670.0)   | 100.0 (670.0)   |
| grid40x40.f10                                          | 97.7 (5460.0)   | 99.1 (5487.6)   | 100.0 (5504.4)  |
| grid40x40.f10.wrap                                     | 81.4 (5246.8)   | 100.0 (5674.4)  | 100.0 (5674.4)  |
| grid40x40.f15                                          | 96.5 (8130.5)   | 98.3 (8183.4)   | 100.0 (8234.3)  |
| grid40x40.f15.wrap                                     | 82.6 (7883.7)   | 98.6 (8448.1)   | 100.0 (8496.7)  |
| grid40x40.f2                                           | 100.0 (1167.8)  | 100.0 (1167.8)  | 100.0 (1167.8)  |
| grid40x40.f2.wrap                                      | 93.4 (1156.6)   | 100.0 (1179.2)  | 100.0 (1179.2)  |
| grid40x40.f5                                           | 99.2 (2773.8)   | 100.0 (2781.6)  | 100.0 (2781.6)  |
| grid40x40.f5.wrap                                      | 79.8 (2618.7)   | 100.0 (2825.5)  | 100.0 (2825.5)  |
| grid80x80.f10                                          | 0.0 (nan)       | 98.2 (21778.5)  | 98.6 (21809.1)  |
| grid80x80.f10.wrap                                     | 0.0 (nan)       | 98.4 (21887.2)  | 98.7 (21912.2)  |
| grid80x80.f15                                          | 0.0 (nan)       | 98.0 (32555.5)  | 98.5 (32618.0)  |
| grid80x80.f15.wrap                                     | 0.0 (nan)       | 97.6 (32904.5)  | 98.3 (33000.5)  |
| grid80x80.f2                                           | 0.0 (nan)       | 100.0 (4677.7)  | 100.0 (4677.7)  |
| grid80x80.f2.wrap                                      | 0.0 (nan)       | 100.0 (4735.7)  | 100.0 (4735.7)  |
| grid80x80.f5                                           | 0.0 (nan)       | 97.9 (11077.5)  | 98.2 (11091.0)  |
| grid80x80.f5.wrap                                      | 0.0 (nan)       | 98.2 (11048.9)  | 99.0 (11078.4)  |
| pdb1jmx                                                | 100.0 (-501.4)  | 100.0 (-501.4)  | 100.0 (-501.4)  |
| pdb1kgn                                                | 100.0 (-748.7)  | 100.0 (-748.7)  | 100.0 (-748.7)  |
| pdb1kwh                                                | 100.0 (-305.5)  | 100.0 (-305.5)  | 100.0 (-305.5)  |
| pdb1m3y                                                | 100.0 (-1054.2) | 100.0 (-1054.2) | 100.0 (-1054.2) |
| pdb1qks                                                | 100.0 (-657.0)  | 100.0 (-657.0)  | 100.0 (-657.0)  |
| pedigree1                                              | 100.0 (-45.6)   | 100.0 (-45.6)   | 100.0 (-45.6)   |
| pedigree13                                             | 100.0 (-73.4)   | 100.0 (-73.4)   | 100.0 (-73.4)   |
| pedigree18                                             | 100.0 (-125.3)  | 100.0 (-125.3)  | 100.0 (-125.3)  |
| pedigree19                                             | 99.4 (-97.6)    | 100.0 (-97.1)   | 100.0 (-97.1)   |
| pedigree20                                             | 100.0 (-53.8)   | 100.0 (-53.8)   | 100.0 (-53.8)   |
| pedigree23                                             | 100.0 (-62.4)   | 100.0 (-62.4)   | 100.0 (-62.4)   |
| pedigree25                                             | 100.0 (-160.8)  | 100.0 (-160.8)  | 100.0 (-160.8)  |
| pedigree30                                             | 100.0 (-137.0)  | 100.0 (-137.0)  | 100.0 (-137.0)  |
| pedigree31                                             | 100.0 (-130.5)  | 100.0 (-130.5)  | 100.0 (-130.5)  |
| pedigree33                                             | 100.0 (-74.9)   | 100.0 (-74.9)   | 100.0 (-74.9)   |
| pedigree34                                             | 100.0 (-111.1)  | 100.0 (-111.1)  | 100.0 (-111.1)  |
| pedigree37                                             | 100.0 (-144.9)  | 100.0 (-144.9)  | 100.0 (-144.9)  |
| pedigree38                                             | 100.0 (-87.3)   | 100.0 (-87.3)   | 100.0 (-87.3)   |
| pedigree39                                             | 100.0 (-155.6)  | 100.0 (-155.6)  | 100.0 (-155.6)  |
| pedigree40                                             | 100.0 (-130.3)  | 100.0 (-130.2)  | 100.0 (-130.2)  |
| pedigree41                                             | 100.0 (-120.7)  | 100.0 (-120.7)  | 100.0 (-120.7)  |
| pedigree42                                             | 100.0 (-81.8)   | 100.0 (-81.8)   | 100.0 (-81.8)   |
| pedigree44                                             | 100.0 (-97.0)   | 100.0 (-97.0)   | 100.0 (-97.0)   |
| pedigree50                                             | 100.0 (-61.7)   | 100.0 (-61.7)   | 100.0 (-61.7)   |
| pedigree51                                             | 100.0 (-109.6)  | 100.0 (-109.6)  | 100.0 (-109.6)  |
| pedigree7                                              | 100.0 (-113.9)  | 100.0 (-113.9)  | 100.0 (-113.9)  |
| pedigree9                                              | 100.0 (-122.9)  | 100.0 (-122.9)  | 100.0 (-122.9)  |
| rovers02ac.wcsp                                        | 100.0 (-0.2)    | 100.0 (-0.2)    | 100.0 (-0.2)    |
| rus_100_200_1_1                                        | 0.0 (nan)       | 100.0 (2683.9)  | 100.0 (2683.9)  |
| rus_100_200_2_1                                        | 0.0 (nan)       | 96.7 (2639.4)   | 96.7 (2639.4)   |
| rus_100_200_3_1                                        | 0.0 (nan)       | 85.8 (2539.4)   | 85.8 (2539.4)   |
| rus_100_200_3_3                                        | 0.0 (nan)       | 75.9 (2449.6)   | 75.9 (2449.6)   |
| rus_100_200_4_3                                        | 0.0 (nan)       | 79.2 (2479.5)   | 79.2 (2479.5)   |
| rus_100_200_5_3                                        | 0.0 (nan)       | 89.5 (2573.3)   | 89.5 (2573.3)   |
| rus_100_200_6_1                                        | 0.0 (nan)       | 56.9 (2276.7)   | 56.9 (2276.7)   |
| rus_50_100_4_1                                         | 39.6 (1535.9)   | 39.6 (1535.9)   | 39.6 (1535.9)   |
| rus_50_100_4_3                                         | 55.8 (1615.8)   | 55.8 (1615.8)   | 55.8 (1615.8)   |
| rus_50_100_6_1                                         | 0.0 (1338.1)    | 0.0 (1338.1)    | 0.0 (1338.1)    |
| rus_50_100_6_2                                         | 64.1 (1656.5)   | 64.1 (1656.5)   | 64.1 (1656.5)   |
| rus_50_100_7_1                                         | 33.1 (1504.1)   | 33.1 (1504.1)   | 33.1 (1504.1)   |
| rus_50_100_7_2                                         | 34.2 (1509.9)   | 34.2 (1509.9)   | 34.2 (1509.9)   |
| rus_50_100_8_1                                         | 21.3 (1446.2)   | 21.3 (1446.2)   | 21.3 (1446.2)   |
| rus_50_100_9_3                                         | 55.5 (1614.3)   | 55.5 (1614.3)   | 55.5 (1614.3)   |
| satellite01ac.wcsp                                     | 100.0 (-0.1)    | 100.0 (-0.1)    | 100.0 (-0.1)    |
| satellite02ac.wcsp                                     | 100.0 (-0.0)    | 100.0 (-0.0)    | 100.0 (-0.0)    |
| scen06.wcsp                                            | 99.9 (-13.6)    | 100.0 (-13.6)   | 100.0 (-13.6)   |
| scen07.wcsp                                            | 94.3 (-5.6)     | 100.0 (-1.4)    | 100.0 (-1.4)    |
| zenotravel02ac.wcsp                                    | 100.0 (-0.1)    | 100.0 (-0.1)    | 100.0 (-0.1)    |
| zenotravel04ac.wcsp                                    | 100.0 (-0.1)    | 100.0 (-0.1)    | 100.0 (-0.1)    |

