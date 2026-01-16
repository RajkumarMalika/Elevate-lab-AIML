# Elevate-lab-AIML
# 📊 Dataset Analysis Using Pandas (Titanic & Students Performance)

 ## 📌 Project Overview

This project focuses on exploratory data analysis (EDA) of two popular datasets using Python and Pandas.
The goal is to understand the structure, features, data quality, and machine learning suitability of each dataset.

## Datasets Used:

Titanic Dataset

Students Performance Dataset

## 🛠️ Tools & Libraries

Python 3

Pandas

Jupyter Notebook 

# 📂 Datasets Description
## 1️⃣ Titanic Dataset

The Titanic dataset contains information about passengers who traveled on the Titanic and whether they survived.

## Key Columns:

Pclass – Passenger class (1st, 2nd, 3rd)

Sex – Gender of passenger

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation

Cabin – Cabin number

Survived – Target variable (0 = No, 1 = Yes)

ML Problem Type: Classification
Dataset Size: 891 rows × 12 columns

# 2️⃣ Students Performance Dataset

This dataset contains academic performance details of students along with demographic information.

## Key Columns:

gender

race/ethnicity

parental level of education

lunch

test preparation course

math score

reading score

writing score

ML Problem Type: Regression / Classification
Dataset Size: 1000 rows × 8 columns

# 🔍 Analysis Steps Followed
## 1. Load Dataset

Loaded datasets using pandas.read_csv()

Displayed first and last few records to understand structure

## 2. Feature Identification

Identified:

Numerical features

Categorical features

Ordinal features

Binary features

## 3. Dataset Structure & Statistics

Used:

df.info() → data types & missing values

df.describe() → statistical summary

4. Categorical Value Analysis

Checked unique values using unique()

Analyzed data distribution

## 5. Target Variable Identification

Titanic: Survived

Students: math score, reading score, writing score

## 6. ML Suitability Analysis

Checked dataset size using df.shape

Determined suitability for machine learning models

## 7. Data Quality Observations

Missing values

Class imbalance

Encoding requirements

Outliers

# 📈 Key Observations
## Titanic Dataset

Missing values in Age and Cabin

Cabin column has many null values

Survival is imbalanced

Fare contains outliers

Suitable for classification models

Students Performance Dataset

No missing values

Clean and balanced dataset

Categorical features require encoding

Suitable for regression and classification

# 📌 Cabin & Deck Insight (Titanic)

First letter of Cabin indicates deck level (A–G)

Higher decks (A, B, C) had better survival chances

Lower decks (F, G) had lower survival rates
