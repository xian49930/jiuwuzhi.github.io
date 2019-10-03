---
layout:     post
title:      "Notes for 'Python for Machine Learning'"
subtitle:   "\"Coursera\""
date:       2019-09-06
author:     XL
header-img: 
catalog: 	 true
tags:
    - Coursera
    - Python
    - Machine Learning
    - Online Courses
---

# Notes 

This posts records all my notes for the online course - Python for Machine Learning - on Coursera.com.

*New notes will be added on the top of the older ones.*

## Week 4

**Clustering**

Intro to Clustering:

- Clustering for segmentation 
	- (showing an example first.)

- What is clustering?
	- A group of objects that are similar to other objects in the cluster, and dissimilar to data points in other clusters.

- Clustering V.S. classification
	- (showing an similar but different term, which may easily confuse people.)
	- classification: labeled dataset
	- clustering: unlabeled dataset

- Clustering applications:
	- Retail/marketing
		- identifying buying patterns of customers
		- recommending new books or moviews to new customers
	- Banking
		- fraud detection in credit card use
		- identifying clusters of customers (e.g. loyal)
	- Insurance
		- fraud detection in claims analysis
		- insurance risk of customers
	- Publication
		- Auto-categorizing news based on their content
		- Recommending similar news articles
	- Medicine
		- Characterizing patient behavior
	- Biology
		- Clustering genetic markers to identify family ties

- Why clustering?
	- Exploratory data analysis
	- Summary generation
	- Outlier detection
	- Finding duplicates
	- Pre-processing step

- Clutering algorithms
	- Partitioned-based Clustering
		- Relatively efficient
		- K-Means, K-Median, Fuzzy c-Means
	- Hierarchical Clustering
		- Produces trees pf c;uters
		- Agglomerative, Divisive
	- Density-based Clutering
		- Produces arbitrary shaped cluters
		- DBSCAN 

## Week 3

- Classification algorithms in ML:
	- Decision Trees (ID3, C4.5, C5.0)
	- Naive Bayes
	- Linear Discriminant Analysis
	- K-Neareest neighbor
	- Logistic Regression
	- Neural Networks
	- Support Vector Machines (SVM)


## Week 2

- **Different types of errors:**
	- \\( R^2 = 1 - RSE\\)

	- \\( RSE = \frac{\sum_{j=1}^{n}(y_j-\hat{y_j})^2}{\sum_{j=1}^{n}(y_j-\bar{y_j})^2} \\)


	- \\( RAE = \frac{\sum_{j=1}^{n}|y_j-\hat{y_j}|}{\sum_{j=1}^{n}|y_j-\bar{y_j}|} \\)


	- \\( RMSE = \sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i-\hat{y_i})^2} \\)


	- \\( MSE = \frac{1}{n}\sum_{i=1}^{n}(y_i-\hat{y_i})^2 \\)


	- \\( MAE = \frac{1}{n}\sum_{j=1}^{n}|y_j-\hat{y_j}|\\)
<!--
\\[ MSE = \frac{1}{n} \\]
-->

- Types of Regression models:
	- Simple Regression
		- Simple Linear Regression
		- Simple Non-linear Regression
	- Multiple Regression:
		- Multiple Linear Regression
		- Multiple Non-linear Regression

- Applications of Regression
	- Sales forecasting
	- Satisfaction analysis
	- Price estimation
	- Employment income

- Regression Algorithms
	- Ordinal regression
	- Poisson regression
	- Fast forest quantile regression
	- Linear, Polynomial, Lasso, Stepwise, Ridge regression
	- Bayesian linear regression
	- Neural network regression
	- Decision forest regression
	- Boosted decision tree regression
	- KNN (K-nearest neighbors)


## Week 1

| **Supervised Learning**                                     | **Unsupervised Learning**                                        |
|---------------------------------------------------------|--------------------------------------------------------------|
| **Classification**:<br/> Classifies labeled data                 | **Clustering**:<br/> Finds patterns and groupings from unlabeled data |
| **Regression**:<br/> Predicts trends using previous labeled data |                                                              |
| Has more evaluation methods                             | Has fewer evaluation methods than supervised learning        |
| Controlled environment                                  | Less controlled environment                                  |

- Unsupervised Learning
	- *The model works on its own to discover information.*
	- Unlabelled data.
	- Techniques include:
		- Dimension reduction
		- Density estimation
		- Market basket analysis
		- **Clustering**  *(one of most popular)*
	- ***Clustering***: grouping of data points or objects that are somehow **similar** by:
		- Discovering structure
		- Summarization
		- Anomaly detection


- Supervised Learning
	- *We "teach the model", then with that knowledge, it can predict unknown or future instances.*
	- Labelled data. 
	- ***Classification***: the process of predicting discrete class lebels or categories.
	- ***Regression***: the process of predicting continuous values.

- Python libraries for machine learning (***upper level marked in bold***)
	- [Numpy](https://numpy.org/)
	- [SciPy](https://www.scipy.org/)
	- [matplotlib](https://matplotlib.org/)
	- [**pandas**](https://pandas.pydata.org/)
	- [**scikit-learn**](https://scikit-learn.org/stable/)

