# Credit_Risk_Analysis

## Overview of The Loan Prediction Risk Analysis

Machine learning is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention. In this project I'm going to use machine learning model to predict which individuals are credit worthy for loans.

# Results

The best outcome for any prediction is to test the data with different models, in this project six different models where used to predict the best risk fator before initializing any loan. This factors are listed below
- Balanced random Forest Classifier 
- Easy Ensemble ADABoost Classifier
- Naïve Random Oversampling
- SMOTE Oversampling
- Cluster Centroids Undersampling
- SMOTEENN Combination (Over and Under) Sampling

# Predicted Results

## Balanced Random Forest Classifier 

![image](https://user-images.githubusercontent.com/86568537/144794324-d06f0d2e-f218-4ea7-975b-66d21b050f46.png)

- Precision High Risk: 3%
- Precision Low Risk: 100%
- Recall High Risk: 77%
- Recall Low risk: 89%

## Easy Ensemble ADABoost Classifier

![image](https://user-images.githubusercontent.com/86568537/144795724-059e4e7a-93ce-4545-9085-397995ef2852.png)

- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 92%
- Recall Low risk: 94%

## Naive Random Oversampling 

![image](https://user-images.githubusercontent.com/86568537/144795938-9400cfc3-156e-402a-8f4d-31ef97a412e8.png)

- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 0%
- Recall Low risk: 100%

## SMOTE Oversampling

![image](https://user-images.githubusercontent.com/86568537/144796422-d39af4e0-af18-4fa5-b210-3605a3bf97d4.png)

## Cluster Centroids Undersampling

![image](https://user-images.githubusercontent.com/86568537/144796921-d1042990-0672-49c3-9c4f-528a2c193a02.png)

- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 0%
- Recall Low risk: 100%

## SMOTEENN Combination (Over and Under) Sampling

![image](https://user-images.githubusercontent.com/86568537/144797292-78559229-886d-40f9-b0af-f75da053910a.png)

- Precision High Risk: 0%
- Precision Low Risk: 100%
- Recall High Risk: 0%
- Recall Low risk: 100%

# Sumarry 
The aim of this project is to use machine learning to determine rick analysis before loans are being considered. With the data being given and processed through different machine learning models it shows that credit risk is low. The model that is close to accuracy in terms of prediction is the Ensemble classifier, although we have a model that is more efficient but its advisable not to use this results for a credit risk analysis.




