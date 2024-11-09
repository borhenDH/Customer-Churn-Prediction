# Customer Churn Prediction

This project aims to predict customer churn in a banking dataset using machine learning classification models. The goal is to identify customers who are likely to leave the bank, helping the company take proactive measures to retain them.

## Table of Contents
- [Description](#description)
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Models and Results](#models-and-results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Description

In this project, a bank's customer data is analyzed to predict whether a customer will churn (leave the bank). The dataset contains features such as **credit score**, **balance**, **age**, **tenure**, and others, which are used to train machine learning models. Three different models were tested: **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Random Forest**. The **Random Forest** model yielded the highest accuracy of **86%**, making it the most effective model for this task.

## Technologies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn for data visualization
- Jupyter Notebook (for exploration)

## Dataset

The dataset contains information about customers who have left the bank and those who have stayed. It includes features such as:
- `credit_score`
- `gender`
- `age`
- `tenure`
- `balance`
- `num_of_products`
- `has_credit_card`
- `is_active_member`
- `estimated_salary`
- `is_left` (target variable: whether the customer churned or not)

## Models and Results

### Models Tested:
- **Logistic Regression**: Used for baseline performance.
- **K-Nearest Neighbors (KNN)**: A simple but effective model.
- **Random Forest Classifier**: The most effective model with an accuracy of **86%**.

### Best Model:
- **Random Forest** was the best-performing model, providing an accuracy of **86%**. This model is robust and capable of handling non-linear relationships in the data.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-churn-prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-churn-prediction
    ```

3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook or Python script to begin analysis.
2. Modify the dataset or model parameters as needed for further experimentation.
3. Run the model training and prediction cells to generate results.

For prediction on new data, pass the data through the trained **Random Forest** model and use the `.predict()` method to obtain churn predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
