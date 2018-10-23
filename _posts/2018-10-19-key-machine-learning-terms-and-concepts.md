---
layout: post
title: "Key Machine Learning Terms and Concepts"
date: 2018-10-19
---

Before we dive into Step by step data modelling with machine learning, i want us To get familiar with Key Machine Learning Terms and Concepts.

Machine learning terms can be confusing. Here are definitions of key terms to help get along.

**Descriptive Analytics, Data Exploration, and Predictive Analytics**.
![]("{{/images/des exp pre.jpg"|absolute_url}})

**Data exploration** is the process of gathering information about a large and often unstructured data set in order to find characteristics for focused analysis. Data mining refers to automated data exploration.

**Descriptive Analytics** is the process of analyzing a data set in order to summarize what happened. The vast majority of business analytics - such as sales reports, web metrics, and social networks analysis - are descriptive.

**Predictive Analytics** is the process of building models from historical or current data in order to forecast future outcomes.

**Supervised and Unsupervised Learning**
![alt text](https://github.com/BolaBen/BolaBen.github.io/blob/master/images/supervise.jpg "Supervised and Unsupervised Learning")

**Supervised Learning Algorithms** are trained with labeled data - in other words, data comprised of examples of the answers wanted. For instance, a model that identifies fraudulent credit card use would be trained from a data set with labeled data points of known fraudulent and valid charges. Most machine learning is supervised.

**Unsupervised Learning** is used on data with no labels, and the goal is to find relationships in the data. For instance, you might want to find groupings of customer demographics with similar buying habits.

**Model Training and Evaluation**

**A Machine Learning model** is an abstraction of the question you are trying to answer or the outcome you want to predict. Models are trained and evaluated from existing data.
![alt text](https://github.com/BolaBen/BolaBen.github.io/blob/master/images/a%20machine%20learning%20model.jpg "A Machine Learning model")

**Training Data**

![alt text](https://github.com/BolaBen/BolaBen.github.io/blob/master/images/training%20data.jpg "Training Data")

When you train a model from data, you use a known data set and make adjustments to the model based on the data characteristics to get the most accurate answer. In Azure Machine Learning, a model is built from an algorithm module that processes training data and functional modules, such as a scoring module.

In Supervised Learning, if you're training a fraud detection model, you use a set of transactions that are labeled as either positive or negative transaction. You split your data set randomly, and use part to train the model and part to test or evaluate the model.

**Evaluation Data**

![alt text](https://github.com/BolaBen/BolaBen.github.io/blob/master/images/evaluation%20data.jpg "Evaluation")
