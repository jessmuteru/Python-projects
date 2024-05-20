#Comparative analysis of unsuprvised machine learning algorithms for fraud detection in healthcare insurance claims:case study on NHIF

Data source:NHIF
This was a group project that involved cleaning data and performing exploratory data analyisis on inpatient claims data, and creating 3 unsupervised ML algorithms: Isolation forest, One-class SVM and Local Outlier Factor.
The main objective was to flag anomalies in the data and the flagged claims would be further investigated for any fraudulent activities. Fraud is the main problem affecting healthcare insurance in Kenya and this project aimed to help solve that problem.
##steps:

Data cleaning; filling null values using KNN imputer, Feature selection, one-hot encoding and label encoding non-numeric values.
Model building; creating the necessary models and asesing their performance metrics.
Deployment; Deploying the best performing model as an easy to use web based tool using streamlit.
