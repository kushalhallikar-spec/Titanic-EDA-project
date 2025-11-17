# **Titanic Survival – End-to-End Data Analysis Project**

## **Overview**

This project performs a complete end-to-end Exploratory Data Analysis (EDA) on the Titanic dataset to identify key factors influencing passenger survival. It includes data cleaning, preprocessing, feature engineering, visualizations, and insight extraction using Python. An interactive Tableau dashboard is also included for better interpretation.

## **Objectives**

Clean and prepare the Titanic dataset

Handle missing values and create new features

Perform detailed univariate, bivariate, and multivariate EDA

Generate visual insights using Matplotlib and Seaborn

Build a Tableau dashboard to present findings

Data Cleaning & Feature Engineering

Imputed missing values (Age → mean, Embarked → mode)

Removed duplicates and corrected inconsistent entries


## **Created new features:**

FamilySize = SibSp + Parch + 1

AgeCategory (Children, Adults, Seniors)

Encoded categorical variables where needed

Exploratory Data Analysis

Survival trends by gender, passenger class, and age

Fare distribution analysis

Family size impact on survival

Correlation heatmaps and categorical plots

Visualizations stored in the images/ folder

## **Tableau Dashboard**

View Dashboard:
https://public.tableau.com/app/profile/kushal.hallikar.y/viz/Titanicproject_17633907097590/Dashboard1?publish=yes

## **Repository Structure**
├── README.md
├── requirements.txt
├── Titanic_I_End_to_end_DA_project.ipynb
├── data/
├── images/
└── src/

## **Technologies Used**

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

Tableau Public

## **Key Insights**

Females and children had significantly higher survival rates

1st-class passengers survived more than 2nd/3rd class

Higher fare generally increased survival probability

Smaller families had better survival chances

## **Conclusion**

The project showcases a complete data analysis workflow—from raw data cleaning to visualization and dashboard creation. It demonstrates strong analytical skills and provides meaningful insights into one of the most well-known datasets in the data science domain.
