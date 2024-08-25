# Customer Churn Prediction using ANN and Streamlit

This repository contains a Streamlit web application that predicts customer churn using a pre-trained Artificial Neural Network (ANN) model. The application allows users to input customer details and receive predictions on the likelihood of customer churn based on various features.

## Features

- **Real-time Predictions**: Enter customer details to get immediate predictions of churn probability.
- **Interactive UI**: User-friendly interface built with Streamlit.
- **Pre-trained Model**: Utilizes a trained ANN model (`model.h5`) for predictions.
- **Data Preprocessing**: Consistent preprocessing using saved encoders and scalers (`.pkl` files).

## Live Demo

Check out the live demo of the application:  
[Customer Churn Prediction App](https://customer-churn-prediction-ann-kfxkke4rnmul6dcxeju32e.streamlit.app/)

## Getting Started

### Prerequisites

- Python 3.7+
- Required Python libraries:
  - `streamlit`
  - `numpy`
  - `tensorflow`
  - `scikit-learn`
  - `pandas`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction-ann.git
   cd customer-churn-prediction-ann
