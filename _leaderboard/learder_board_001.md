---
title: "Sep 7th. Mini Evaluation of Submitted Solvers"
---

Each table shows the sum of normalized scores from all problems.
* +1 is the maximum possible score if the solution was exact or best known value
* 0 is the lowest score for the worst solution
* -1 if a solver couldn't generate a solution within time limit


## PR Task

| time | lbp-ihler-pr | uai14-ihler-pr|
|------|--------------|---------------|
| 20 sec | -119.000 | 59.901|
| 20 min | -2.000 | 129.739|
| 1 hr | -2.000 | 129.514|


## MAR Task

| time | lbp-ihler-mar | uai14-ihler-mar|
|------|---------------|----------------|
| 20 sec | -124.68691 | 35.55407|
| 20 min | -4.00000 | 129.90830|
| 1 hr | -1.00000 | 129.97855|


## MPE Task

| time | dallouche | daoopt-1hr-ib35 | daoopt-1hr-weak | daoopt-20min-ib25 | daoopt-20min-weak | daoopt-20sec-ib15 | daoopt-20sec-weak | uai14-ihler-mpe|
|------|-----------|-----------------|-----------------|-------------------|-------------------|-------------------|-------------------|----------------|
| 20 sec | 84.0479547199078 | - | - | - | - | 114.51530743500814 | 27.05534913637 | 13.141232959462354|
| 20 min | 87.3741956794668 | - |- | 118.6553378210136 | 54.43140082376853 | - | - | 14.817527070362386|
| 1 hr | 89.44697327088785 | 119.98262860302961 | 57.67113028787544|-|-|-|-|15.61187557275482|


## MMAP Task

| time | daoopt-1hr-ib35 | daoopt-20min-ib25 | daoopt-20sec-ib15 | lbp-ihler-mmap | uai14-ihler-mmap|
|------|-----------------|-------------------|-------------------|----------------|-----------------|
| 20 sec|-|-|98.2112985778558|-118|-39.96896818798335|
| 20 min|-|114.39109015864231|-|-2.683779663964|-29.563955897567553|
| 1 hr|112.64616310269994|-|-|6.070824054320708|-39.314566484996654|
