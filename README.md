# 🎯 Reservation-Radar
A Cancellation Classifier for Hotel Booking Prediction using ML

![Hotel Booking Image](https://i.imgur.com/hotel-booking-banner.jpg)  
*Machine Learning meets Hospitality — Reducing Cancellations, Maximizing Stays!*

## 📝 Project Overview  

This project dives deep into the fascinating world of hotel bookings 🏨 and cancellations ❌.  

We’ve analyzed real-world hotel booking data to uncover why customers cancel their stays — and used machine learning to predict it before it happens!  

Our goal?  
Help hotels make smarter decisions 💡, avoid empty rooms, and give customers a smoother experience ✈️.

## 📊 What’s Inside?  

- 🔍 In-depth Data Analysis  
- 🧹 Clean & Preprocessed Data  
- 📈 Visual Storytelling with Charts  
- 🧠 Machine Learning Models for Prediction  
- 💡 Actionable Business Insights  

## 💾 Dataset Highlights  

The dataset captures key booking details like:

- 👨‍👩‍👧‍👦 No. of Adults & Children  
- 🍽️ Meal Plans  
- ⏰ Lead Time (Days before Arrival)  
- 💵 Average Price per Room  
- 🚗 Parking Requirement  
- 🏠 Room Type Reserved  
- 🔄 Repeated Guest or First Timer  
- 🎯 Booking Status (Canceled / Not Canceled)  

## 🚀 Project Flow  

### 1️⃣ Data Cleaning & Preprocessing  
- Removed invalid entries  
- Handled missing values  
- Outlier treatment using Sqrt & Log Transformations  
- Extracted new features like Month, Week, Day  

### 2️⃣ EDA - Exploratory Data Analysis  

> We love pretty charts! 📊 Here are some cool insights:

| 🔍 Finding | 🛠 Recommendation |
|------------|------------------|
| Bulk Bookings cancel more | Customize Group Booking Policies |
| Higher Price = More Cancellations | Offer Loyalty Discounts & Promotions |
| First Time Guests cancel 34% | Introduce Reward Programs |
| Guests with Reserved Parking cancel less | Offer Non-Parking Perks |
| Cancellations Low in Quarter 4 | Promote Early Booking Discounts |

### 3️⃣ Feature Engineering  
Selected top features using Recursive Feature Elimination (RFE):

- Lead Time  
- Avg Price per Room  
- Parking Requirement  
- Repeated Guest  
- Special Requests  

### 4️⃣ Machine Learning Models  

| Model | Accuracy 🎯 | AUC 📈 |
|-------|-------------|--------|
| Logistic Regression | 74% | 0.72 |
| Random Forest 🌲 | 89% | 0.92 |
| XGBoost ⚡ | 84% | 0.90 |

> 🔥 *Random Forest* emerged as the best-performing model!

## 🛠 Tech Stack  

- Python 🐍  
- Pandas & Numpy  
- Matplotlib & Seaborn (for beautiful charts)  
- Scikit-learn & XGBoost  
- FPDF (Auto-generate Reports)  

## 📈 Visual Sneak Peek  

![Booking Status Pie Chart](https://i.imgur.com/booking-status.png)  
*Booking Status Distribution*  

![Feature Importance Bar Chart](https://i.imgur.com/feature-importance.png)  
*Top Features Driving Cancellations*  

## 🏆 Business Impact  

Hotels can use this project to:  

✔️ Predict booking cancellations before they happen  
✔️ Optimize pricing strategies  
✔️ Offer smart discounts for loyalty building  
✔️ Manage overbookings efficiently  
✔️ Boost revenue & guest experience  

## 📂 Repository Structure  

```
📁 data/           - Dataset files  
📁 notebooks/      - Jupyter notebooks for analysis & modeling  
📁 visuals/        - Charts & Graphs  
📁 reports/        - Final Project Report (.pdf)  
📄 README.md       - You’re here!  
```

## ❤️ Let’s Connect!  
