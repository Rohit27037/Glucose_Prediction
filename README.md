# Glucose_Prediction
Project for EDGENIUS SKILLFIED MENTOR PRIVATE LIMITED
# 🩺 Glucose Level Prediction using Logistic Regression

This project focuses on predicting whether a person is likely to have high glucose levels based on health and demographic features from the **Framingham Heart Study** dataset.

## 📌 Objective

To build a binary classification model that predicts the **risk of elevated glucose levels**, which can be an early indicator of diabetes or metabolic syndrome.

## 📁 Dataset: Framingham.csv

- The dataset contains medical, demographic, and lifestyle features.
- Key features used in this project:
  - **Age**
  - **BMI (Body Mass Index)**
  - **Blood Pressure**
  - (Other features may be available but were excluded for simplicity)

## 🧪 Model Used

- **Logistic Regression**
  - A supervised classification algorithm ideal for binary outcomes like high vs normal glucose levels.

## 🛠️ Workflow

1. **Data Import & Exploration**
   - Load dataset
   - Display basic statistics
   - Handle missing values

2. **Feature Selection**
   - Selected only relevant features: `BMI`, `Age`, and `Blood Pressure`

3. **Data Preprocessing**
   - Normalization or Standardization (if applied)
   - Train-test split

4. **Model Training**
   - Trained a Logistic Regression model on the training set

5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report (precision, recall, F1-score)

6. **Visualization**
   - Correlation heatmap
   - Performance metrics

## 📊 Results

- The model gives a good balance between sensitivity and specificity for predicting elevated glucose levels.
- Accuracy, precision, and recall metrics are reported in the notebook.

## 📎 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
