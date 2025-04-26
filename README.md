
# Credit Card Fraud Detection

## Objective
The goal of this project is to build a machine learning model that accurately distinguishes fraudulent transactions from legitimate ones using a publicly available dataset.

## Dataset
- Dataset Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Features include transaction amount, anonymized transaction features, timestamps, and a 'Class' label (0 = Not Fraud, 1 = Fraud).

## Steps to Run the Project

1. **Clone the repository**:
   ```bash
  gh repo clone Thiru9160/creditcardfrauddetection
   cd credit-card-fraud-detection
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Download the Dataset:

Download from Kaggle manually or using the Kaggle API.

Place the creditcard.csv file in the working directory.

Run the Python script:

bash
Copy
Edit
python credit_card_fraud_detection.py
Key Features
Data Preprocessing and Standardization

Handling Class Imbalance using Upsampling and SMOTE

Model Building using Random Forest Classifier

Performance Metrics: Accuracy, Precision, Recall, Confusion Matrix

Evaluation
Accuracy: (put the final accuracy here)

Precision, Recall, and F1 Score reported.

Optimized for minimizing false positives while maximizing fraud detection.

Requirements
See requirements.txt for a full list.

Developed as part of the GrowthLink Internship Task.

yaml
Copy
Edit

---

### 📦 Here’s the **requirements.txt**:

```text
pandas
numpy
scikit-learn
imbalanced-learn
matplotlib
seaborn
