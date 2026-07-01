# Credit Card Fraud Detection

## Overview
This project uses Machine Learning to detect fraudulent credit card transactions. The model is trained on historical transaction data and predicts whether a transaction is legitimate or fraudulent.

## Features
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling imbalanced dataset
- Machine Learning model training
- Model evaluation
- Fraud prediction

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

CreditCardFraudDetection/
│── data/
│── notebooks/
│── models/
│── credit_card_fraud_detection.py
│── requirements.txt
│── README.md

## Dataset
The dataset contains:
- Transaction details
- Time
- Amount
- Features V1 to V28
- Class (0 = Genuine, 1 = Fraud)

## Algorithms
- Logistic Regression
- Random Forest (optional)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## How to Run

1. Clone the repository

```
git clone <repository-link>
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run

```
python credit_card_fraud_detection.py
```

## Output
The program predicts whether a transaction is:

- Legitimate
- Fraudulent

## Future Improvements
- Deep Learning models
- Real-time fraud detection
- Web application deployment

## Author
Shakeena
