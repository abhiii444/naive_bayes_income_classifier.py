# naive_bayes_income_classifier.py
Income prediction using Naive Bayes Classification on the Adult Census dataset. The project includes data cleaning, categorical feature handling, encoding, feature scaling, model training, and performance evaluation.
#  Income Prediction using Naive Bayes Classifier

This project implements a **Naive Bayes Classification model** to predict whether a person earns **more than or less than $50K per year** using the **Adult Census Income Dataset**.

The project demonstrates a complete machine learning workflow including data preprocessing, handling categorical variables, feature scaling, model training, and evaluation.

---

##  Project Overview

- Predicts income category using demographic and employment data
- Handles missing values and categorical features
- Uses **Gaussian Naive Bayes** for classification
- Evaluates model performance using accuracy, confusion matrix, and classification report

---

##  Dataset

- **Adult Census Income Dataset**
- Target variable: `income`
  - `<=50K`
  - `>50K`
- Contains both **categorical** and **numerical** features

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Category Encoders

---

##  Project Workflow

1. Load Dataset
2. Assign Column Names
3. Identify Categorical and Numerical Variables
4. Handle Missing Values
5. Feature Encoding (One-Hot Encoding)
6. Feature Scaling (RobustScaler)
7. Train-Test Split
8. Model Training (Gaussian Naive Bayes)
9. Model Evaluation

---

##  Machine Learning Algorithm

- **Gaussian Naive Bayes**

Why Naive Bayes?
- Simple and fast
- Works well with high-dimensional data
- Effective for classification problems

---

##  Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Train vs Test Accuracy Comparison
- Null Accuracy

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/abhiii444/naive-bayes-income-classifier.git
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
3. Run the script:
   ```bash
   python naive_bayes_income_classifier.py

---

## Results

- The model achieves reliable accuracy on both training and test data

- No significant overfitting or underfitting observed

- Naive Bayes performs efficiently on mixed data types after encoding

---



