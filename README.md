---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 5 Sec 37  V2         <br/>
**Topic**: PCA <br/>
**Amount of time**: 60 minutes <br/>
**Author**: Alison Peebles + Greg Damico

Adapted from the DS Lesson Starters repository.

***

#### Lesson Summary:

This lesson introduces PCA. It is likely to be student's first introduction to unsupervised learning. While the lesson is short, it should also provide additional practice and assessment opportunities for other student fundamentals including Pandas and Matplotlib. Be sure to stress important implications of PCA including the curse of dimensionality.

#### Topic:

Principal Component Analysis (PCA)

#### Learning goals for this lesson:

* Students will be able to implement PCA using scikit-learn
* Students will be able to determine the percentage of variance accounted for from the first n components of a PCA model.
* Students will be able to give a high level explanation of what PCA does and its use cases.

#### Prerequisite knowledge:

* Students should have a strong working understanding of pandas DataFrames.
* Students should have previous exposure to using the scikit-learn framework of instantiating models and using the `.fit()` and `.predict()` methods.
* Students should have previous exposure to covariance.
* Students should have previous exposure to linear regression.

#### Prequisite Learn-Materials:

* [Unsupervised Learning](Unsupervised Learning)
* [Curse of Dimensionality](Curse of Dimensionality)
* [Principal Component Analysis in scikit-learn](Principal Component Analysis in scikit-learn)
* [Performing Principal Component Analysis](Performing Principal Component Analysis)

#### Post Learn-Materials:

* [Curse of Dimensionality - Lab](Curse of Dimensionality - Lab)
* [Principal Component Analysis in scikit-learn - Lab](Principal Component Analysis in scikit-learn - Lab)
* [PCA Background: Covariance Matrix and Eigendecomposition](PCA Background: Covariance Matrix and Eigendecomposition)
* [Performing Principal Component Analysis - Lab](Performing Principal Component Analysis - Lab)
* [PCA and Digital Image Processing](PCA and Digital Image Processing)
* [PCA and Digital Image Processing - Lab](PCA and Digital Image Processing - Lab)

#### Relevant learning goals from Airtable: 

*  PCA.1.rec27rsG7ERzM6IjM
*  PCA.1.rec338UHbLBobkxED
*  PCA.1.rec9lSDned5r6G2qV
*  PCA.1.recAZVV5Xca5RIPKC
*  PCA.1.recNr3fg3Jxa9s4nk
*  PCA.1.recVbLQapk8V2iEpd
*  PCA.1.recdmDBQ9h2d4FfRm
*  PCA.1.recwxpXTvTbdTlMjU
*  PCA.2.rec3C9HseRRmNe3MI
*  PCA.2.rec3C9HseRRmNe3MI
*  PCA.2.recEBqCbR8pKU0EP1
*  PCA.2.recJtQQP6Tla0gMqF
*  PCA.2.recNke1q3QlSsTg5R
*  PCA.2.recNke1q3QlSsTg5R
*  PCA.2.recoB1rtCRuFyqhz1
*  PCA.2.recpC1qPLCfpcWPQc
*  PCA.2.recr9lmmvlldZSCk0
*  PCA.3.recfrKc0NhBHishNp
*  PCA.3.recg5qO858VYTLdM4
*  PCA.3.recuGexa01KxlbyXF
*  PCA.4.recDDnOA3iNDHE8VG

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Eigenvector
* Eigenvalue
* Principal Component Analysis


#### Lesson Outline:

* Introduction (10 minutes)
* Loading the Iris Dataset
* Implementing PCA
	* n_components
	* explained_variance / explained_variance_ratio
* Visualizing Components
* Appendix 