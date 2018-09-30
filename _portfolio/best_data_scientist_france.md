---
title: Best Data Scientist France 2018
duration: 
role: 
skills:
  - Python
  - Machine Learning
  - Feature Engineering
  - Scikit-Learn
---

Please see [Github Repository](https://github.com/selimamrouni/best-data-scientist-france-2018)

This repository presents a [web-app](https://gas-app-usa.herokuapp.com/) developed based on a discussion This is a small attempt on a dataset released during a data science contest in France. The dataset comes from [Label Emmaüs](https://www.label-emmaus.co/fr/), a French non-profit organization.

Unfortunately, I was not in France during the contest and could not take part in it. But the dataset was released and is available on the [Meilleur Data Scientist](https://www.meilleurdatascientistdefrance.com/) and it is still possible to submit your prediction on the platform. 

[Label Emmaüs](https://www.label-emmaus.co/fr/) offers for sale objects renovated or created by the movement Emmaüs. The aim is to estimate the range of time to sale each object.

This is a multi-labels classification, with 3 labels:

- 0 : between 0 et 10 days
- 1 : between 10 et 60 days
- 2 : more than 60 days
<br>
The evaluation metric is multilogloss. 

For this project, I started by some features engineering, then used machine learning technics and deep learning technics. 

The files are:
- X_train.csv, X_test.csv, y_train.csv: Data files. 
- description.pdf: An overview of the challenge proposed by the platform. 
- meilleur_DS_france.ipynb: The notebook file. 

## Feature Engineering

This is a real-world data problem. Thus, some data cleaning has been realized and features have been removed: too much NaNs or non relevant features (like listings URLs). 

The numerical data have been normalized and the categorical have been one-hot encoded. 

Finally, I used text mining technics (length, count of words, sentiment analysis) to extract features from titles and descriptions. 

## Machine Learning

I tested several classification pipelines using PCA with different level of dimensionality reduction and classification algorithms.
The best algo was the logistic regression with no PCA. It scored 1.01409 of log_loss on the platform.

## Deep Learning

I prototyped a neural net model using Keras. I faced over-fitting and used both early-stopping and dropout to limit it. I think the dataset is too small, with more data, we might reach better results. It scored 0.99662 of log_loss on the platform.

## Thanks to

Special thanks to **Artem Golubin** [rushter](https://github.com/rushter)
The one-hot encoding is inspired by this amazing git: https://github.com/rushter/heamy/blob/master/heamy/feature.py#L7

## Author

* **Selim Amrouni** [selimamrouni](https://github.com/selimamrouni)
