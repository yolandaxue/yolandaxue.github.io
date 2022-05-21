---
title: "Handbook of Machine Learning for Social Sciences"
permalink: /posts/2022/05/ml-for-socsci
date: 2022-05-21
excerpt_separator: <!--more-->
share: true
comments: true
toc: true
tags: - machine learning
---
This handbook is a collaborative work with <a href="https://angelhwang.github.io/">Angel Hwang</a> and <a href="https://remypstewart.github.io/">Remy Stewart</a> designed for researchers in social sciences. We expect that the audience will have basic knowledge of Python and have at least taken a course in calculus and statistics. This handbook aims to offer you practical experience with machine learning models.
<!--more-->

In this handbook, we are not attempting to teach math behind machine learning. When we walk you through the basic concepts, we use the minimum amount of equations. However, it is essential to understand statistical inference in order to use machine learning in your research better and be able to discuss the advantages and flaws of the application of machine learning models. Therefore, in each chapter (and each section in each chapter), we provide you with a list of resources in case you are interested in digging into certain concepts and/or models.

Chapter 1 introduces machine learning, including the overview of machine learning, different types of machine learning models, and the application of machine learning for social sciences. In Chapter 2, we cover Python basics to prepare you for data preprocessing steps (data visulzation and feature engineering) before delving into machine learning tasks. We discuss classification in Chapter 3 and regression in Chapter 4 by introducing the basic models using simulation data and walking you through a case study using the real research datasets. Chapter 5 illustrates the unsupervised learning models and offers you hands-on experience on clustering. Chapter 6 discusses model inference, including prediction and causal inference after training the machine learning models. Finally, we present a glossary of the key concepts illustrated in the handbook and cheatsheets for supervised and unsupervised learning in Chapter 7.

## Table of Contents

<h2><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt">Chapter 1. Introduction</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=SIuDePQCBT8t">Introduction to Machine Learning for Social Sciences</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=aTm3hetVc3P7">Who Should Read this Handbook?</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=53Dbt9pO1_08">What is ML?</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=eJ10jv7TglWa">Why ML?</a></h4>


* <h3><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=6p8-YD3Sc9K-">A Guide to the Types of Machine Learning Algorithms</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=z_dwU71lB9G3">Supervised Learning</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=Suhga8tPPjRV">Unsupervised Learning</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=jD1TyxL9hRjX">Application of Machine Learning for Social Sciences</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=KVCmvjsqcuCB">How to Apply ML?</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=iY8RjVAvcwMB">What are the Concerns about ML for Social Sciences?</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=2oZVwZ4jE5EW">Key (Statistical) Concepts</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=g-h9hVTxE_t6">Points and Lines</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=c1FrEPRbLqnZ">Loss and Cost Function</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=5pzKdrbGO2wc">Gradient Discent</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=1w7ooLCdX4IB">Learning Rate</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1x3bvlob4KF247pIsy0Ejwaav7gETWRWt#scrollTo=u3xtmZOlhCUW">Reference</a></h3>

<h2><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC">Chapter 2. Python Basics</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=d8nut5JqQV_e">Data Visualization Essentials</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=jHDdDYUEReqM">Distribution</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=FRNFxR3TRg9y">Correlation</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=vfoJOrDJRjXP">Ranking</a></h4>


* <h3><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=Fivyd0TVQfw6">Feature Engineering</a></h3>

  * <h4> Still in Progress </h4>

* <h3><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=vrUFY5arQkg3">Data Cleaning & Pre-Processing</a></h3>

  * <h4> Still in Progress </h4>

* <h3><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=8V_IP0TpRBUo">Handling Missing Values</a></h3>

  * <h4> Still in Progress </h4>

* <h3><a href="https://colab.research.google.com/drive/1kVknAq2tnHX4h-nr_WUS2vnrh6FXMrKC#scrollTo=_wEfvBxtREpk">Handling Data with Domain Knowledge</a></h3>

  * <h4> Still in Progress </h4>

