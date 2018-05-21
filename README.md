# EasyLearn
This repository is for EasyLearn, a framework to automate repeatable parts of machine learning.

This initiative was started @Happiest Minds for automating Machine Learning

**The idea behind this project is to provide utilities to data scientist for quick prototyping of machine learning models. The utilities should provide varying levels of automation from generating single model in one command to having function transformation of a column in data.**

Following are guiding principles for this repository:
 1. Easy integration with `pandas`, `sklearn`, `numpy` and `scipy`
 2. Strike a balance between having too much automation and no automation
 
The whole project will be broken down into 3 folder:
 1. **data_preprocessing_utils**:
    Some examples of modules in this category are:
    * Imputation techniques
    * Column filtering (remove columns with zero variance, all NA's etc)
    * Preprocessing unstructured data (text features)
    * Converting categoricals text data to numerical labels (To be consistent with sklearn)
    
 2. **feature_engineering**
    Some examples of modules in this category are:
    * Log, quantile and scale transformations examples
    * Target encoding for Categoricals
    * Aggregation features for categoricals
    * Groupby aggregations
    * Auto selection of interaction features based on shallow random forest
    * Ratio features selection and recommendation
    
 3. **model_selection_ensemble**:
    Some examples of modules in this category are:
    * Select GBM, Linear model and a MLP and perform bayesian hyper-parameter tuning
    * Train meta-stacker on out of fold results of different models
    
The master will contain end-to-end modules
    
For python scripting guidelines, please follow this link:
https://www.python.org/dev/peps/pep-0008/

Always run pylint on your code before you commit. It will help others benefit from your code.
For guidelines specific to each section, refer to guidelines in that folder.

*Coming Soon: A repository with examples of where EasyLearn has been used*

 
 
