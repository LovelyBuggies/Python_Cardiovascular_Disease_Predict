## Cardiovascular Disease Prediction

[SoC2020 Link](https://code.ihub.org.cn/projects/1360)

### Table of Contents

- [Description](#description)
- [Project Plan](#project-plan)
  * [Data Preprocessing](#data-preprocessing)
  * [Classification](#classification)
  * [Evaluation](#evaluation)
  * [Follow Up](#follow-up)
- [Millestones](#millestones)

### Description

In classification problems, the purpose of classification is to select a category from a set of data (e.g., to give a picture of an apple or orange and identify which fruit is in the picture). This project uses the cardiovascular disease data set, which provides 11 eigenvalues and 1 target value and contains data from 70,000 patient records. An algorithm model was constructed to predict whether the sample had cardiovascular disease. This training mainly introduces how to realize the development of "cardiovascular disease prediction model". Through this training program, the audience can understand the development of the prediction model.

### Project Plan

My project can be divided into the following parts.

#### Data Preprocessing

A nice data set that includes patient characteristics and a label about cardiovascular diseases is given in https://www.kaggle.com/sulianova/cardiovascular-disease-dataset. The first thing I need to do to predict cardiovascular disease is to preprocess the data, which should include but not limited to:

- Load the dataset and read the data;
- Handling outliers in the dataset;
- Correlation analysis for features;
- *Add new features (feature engineering);*
- *Eliminate insignificant features.*

#### Classification

I plan to use several classification methods, like Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, K-Nearest Neighbors, and Naive Bayes, to predict the cardiovascular disease, and compare their performance.

I also plan to use some methods to find the best hyperparameters for the winning classification algorithm and avoid unexpected phenomena like overfitting.

#### Evaluation

To find the best classification algorithm, some criteria for evaluation are needed, such as Precision, Recall, and F1 scores. Some other evaluating metrics are still under discussion.

#### Follow Up

Plan to add some ANN methods, like RNN, if time allows.

### Millestones

| Due            | &nbsp;&nbsp;&nbsp;Progress                                   |
| ------------------ | ------------------------------------------------------------ |
| Aug. 14  | &nbsp;&nbsp;&nbsp;**Data Pre-processing**<br />-  Load the dataset and read the data.<br />-  Handling outliers in the dataset.<br />-  Correlation analysis for features.<br />-  *Add new features (feature engineering) if necessary.*<br />-  *Eliminate unsignificant features if necessary.* |
| Sep. 27 | &nbsp;&nbsp;&nbsp;**Classification and Evaluation**<br />-  Use several classification methods to predict the cardiovasular disease.<br />-  Evaluate the performance of each method.<br />-  Find the well-behaved hyperparameters.<br />-  *Explore Artifical Neural Network to classify if time allows.* |