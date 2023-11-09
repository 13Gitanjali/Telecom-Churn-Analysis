# Telecom Churn Analysis

## Project Overview
This project aims to predict customer churn in the telecom industry over a span of four consecutive months. The business objective is to predict the churn in the last month using the data from the first three months. The months are encoded as 6, 7, 8 and 9, respectively.

## Understanding Customer Behaviour During Churn
Customers usually do not decide to switch to another competitor instantly, but rather over a period of time. In churn prediction, we assume that there are three phases of customer lifecycle:
1. The ‘good’ phase: In this phase, the customer is happy with the service and behaves as usual.
2. The ‘action’ phase: The customer experience starts to sore in this phase. In this phase, the customer usually shows different behaviour than the ‘good’ months.
3. The ‘churn’ phase: In this phase, the customer is said to have churned. You define churn based on this phase.

## Dataset
The dataset used in this project is from a telecom company and includes customer-level information.

## Data Preparation
The following data preparation steps are crucial for this problem:
1. Derive new features: This is one of the most important parts of data preparation since good features are often the differentiators between good and bad models.
2. Filter high-value customers: Those who have recharged with an amount more than or equal to X, where X is the 70th percentile of the average recharge amount in the first two months (the good phase).
3. Tag churners and remove attributes of the churn phase: Now tag the churned customers (churn=1, else 0) based on the fourth month.

## Requirements
- Python 3.7+
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
1. Clone the repository: `git clone https://github.com/13Gitanjali/telecom-churn-analysis.git`
2. Install the requirements: `pip install -r requirements.txt`

## Usage
Run the main script to start the analysis: `python main.py`

## Results
The results of the analysis will be saved in the `results` directory.

## Contributing
Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

