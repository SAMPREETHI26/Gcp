# Telecom Customer Churn Predictor

## Overview
The Telecom Customer Churn Predictor is a **machine learning-based project** designed to predict whether a customer will churn or stay with a telecom service provider. 
The model is trained on **Google Cloud Vertex AI** and deployed as a REST API. A **Tkinter GUI interface** and **cURL-based API requests** are provided for seamless prediction.

---

## Key Features
- **Churn Prediction:** Classifies customers as likely to churn or stay based on input features.
- **Cloud-Based ML Model:** Trained and deployed using **Google Cloud Vertex AI** for scalable performance.
- **cURL API Integration:** Make predictions by sending JSON data via cURL requests to the deployed model endpoint.
- **Tkinter GUI:** Simple desktop interface for entering customer data and viewing predictions.
- **Data Preprocessing:** Includes feature engineering, scaling, and cleaning of customer data.

---

## Tech Stack
- **Language:** Python
- **Libraries:** scikit-learn, pandas, numpy, Tkinter (for GUI)
- **Cloud Platform:** Google Cloud Platform (Vertex AI)
- **Deployment:** Vertex AI endpoints with REST API
- **Interface:** Tkinter GUI + cURL commands

---

## How It Works
1. **Model Training:** Customer data is preprocessed and used to train an ML model  in Vertex AI.
2. **Deployment:** The trained model is deployed as an API endpoint on **Google Cloud Vertex AI**.
3. **Prediction via API:** User sends a JSON payload with customer features using cURL or Python requests to get churn predictions.
4. **Tkinter Interface:** Local desktop app allows users to input customer details and fetch predictions from the deployed model.
