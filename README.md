# EasyLearn
This repository is for Auto Machine learning project in collaboration with Happiest Minds.

The idea behind this project is to provide utilities to data scientist for quick prototyping of machine learning models. 

Following are guiding principles for this repository:
 1. Easy integration with `pandas`, `sklearn`, `numpy` and `scipy`
 2. Strike a balance between having too much automation and no automation
 
The whole project will be broken down into 3 branches:
  1. Data Preprocessing utitlies:
    * Imputation techniques
    * Column filtering (remove columns with zero variance, all NA's etc)
    * Preprocessing unstructured data (text features)
    * Converting categoricals text data to numerical labels (To be consistent with sklearn)
    
 2. Feature Transformations and Feature engineering:
    * Log, quantile and scale transformations examples
    * Target encoding for Categoricals
    * Aggregation features for categoricals
    * Groupby aggregations
    * Auto selection of interaction features based on shallow random forest
    * Ratio features selection and recommendation
    
 3. Model Selection, hyperparameter tuning and emsembling:
    * Select GBM, Linear model and a MLP and perform bayesian hyper-parameter tuning
    * Train meta-stacker on out of fold results of different models
    
    
 
 
