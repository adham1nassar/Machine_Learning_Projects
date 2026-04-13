# Heart Disease Classification — Logistic Regression

This project focuses on **predicting whether a person has heart disease** using a Logistic Regression model.  
The goal was to build a **clean, end-to-end machine learning pipeline** starting from raw data to a trained and saved model.

---

## Project Objectives

- Build a **binary classification model** to predict heart disease presence.  
- Perform **data cleaning and preprocessing**.  
- Apply **feature scaling** where needed.  
- Train and evaluate a **Logistic Regression model**.  
- Save the trained model for future use.  

---

## Data Preparation Approach

The dataset was loaded from a CSV file and prepared for modeling.

### Data Cleaning
- Removed **duplicate rows** to ensure data consistency.  
- Checked for **missing values** across all features.  
- Explored feature distributions and summary statistics.  

### Feature Engineering
- Split features into:
  - **Numerical features** (e.g., age, cholesterol, heart rate)  
  - **Categorical features** (e.g., chest pain type, sex, slope)  
- Applied **standardization** to numerical features using `StandardScaler`.  

---

## Model Training

### Train-Test Split
- Split the dataset into:
  - **80% Training set**
  - **20% Test set**
- Used **stratified sampling** to maintain class balance.  

### Model Used
- **Logistic Regression**
  - Simple and interpretable baseline model for binary classification  

---

## Model Evaluation

- Evaluated performance using **accuracy score**:
  - Training Accuracy: High (indicates good learning)  
  - Test Accuracy: Close to training accuracy (indicates low overfitting)  

This shows that the model generalizes reasonably well to unseen data.

---

## Pipeline

- Built a preprocessing + modeling workflow:
  - Standardization for numerical features  
  - Model training using Logistic Regression  

This ensures the model can be **reused consistently** on new data.

---

## Model Saving

- Saved the trained model using `joblib`:
  - `logistic-regression-model.pkl`  

This allows the model to be **loaded and used in future applications** without retraining.

---

## Key Insights

- Proper **data cleaning and scaling** significantly improves model performance.  
- Logistic Regression provides a strong baseline for **medical classification tasks**.  
- Stratified splitting helps maintain **balanced evaluation**.  
- Even simple models can perform well when the pipeline is properly structured.  

---

## Tools Used

- **Python**
  - pandas, numpy  
- **Machine Learning**
  - scikit-learn (LogisticRegression, train_test_split, StandardScaler)  
- **Model Persistence**
  - joblib  

---

## Dataset

- Source: Heart Disease Dataset  
- File: `heart_disease_data.csv`  

Typical features include:
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- And other medical indicators  

Target variable:
- `target` → 0 (No disease), 1 (Disease present)

---

## Project Files

- Jupyter Notebook (`.ipynb`)  
- Trained Model (`.pkl`)  
- Dataset: [Heart Disease Dataset]( ../assets/heart-disease-classification-logistic-regression/heart_disease_data.csv  )

---

## Author

**Adham Nassar**  
[LinkedIn](https://www.linkedin.com/in/adham-nassar-83ba54347)  

This project demonstrates strong understanding of **machine learning fundamentals, data preprocessing, and model evaluation**, with a focus on building **clean and reproducible ML pipelines**.