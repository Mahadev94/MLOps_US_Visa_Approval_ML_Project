# US VISA APPROVAL PREDICTION:

## Project workflows explain to interviewers::
1. Problem statement
2. solution
3. Pipeline walkthrough and code explanation
4. Deployment workflow - tools

## Problem statement.
OFLC(Office of Foreign Labor Certification) gives job certification applications for employers seeking to bring foreign workers into the United States and grants certifications.
As In last year the count of employees were increased so OFLC needs Machine learning models to shortlist visa applicants based on their previous data.

## Solution approach with:
1. Machine learning models: ML classification algorithms
2. Deep learning models: Custom ANN with sigmoid activation Function.
### Solution Proposed with:
we will be using ML:
This model is to check if Visa get approved or not based on the given dataset.
This can be used to Recommend a suitable profile for the applicants for whom the visa should be certified or denied based on the certain criteria which influences the decision.
1. load the data from DB
2. Perform EDA and FE to select the desirable features.
3. fit the ML classification algorithm and find out which one perform better.
4. select top few models and tune hyperparameters.
5. select best model based on desired metrics.
 ----------------------------------------------------------------
 ## how to run:
  conda create -p venv14 python=3.8 -y  
  conda activate venv14  
  pip install -r requirements.txt  
 ## Workflow:
1. constants
2. entity
3. components
4. pipeline
5. Main file

## for FLowchart creation :
https://whimsical.com/

## MLOps Tool:
1. https://www.evidentlyai.com/ --> we are using EvedentlyAI for Data drift.

### Here are some ways to detect data drift:
- Monitor model performance
- Look for significant changes in accuracy or other performance metrics over time.
Check data quality
- Regularly check the quality of the input data for sudden changes in the range or variance of the features. 

### Here are some ways to deal with data drift:
- Retrain the ML model on fresh data
- Perform robust feature engineering
- Use ensemble methods like model blending and stacking
- Build a fully-online machine learning pipeline that can continuously update and retrain itself
- Use synthetic data generators to provide a high-quality, low-friction source of data on which to retrain the ML models 

