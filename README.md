# 🫀 Heart Disease Predictor

This project aims to predict the likelihood of heart disease in patients using a dataset of anonymized health indicators. Multiple machine learning models were developed, trained, and evaluated to identify the most effective approach for this classification task.

## 📌 Project Objectives

- Load and explore patient health data.
- Build and evaluate multiple machine learning models:
  - Random Forest
  - Logistic Regression
  - Gradient Boosting (XGBoost)
  - Neural Networks (TensorFlow/Keras)
- Compare model performance using cross-validation, accuracy, sensitivity, specificity, and MCC.
- Feature selection and optimization for improved performance.

## 🧠 Models Compared

| Model               | Accuracy | Sensitivity | Specificity | MCC    |
|--------------------|----------|-------------|-------------|--------|
| Random Forest       | 98.5%    | 97.1%       | 100%        | 0.971  |
| Logistic Regression | 79.5%    | 87.4%       | 71.6%       | 0.597  |
| XGBoost             | 98.5%    | 97.1%       | 100%        | 0.971  |
| Neural Network      | 95.6%    | 92.2%       | 91.5%       | 0.93+  |

> *Metrics may vary slightly based on data splits.*

## 📂 Dataset

- The dataset contains 14 attributes related to patient health including:
  - Age, Sex, Chest Pain Type (`cp`)
  - Resting Blood Pressure (`trestbps`)
  - Cholesterol, Fasting Blood Sugar (`fbs`)
  - ECG results, Maximum Heart Rate (`thalach`)
  - Exercise-induced Angina, ST Depression (`oldpeak`)
  - Slope, Major Vessels (`ca`), Thalassemia (`thal`)
- Target: Presence of heart disease (1 = Yes, 0 = No)

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/HunterRSloan/Heart-Disease-Predictor.git
   cd Heart-Disease-Predictor

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run Notebook

   Open notebooks/SEProject.ipynb in Jupyter or Colab.

📈 Visualizations & Feature Importance

- Feature importance plots
- Training/validation accuracy/loss graphs (Neural Net)
- Confusion matrices per model

🧪 Evaluation Metrics

- Accuracy: Correct predictions
- Sensitivity: Correctly predicted positive cases
- Specificity: Correctly predicted negative cases
- MCC: Balanced measure even for imbalanced datasets

📘 Future Work

- Deploy the best model via Flask or Streamlit
- Add visual dashboard for patient likelihood
- Explore SHAP for model explainability

📄 License

- MIT License
