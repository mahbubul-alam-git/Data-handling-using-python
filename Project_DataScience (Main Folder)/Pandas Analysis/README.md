# 🚢 Titanic Data Analysis & Feature Engineering

## 📌 Project Overview
This project demonstrates a comprehensive Exploratory Data Analysis (EDA), data cleaning, and feature engineering pipeline using the classic Titanic dataset. The goal of this repository is to showcase proficiency in data manipulation, statistical analysis, and preparing raw data for Machine Learning models using Python and Pandas.

## 🛠️ Skills Demonstrated
Based on the scripts in this repository, the following data science techniques were applied:

### 1. Exploratory Data Analysis (EDA)
* Extracted high-level statistical summaries using `.info()` and `.describe()`.
* Sliced and filtered data based on complex, multi-conditional logic (e.g., identifying female passengers over 30, or 1st-class passengers who did not survive).
* Analyzed categorical distributions and survival rates.

### 2. Data Cleaning
* Identified and handled missing values across multiple columns.
* Imputed missing `Age` values using the median.
* Filled missing categorical data in `Embarked` with the mode.
* Dropped columns with excessive missing data (e.g., `Cabin`) to maintain data integrity.

### 3. Feature Engineering & Manipulation
* **Text Extraction:** Used Regular Expressions (Regex) to extract passenger titles (Mr., Mrs., Miss) from the `Name` column.
* **Variable Creation:** Engineered a new `FamilySize` feature by combining sibling/spouse and parent/child counts.
* **Categorical Encoding:** Applied One-Hot Encoding (`pd.get_dummies`) and binary mapping to prepare categorical variables for machine learning.
* **Relational Operations:** Demonstrated SQL-like operations in Pandas by merging DataFrames (`pd.merge`) on common keys.

### 4. Statistical Outlier Detection
* Applied the **Interquartile Range (IQR)** method to detect and isolate statistical outliers in the `Fare` column.
* Established dynamic upper and lower boundaries to cleanly separate anomalies from the main dataset.

## 💻 Technologies Used
* **Language:** Python
* **Library:** Pandas (for all data manipulation, aggregation, and statistical analysis)

## 🚀 How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have Python and Pandas installed (`pip install pandas`).
3. Download the `Titanic-Dataset.csv` file and place it in the root directory.
4. Run the Jupyter Notebook or Python scripts to view the step-by-step analysis.