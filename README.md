# Taxi Tip Prediction Model

A machine learning project to predict **taxi tip amounts** based on trip details such as fare, distance, and passenger count.  
This model uses **regression techniques** and is built with Python and scikit-learn.

---

## Project Overview
The main goal of this project is to build a regression model that can accurately predict taxi tip amounts based on trip-related features.  
The dataset used for training and testing comes from the **NYC Taxi and Limousine Commission (TLC)** and is authorized to specific users only.

---

## Dataset
- **Source:** NYC TLC (Taxi and Limousine Commission)  
- **Access:** Dataset is authorized to specific users and is **not publicly available**.  
- **Features Used:**
  - `fare_amount`
  - `tolls_amount`
  - `trip_distance`
  - `RatecodeID`
  - `DOLocationID`
  - `passenger_count`
  - `store_and_fwd_flag`
  - `improvement_surcharge`
  - `PULocationID`
  - `mta_tax`
  - **Target Variable:** `tip_amount`

---

## Technologies Used

- **pandas** for data manipulation  
- **scikit-learn** for model training and evaluation  
- **matplotlib** for data visualization  

---

## Model Training
1. **Data Preprocessing:**  
   - Handled missing values  
   - Selected relevant features  
   - Split dataset into training and testing sets  

2. **Model Used:**  
   - Decision Tree Regressor  

3. **Training:**  
   ```python
   dt_reg.fit(X_train, y_train)
