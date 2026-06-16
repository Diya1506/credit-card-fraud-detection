# 💳 Credit Card Fraud Detection using Machine Learning

## Overview

This project implements a Machine Learning-based Credit Card Fraud Detection system that identifies potentially fraudulent transactions using historical transaction data.

The goal is to assist financial institutions in detecting suspicious activities and reducing financial losses caused by fraudulent credit card usage.

The model is trained using Logistic Regression and evaluated using standard classification metrics.

---

## Features

* Data preprocessing and cleaning
* Feature scaling using StandardScaler
* Train-test data splitting
* Logistic Regression classifier
* Performance evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Fraudulent transaction prediction

---

## Dataset

The dataset contains customer transaction information and anonymized features used for fraud detection.

### Dataset Information

* Total Records: 690
* Features: 16 input features
* Target Variable:

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction

Example features:

* Customer_ID
* A_1
* A_2
* A_3
* ...
* A_14

---

## Technology Stack

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn

---

## Machine Learning Workflow

### 1. Data Collection

Load the dataset into a Pandas DataFrame.

### 2. Data Preprocessing

* Handle missing values
* Feature selection
* Data scaling using StandardScaler

### 3. Train-Test Split

Split the dataset into training and testing sets.

### 4. Model Training

Train a Logistic Regression model using Scikit-learn.

### 5. Model Evaluation

Evaluate performance using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score

### 6. Prediction

Predict whether a transaction is fraudulent or legitimate.

---

## Project Structure

```text
credit-card-fraud-detection/
│
├── SecureSwipe.ipynb
├── cc fraud detection.csv
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Diya1506/credit-card-fraud-detection.git
```

Move to project directory:

```bash
cd credit-card-fraud-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```bash
jupyter notebook SecureSwipe.ipynb
```

or upload the notebook directly to Google Colab.

Run all cells sequentially to:

1. Load the dataset
2. Preprocess data
3. Train the model
4. Evaluate performance
5. Generate predictions

---

## Future Improvements

* Random Forest Classifier
* XGBoost Classifier
* Real-time Fraud Detection API
* Hyperparameter Optimization
* Model Deployment using Flask/FastAPI
* Interactive Dashboard

---

## Results

The model successfully classifies transactions as fraudulent or legitimate using supervised machine learning techniques.

Performance is evaluated using classification metrics to ensure reliable fraud detection.

---

## Author

**Diya**

GitHub: https://github.com/Diya1506

---

## License

This project is intended for educational and research purposes.
