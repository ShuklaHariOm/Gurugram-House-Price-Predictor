# Real Estate Price Prediction and Recommendation System

## Introduction

This project is a comprehensive **Real Estate Price Prediction** and **Apartment Recommendation System** designed to assist users in navigating the property market of Gurugram, India. Utilizing advanced machine learning models, primarily XGBoost Regressor, the project aims to provide accurate price predictions for properties and recommend similar apartments based on various features such as location, size, proximity to amenities, and more.

## Features

- **Price Predictor**: Allows users to input property details like location, size, and other features to predict the price range.
- **Apartment Recommender**: Suggests similar apartments to the user by analyzing property characteristics and proximity factors.
- **Data Visualizations**: Offers insights into real estate trends, price distributions, and market analytics in an interactive format.

## Technologies Used

- **Python**: Core programming language for building the application.
- **Streamlit**: Framework used to create a user-friendly web application interface.
- **XGBoost**: Machine learning model used for price prediction.
- **Pandas & Numpy**: Data manipulation and processing libraries.
- **scikit-learn**: For preprocessing and building the machine learning pipeline.
- **SQLite**: Database for storing and retrieving user information and property data.

## System Architecture

The system follows a streamlined architecture to process the real estate dataset, train and test the model, and predict property prices:

1. **Real Estate Dataset**: The raw data is split into train and test datasets.
2. **Train Dataset**: Used to train the XGBoost Regressor model.
3. **Test Dataset**: Used to test and validate the model.
4. **XGBoost Regressor**: The core machine learning model applied for price prediction.
5. **Build Model**: Trains the XGBoost model using the training dataset.
6. **Price Prediction**: The final output, providing predicted property prices based on user inputs.

## Getting Started

### Prerequisites

- Python 3.8+
- Required Python libraries:
  - `streamlit`
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `xgboost`
  - `category_encoders`

To install the dependencies, run:

```bash
pip install -r requirements.txt
```

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sumit-Autade/REAL-ESTATE.git
   ```
2. Run the Streamlit application:
   ```bash
   streamlit run home.py
   ```
3. Open the application in your browser to start predicting property prices and exploring the recommendation system.

## Usage

### Price Predictor

- Enter the property type, sector, number of rooms, built-up area, and other details.
- Click on the "Predict" button to get the predicted price range for the property.

### Apartment Recommender

- Select a location and radius to find nearby apartments.
- Alternatively, enter the name of an apartment to get a list of similar properties based on multiple similarity factors.

## Contribution

This project is open for contributions. Feel free to fork the repository and create pull requests for enhancements, bug fixes, or additional features.
