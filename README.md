# Diabetes Prediction 🩺🩸

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-informational)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)


This project focuses on building a **machine learning model** to predict whether a person has diabetes based on medical and demographic data.

The project includes **data preprocessing**, **exploratory data analysis (EDA)**, **model training**, and **model evaluation**.

---

## 📂 Project Structure

- `Diabetes_Prediction.ipynb`: Jupyter Notebook containing the complete workflow — data loading, cleaning, analysis, modeling, and evaluation.
- `diabetes.csv`: Dataset containing patient health information and diabetes diagnosis labels.

---

## 🗃️ Dataset Overview

The dataset (`diabetes.csv`) includes the following features:

| Column Name | Description |
|:------------|:------------|
| `Pregnancies` | Number of times pregnant |
| `Glucose` | Plasma glucose concentration |
| `BloodPressure` | Diastolic blood pressure (mm Hg) |
| `SkinThickness` | Triceps skinfold thickness (mm) |
| `Insulin` | 2-Hour serum insulin (mu U/ml) |
| `BMI` | Body Mass Index (weight in kg/(height in m)^2) |
| `DiabetesPedigreeFunction` | Diabetes pedigree function |
| `Age` | Age (years) |
| `Outcome` | Class variable (0: No diabetes, 1: Diabetes) |

---

## 🔎 Project Highlights

- **Data Preprocessing:**
  - Handled missing or unrealistic values.
  - Normalized/standardized features where necessary.

- **Exploratory Data Analysis (EDA):**
  - Explored feature distributions and correlations.
  - Visualized the relationship between features and diabetes outcome.

- **Model Building:**
  - Built models using **Logistic Regression**, **Random Forest**, and other classifiers.
  - Evaluated models using **accuracy**, **confusion matrix**, **precision**, **recall**, and **F1-score**.

- **Optimization:**
  - Used techniques like cross-validation and hyperparameter tuning.

---

## 📊 Results

- Achieved a predictive accuracy of 78%.
- Identified **glucose levels**, **BMI**, and **age** as critical predictors for diabetes diagnosis.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/CraigDaGama/Diabetes-Prediction.git
   cd Diabetes_Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Diabetes_Prediction.ipynb
   ```

4. Run all cells to reproduce the analysis and predictions.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---




