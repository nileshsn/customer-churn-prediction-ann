# Customer Churn Prediction using ANN and Streamlit

This repository contains a Streamlit web application that predicts customer churn using a pre-trained Artificial Neural Network (ANN) model. The model was trained on customer data and can predict the likelihood of a customer leaving a service.

## Features

- **Real-time Predictions**: Input customer details to get immediate predictions of churn probability.
- **Interactive UI**: User-friendly interface built with Streamlit.
- **Pre-trained Model**: Utilizes a trained ANN model (`model.h5`) for predictions.
- **Data Preprocessing**: Encodes categorical variables and scales numerical data using saved encoders and scaler (`.pkl` files).

## Getting Started

### Prerequisites

- Python 3.7+
- Required Python libraries:
  - streamlit
  - numpy
  - tensorflow
  - scikit-learn
  - pandas

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction-ann.git
   cd customer-churn-prediction-ann
