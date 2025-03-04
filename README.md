# Hospital-LOS-Prediction

Built a serialized machine learning model that predicts the Length of Stay (LOS) of a patient at HealthPlus Hospital using data available during admission and initial diagnostic tests.

## Project Overview

This project aims to predict the length of stay (LOS) for patients in a hospital setting. Accurate LOS predictions are critical for optimizing hospital resource allocation, improving patient care, and reducing operational inefficiencies.

## Dataset

The dataset includes over **500,000 patient admission records** with features such as:
- Patient demographics
- Severity of illness
- Type of admission
- Department
- Deposit amounts
- Visitor counts

The target variable is:
- **Length of Stay (LOS)**

## Objectives

- Analyze factors influencing hospital length of stay.
- Build predictive models to estimate patient LOS.
- Enable future deployment of the model for real-time predictions in hospital management systems.

## Methods

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training with **Random Forest Regressor**
- Model serialization using **Pickle** and **Joblib**

## Results

- Identified key factors affecting LOS, including **severity of illness** and **type of admission**.
- Trained a **Random Forest Regressor** with strong predictive performance.
- Serialized the final model for reuse without retraining.

## Business Impact

- Improved hospital resource planning.
- Enabled proactive staffing and bed allocation.
- Reduced operational bottlenecks through predictive insights.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Random Forest
- Pickle
- Joblib
- Matplotlib

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hospital-los-prediction.git
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run the notebook to reproduce the results.
5. 
