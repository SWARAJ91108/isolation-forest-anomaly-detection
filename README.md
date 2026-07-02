# Isolation Forest for Machine Anomaly Detection

## Overview

This project demonstrates how Isolation Forest, an unsupervised machine learning algorithm, can detect abnormal machine sensor readings for predictive maintenance.

## Business Problem

SmartFactory Industries monitors industrial machines using IoT sensors that record:

- Temperature (°C)
- Vibration (mm/s)
- Pressure (bar)
- Flow Rate (L/min)
- Efficiency (%)

Since machine failures are rare and unlabeled, supervised learning cannot be applied effectively. Isolation Forest automatically identifies unusual sensor patterns and flags them as anomalies.


## Dataset

**File:** `machine_sensor_data.csv`

Features:

- Timestamp
- Temperature (°C)
- Vibration (mm/s)
- Pressure (bar)
- Flow Rate (L/min)
- Efficiency (%)



## Workflow

- Data Cleaning
- Handle Missing Values
- Convert invalid values (ERROR)
- Remove Timestamp column
- Train Isolation Forest
- Predict anomalies
- Count anomalous observations
- Visualize normal vs anomalous machines



## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn



## Results

- Successfully detected anomalous machine observations.
- Classified observations as:
   1 → Normal
  -1 → Anomaly
- Visualized anomalies for predictive maintenance.



## Applications
- Manufacturing Analytics

