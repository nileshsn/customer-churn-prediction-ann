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


## Installation

2. **Install required libraries**: Create a `requirements.txt` file with the following content:

    ```plaintext
    streamlit
    numpy
    tensorflow
    scikit-learn
    pandas
    ```

    Then install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:

    ```bash
    streamlit run app.py
    ```

## Usage

- Open your web browser and navigate to [http://localhost:8501](http://localhost:8501) to access the Streamlit application.
- Enter the required customer details into the form fields provided.
- Click the 'Predict' button to view the churn probability and the prediction result.

## Files

- `app.py`: The main Streamlit application script.
- `model.h5`: The pre-trained ANN model file.
- `label_encoder_gender.pkl`: Saved LabelEncoder for encoding the `gender` feature.
- `onehot_encoder_geo.pkl`: Saved OneHotEncoder for encoding the `geography` feature.
- `scaler.pkl`: Saved StandardScaler for feature scaling.

## Model Training

The model was trained using a dataset with the following features:

- Credit Score
- Geography
- Gender
- Age
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

The model architecture consists of a deep neural network with:

- Input Layer
- Hidden Layer 1: Dense layer with 64 units and ReLU activation
- Hidden Layer 2: Dense layer with 32 units and ReLU activation
- Output Layer: Dense layer with 1 unit and sigmoid activation function for binary classification

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Streamlit team for providing an excellent framework for building web applications.
- TensorFlow community for the powerful deep learning tools.
- Scikit-learn for the robust preprocessing utilities.

