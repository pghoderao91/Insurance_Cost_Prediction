# Insurance_Cost_Prediction

## Introduction 
Insurance companies rely on accurate predictions of healthcare expenses to set premiums that cover potential claims while ensuring profitability. Since healthcare costs vary widely due to individual health factors, lifestyle, and medical history, creating a reliable prediction model is complex but essential. This project, "Healthcare Expense Prediction for Insurance Premium Optimization," aims to apply machine learning algorithms to forecast healthcare costs. By improving cost predictions, insurance providers can set fair premiums, better manage financial risk, and support sustainable operations.

## Bussiness Goal 
To develop a predictive model for healthcare expenses that enables insurance companies to set premiums accurately, ensuring profitability while covering potential costs.

## Task : Regression Problem

## Domain Analysis

First understand the menaing of feature and checking the impact of input feature to dependant feature

1]age: age of primary beneficiary

2]sex: insurance contractor gender, female, male

3]Bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

4]children: Number of children covered by health insurance / Number of dependents

5]smoker: Smoking

6]region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

7]charges: Individual medical costs billed by health insurance


## DATA PREPROCESSING AND FEATURE ENGINNERING:

1.	MISSING VALUE:
•	In this data no missing value is present.

2.	CATEGORICAL DATA:
•	There were 3 categorical column we have perfomed Manual and Frequency encoding on it.

3.	OUTLIER HANDLING:
• In this data the outlier were not handle data quality may get distributed 

4.	FEATURE SCALING:
 •   No scaling was done has it has distrubted the quality of data

## FEATURE SELECTION:

1.	DROP UNIQUE AND CONSTANT COLUMN:
•	In this data only one unique column is present

2.	CHECK THE CORRELATION:
•	In this data no highly correlated feature is present

3.	CHECK DUPLICATES:
•	There is no duplicates present in data

## MODEL CREATION AND SELECTION:

###  OBSERVATION:
Conclusion

1] Linear Regression R2_score = 0.74

2] Random Forest Regressor R2_Score = 0.84

3] Gradient Boosting Regressor R2_Score = 0.86

The Linear Regression model achieved an R² score of 0.74, indicating a moderate fit to the data.

The Random Forest Regressor performed better with an R² score of 0.84, demonstrating stronger predictive power.

The Gradient Boosting Regressor outperformed both models, achieving the highest R² score of 0.86, making it the most accurate for this dataset.
