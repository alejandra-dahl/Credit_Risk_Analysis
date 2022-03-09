# Credit Risk Analysis

## Overview of the Analysis

This analysis was created, through machine learning, to accurately predict credit risk. Credit risk is an unbalanced classification problem. Several different techniques were used to train and evaluate models with unbalanced classes. The data set that was used came from LendingClub, a peer-to-peer lending services company.

### Purpose

The purpose of this analysis was to use Resampling models, SMOTEENN Algorithm, Ensemble Classifiers to predict credit risk.

## Results

   **Naive Random Oversampling**
   
![image](https://user-images.githubusercontent.com/90485451/157358072-61d6ce73-8df5-4aa7-8e0d-0a87b031eca9.png)

  - Balanced Accuracy Score: 0.646 
  - Precision Score: 1% or 0.01, low precision for high-risk loans and high for low-risk loans
  - Recall Score: .71 high risk/.58 low risk



  **SMOTE Oversampling**

  ![image](https://user-images.githubusercontent.com/90485451/157359222-9f0bdc4c-f455-4d2b-8c57-895f494ba55b.png)

  - Balanced Accuracy Score: .659
  - Precision Score: 1% or 0.01 (high risk)
  - Recall Score: 0.63 high risk/ .68 low risk

  **Undersampling**
  
  ![image](https://user-images.githubusercontent.com/90485451/157359288-5fe8451d-b360-4886-ab4b-cc4ae24af5e2.png)

  - Balanced Accuracy Score: 0.659
  - Precision Score: 1% or 0.01 (high risk)
  - Recall Score: 0.69 high risk/ 0.40 low risk
  
  **Combination Sampling**
  
  ![image](https://user-images.githubusercontent.com/90485451/157359337-8b90a81f-bbb3-4848-9c34-373e84552997.png)

  - Balanced Accuracy Score: 0.545
  - Precision Score: 1% or 0.01 (high risk)
  - Recall Score: 0.72 high risk/ 0.57 low risk
  
  **Balanced Random Forest Classifier**
  
  ![image](https://user-images.githubusercontent.com/90485451/157359630-457d160e-0365-470a-91cb-134b3965bee6.png)
  
  - Balanced Accuracy Score: 0.782
  - Precision Score: 0.03 or 3% (high risk)
  - Recall Score: 0.69 high risk/ 0.87 low risk
  
  **Easy Ensemble AdaBoost Classifier**
  
  ![image](https://user-images.githubusercontent.com/90485451/157359588-1db2adac-e5d3-48b9-86cc-27aedef7ef77.png)
  
  - Balanced Accuracy Score: 0.918
  - Precision Score: 0.09 or 9% (high risk)
  - Recall Score: 0.89 high risk/ 0.94 low risk


## Summmary

The purpose of this analysis was to find the best machine learning model that can detect if a loan is high risk or low risk. The most favorable model will have a higher balance accuracy score. The ensemble classifiers show higher accuracy scores than the previous four models. I would recommend the Easy Ensemble AdaBoost Classifier is considered the best model, having an accuracy score of 0.918. It also has the highest recall score, 0.89, for high risk loans. A high risk loan is what we want to avoid so the higher the recall, the more loans we see that could have a bigger impact on credit.

---

