# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

The goal of the task was to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle, and identify key patterns and relationships.

## 📌 Task Description

Perform data cleaning and EDA on a dataset of your choice, such as the Titanic dataset. Explore the relationships between variables and identify patterns and trends in the data.

## 📂 Dataset

- [Titanic: Machine Learning from Disaster - Kaggle](https://www.kaggle.com/c/titanic/data)

## 🛠️ Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Warnings (to suppress future warnings)
- OS (for file access)

## ✅ Key Steps Performed

1. **Data Loading & Inspection**
   - Loaded train and test datasets.
   - Displayed first few records and structure.

2. **Data Cleaning**
   - Removed duplicates.
   - Filled missing values in `Age`, `Embarked`, and `Fare`.
   - Dropped the `Cabin` column.
   - Converted data types for better processing.

3. **Feature Engineering**
   - Created `Member` (SibSp + Parch + 1).
   - Derived `Alone` status.
   - Extracted `Title` from the `Name`.
   - Created `AgeBin` and `FareBin` using binning.

4. **Exploratory Data Analysis**
   - Plotted distributions using histograms and bar plots.
   - Visualized survival rates by:
     - Gender
     - Passenger class
     - Alone status
     - Age group
     - Fare group
     - Titles
   - Created a pie chart for passenger distribution by gender.

## 📊 Visualizations

All plots were generated using Seaborn and Matplotlib to observe trends and relationships among variables.

## 🔗 Project Link

[GitHub Repository](https://github.com/SanKrishnan/Prodigy_DS_02)
