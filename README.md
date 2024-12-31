# Bank account fraud detection 🏦 
This is the project I created for the business analysis course for the year 2023 in my computer science master degree track in artificial intelligence at the Università degli studi di Genova.

I used this dataset in the project: [Bank Account Fraud Dataset Suite (NeurIPS 2022)](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022/data)
> Here you can find the processed dataset: [Drive](https://drive.google.com/drive/folders/19yJMc_P9PpwfqLp4NiloRzB6UzCy-pDl?usp=sharing) (In the .ipynb file I used the dummies.csv file)

## Introduction

In this project I tried to detect the outliners in the dataset that might indicate fraudolent request for a new bank account from a malicious agent. To solve this **unbalanced classification** problem I decided to use a [Random forest classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) and I tiried different **resampling** methods such as [NearMiss](https://imbalanced-learn.org/stable/references/generated/imblearn.under_sampling.NearMiss.html) and [SMOTE](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html) to find the best result.

## Files 📂
- *BAP_RandomForest_model.ipynb* file with all the implementation for the detect the fraudolent request of new bank account.
- *BAP_presentation.pdf* briefly project presentation.
- *BAP_data_visualization_and_preparation.ipynb* file with the preprocessing and visualization part.

