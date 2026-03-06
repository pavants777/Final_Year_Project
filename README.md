# 🌾 AI Powered Smart Agriculture Assistant

An AI-powered system that helps **farmers decide what to grow, what
fertilizer to use, and when to sell crops for maximum profit**.

The system uses multiple **Machine Learning models trained on
agricultural datasets** to provide intelligent recommendations.

------------------------------------------------------------------------

# 📌 Problem Statement

Farmers often struggle with:

-   Choosing the best crop for their soil and weather
-   Selecting the correct fertilizer
-   Knowing the best season to sell crops
-   Predicting market prices

This project builds **AI models to solve these problems using
agricultural datasets.**

------------------------------------------------------------------------

# 🎯 Project Goals

The system provides three intelligent services:

1.  Crop Recommendation System
2.  Fertilizer Recommendation System
3.  Crop Price Prediction System

These models together form a **Smart Agriculture Decision Support
System.**

------------------------------------------------------------------------

# 📊 Datasets Used

## 1️⃣ Crop Recommendation Dataset

File: `Crop_recommendation.csv`

Features: - Nitrogen (N) - Phosphorus (P) - Potassium (K) -
Temperature - Humidity - pH - Rainfall

Target: - Crop Label

Example crops: Rice, Wheat, Maize, Cotton, Chickpea, Banana.

------------------------------------------------------------------------

## 2️⃣ Fertilizer Recommendation Dataset

File: `Fertilizer Prediction.csv`

Features: - Temperature - Humidity - Moisture - Soil Type - Crop Type -
Nitrogen - Potassium - Phosphorous

Target: - Fertilizer Name

Example fertilizers: Urea, DAP, NPK.

------------------------------------------------------------------------

## 3️⃣ Crop Production Dataset

File: `crop_production.csv`

Features: - State - District - Crop - Season - Area - Production

Used to analyze **crop yield and seasonal production trends.**

------------------------------------------------------------------------

## 4️⃣ Agriculture Price Dataset

File: `Agriculture_price_dataset.csv`

Features: - Commodity - Market - Date - Min Price - Max Price - Modal
Price

Used for **crop price prediction and demand analysis.**

------------------------------------------------------------------------

# 🤖 Machine Learning Models

## Crop Recommendation Model

Algorithm: **Random Forest Classifier**

Inputs: - N, P, K - Temperature - Humidity - pH - Rainfall

Output: - Recommended crop

Example:

Input: N=90, P=40, K=45, Temperature=22, Humidity=80, Rainfall=200

Output: Rice

------------------------------------------------------------------------

## Fertilizer Recommendation Model

Algorithm: **Decision Tree / Random Forest**

Inputs: - Soil Type - Crop Type - Temperature - Humidity - N, P, K

Output: - Recommended fertilizer

Example:

Input: Crop: Maize, Soil: Sandy, N=40, P=20, K=10

Output: Urea

------------------------------------------------------------------------

## Crop Price Prediction Model

Algorithm: - XGBoost - Random Forest - LSTM (time series)

Inputs: - Crop - Location - Month - Historical prices

Outputs: - Predicted price - Best selling time

Example:

Input: Crop: Onion, Month: September

Output: Predicted Price: ₹1500/quintal\
Recommendation: Sell Now

------------------------------------------------------------------------

# 🏗 System Architecture

Datasets\
↓\
Data Preprocessing\
↓\
Feature Engineering\
↓\
Machine Learning Models\
- Crop Recommendation\
- Fertilizer Recommendation\
- Price Prediction\
↓\
API Layer\
↓\
Farmer App / Web Platform

------------------------------------------------------------------------

# 🌍 Real World Implementation

Farmers enter:

-   Location
-   Soil type
-   Crop
-   Season

System returns:

-   Best crop to grow
-   Recommended fertilizer
-   Expected crop price
-   Best selling time

This system can be integrated into **farmer mobile apps or agriculture
marketplaces.**

------------------------------------------------------------------------

# 📅 6 Week Development Plan

## Week 1

-   Dataset understanding
-   Data cleaning
-   Exploratory Data Analysis

## Week 2

-   Train Crop Recommendation Model
-   Evaluate accuracy

## Week 3

-   Train Fertilizer Recommendation Model
-   Hyperparameter tuning

## Week 4

-   Train Crop Price Prediction Model
-   Time-series analysis

## Week 5

-   Build API using Flask or FastAPI
-   Create prediction endpoints

## Week 6

-   Integrate models with frontend
-   Testing and evaluation
-   Prepare project presentation

------------------------------------------------------------------------

# 🚀 Future Improvements

-   Weather prediction integration
-   Satellite crop monitoring
-   Farmer--buyer marketplace
-   Government scheme recommendations
-   Mobile app deployment

------------------------------------------------------------------------

# 🛠 Technologies Used

-   Python
-   Scikit-Learn
-   XGBoost
-   Pandas
-   NumPy
-   FastAPI / Flask
-   Jupyter Notebook

------------------------------------------------------------------------

# 👨‍💻 Author

Pavan Gowda T S\
AI + Agriculture Technology Project
