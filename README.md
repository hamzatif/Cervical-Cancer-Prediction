# Cervical Cancer Prediction Project

## Overview

This project analyzes and predicts cervical cancer risk factors using a dataset collected from "Hospital Universitario de Caracas" in Caracas, Venezuela. The goal is to identify key drivers of cervical cancer and develop predictive models to assist in early detection and prevention efforts.

The project involves data preprocessing, exploratory data analysis (EDA), and predictive modeling to extract insights and create actionable outcomes.

## Features

- **Dataset**: Contains 858 samples with 36 attributes, including demographic, reproductive, lifestyle, and medical history information.
- **Model**: XGBoost classifier
- **Evaluation Metrics**: Accuracy

## Model and Results

The **XGBoost classifier** was trained on the dataset and achieved the following results:

- **Training Accuracy**: 96%
- **Testing Accuracy**: 97%

### Best Model

The **XGBoost classifier** demonstrated strong performance, achieving **96% accuracy on training data** and **97% accuracy on testing data**. Its ability to handle complex relationships between features makes it the most suitable model for predicting cervical cancer risk.

## Applications and Insights

### Key Insights

- **Important Risk Factors**:
  - Number of pregnancies and age of first sexual intercourse strongly correlate with cancer risk.
  - Lifestyle factors, such as smoking, and contraceptive usage, also play significant roles.

### Business Applications

1. **Early Detection**:
   - The predictive model can be integrated into healthcare systems to screen patients and prioritize those at higher risk for further testing.
2. **Resource Optimization**:
   - Hospitals can allocate resources more effectively by identifying high-risk individuals.
3. **Preventive Measures**:
   - Insights from feature importance analysis can guide public health campaigns to target key modifiable risk factors.
