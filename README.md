# Hotel_Cancellation_Prediction_DS

##  Team Members
- **Member 1:** Amit Kadane — amitkadane@iisc.ac.in  
- **Member 2:** Ghanshyam Burnwal — ghanshyamb@iisc.ac.in  
- **Member 3:** Nitish Kumar — nitishkumar@iisc.ac.in  
- **Member 4:** Shalin Shah​ — shalinshah@iisc.ac.in 



---

## Problem Statement

Hotel booking cancellations significantly impact revenue management, inventory planning, and operational efficiency.  
Our goal is to **predict whether a hotel booking will be cancelled** based on historical customer and booking attributes.  

Accurate prediction helps hotels to:
- Reduce last-minute losses  
- Apply smarter overbooking strategies  
- Improve revenue forecasting  
- Optimize room allocation  

---

## Dataset Description

The dataset used in this project is the **Hotel Booking Demand Dataset**, containing **119,390 records and 36 features**.

### Key features include:
- **Customer Details:** country, repeated guest, adults, children  
- **Booking Details:** lead time, arrival date, booking changes  
- **Stay Information:** nights stayed, weekend nights, meal type  
- **Financial Details:** average daily rate (ADR)  
- **Cancellation:** target variable (`is_canceled`)

### Target Variable:
- `is_canceled`  
  - **0** → Not Cancelled  
  - **1** → Cancelled

---

##  High-Level Approach

Our workflow followed a clean, modular pipeline split across six notebooks:

###  Data Collection
- Loaded raw data  
- Basic structure and schema validation  

###  Data Preprocessing
- Removed missing values  
- Encoded categorical features  
- Scaled numeric features  
- Ensured target variable remains discrete  

### Exploratory Data Analysis (EDA)
- Distribution plots  
- Boxplots for outliers  
- Correlation heatmap  
- Target distribution analysis  

###  Modeling
- Feature–target split  
- Train/test split  
- Trained models
    - Logistic Regression​
    - Random Forest​
    - Gradient Boosting ​
    - XGBoost​
- Evaluated using accuracy & classification report  

### Evaluation & Analysis
- Model Comparison:               
- Model  roc_auc             
 - xgboost 0.959185       
 - random_forest 0.957479   
 - gradient_boosting 0.925504 
 - logistic_regression 0.856473


## Summary of Results 

- XGBoostModel Performance Metrics:   
  - ROC-AUC Score: 0.9611   
  - PR-AUC Score: 0.9426  
  - Accuracy: 0.8948  
  - Precision: 0.8718   
  - Recall: 0.8393   
  - F1-Score: 0.8553







