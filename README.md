# One-Way ANOVA Analysis on Diabetes Datasets

This project performs **one-way ANOVA (Analysis of Variance)** to compare numerical features between:
- **UCI Diabetes dataset** (`uci_diabetes.csv`)
- **Pima Indians Diabetes dataset** (`pmi_diabetes.csv`)

## 📌 Features
- Load datasets using **Pandas**
- Select relevant numerical columns:
  - Glucose
  - BloodPressure
  - BMI
- Perform one-way ANOVA tests for each feature
- Generate a summary table of F-statistics and P-values

## 🚀 Usage
1. Place `uci_diabetes.csv` and `pmi_diabetes.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
