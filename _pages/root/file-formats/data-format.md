---
title: "File Formats"
permalink: /file-formats/data-format/
---

## Data Format (for MLC task only)
Data is specified in a separate file. This file has the same name as the original network file but with an added **.data** suffix. 
For instance, _problem.uai_ will have training data in _problem.uai.data_ file.

The evidence file consists of the following:
* A four line preamble:
    * the first line is a single integer specifying the total number of variables
    * the second line begins with the number of observed (ie. evidence) variables followed by the indexes of the observed variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
    * the third line begins with the number of query variables (or labels) followed by the indexes of the query variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
    * the fourth line begins with the number of hidden variables followed by the indexes of the hidden variables. The indexes correspond to the variable indexes correspond to the variable indexes implied the original .uai problem file.
* The data section:
    * the first line of the data section is a single integer, _T_, indicating the number of data points
    * the next _T_ lines will specify the data points. Each line will contain an assignment _(e,q)_ to the observed and query variables (space delimited) followed by the weight of the score of the assigment. The weight of the assignment _(e,q)_ is given by _log10 Pr(e,q) + log10 Z_ where _Z_ is the partition function of the Markov network. 

For example, given a Markov network having _10_ variables, let the indices of the evidence (observed), query, and hidden variables be (_5,6,8_), (_1,4,7_), and (_0,2,3,9_) respectively. Assume we have the following _2_ data points:

* The first data point is an assignment of values _(2,1,0)_ to the evidence variables and _(0,2,1)_ to the query variables. The weight of the assignment is -48.21
* The second data point is an assignment of values _(1,0,3)_ to the evidence variables and _(1,0,1)_ to the query variables. The weight of the assignment is -76.27

the data file will contain the following:

```
10
3 5 6 8
3 1 4 7
4 0 2 3 9

2
5 2 6 1 8 0 1 0 4 2 7 1 -48.21
5 1 6 0 8 3 1 1 4 0 7 1 -76.27
```
