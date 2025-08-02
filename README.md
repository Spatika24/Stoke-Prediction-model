## 🧠 Stroke Prediction Using Machine Learning

This project focuses on building a predictive model to assess the risk of stroke in individuals based on various health and demographic attributes. The goal is to assist early diagnosis and intervention using supervised machine learning techniques.

### 🔍 Project Overview

* Developed a classification model to predict the likelihood of a stroke using patient data (age, gender, hypertension, heart disease, BMI, etc.).
* Conducted data preprocessing including missing value imputation, encoding categorical variables, and feature scaling.
* Explored multiple machine learning algorithms including:

  * Logistic Regression
  * Naive Bayes
  * K-Nearest Neighbors (KNN)
  * Support Vector Machine (SVM)
  * Decision Tree
  * Random Forest
  * XGBoost
* Performed hyperparameter tuning using `caret` and `tidymodels` framework in R.
* Evaluated model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
* Identified the best-performing model based on ROC-AUC and confusion matrix analysis.

### 🛠️ Tech Stack

* **Language**: R
* **Libraries**: `tidyverse`, `caret`, `tidymodels`, `xgboost`, `e1071`, `rpart`, `randomForest`
* **Data Visualization**: `ggplot2`, `corrplot`
* **Environment**: RStudio

### 📈 Results

* Achieved high classification performance, with the XGBoost and Random Forest models showing the best predictive power.
* The final model helps classify stroke risk with promising accuracy on imbalanced health data.

Let me know if you want a **shorter version**, or if your project includes **a Shiny app or visual dashboard**, I can include that too.
