# HEART DISEASE PREDICTION

## Description 
### Introduction
World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This project intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk.

### Problem
The dataset is from a cardiovascular study on residents of the town of Framingham, Massachusetts. The goal (objective) is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

### Features
- Sex: male or female(Nominal)
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
- Current Smoker: whether or not the patient is a current smoker (Nominal)
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette).
- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)
- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous)
- Dia BP: diastolic blood pressure (Continuous)
- BMI: Body Mass Index (Continuous)
- Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
- Glucose: glucose level (Continuous)
- 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

## Tasks
1. Perform Exploratory Data Analysis
1. Preprocess the data to make it ready for model building (encode categorical features, standardize or normalize numerical features, handle missing values, etc).
1. Identify the type of machine learning this project falls under briefly explain it in your own words (In your report).
1. Build and train model to predict whether or not a patient has a 10-year risk factor of heart diseases.
1. Predict the heart disease risk of patients.
1. Check the performance of the model using various metrics familiar to you (perform hyperparameter tuning if necessary).
1. Write a brief report (no more than 5 pages) of your project. The report should at least include
    - a brief description of the dataset used
    - a brief overview of the machine learning algorithm used
    - a brief overview of the metrics used to evaluate the performance of the model and what they mean
    - results and interpretation
    


## References
[Heart Disease](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)