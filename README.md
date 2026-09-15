# Air-Quality-Prediction
## 🌍 HACKADE: Predicting CO₂ Emissions Using Low-Cost Sensors

Competition: https://zindi.africa/competitions/air-quality-prediction-from-low-cost-iot-devices/


## Project Overview
Carbon emissions are a major driver of climate change, yet accurate monitoring remains inaccessible due to the high cost of reference-grade CO₂ meters. Chemotronix aims to close this gap by developing low-cost sensor devices that, when paired with machine learning, can deliver accuracy comparable to expensive reference meters.
This project focuses on building a machine learning model that maps low-cost sensor readings to true CO₂ concentration values, enabling scalable and affordable carbon emission monitoring.

## Problem Statement
High-accuracy CO₂ reference meters are prohibitively expensive, limiting their use to well-funded institutions. This restricts large-scale environmental monitoring and slows climate action.
The challenge is to:
-	Use data from low-cost sensor prototypes
-	Learn the relationship between sensor readings and reference CO₂ measurements
-	Produce accurate predictions that generalize across varying environmental conditions

## Objective
Develop a machine learning model that accurately predicts CO₂ concentration levels using sensor data from Chemotronix’s prototype devices.
A successful model would:
-	Bridge the gap between affordability and precision
-	Enable mass deployment of low-cost CO₂ sensors
-	Support data-driven environmental and sustainability policies

## Dataset Description
The dataset was generated from an experiment conducted by Chemotronix, involving three prototype sensor devices:
-	Alpha
-	Beta
-	Charlie
Each device collected sensor readings alongside measurements from a high-accuracy reference meter, across diverse environmental conditions to ensure robustness.
### Data Split
-	Training Data: Sensor readings + corresponding CO₂ reference values
-	Test Data: Sensor readings only (CO₂ values to be predicted)
-	Test set split: 70% Public / 30% Private

## Evaluation Metric
Model performance is evaluated using Root Mean Squared Error (RMSE), emphasizing accurate numerical prediction and penalizing large errors.

## Machine Learning Approach
The project follows a standard, production-relevant ML workflow:
1. Data Preparation
  -	Cleaning and validation of sensor readings
  -	Handling missing or inconsistent values
2. Exploratory Data Analysis (EDA)
  - Distribution analysis of sensor features
  -	Relationship between sensor readings and CO₂ levels
  -	Device-level behavior comparison
3. Feature Engineering
  -	Selection and transformation of meaningful sensor features
  -	Reduction of noise and redundancy
4. Modeling
  -	Training regression-based ML models
  -	Hyperparameter tuning for performance vs interpretability
5. Evaluation & Prediction
  -	Model evaluation using RMSE
  -	CO₂ predictions generated for unseen test data

## Results & Impact
An accurate prediction model enables Chemotronix to:
-	Manufacture low-cost sensors with near reference-grade accuracy
-	Democratize access to environmental monitoring tools
-	Support governments, NGOs, and communities in climate action
-	Scale carbon emission tracking globally

## Key Learnings
-	Low-cost hardware can achieve high accuracy when paired with ML
-	Feature understanding matters more than model complexity
-	Environmental data requires careful validation and generalization checks

## Future Work
-	Device-specific calibration models
-	Ensemble methods for improved robustness
-	Deployment as a real-time monitoring system


