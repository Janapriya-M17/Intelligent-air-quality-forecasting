# Intelligent Air Quality Forecasting and Risk Alert System

## Project Overview
The Intelligent Air Quality Forecasting and Risk Alert System is a machine learning-based framework developed to predict both the current Air Quality Index (AQI) and forecast air quality conditions for the next 24 hours.

The system transforms environmental and air pollution data into meaningful predictions and health advisory alerts, enabling proactive environmental monitoring and informed decision-making.

It predicts continuous AQI values and classifies air quality into standard categories:
- Good
- Satisfactory
- Moderate
- Poor
- Very Poor
- Severe

Additionally, the system provides early alerts when future pollution levels are expected to become unhealthy.

---

## Objectives
- Predict the current Air Quality Index (AQI)
- Forecast AQI for the next 24 hours
- Categorize pollution levels based on AQI standards
- Generate risk alerts and health advisory messages
- Provide an interactive and user-friendly interface

---

## Features
✔ Current AQI Prediction  
✔ 24-Hour Air Quality Forecasting  
✔ Air Quality Classification  
✔ Risk Alert System  
✔ Health Advisory Generation  
✔ Interactive User Interface  

---

## Technologies Used
- Python
- Google Colab
- Machine Learning
- Random Forest Regression
- Pandas
- NumPy
- Scikit-learn
- Gradio (User Interface)

---

## Input Parameters
The system uses environmental and pollutant parameters including:

### Pollutant Parameters
- PM2.5
- PM10
- NO₂
- SO₂
- CO
- O₃

### Environmental Parameters
- Temperature
- Humidity
- Wind Speed

---

## Methodology
1. Data Collection  
2. Data Cleaning and Preprocessing  
3. Missing Value Handling  
4. Feature Preparation  
5. Model Training using Random Forest Regression  
6. Current AQI Prediction  
7. 24-Hour AQI Forecasting  
8. AQI Classification  
9. Risk Alert Generation  
10. User Interface Deployment  

---

## Machine Learning Model
The system uses **Random Forest Regression** to predict AQI values.

Reasons for selecting Random Forest:
- Handles nonlinear relationships effectively
- Works well with environmental datasets
- Provides strong prediction performance
- Reduces overfitting

---

## Performance Evaluation

### Regression Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1-Score

The experimental results demonstrate high predictive performance and reliable forecasting capability.

---

## User Interface
An interactive interface developed using **Gradio** enables users to:
- Enter environmental values
- Predict current AQI
- Forecast next 24-hour AQI
- View pollution category
- Receive health advisory alerts

---

## Future Enhancements
- Real-time sensor integration
- Mobile application deployment
- Live weather integration
- Enhanced forecasting accuracy
- Notification and alert system

---
