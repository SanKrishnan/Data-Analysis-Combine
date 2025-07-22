## 📌 Project Title: Customer Subscription Prediction using Decision Tree

This project aims to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data. The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

---

## 📊 Dataset Description

- **Source:** UCI Machine Learning Repository  
- **Format:** CSV (semicolon-separated)  
- **Target Variable:** `y` (yes/no) – whether the client subscribed to a term deposit  
- **Features:** Age, Job, Marital Status, Education, Default, Balance, Housing, Loan, Contact, Day, Month, Duration, Campaign, Pdays, Previous, Poutcome

---

## 🧠 Steps Performed

1. **Data Loading and Exploration**  
   - Used `pandas` to load and preview data  
   - Analyzed target distribution using `seaborn` countplot

2. **Preprocessing**  
   - Encoded categorical features using `LabelEncoder`  
   - Split the dataset using `train_test_split` with stratification

3. **Model Building**  
   - Trained a `DecisionTreeClassifier` from `sklearn`  
   - Evaluated the model with `accuracy_score` and `classification_report`

4. **Feature Importance**  
   - Visualized important features contributing to the prediction  
   - Identified key drivers such as job, contact type, and call duration

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn

---

## 📁 Output

- Trained Decision Tree model  
- Classification report with precision, recall, and F1-score  
- Feature importance bar chart  
- Insights on customer behavior patterns

---


## 📬 Contact

Feel free to connect or reach out if you'd like to collaborate or provide feedback!

---
