# Future-Customer-Booking-Prediction
📌 Overview

This project was completed as part of the British Airways Data Science Job Simulation on the Forage platform. It focuses on analyzing customer booking behavior and building a machine learning model to predict the likelihood of booking completion.

The goal is to help airlines better understand customer intent and improve conversion strategies using data-driven insights.

🎯 Project Objective

To develop a predictive model that estimates the probability of a customer completing a flight booking based on their behavior and booking details.

📊 Dataset
50,000 customer booking records
14 features related to booking and customer behavior
Key Features:
Purchase lead time
Flight day and hour
Route
Booking origin
Number of passengers
Additional services:
Extra baggage
Preferred seats
Meals
⚙️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn (for visualization)
🔍 Project Workflow
1. Data Exploration & Preprocessing
Performed exploratory data analysis (EDA)
Identified categorical and numerical variables
Handled encoding of categorical features:
Sales channel
Trip type
Route
Booking origin
Prepared dataset for model training
2. Feature Analysis
Studied patterns influencing booking completion
Analyzed distributions of:
Purchase lead time
Flight timing
Service preferences
3. Machine Learning Model
Implemented Random Forest Classifier
Performed train-test split
Generated probability predictions for booking completion
4. Model Evaluation
Evaluated performance using:
Accuracy
ROC-AUC Score
Analyzed feature importance to identify key drivers
📈 Key Findings
📌 Booking completion rate: ~15%
📌 Sample prediction: 24% booking probability (above average intent)
📌 Important predictors:
Purchase lead time
Route
Booking origin
Additional service selections
💡 Business Impact

This model can help airlines:

Identify high-intent customers
Improve targeted marketing campaigns
Optimize conversion rates
Increase revenue opportunities
🚀 Learnings
Applied machine learning to a real-world aviation dataset
Strengthened skills in:
Data preprocessing
Feature engineering
Model evaluation
Gained experience in translating data insights into business value
