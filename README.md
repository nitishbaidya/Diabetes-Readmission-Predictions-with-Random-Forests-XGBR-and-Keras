# Diabetes Readmission Prediction

This repository contains a comparative analysis of three different machine learning models—Random Forest (RF), XGBoost (XGBR), and a neural network implemented in Keras—for predicting the readmission of diabetes patients. The dataset used for this analysis is sourced from the "Diabetes 130-US hospitals for years 1999-2008" database, and the original paper titled "Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records" [https://doi.org/10.1155/2014/781670] has been referenced for a comprehensive understanding of the coded data.

# Dataset Details

The complete dataset and mapping details can be accessed here. The research is primarily focused on predicting readmission within 30 days of discharge, treating the problem as a binary classification task. Given the imbalanced nature of the dataset, where instances of readmission within 30 days are limited, the analysis incorporates Synthetic Minority Over-sampling Technique (SMOTE) to enhance recall and improve model performance.

# Key Findings

All three models—Random Forest, XGBoost, and Keras—demonstrate commendable performance in predicting readmissions. Notably, XGBoost leads with the highest accuracy, recording an impressive 87.4%, followed closely by Random Forest with 85.9%. The neural network implemented in Keras exhibits strong performance as well, achieving an accuracy of 81.9%. These accuracy values underscore the efficacy of the models in addressing the complex task of predicting readmission outcomes for diabetes patients.

The research aims to provide valuable insights into predicting readmission outcomes and highlights the nuances in model performances. The detailed analysis and findings contribute to the ongoing discourse on leveraging machine learning for healthcare outcomes.
