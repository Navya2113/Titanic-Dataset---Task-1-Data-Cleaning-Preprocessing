# Titanic-Dataset---Task-1-Data-Cleaning-Preprocessing
This repository contains my submission for Task 1 of the AI &amp; ML Internship Program. The notebook demonstrates basic data preprocessing steps including handling missing values, encoding categorical variables, normalizing features, and outlier removal using the Titanic dataset.  
# 🧹 Task 1: Data Cleaning & Preprocessing - Titanic Dataset

This project demonstrates basic data cleaning and preprocessing steps using the Titanic dataset from Kaggle.

## 🔧 Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib


## 📦 Dataset
We used the Titanic dataset from [Data Science Dojo’s GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

## 🚀 Steps Performed

1. **Imported the dataset** and explored its structure.
2. **Handled missing values**:
   - Filled `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped `Cabin` (too many missing values).
3. **Encoded categorical features** using one-hot encoding.
4. **Standardized numerical features** like `Age` and `Fare`.
5. **Visualized outliers** using boxplots and removed them using IQR.

## 📊 Output
The cleaned DataFrame is ready for machine learning model input, with no missing values, normalized features, and no extreme outliers in `Fare`.

---

## 📁 Files Included
- `task1_titanic_preprocessing.ipynb` – Jupyter notebook with full code and explanations.
- `README.md` – This file.

## 📝 Submission
Upload the notebook and README to your GitHub repository and submit the link as instructed.

