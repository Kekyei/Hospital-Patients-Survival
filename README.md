# Hospital-Patients-Survival
## Problem Statement
A hospital in the province of Greenland has been trying to improve its care conditions by analyzing the historic survival rates of its patients. However, the hospital has been unable to identify the main factors that contribute to high survival rates. As the best data scientist in Greenland, you have been hired to solve this problem. Your task is to develop a model that can predict the chances of survival of a patient after 1 year of treatment, based on data collected from the hospital.

![Survival](https://user-images.githubusercontent.com/115629197/199121361-2500d032-2944-431b-9791-c8f1eaea5ac0.png)

## Objective
The objective of this project is to develop a model that can predict the chances of survival of a patient after 1 year of treatment, based on data collected from a hospital in Greenland. The target variable, "Survived_1_year" can take on binary values of either 0 or 1, with a value of 0 indicating that the patient did not survive after 1 year of treatment and a value of 1 indicating that the patient did survive after 1 year of treatment.

This project is the final assignment of a data science bootcamp and it evaluates my skills and knowledge as a data scientist.

## Evaluation Criteria
Submissions for this project will be evaluated using the F1 Score. This score is calculated by comparing the true values of the target variable with the predictions generated by the model on the evaluation dataset. The true values of the target variable are not provided, and the F1 Score is used to evaluate the performance of the model on the evaluation data.

## Data Description
The dataset for this project contains patient records from the hospital in Greenland and includes the following fields:

- ID_Patient_Care_Situation: Care situation of the patient during treatment
- Diagnosed_Condition: The diagnosed condition of the patient
- ID_Patient: Patient identifier number
- Treatment_with_drugs: Class of drugs used during treatment
- Survived_1_year: If the patient survived after one year (0 means did not survive; 1 means survived)
- Patient_Age: Age of the patient
- Patient_Body_Mass_Index: A calculated value based on the patient???s weight, height, etc.
- Patient_Smoker: If the patient was a smoker or not
- Patient_Rural_Urban: If the patient stayed in Rural or Urban part of the country
Previous_Condition: Condition of the patient before the start of the treatment (This variable is split into 8 columns - A, B, C, D, E, F, Z and Number_of_prev_cond. A, B, C, D, E, F and Z represent previous conditions of the patient. For example, if the entry in column A is 1, it means that the patient had a previous condition of A. If the patient did not have that condition, the value is 0. 
- The Number_of_prev_cond column represents the total number of previous conditions the patient had.

## Resources
- Training data: https://raw.githubusercontent.com/dphi-official/Datasets/master/pharma_data/Training_set_begs.csv
- Test data: https://raw.githubusercontent.com/dphi-official/Datasets/master/pharma_data/Testing_set_begs.csv
- Sample submission: https://raw.githubusercontent.com/dphi-official/Datasets/master/pharma_data/Sample_submission_begs.csv

## Submission guidelines
Your predictions file is a CSV and its first row (i.e., the header field) is "prediction".
I uploaded the .ipynb notebook file as a solution to the question.

## Evaluation Metric
The F1Score evaluation metric will be used to evaluate the model predictions.


