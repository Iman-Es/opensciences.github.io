---
title: wspomaganiepi
excerpt: Towards Identifying Software Project Clusters with Regard to Defect Prediction
layout: repo-dataset
author: Marian Jureckzo
---


# URL

* [Data in Terapromise](https://terapromise.csc.ncsu.edu/!/#repo/view/head/defect/ck/wspomaganiepi/)
* [Paper in ACM Digital Library](http://dl.acm.org/citation.cfm?id=1868328.1868342&coll=DL&dl=GUIDE&CFID=96280125&CFTOKEN=47274353)

# Change Log

When | What
---- | ----
February 2, 2016 | updated BibTeX and paper link, added abstract
July 26, 2010 | Donated by [Marian Jureckzo](/repo/people/data-donors/promise3.html)

# About the data

This dataset is one of the [Marian Jureckzo](/repo/people/data-donors/promise3.html) Datasets.

This dataset uses the [CK](/repo/defect/ck/tut.html) OO metrics.

# Reference

```
@inproceedings{Jureczko:2010:TIS:1868328.1868342,
 author = {Jureczko, Marian and Madeyski, Lech},
 title = {Towards Identifying Software Project Clusters with Regard to Defect Prediction},
 booktitle = {Proceedings of the 6th International Conference on Predictive Models in Software Engineering},
 series = {PROMISE '10},
 year = {2010},
 isbn = {978-1-4503-0404-7},
 location = {Timi\şoara, Romania},
 pages = {9:1--9:10},
 articleno = {9},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/1868328.1868342},
 doi = {10.1145/1868328.1868342},
 acmid = {1868342},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {clustering, defect prediction, design metrics, size metrics},
}
```

## Paper abstract

Background: This paper describes an analysis that was conducted on newly collected repository with 92 versions of 38 proprietary, open-source and academic projects. A preliminary study performed before showed the need for a further in-depth analysis in order to identify project clusters.
<br>
Aims: The goal of this research is to perform clustering on software projects in order to identify groups of software projects with similar characteristic from the defect prediction point of view. One defect prediction model should work well for all projects that belong to such group. The existence of those groups was investigated with statistical tests and by comparing the mean value of prediction efficiency.
<br>
Method: Hierarchical and k-means clustering, as well as Kohonen's neural network was used to find groups of similar projects. The obtained clusters were investigated with the discriminant analysis. For each of the identified group a statistical analysis has been conducted in order to distinguish whether this group really exists. Two defect prediction models were created for each of the identified groups. The first one was based on the projects that belong to a given group, and the second one - on all the projects. Then, both models were applied to all versions of projects from the investigated group. If the predictions from the model based on projects that belong to the identified group are significantly better than the all-projects model (the mean values were compared and statistical tests were used), we conclude that the group really exists.
<br>
Results: Six different clusters were identified and the existence of two of them was statistically proven: 1) cluster proprietary B -- T=19, p=0.035, r=0.40; 2) cluster proprietary/open - t(17)=3.18, p=0.05, r=0.59. The obtained effect sizes (r) represent large effects according to Cohen's benchmark, which is a substantial finding.
<br>
Conclusions: The two identified clusters were described and compared with results obtained by other researchers. The results of this work makes next step towards defining formal methods of reuse defect prediction models by identifying groups of projects within which the same defect prediction model may be used. Furthermore, a method of clustering was suggested and applied.
