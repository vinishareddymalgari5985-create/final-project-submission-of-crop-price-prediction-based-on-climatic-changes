# Crop Price Prediction - Deployment

## Overview
This repository contains the **Week-3 deployment version** of the Crop Price Prediction project. The project predicts monthly crop prices based on climate features such as temperature, rainfall, humidity, and season.

The ML model used is a **Random Forest Regressor**, trained on historical crop price data and enhanced with climate features for more accurate predictions.

---

## Repository Contents
- `Week3_Deployment.ipynb` : Jupyter notebook containing the **deployment code**, including:
  - Loading the trained model and scaler
  - Scaling new input data
  - Making manual predictions
  - Displaying model evaluation metrics
- `final_model.pkl` (optional, if under 10 MB) : Saved Random Forest model
- `scaler.pkl` (optional) : Saved StandardScaler object

---

## Features
- End-to-end ML workflow:
  - Data preprocessing
  - Model training (Random Forest)
  - Model evaluation (MSE, R²)
  - Deployment demo with manual input
- Scalable and reusable: The saved model can be loaded in any Python environment to predict crop prices.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Crop-Price-Prediction-Deployment.git
