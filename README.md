# Predict-diamond-price-with-linear-regression
# Diamond Price Prediction

Welcome to the Diamond Price Prediction repository! This project contains a Python program designed to predict the price of diamonds based on various features. The model utilizes machine learning techniques to provide accurate price estimates, making it a valuable tool for jewelers, buyers, and sellers.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Contributing](#contributing)

## Installation

To get started with the Diamond Price Prediction program, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/BozorgmehrFatahi/Predict-diamond-price-with-linear-regression
    cd Predict-diamond-price-with-linear-regression
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To predict diamond prices, you need to provide a dataset with diamond features. The program includes scripts for training the model and making predictions.

### Training the Model

1. **Prepare your dataset:**
   
    Ensure your dataset is in CSV format and contains the necessary features (e.g., carat, cut, color, clarity, depth, table, x, y, z).

2. **Run the training script:**

    ```bash
    jupyter lab
    ```

in the jupyter run every cell with ctrl+Enter 


## Code Explanation

### Data Preprocessing

The data preprocessing steps include loading the dataset, mapping categorical features (cut, color, clarity) to numerical values, and scaling numerical features using MinMaxScaler. This ensures that the features are on a similar scale, which is important for many machine learning algorithms.

### Model Training

The features (X) and target variable (y) are prepared from the preprocessed dataset. The data is then split into training and testing sets. A Linear Regression model is trained on the training data.

### Model Evaluation

The model's performance is evaluated using the R² score, which indicates how well the model's predictions match the actual data. This is done by comparing the predicted prices with the actual prices in the test set.

## Features

- **Data Preprocessing:** Handles missing values, encodes categorical variables, and scales numerical features.
- **Model Training:** Trains
