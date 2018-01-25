---
layout: post
title: Modeling how to handle unbalanced data
excerpt: "This article comes from machinelearningmastery.com . This specific article outlines goes over the major problem of imbalanced data and how to correct for it."
comments: true
---

A common problem in data science especially predictive machine learning is to have imbalanced data. for example, In a binary classification meaning you are trying to predict a feature that has two outcomes such as failure or success one of the outcomes in your training data is far more prevalent than the other. This can lead to misleading accuracy results. For instance if you have an Algorithm that was trained on a data set that predicts A or B and out of the 1000 observations A occurs 990 times your algorithm can predict A for every observation and have an accuracy of 99% (this is known as the accuracy paradox). The article linked below gives several examples of how to deal with imbalanced data. Personally, I have used SMOTE (Synthetic Minority Over-sampling Technique) to handle imbalanced data, and F-1 scores. If you want to see these methods in action check out my Device Failure project for a more in-depth look at imbalanced data.

<a href="https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/">Tactics to Combat Imbalanced Classes in Your Machine Learning Dataset</a> by: Jason Brownlee
