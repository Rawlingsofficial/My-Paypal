# Fraud Detection System  (My-Paypal)

## Overview
This project implements a fraud detection system using machine learning techniques. The system is designed to detect fraudulent transactions in credit card data. It employs various classifiers trained on a dataset containing both legitimate and fraudulent transactions.

## Features
- Data collection from CSV file
- Data exploration and visualization
- Machine learning models for fraud detection
- Prediction and decision logic for fraud detection
- Model evaluation and comparison
- Preprocessing techniques including SMOTE for handling imbalanced data

## Dataset
The dataset used in this project is from PayPal credit card transactions. It contains a total of 284,807 transactions with 31 features including time, transaction amount, and various anonymized features.

## Setup
1. Clone the repository:
## Setup
1. ** git Clone the repository**:
   ```git
   https://github.com/Rawlingsofficial/My-Paypal>
   ```
2.  Install dependencies:
   ```python
   pip install -r requirements.txt
   ```
3.   Run the main script:
  ```python
   run the main sript in your jupyter enviroment of choice 
   ```
## Usage
1. **Data Exploration**: Explore the dataset to understand its structure and characteristics.

2. **Data Visualization**: Visualize data distributions, correlations, and other patterns using plots and heatmaps.

3. **Machine Learning**: Train and evaluate machine learning models for fraud detection. Models include:
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier
- K Nearest Neighbors Classifier

4. **Prediction and Decision Logic**: Predict fraud using trained models and implement decision logic based on model predictions.

## Results
- **Random Forest Classifier**:
- Accuracy: 99.94%
- AUPRC: 87.66%

- **XGBoost Classifier**:
- Accuracy: 99.94%
- AUPRC: 86.70%

- **Other Models**: Results for Gradient Boosting and K Nearest Neighbors classifiers are also available.

## Files Structure
- `my_paypal.ipynb`: Main file for this project.
- `README.md`: Documentation for the project.

## Authors
- [Rrawling Mukhen](https://github.com/Rawlingsofficial)
  

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
