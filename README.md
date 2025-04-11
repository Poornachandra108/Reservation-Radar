# Reservation Radar: Hotel Booking Cancellation Prediction Using ML

> A Machine Learning Approach to Predicting and Reducing Hotel Booking Cancellations  

## Project Overview  

This project presents an end-to-end data science solution designed to help the hospitality industry tackle one of its critical challenges — booking cancellations.

Using real-world hotel booking data from the pre-COVID era (2017-2019), this project aims to uncover the key factors contributing to cancellations and build predictive models to identify at-risk bookings.

Hotels can leverage this analysis to improve operational efficiency, optimize pricing, enhance customer loyalty, and minimize lost revenue due to cancellations.

## Problem Statement  

Hotel booking cancellations cause significant disruptions in the hospitality sector, affecting:  
- Revenue generation  
- Capacity planning  
- Inventory & Resource allocation  
- Customer experience  

The primary objective of this project is to use Machine Learning techniques to predict whether a booking will be canceled based on customer and booking attributes.

## Dataset Description  

The dataset contains detailed records of hotel bookings with the following key features:

- Number of adults and children per booking 👨‍👩‍👧‍👦  
- Lead time between booking and arrival ⏳  
- Room type reserved 🏠  
- Average price per room 💵  
- Special requests (e.g., extra bed, late check-in)  
- Guest type (First-time or Repeated Guest) 🔄  
- Parking space requirement 🚗  
- Market segment (Online, Offline, Corporate, etc.)  
- Booking status (Canceled or Not Canceled) 🎯  

## Workflow  

### 1️⃣ Data Preprocessing  
- Removal of invalid records (e.g., impossible dates, zero prices)  
- Handling of missing values  
- Outlier treatment using appropriate transformations (Sqrt & Log)  
- Date feature extraction (Month, Week, Day of Year)  
- One-hot encoding of categorical variables  

### 2️⃣ Exploratory Data Analysis (EDA)  

Comprehensive analysis was conducted to identify trends and patterns within the dataset.

#### Key Insights:  

| Observation | Business Recommendation |
|-------------|-------------------------|
| Bulk bookings (large groups) have higher cancellation rates | Design flexible policies and offers for group bookings |
| Higher room prices correlate with cancellations | Implement loyalty discounts & early booking offers |
| First-time guests cancel more often than repeat guests | Launch customer loyalty and rewards programs |
| Reserved parking guests have lower cancellation rates | Provide incentives to non-parking guests |
| Fewer cancellations observed in Quarter 4 | Promote early booking campaigns during other quarters |

### 3️⃣ Feature Engineering  

Recursive Feature Elimination (RFE) was applied to select the most influential features for prediction:

- Lead Time  
- Average Price per Room  
- Parking Space Requirement  
- Repeated Guest Status  
- Special Requests  
- Room Type Reserved  
- Market Segment Type  

### 4️⃣ Machine Learning Models  

Multiple models were built and evaluated to classify bookings as Canceled or Not Canceled.

| Model | Accuracy | AUC Score |
|-------|----------|-----------|
| Logistic Regression | 74% | 0.72 |
| Random Forest | 89% | 0.92 |
| XGBoost | 84% | 0.90 |

#### The Random Forest Classifier outperformed other models in accuracy and robustness, making it the preferred choice for deployment.

## Tools & Technologies Used  

- Python 3.x  
- Pandas & NumPy for data manipulation  
- Matplotlib & Seaborn for visualization 📊  
- Scikit-learn for machine learning models (Logistic Regression, Random Forest) 
- XGBoost for advanced boosting algorithms  

## Business Impact & Recommendations  

This project equips hotels with a data-driven approach to:  

- Proactively manage bookings and cancellations  
- Optimize pricing strategies and room allocation  
- Strengthen customer loyalty programs  
- Improve marketing campaigns based on seasonal trends  
- Minimize revenue loss due to last-minute cancellations  

## Final Note  

This project demonstrates the power of Data Science in the hospitality industry. By leveraging Machine Learning models, hotels can move from reactive to proactive cancellation management — improving both profitability and guest satisfaction.

## Let's Connect!

