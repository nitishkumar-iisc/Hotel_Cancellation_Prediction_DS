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
- Accuracy  
- Confusion matrix  
- Feature importance ranking  


---

## Summary of Results

| Metric | Value |
|--------|--------|
| **Accuracy** | ~XX% |
| **Precision** | XX% |
| **Recall** | XX% |
| **F1-score** | XX% |

> *(Replace XX with your actual results from Step 5.)*

###  Key Observations
- Lead time, previous cancellations, and ADR are strong predictors.  
- Repeated guests are less likely to cancel.  
- Longer stays have slightly higher cancellation likelihood.  

---

##  Project Structure