<h2><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX"> Chapter 3. Supervised Learning - Classfication</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=6yzQgybyAoir">Introduction to Classification</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=8LI6rMMPBilR">Libraries and Modules</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=dME_BenBAzat">Models and Basic Concepts</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=CFMEES4EC_z0">Logistic Regression</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=FyulmvXTV1ft">Underfitting versus Overfitting</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=5cXFY_E8BAJc">Regularization</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=T18mMnqxQUTA">Tree-based Model</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=bQVGm_XRn-hz">Model Comparison</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=5WpHkdOvELVv">Model Pipeline</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=79teDOOvWQfy">Hyperparameter Tuning</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=bbnY-LH3EXo6">Model Training</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=0b31DPXZERqt">Cross Validation</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=LXwIHuWt4VXA">Model Evaluation</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=lLm76lKroAh7">Case Study: Predict the Income Level</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=PxGHdiAdHegY">Import Online Dataset</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=T5zSoT1Mr7dW">Exploratory Data Analysis and Data Cleaning</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=_x-1xkMApE-G">Model Training</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1eZ7doC7G0l4JM_3QX5BRMhFV0F6MzWHX#scrollTo=2nU-kivEZOhy">Model Evaluation</a></h4>

<h2><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD"> Chapter 4. Supervised Learning - Regression</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=8LI6rMMPBilR">Libraries and Modules</a></h3>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=0IvqWBT1a2Os">Introduction to Linear Regression</a></h3>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=R8QMkLAnFiV_">Key Concepts</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=qHNwnCFpjRg_">Points and Lines</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=60Xc9Lx5j-gA">Loss</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=6-ftRB4qFXfZ">Gradient Discent</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=x3yYh3EGHX2-">Convergence</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=hOgYHdEfKUza">Learning Rate</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=gtPHnTE_TsRB">Linear Regression with Scikit-Learn</a></h3>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=J5aYeVrjurQL">Mini Case Study: Predict Prices of Houses in Boston</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=gKx6rjRz6yii">Simple Linear Regression</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=Z8aGXD9adL4y">Fitting & Comparing Different Types of Regressors</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=_x-1xkMApE-G">Model Training</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=2nU-kivEZOhy">Model Evaluation</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=KuztwNPyuMnm">Other Regressors</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=5cXFY_E8BAJc">Regularized-Linear Regression</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=TIHlKjViwLWC">Generalized Linear Regression</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1512eKBtl5O_UVqL2xvZz2R6FqJ39beyD#scrollTo=T18mMnqxQUTA">Tree-based Model</a></h4>

<h2><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw"> Chapter 5. Unsupervised Learning</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=XQfbm9Sv8_OR">Introduction to Clustering</a></h3>

* <h3><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=YNWGYCtfBSgg">K-Means Clustering</a></h3>

* <h3><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=j52OJ786SmqW">Implement K-Means using Scikit-Learn</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=pAMs4qIwXEw6">K-means essentials: A quick exercise to build your first clustering model</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=J5aYeVrjurQL">Mini Case Study: Clustering Houses in Boston</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=oyZCqy8cqxKL">Import libraries and dataset</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=fS1xQ8Fdu17L">Visualize before K-Means</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=ziAWLfKLLt7q">Dimension Reduction using PCA</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=SZkYpkyFD1Vi">Determining the Number of Clusters</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=SR9v0FSRD1Vj">Fitting the K-Means Model</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=J4zY3EyCD1Vk">Analyze the K-Means Clustering Results</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=NZGo2TYPY5MC">Visualize clusters after fitting K-Means</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=oIWHLsvuumby">Handling new data</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1WWEVml4n7QUADD2S3aRDaYSzQQtrhLvw#scrollTo=1F2KIT855nEi">Unsupervised learning beyond K-Means</a></h3>

<h2><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw">Chapter 6. Inference</a></h2>

* <h3><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=fJJRvctzz7Ff">Prediction</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=ol_x7jTLSPOf">Predict with Classification Models</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=el45xztXSS_l">Predict with Regression Models</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=cg8_J6kRz36E">Causal Inference</a></h3>

  * <h4><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=c_XKJZ7ghb39">What is Causal Inference?</a></h4>

  * <h4><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=gite0V0j0AQN">Machine Learning for Causal Inference</a></h4>

* <h3><a href="https://colab.research.google.com/drive/1rSOrpqGJ3ZRWSI_lhQlYZxDpHfZ1PcFw#scrollTo=cmUh8uBtIqL4">Reference</a></h3>
