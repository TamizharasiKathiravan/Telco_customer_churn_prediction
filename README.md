# 📊 Customer Churn – Data Preprocessing  
This repository contains data preprocessing steps for the **Telco Customer Churn dataset**. Preprocessing ensures data quality and prepares features for machine learning models.  
## ⚡ Steps Done  
- Converted **TotalCharges** column to numeric:  
  ```python
  df["TotalCharges"] = pd.to_numeric(df["TotalCharges"], errors='coerce')
Filled missing values with the median:

df["TotalCharges"] = df["TotalCharges"].fillna(df["TotalCharges"].median())


Cleaned categorical features and removed duplicates.

📘 Usage

Clone the repo:

git clone https://github.com/your-username/churn-preprocessing.git
cd churn-preprocessing


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook or Python script:

jupyter notebook preprocessing.ipynb

or

python preprocess.py

📊 Dataset

The dataset used is Telco Customer Churn (publicly available on Kaggle).
