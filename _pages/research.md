---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Publication
--------------
- Computational prediction and functional analysis of arsenic binding proteins in human cells, Quantitative Biology. Shichao Pang, <b>Junchen Yang</b>, Yilei Zhao, Yixue Li and Jingfang Wang (under review)
- Yi Xiong, Qiankun Wang, <b>Junchen Yang</b>, Xiaolei Zhu, Dong-Qing Wei. PredT4SE-Stack: Prediction of Bacterial Type IV Secreted Effectors From Protein Sequences Using a Stacked Ensemble Method. Frontiers in Microbiology.

Research Experience
--------------

## Algorithm Development in Single-cell RNA-seq quantification, July 2018 - Current, UCLA

I developed an algorithm called ANT that transforms the genome alignment results to build TCC-matrix (transcript compatibility counts matrix, an expression quantification matrix). 
* The algorithm's workflow, codes and more details can be found [here](https://github.com/KevinBastianYang/ANT).
* Tested on 3381 mouse cell data, ANT showed an effciency in saving useful information such as the raw reads and the umis. Also, ANT is competitive in terms of speed at cell level.

<img src="https://jcyang.net/images/7.PNG" class="floatpic" align= "center" width="305" height="230">
<img src="https://jcyang.net/images/8.PNG" class="floatpic"  align = "center" width="305" height="230"> 

<img src="https://jcyang.net/images/9.PNG" class="floatpic" align = "center" width="305" height="230"> 
<img src="https://jcyang.net/images/10.jpg" class="floatpic" align = "center" width="305" height="230"> 

## Computational Prediction and Functional Analysis of Arsenic Binding Proteins in Human Cells, March 2018 - July 2018

* I built a computational tool called Arsenic Finder to predict arsenic binding proteins based on position-specific score matrix (PSSM) transformed by single-mutation free energy profile. The tool is freely available [here](http://47.254.78.183:8000/server/). The development is based on Django + Nginx + uWSGI.

* Our work was invited for an oral presentation at the 2018 International Comference on Computational Systems Biology. The full manuscript has been submitted to *Quantitative Biology* for publication.

## Drug Combination Database and Predictive Model Construction Based on Drug and Target Information, March 2017 - March 2018

### Database Construction
* Based on Django framework, I developed the front end of the database, which links the drugs, drug combinations, and target information.
<img src="https://jcyang.net/images/11.jpg" class="floatpic" align= "center" width="679" height="328">

### Drug Combination Prediction 
* An ensemble machine learning model is used. The base classifiers are NB, SVM, adaBoost, Random Forest, and Gradient Boost. The meta classifier is XGBoost. The following shows the workflow of the prediction model.
<img src="https://jcyang.net/images/12.png" class="floatpic" align= "center" width="500" height="350">

* AUC Results of different algorithms on test set.
<img src="https://jcyang.net/images/13.png" class="floatpic" align= "center" width="700" height="500">

* The project received an A (highest) in the 15th Undergraduate Innovation Program in Shanghai Jiao Tong University and I received an A+ (highest).


