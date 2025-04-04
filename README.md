# Multiple Disease Prediction System

## Overview
A web-based application that uses machine learning to predict the likelihood of three different diseases:
- Diabetes
- Heart Disease
- Parkinson's Disease

The system provides an intuitive interface for users to input their medical parameters and receive instant predictions about their health conditions.

## Features

### 1. Diabetes Prediction
Predicts diabetes risk using the following parameters:
- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

### 2. Heart Disease Prediction
Analyzes cardiovascular health using:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Serum Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia Type

### 3. Parkinson's Disease Prediction
Evaluates Parkinson's disease risk through voice parameters:
- Various vocal frequency measurements
- Jitter and Shimmer variations
- Harmonic-to-noise ratios
- Nonlinear dynamical features

## Technology Stack
- **Frontend**: Streamlit (Python web framework)
- **Backend**: Python
- **Machine Learning**: scikit-learn
- **Data Processing**: pandas, numpy
- **Model Storage**: pickle

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd MultipleDiseasePredictionSystem
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Linux/Mac
# OR
venv\Scripts\activate     # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
streamlit run multiple_disease_pred.py
```

## Usage
1. Launch the application using the command above
2. Select the disease prediction system from the sidebar
3. Input the required medical parameters
4. Click the "Test Result" button to get the prediction
5. View the prediction result and probability score

## Model Performance
- Diabetes Prediction Model: ~80% accuracy
- Heart Disease Prediction Model: ~85% accuracy
- Parkinson's Disease Prediction Model: ~89% accuracy

## Data Privacy
- The application processes all data locally
- No medical data is stored or transmitted
- Predictions are made in real-time using pre-trained models
