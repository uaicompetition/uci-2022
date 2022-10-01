---
title: "File Formats"
permalink: /file-formats/test-format/
---

## Test File Format (for MLC task only)
When testing solvers, solvers will be passed a [model file](../model-format.md) corresponding to the network model currently being evaluated 
as well as a test file (that has the same name as the original network file but with an added **.test** suffix, 
for instance, a model file _problem.uai_ will have associated test file _problem.uai.test_).  The test file contains a series of evidence assignments 
for which solvers are to make predictions with respect to.  Here we describe this test file format.
.

The test file format is identical to the [data file](../model-format.md) format
if the data lines were to omit query assignments and associated costs.


Namely, the test file format has:
* A four line preamble:
    * the first line is a single integer specifying the total number of variables
    * the second line begins with the number of observed (ie. evidence) variables followed by the indexes of the observed variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
    * the third line begins with the number of query variables (or labels) followed by the indexes of the query variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
    * the fourth line begins with the number of hidden variables followed by the indexes of the hidden variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
* A test section:
    * the first line of the test section is a single integer, _T_, indicating the number of test points
    * the next _T_ lines will specify the test points. Each line will contain an assignment _e_ to the observed variables (space delimited). 

For example, given a Markov network having _10_ variables, let the indices of the evidence (observed), query, and hidden variables be (_5,6,8_), (_1,4,7_), and (_0,2,3,9_) respectively. Assume we have the following _2_ test points:

* The first test point is an assignment of values _(2,1,0)_ to the evidence variables
* The second data point is an assignment of values _(1,0,3)_ to the evidence variables

the test file will contain the following:

```
10
3 5 6 8
3 1 4 7
4 0 2 3 9

2
5 2 6 1 8 0
5 1 6 0 8 3
```
