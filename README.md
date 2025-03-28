# MASTER’S THESIS 

## 📊 DEVELOPMENT OF A SCORING MODEL BASED ON DATA FROM COMPANIES CONNECTED TO THE EVOTOR 

### Field of study: Business Informatics
### Degree programme: Business Analytics and Big Data Systems

__Student:__ Turakulov Akramjon

## 📌 Overview

This project focuses on developing a predictive model for identifying bankruptcy risks in commercial sector companies connected to the **Evotor** online cash register system. Various machine learning algorithms were evaluated to determine their effectiveness in forecasting company insolvency.

The study involves analyzing financial and non-financial indicators, incorporating risk flags and average check data obtained from Evotor. A dataset of retail companies from **2020 to 2022** was collected using public financial statements from **SPARK-INTERFAX** and Evotor API calls.

## 🏆 Key Findings

- **Random Forest** demonstrated the highest predictive performance.
- **Logistic Regression with binning** closely followed in effectiveness.
- The **average check amount** and **risk flags from Evotor** proved to be strong predictors of bankruptcy.

## 🛠️ Algorithms Evaluated

The following classification models were tested:

- **Logistic Regression** (Логистическая регрессия)
- **Decision Tree** (Дерево решений)
- **Random Forest** (Случайный лес)
- **CatBoost Classifier**
- **Support Vector Classification (SVC)** (Метод опорных векторов)
- **K-Nearest Neighbors (KNN)** (Метод k-ближайших соседей)

## 📊 Data Preprocessing & Feature Selection

Special attention was given to:

- Checking variables for **significance, informativeness, correlation, and multicollinearity**.
- Using both **financial** and **non-financial** indicators.
- Feature engineering using Evotor **risk flags** and **average transaction values**.

## 📈 Model Evaluation

To assess model quality, we used **ROC AUC** and the **Gini coefficient**:

\[
Gini = 2 \times AUC - 1
\]

where:

- \( AUC \) (Area Under Curve) is the area under the ROC curve.
- \( Gini \) measures model separation power (higher values indicate better performance).

## 📦 Data Sources

- **SPARK-INTERFAX** — Public financial statements
- **Evotor API** — Online cash register transaction data

## 🚀 Conclusion

The **Random Forest model** emerged as the best performer, followed by **Logistic Regression with binning**. This work highlights the **importance of transaction-based risk indicators** in bankruptcy prediction and their potential use in scoring models.
