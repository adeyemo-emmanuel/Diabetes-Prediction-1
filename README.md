# 🩺 Diabetes Risk Prediction using BRFSS 2015 Data
## 📌 Project Overview
Diabetes is one of the most prevalent chronic diseases in the United States, affecting over 34 million Americans and costing the economy nearly $400 billion annually. Early detection is crucial, as many people with diabetes or prediabetes are unaware of their condition.

This project uses the 2015 CDC Behavioral Risk Factor Surveillance System (BRFSS) dataset, containing 441,455 survey responses and 330 health-related features, to build predictive models for Type II diabetes risk.

Our goals are to:

* Identify key health and lifestyle factors influencing diabetes risk.

* Develop accurate machine learning models for prediction.

* Provide insights for public health decision-making and prevention strategies.

## 📊 Dataset
**Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS) – 2015 dataset available on Kaggle.

**Details:**

* **Rows:** 441,455 participants.

* **Features:** 330 variables on demographics, lifestyle, medical history, and preventive care.

* **Data Type:** Survey responses (categorical, binary, numerical).

* **Year:** 2015.

**Target Variable:**

Diabetes_binary – 1 if the participant has been diagnosed with diabetes, 0 otherwise.

## ⚙️ Methodology
**1. Data Preprocessing**

  * Handle missing values.

  * Encode categorical variables.

  * Normalize/scale numerical data.

**2. Exploratory Data Analysis (EDA)**

  * Distribution of diabetes cases by age, gender, BMI, lifestyle factors.

  * Correlation analysis to find key predictors.

**3. Modeling**

  * Baseline models: Logistic Regression, Random Forest, XGBoost, LightGBM.

  * Hyperparameter tuning with GridSearchCV/RandomizedSearchCV.

  * Cross-validation to ensure generalization.

**4. Evaluation Metrics**

  * Accuracy, Precision, Recall, F1-Score.

  * ROC-AUC curves.

  * Confusion matrices.

## 🤖 Models Used
* **Logistic Regression** – interpretable baseline.

* **Random Forest** – handles feature interactions well.

* **XGBoost** – high-performance gradient boosting.

* **LightGBM** – efficient gradient boosting for large datasets.

## 📈 Results
* Best performing models achieved 75% accuracy and ROC-AUC of 83%.

## 📚 References
* Centers for Disease Control and Prevention – BRFSS Data. <https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system>

* Kaggle – Cleaned BRFSS 2015 Dataset. <https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset>

## 🛠️ Technologies Used
* Python (Pandas, NumPy, Scikit-learn)

* Random Forest Classifier, XGBoost, LightGBM

* Matplotlib for visualization

* Jupyter Notebook
