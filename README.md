
# Car Price Predictor

This project utilizes machine learning techniques to predict the selling price of used cars based on various features such as mileage, engine capacity, fuel type, and more. The model is built using Python and deployed as a web application for user interaction.

## 🧠 Project Overview

The Car Price Predictor aims to assist users in estimating the market value of used cars. By inputting specific details about the car, users can receive an estimated selling price. The underlying model leverages a linear regression algorithm trained on a dataset sourced from CarDekho.

## 📊 Dataset

The dataset used for training the model includes the following features:

- **Car_Name**: Name of the car
- **Year**: Year of manufacture
- **Selling_Price**: Price at which the car is being sold
- **Present_Price**: Current market price of the car
- **Kms_Driven**: Total kilometers driven
- **Fuel_Type**: Type of fuel used (Petrol, Diesel, CNG)
- **Seller_Type**: Type of seller (Individual, Dealer)
- **Transmission**: Type of transmission (Manual, Automatic)
- **Owner**: Number of previous owners

## ⚙️ Technologies Used

- **Python**: Programming language
- **Flask**: Web framework for deploying the application
- **Scikit-learn**: Machine learning library for model building
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **HTML/CSS**: Frontend development

## 🚀 Features

- **User Input Form**: Allows users to enter car details
- **Price Prediction**: Displays the predicted selling price based on input
- **Model Training**: Includes code for training the linear regression model

## 📂 Project Structure

car_price_predictor/
│
├── application.py         # Main application file
├── car.ipynb              # Jupyter notebook for model training
├── LinearRegressionModel.pkl  # Trained model file
├── Cleaned_Car_data.csv   # Cleaned dataset
├── requirements.txt       # Python dependencies
├── templates/             # HTML templates
│   └── index.html
└── static/                # Static files (CSS, images)
    └── css/
        └── style.css

