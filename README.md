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

## 3) Classification Model Comparison — Multiple Algorithms [🔗](/classification-model-comparison)

* Built and compared multiple classification models including:
  * Logistic Regression  
  * K-Nearest Neighbors (KNN)  
  * Decision Tree  
  * Random Forest  
  * XGBoost  
* Performed **data preprocessing and feature preparation** to ensure compatibility across models.
* Evaluated model performance using:
  * Accuracy  
  * Precision  
  * Recall  
  * F1-Score  
  * ROC AUC Score  
* Compared models using **ROC curves and confusion matrices** for deeper performance analysis.
* Identified the best-performing model based on overall evaluation metrics and trade-offs.

## 4) Regression Model Comparison — Multiple Algorithms [🔗](/Regression-model-comparison)

* Built and compared multiple regression models including:
  * Linear Regression  
  * KNN Regressor  
  * Decision Tree Regressor  
  * Random Forest Regressor  
  * XGBoost Regressor  
  * Support Vector Regressor (SVR)  
* Evaluated model performance using:
  * R² Score  
  * Cross-validation  
* Compared models using **actual vs predicted visualizations** and performance metrics.
* Applied **Grid Search hyperparameter tuning** to improve model performance.
* Identified the best-performing model based on accuracy and stability across folds.

---

### Tools & Techniques (across projects)

* **Python (Pandas, NumPy)**
* **Machine Learning (scikit-learn, XGBoost)**
* **Data preprocessing & feature engineering**
* **Model training & evaluation**
* **Classification & Regression models**
* **Feature scaling & encoding**
* **Model persistence (joblib)**
* **Hyperparameter tuning (GridSearchCV)**