# MASTER’S THESIS 

## DEVELOPMENT OF A SCORING MODEL BASED ON DATA FROM COMPANIES CONNECTED TO THE EVOTOR 

### Field of study: Business Informatics
### Degree programme: Business Analytics and Big Data Systems

__Student:__ Turakulov Akramjon

-----

The work is devoted to developing a model for predicting the bankruptcy of companies in the commercial sector, which are connected to the online cash register system Evotor. A comparison of the ability of various models to predict the bankruptcy of companies is presented. Such algorithms as logistic regression, Decision Tree, Random Forest, CatBoost Classifier, Support Vector Classification and K-Nearest Neighbors are considered. Attention is devoted to checking variables for significance, informativeness, correlation, and multicollinearity. Non-financial and financial indicators with the addition of data on risk flags and average checks from the Evotor online cash register system were used in the work. The dataset of retail companies for the period from 2020 to 2022 was collected based on public financial statements from SPARK-INTERFAX and Evotor API method calls. The Gini coefficient or ROC AUC were used as a metric for model quality. It was found that Random Forest outperformed other algorithms, while Logistic Regression with binning closely followed. It is found that the average check and risk factors from Evotor have good predictive ability and can be used to create scoring models.
