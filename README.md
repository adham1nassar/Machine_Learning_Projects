# Machine Learning Projects — Main Features

This repo contains self-contained machine learning projects (each in its own folder). Below are the **main features** covered in each project.

## 1) Heart Disease Classification — Logistic Regression [🔗](/heart-disease-classification-logistic-regression)

* Built a **binary classification model** to predict the presence of heart disease.
* Performed **data cleaning and preprocessing** including handling missing values and duplicates.
* Applied **feature scaling** using StandardScaler for numerical features.
* Split the dataset using **train-test split with stratification** to preserve class balance.
* Trained a **Logistic Regression model** as a baseline for medical classification.
* Evaluated model performance using accuracy and classification metrics.
* Saved the trained model for reuse using joblib.

## 2) Car Price Prediction — Linear & Ridge Regression [🔗](/car-price-prediction-linear-Ridge-regression)

* Built regression models to predict car prices using **Linear Regression and Ridge Regression**.
* Performed **extensive data preprocessing**, including:
  * Cleaning inconsistent and mixed-format columns  
  * Converting string-based features into numerical values  
  * Handling missing values and outliers  
* Applied **feature engineering** and encoding for categorical variables such as:
  * Car brand  
  * Fuel type  
  * Transmission  
* Compared model performance between:
  * Linear Regression (baseline)  
  * Ridge Regression (regularized model)  
* Visualized results using **actual vs predicted comparison plots** to evaluate model performance.
* Highlighted the impact of **regularization in improving model stability and generalization**.

---

### Tools & Techniques (across projects)

* **Python (Pandas, NumPy)**
* **Machine Learning (scikit-learn)**
* **Data preprocessing & feature engineering**
* **Model training & evaluation**
* **Classification & Regression models**
* **Feature scaling & encoding**
* **Model persistence (joblib)**