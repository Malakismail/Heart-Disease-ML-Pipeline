# Heart-Disease-ML-Pipeline
# 🫀 Heart Disease Prediction using Machine Learning

This project builds a machine learning pipeline to predict the presence of heart disease using the UCI Heart Disease dataset. It covers data preprocessing, model training, evaluation, and performance comparison across multiple algorithms.

## 📊 Dataset

The dataset used in this project comes from the "https://archive.ics.uci.edu/ml/datasets/heart+Disease".
It contains patient medical records and diagnostic results to determine the presence of heart disease.

- **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, etc.
- **Target:** Presence (1) or absence (0) of heart disease.

## 🧪 Project Structure
data/
│ ├── heart_disease.csv
│── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_pca_analysis.ipynb
│ ├── 03_feature_selection.ipynb
│ ├── 04_supervised_learning.ipynb
│ ├── 05_unsupervised_learning.ipynb
│ ├── 06_hyperparameter_tuning.ipynb
│── models/
│ ├── final_model.pkl
│── ui/
│ ├── app.py (Streamlit UI)
│── deployment/
│ ├── ngrok_setup.txt
│── results/
│ ├── evaluation_metrics.txt


## 🔧 Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn** – ML models, preprocessing, and metrics
- **Matplotlib, Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive development

## 🧠 Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine
