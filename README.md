# KKBOX-Churn-Prediction

Group project for the course 2487_A-Machine Learning TA-2122_S2.

KKBOX is Asia’s leading music streaming service, holding the world’s most comprehensive Asia-Pop music library with over 30 million tracks. They offer a generous, unlimited version of their service to millions of people, supported by advertising and paid subscriptions. This delicate model is dependent on accurately predicting churn of their paid users.

Can you predict whether a user will churn after his/her subscription expires?

 Data available at https://www.kaggle.com/qmdo97/kkboxdataset
 
 ## Workflow
 
 [**Data Understanding:**](kkbox_data_understanding.ipynb)
 *Analysis of available data files and attribute structure and processing into one file to continue with*
 
 [**Data Processing & Modelling:**](kkbox_machine_learning.ipynb)
 *First version of data pre-processing and fitting Decision Tree model (already 0.93 accuracy)*
 
 
 ## To-Do's
 
 - [ ] Describe **business case** situation and our approach to create value through machine learning - Arabella
 
 - [ ] Conduct **exploratory data analysis** (summary stats, correlations, distributions, outlier detection, missing value detection <- partly done) - Kevin
 
 **Pre-Processing:**
 
 - [ ] Implement **feature selection** methods and test if we get better model

 - [ ] Expand on pre-processing methods (feature scaling?, dimensionality reduction? ...) - Fynn

**Modelling: - Farouq**

 - [ ] Logistic Regression

 - [ ] Lasso Regression
 
 - [ ] Ridge Regression
 
 - [ ] Support Vector Machines
 
 - [ ] Naive Bayes
 
 - [ ] Neural Network
 
**Validation:**
 
 - [ ] Analyse business case and appropriate data validation procedure (accuracy, precision, recall, other) --> *shouldnt be too hard, probably just accuracy* - Arabella & Fynn

**Overall Process:**

 - [ ] Set up pipeline (put all code parts starting from pre-processing into pipeline elements so that we can put them as blocks in and out of pipeline to find the best configuration) --> *probably a looot of work* - Vaz & Fynn
 
 - [ ] Run code with different configurations of pre-processing steps and models and evaluate which one works best --> *the fun part once everything works* - Vaz
