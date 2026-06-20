# Industrial HVAC Predictive Maintenance using Machine Learning

A machine learning based predictive maintenance system for an industrial
water-cooled chiller plant using historian sensor data.

The project predicts plant efficiency (IKW/TR), detects anomalies,
computes subsystem health scores, and generates maintenance
recommendations for chillers, cooling towers, and pumps.

#Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Isolation Forest
- Matplotlib
- Seaborn

#Workflow Section
Industrial Sensor Data
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Isolation Forest
(Anomaly Detection)
        ↓
XGBoost Regressor
(Predict IKWTR)
        ↓
Health Score Calculation
        ↓
Maintenance Recommendation

#Model Performance
XGBoost Regressor

R² Score : 0.79
MAE      : 0.063

Isolation Forest

Detected anomalies in:
- Chiller system
- Cooling tower
- Pumps
- Entire plant

  
