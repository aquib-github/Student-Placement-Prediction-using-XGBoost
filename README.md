# 🎓 Student Placement Prediction using XGBoost (Internship Project)

This repository contains my **Machine Learning Internship Project** titled **"Student Placement Prediction using XGBoost"**.  
The goal of this project is to predict whether a student will be **Placed** or **Not placed** based on key academic and skill-related features.

---

## 📌 Internship Project Details

- **Domain:** Machine Learning / Data Science  
- **Project Title:** Student Placement Prediction using XGBoost  
- **Intern Name:** Aquib Zakir Ahmad  
- **Internship Program:** IAC Internship Program  
- **Project Duration:** 24-12-2025 to 31-01-2026  
- **Methodology:** Waterfall Model (Requirement → Planning → Design → Development → Testing → Deployment → Closure)

---

## 🎯 Problem Statement

Placement is a major outcome for students and academic institutes.  
However, placement depends on multiple factors like academic performance, communication skills, and technical knowledge.

This project builds a machine learning system that predicts placement status using the dataset features:

- CGPA  
- Speaking Skills  
- ML Knowledge  

---

## 🚀 Key Features Implemented

- Loads **training** and **test** datasets from Excel files  
- Performs preprocessing and data validation  
- Handles missing feature values  
- Handles missing target labels using a helper model (semi-supervised approach)  
- Applies feature scaling using **StandardScaler**  
- Balances the dataset using **SMOTE**  
- Trains an optimized **XGBoost Classifier**  
- Evaluates model using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - Confusion Matrix  
- Predicts placement status for test dataset  
- Exports final predictions into Excel output file  

---

## 🧠 Machine Learning Workflow

1. Load Train and Test datasets  
2. Identify missing placement labels in training data  
3. Fill missing labels using a helper XGBoost model  
4. Prepare final labeled dataset  
5. Train-test split  
6. Feature scaling (StandardScaler)  
7. Class balancing using SMOTE  
8. Train final XGBoost model  
9. Evaluate model performance  
10. Predict on test dataset  
11. Export predictions to Excel  

---

## 🛠️ Tech Stack & Libraries

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Imbalanced-learn (SMOTE)**
- **OpenPyXL** (for Excel input/output)

---

## 📂 Project Structure

```text
Student-Placement-Prediction-XGBoost/
│
├── student_placement_prediction_using_xgboost.py
├── requirements.txt
│
├── 01_train_data.xlsx
├── 02_test_data.xlsx
├── baseline_placement_predictions.xlsx
│
├── docs/
│   ├── Project_Charter.pdf
│   ├── Requirement_Elicitation_Questionnaire.pdf
│   ├── SRS.pdf
│   ├── Project_Schedule.pdf
│   ├── RAID_Log.pdf
│   ├── Lessons_Learnt_Log.pdf
│   ├── Project_Report.pdf
│   ├── WBS.pdf
│
└── README.md
