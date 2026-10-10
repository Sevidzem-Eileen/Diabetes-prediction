
# Diabetes Prediction Using Machine Learning

## Project Overview
Diabetes is a chronic metabolic condition that develop slowly and may remain undiagnosed for a long period of time. Identifying associated factors can help improve understanding of individuals who may be at risk.
This project explores the use of health indicators
to predict diabetes status using statistical
analysis and machine learning techniques.

## Objectives
- Clean and explore the dataset.
- Investigate relationships between health
  indicators and diabetes status.
- Develop a logistic regression model.
- Evaluate model performance using appropriate
  classification metrics.

## Overall workflow
- Data cleaning and preprocessing
- Data description
- Exploratory data analysis
- Logistic regression
- Cross-validation
- Model evalution
- Feature importance
## Data set source 

 [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)



## Variable description
Number of participants: 768
Age-Age of participant
Glucose-Plasma glucose level
Insulin-Insulin level
Pregnancies-Number of pregnancies
BMI-Body mass index
BloodPressure-Blood pressure
Skin thickness- triceps skin thickness
Diabetes pedigree function- 
Diabetes-Diabetes status, 500 positive, 268 negative cases

                                                               
## Prerequisite Tools
- R
- RStudio
- Rmarkdown

## Methods

1. The analysis consisted of:
Data importing the data in the R studio and loading libraries
2. Data cleaning 
Ensure correct dataset structure, standardize column names, and handle missing values
3. Description of data-statistical properties
4. Exploration of data
- Outcome distribution
- Feature distribution
- Distribution of variables between outcome groups
- Correlation between variables.
5. Data preparation
 Prepare dataset for machine learning by processing relevant target values.
6. Model training
Logistic regression, cross validation and pruning
7. Model evaluation
Test the model on a new dataset
Analysis of ROC-AUC
8. Explore important features 

## Results 
The notebook contains experimemts, experimental results and visualisations

## Limitations
- The analysis is based on an existing dataset and therefore depends on the quality of the original data.
- Missing or implausible values may affect the accuracy and reliability of the analysis and model predictions
- The models show predictive associations and should not be interpreted as establishing causation.
- External validation using an independent dataset was not performed.

## Conclusion
Further work could include comparing alternative classification algorithms, refining predictor selection, and validating the model on independent datasets.

## Project Status
Ongoing.