Medical Insurance Cost Analysis and Prediction System
Abstract

Health insurance companies manage large amounts of customer information, including age, gender, BMI, number of children, smoking habits, region, and insurance charges. Estimating insurance premiums manually is difficult and may lead to inaccurate premium calculations, poor risk assessment, and inefficient decision-making. This project aims to analyze medical insurance data using Exploratory Data Analysis (EDA) and Machine Learning techniques. Linear Regression, Multiple Linear Regression, and Logistic Regression models are used to predict insurance costs and classify customers based on risk levels. Interactive visualizations and dashboards help insurance providers understand customer behavior and make data-driven decisions.
Introduction

Medical insurance plays a vital role in protecting individuals from healthcare expenses. Insurance companies must accurately estimate premiums to maintain profitability while ensuring fairness to customers. Various factors such as age, BMI, smoking status, and family size significantly influence medical costs.

This project uses the Medical Cost Personal Dataset from Kaggle to analyze customer information and predict insurance charges. The system automates insurance cost estimation and risk classification using machine learning techniques.
Problem Statement

Health insurance companies collect large volumes of customer data, including age, gender, body mass index (BMI), number of children, smoking habits, region, and insurance charges. Analyzing this information manually to estimate insurance costs and identify high-risk customers is difficult, time-consuming, and prone to errors.

Incorrect premium estimation can result in:

  Financial losses for insurance companies
    Unfair premium charges for customers
    Poor risk assessment and policy planning
    Inefficient decision-making in the insurance sector

Therefore, an automated system is required to analyze customer information, identify factors affecting insurance costs, and predict future insurance charges.
Objectives

  Perform Exploratory Data Analysis (EDA)
    Analyze factors affecting insurance charges
    Build Linear Regression models for prediction
    Build Multiple Linear Regression models using multiple features
    Classify customers using Logistic Regression
    Identify high-risk customers
    Create interactive dashboards for business insights
    Support data-driven premium estimation

Features:

   age : Age of customer
    sex : Gender
    bmi : Body Mass Index
    children : Number of dependents
    smoker : Smoking status
    region : Residential region
    charges : Medical insurance charges

Number of Records: 1338

Number of Features: 7
Methodology
Phase 1: Data Collection

The insurance dataset is loaded from Kaggle. Dataset structure and features are examined to understand customer demographics and insurance information.
Phase 2: Data Cleaning and Preprocessing

The following preprocessing operations are performed:

  Missing value detection
    Duplicate removal
    Data type verification
    Label Encoding of categorical variables
    Feature preparation for machine learning

Phase 3: Exploratory Data Analysis

EDA helps understand customer characteristics and insurance charge patterns.

Analysis includes:

  Average age
    Average BMI
    Average insurance charges
    Average number of children

Group-based comparisons:

  Smokers vs Non-Smokers
    Male vs Female
    Different Regions
    Different BMI Categories

Phase 4: Visualization

Several visualizations are created:
<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/9250a5fa-4bc1-479d-b158-30aa087f9b24" />
<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/717c73aa-db1c-4501-819c-a7361cb940ce" />
<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/d4fceb58-6a16-46ee-a25f-9a6bb04a8caa" />
<img width="713" height="470" alt="image" src="https://github.com/user-attachments/assets/870df15a-262b-4abe-acfc-1bd794b1a6b3" />
<img width="713" height="470" alt="image" src="https://github.com/user-attachments/assets/2ce3b2a3-224c-404b-81f7-2dda206c217e" />
<img width="713" height="470" alt="image" src="https://github.com/user-attachments/assets/a8b425d8-b9dc-4fdd-a638-d200b7adb78b" />
<img width="713" height="470" alt="image" src="https://github.com/user-attachments/assets/a202754f-04a5-465e-b70c-1af80adc28ff" />
<img width="757" height="528" alt="image" src="https://github.com/user-attachments/assets/a89dbe54-e9a3-49ae-912d-872be54d0285" />
