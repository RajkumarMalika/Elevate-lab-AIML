# 📊 Task 2: Data Cleaning & Missing Value Handling
## 📌 Objective

The objective of this task is to gain hands-on experience in data preprocessing by identifying, visualizing, and handling missing values in real-world datasets using Python (Pandas, NumPy).

### 🛠 Tools & Technologies

Programming Language: Python

Libraries Used:

Pandas

NumPy

Matplotlib (for visualization)

Environment: Jupyter Notebook /  VS Code

📂 Datasets Used

## Housing Prices Dataset

File: housing_prices.csv

## Medical Appointment No Shows Dataset

File: medical_appointment.csv

Both datasets contain intentional missing values for practicing data cleaning techniques.

# 🧪 Task Workflow
## 1️⃣ Load Dataset

Load the CSV files using Pandas

Display first and last few rows to understand structure

import pandas as pd
df = pd.read_csv("dataset.csv")
df.head()

## 2️⃣ Identify Missing Values

Detect missing values using:

df.isnull().sum()

## 3️⃣ Visualize Missing Data

Plot bar charts to understand missing value distribution across columns

df.isnull().sum().plot(kind='bar')

## 4️⃣ Handle Missing Values

Numerical Columns:

Filled using mean or median

Categorical Columns:

Filled using mode

High Missing Columns:

Dropped if missing values exceed a defined threshold (e.g., 40%)

## 5️⃣ Validate Cleaned Dataset

Ensure no unwanted missing values remain

Verify dataset shape and consistency

df.isnull().sum()

## 6️⃣ Compare Before vs After

Compare dataset size and quality before and after cleaning

print("Before:", raw_df.shape)
print("After:", cleaned_df.shape)

## 7️⃣ Save Cleaned Dataset

Export the cleaned dataset as a new CSV file

df.to_csv("cleaned_dataset.csv", index=False)

# 📦 Deliverables

✔ Cleaned CSV datasets

✔ Jupyter Notebook with step-by-step preprocessing

✔ README file explaining task workflow

# 🎯 Final Outcome

By completing this task, the intern gains:

Practical understanding of data preprocessing

Experience handling missing values

Confidence working with real-world datasets

Industry-relevant data cleaning skills