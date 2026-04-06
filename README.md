# Data-Science-British-Airways
This repository contains the completed tasks for the British Airways Data Science Virtual Internship on The Forage. The project focuses on two main areas: Customer Loyalty & Lounge Eligibility Analysis and Predictive Modeling for Customer Bookings.

## 📊 Project Overview
British Airways aims to leverage data science to improve customer experience and optimize booking conversions. This project provides data-driven insights into passenger behavior and loyalty distributions.

## 🛠 Task 1: Lounge Eligibility Analysis (Excel)
Objective: Analyze passenger loyalty distributions and define lounge access rules to ensure operational sustainability.

### Key Activities:
1. Data Categorization: Grouped flights by Haul Type (Long vs Short) and Time of Day (AM vs PM).
2. Loyalty Mix Analysis: Used Pivot Tables to calculate the density of Tier 1 (Gold), Tier 2 (Silver), and Tier 3 (Bronze) members.
3. Findings: Discovered that Tier 1 (Gold) and Tier 2 (Silver) members represent only ~22% of the total loyalty population.
4. Conclusion: Setting eligibility to 100% for Tier 1 and Tier 2 is sustainable and will not lead to lounge overcrowding.

## 🤖 Task 2: Predictive Modeling (Python)
Objective: Build a machine learning model to predict the likelihood of a customer completing a holiday booking.

### Technical Workflow :
1. Data Cleaning:
   - Handled a dataset of 50,000 records.
   - Removed 719 duplicate rows, resulting in 49,281 clean records.
2. Exploratory Data Analysis (EDA): Mapped flight_day to numerical values and analyzed class imbalance.
3. Modeling: Trained a Random Forest Classifier with an 80:20 data split.
4. Performance:
   - Overall Accuracy: 85%
   - Precision (Class 1): 0.48
   - Feature Importance: Identified that purchase_lead, flight_hour, and length_of_stay are the top 3 predictors of booking completion.

## 📈 Strategic Recommendations
1. Target Early Planners: Focus marketing campaigns on customers with a high purchase_lead.
2. Flight Hour Optimization: Tailor incentives during peak flight_hour windows to boost conversions.
3. Integrated Insights: Incorporate Loyalty Tiers from Task 1 into the predictive model to improve targeting for high-value customers.

Author: Rizki Amanda Putri
<br> Date: April 2026
