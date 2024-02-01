# Car Insurance Customer Behavior Analysis

**Overview**

The company has shared its annual car insurance data, and the goal is to uncover real customer behaviors within the dataset. This analysis aims to provide valuable insights that can help the company understand its customer base, make informed business decisions, and enhance its overall strategy in the car insurance market.

**Objective**

The primary objective is to identify patterns, trends, and key factors that influence customer behaviors related to car insurance. This includes understanding customer preferences, factors affecting policy renewals, claim patterns, and any potential correlations between customer characteristics and insurance interactions.

**Feature Engineering**

Feature engineering plays a crucial role in extracting meaningful information from raw data and improving the performance of machine learning models. For example combining two or more features to create new, composite features. In addition, Feature selection is a critical step in the machine learning pipeline that involves choosing a subset of relevant features to train the model, improving model performance, and reducing overfitting.


**Here are the Top 10 Features of the Dataset**

![image](https://github.com/amd3897/Car-Insurance/assets/145266280/b949cc22-70f3-4c01-8394-926b0312f96d) 

*Fig. 1: Feature Importance*

*Having children is slightly positively correlated. This means that when having children, it makes the person worried about his family, so they tend to purchase insurance.*

![image](https://github.com/amd3897/Car-Insurance/assets/145266280/b3446ab4-1195-4fa2-92ae-5c0a0e777138) 

*Fig. 2: Having Children vs Outcome*

*We can see a negative trend when the car is older than 2015. This means that the older the car is, the less likely its owner will want to purchase insurance.*

![image](https://github.com/amd3897/Car-Insurance/assets/145266280/4ddcc819-099b-432e-9e24-5d750994521a) 

*Fig. 3: Car Age vs Outcome*


**Neural Network Summary**

- Network Architecture:
  - Input layer, 1 Hidden layer, Dropout layer and Output layer
  - Different dimensions, dropout, training itterations and other parameters were used
  - Loss function used is bce (Binary Cross Entropy) since the ouptut is a binary classification
  - Validation accuracy was monitored during the training of the model
  - The model chosen did a very good job on unseen data, with accuracy 84%, f1_score 81%, recall 81% and precision 82%
 
- Our baseline model compared to the Neural Network, did a very similar job
  - Accuracy: 84% (ANN) vs 84% (Baseline)
  - f1_score: 81% (ANN) vs 81% (Baseline)
  - Recall: 81% (ANN) vs 81% (Baseline)
  - Precision: 82% (ANN) vs 82% (Baseline)

- This dataset was quite simple, that's why the two models performed exactly the same, and very well, so either of them is applicable.
