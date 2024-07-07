---

# Aspirenex Project

Welcome to the Aspirenex project repository. This project focuses on two main aspects: credit card fraud detection and customer churn prediction. This README provides an overview of the project structure, setup instructions, and usage guidelines.

## Project Structure

The project consists of the following main files and directories:

```
Aspirenex Project/
│
├── creditcard.csv
├── creditcard.ipynb
├── customerchurn.csv
├── customerchurn.ipynb
└── README.md
```

- **creditcard.csv**: Dataset for credit card fraud detection.
- **creditcard.ipynb**: Jupyter Notebook containing the analysis and model development for credit card fraud detection.
- **customerchurn.csv**: Dataset for customer churn prediction.
- **customerchurn.ipynb**: Jupyter Notebook containing the analysis and model development for customer churn prediction.
- **README.md**: This README file.

## Setup Instructions

To get started with the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd Aspirenex-Project
    ```

2. **Install dependencies**:
    Create a virtual environment and install the required Python packages.
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**:
    Start Jupyter Notebook to interact with the provided notebooks.
    ```bash
    jupyter notebook
    ```

## Usage Guidelines

### Credit Card Fraud Detection

1. Open the `creditcard.ipynb` notebook.
2. Follow the steps to preprocess the data, explore the dataset, and develop the machine learning models for fraud detection.
3. Run each cell sequentially to execute the code and visualize the results.

### Customer Churn Prediction

1. Open the `customerchurn.ipynb` notebook.
2. Follow the steps to preprocess the data, explore the dataset, and develop the machine learning models for churn prediction.
3. Run each cell sequentially to execute the code and visualize the results.

## Datasets

### Credit Card Fraud Detection
- **File**: `creditcard.csv`
- **Description**: This dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where there are 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

### Customer Churn Prediction
- **File**: `customerchurn.csv`
- **Description**: This dataset includes customer-level information for a telecom company. The data includes information about the customers' account information, demographic information, and services they have subscribed to. The goal is to predict whether a customer will churn (leave the company).
