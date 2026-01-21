# 🚢 Titanic Survival Analysis

An exploratory data analysis (EDA) and machine learning project on the famous
**Titanic dataset**, aimed at understanding what factors influenced passenger
survival and building models to predict survival outcomes.

This project combines data cleaning, visualization, statistical reasoning,
and machine learning.

---

## 📌 Project Objective

To answer questions like:

- Who was more likely to survive the Titanic disaster?
- How did class, gender, age, and family size affect survival?
- Can we build a model to predict survival accurately?

---

## 📁 Dataset

Source: Kaggle Titanic Dataset

Features include:
- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Family size (SibSp, Parch)
- Embarkation port
- Survival label (target)

---

## 🛠 Key Steps in the Analysis

### 1. Data Cleaning
- Handled missing values (Age, Embarked, Cabin)
- Converted data types
- Created new features:
  - FamilySize
  - IsAlone

---

### 2. Exploratory Data Analysis

Key visual insights:

- Females had much higher survival rate than males  
- 1st class passengers survived more than 2nd and 3rd class  
- Children had better survival chances than adults  
- Passengers traveling alone had lower survival probability  

Used:
- Bar plots
- Histograms
- Grouped statistics
- Correlation analysis

---

### 3. Feature Engineering

Created meaningful features:
- FamilySize = SibSp + Parch + 1  
- IsAlone = whether passenger traveled alone  
- Encoded categorical variables  

---

### 4. Model Building

Models trained:

- Logistic Regression  
- Random Forest / Decision Tree (if used in notebook)  

Steps:
- Train-test split  
- Feature scaling where needed  
- Model fitting  
- Prediction on test set  

---

### 5. Model Evaluation

Metrics used:
- Accuracy  
- Confusion Matrix  
- Classification Report  

Results show that survival can be predicted reasonably well using demographic
and travel features.

---

## 📊 Key Insights

- Gender was the strongest survival factor  
- Passenger class strongly affected survival  
- Family size had a non-linear effect  
- Fare correlated with class and survival  
- Alone passengers were less likely to survive  

---

## 🌐 Project Report

A full HTML report is available here:

👉 https://akashkolte.github.io/titanic_survival_dataset_analysis/survival_analysis_on_titanic_report.html

---

## 📦 How to Run

git clone https://github.com/akashkolte/titanic_survival_dataset_analysis.git

jupyter notebook Survival_Analysis_on_Titanic.ipynb
or run in Google Colab

📌 Skills Demonstrated
	•	Data Cleaning & Preprocessing
	•	Exploratory Data Analysis
	•	Feature Engineering
	•	Classification Models
	•	Model Evaluation
	•	Visualization


❤️ Author

Akash Kolte
MS in Computer Science (AI/ML) – SUNY Buffalo
GitHub: https://github.com/akashkolte
LinkedIn: https://linkedin.com/in/akash-kolte

🚀 Future Improvements
	•	Hyperparameter tuning
	•	Cross-validation
	•	Feature importance analysis
	•	Deployment as a web app
