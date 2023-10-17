# COMP3009 Machine Learning Assignments

These folders contain the two projects submitted for the module COMP3009 Machine Learning.

## Assignment 1

The first project was to show proof that we could use ML techniques correctly, by choosing any two datasets and applying eight ML models to them. One dataset would be used for classification, and the other regression, and four different models were applied to each. The folder named Assignment 1 includes the datasets for concrete (used for classification) and wine (used for regression). In both cases, the models used were SVM, MLP, DT and Linear/Logistic Regression for both classfication and regression. The results folder shows the various plots produced over the course of the project to illustrate how the models worked. 

The metrics used to evaluate the model were K-fold Cross Validation, classification accuracy, MSE and R2 scores.

## Assignment 2

The second project applied ML models to breast cancer screening. Given the data on patients who had recieved chemotherapy to treat breast cancer, there were two predictions to be made. The Pathological Complete Response (PCR) denotes the complete resolution of the tumour at surgery, which has a high likelihood of cure and longer Relapse Free Survival (RFS). RFS is the length of time after receiving treatment without any further signs or symptoms of the same cancer. 

The models analysed were ANNs, XGBoost, Logistic and Linear Regression, SVMs, RFs, and the KNN algorithm. Ultimately, the SVM Classifier was the best model for PCR prediction, with a final classification accuracy of 75.7%, and the best model for RFS prediction was the RF Regressor, with a final MAE of 20.73.
