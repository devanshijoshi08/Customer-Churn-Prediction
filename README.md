# E-commerce Customer Churn Analysis

## Overview
This project focuses on analyzing customer churn data for an E-commerce platform. Churn prediction is critical for the business to understand the attributes leading to customer turnover and to develop strategies to retain valuable customers.

## Dataset Description
Dataset link: [E-commerce Dataset](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)
The dataset used in this analysis is `ecommerce.csv`, which contains various features related to customer behavior and their churn status. Here's a brief overview of some of the key features:

- `CustomerID`: Unique identifier for the customer
- `Churn`: Churn flag indicating whether the customer has churned (1) or not (0)
- `Tenure`: Duration of customer association with the platform
- `PreferredLoginDevice`, `PreferredPaymentMode`, `PreferedOrderCat`: Preferences of the customer
- `SatisfactionScore`: Satisfactory score of customer on service
- `CashbackAmount`: Average cashback received by the customer

*For a full list of features and descriptions, please refer to the variable descriptions within the Jupyter notebook.*

## Files
- `ecommerce.csv`: The dataset file.
- `churn_analysis.ipynb`: Jupyter notebook containing the exploratory data analysis and predictive modeling.
- `requirements.txt`: List of packages required to run the analysis.

## Setup Instructions
To run this project, you need to have Python installed on your machine. I recommend using a virtual environment.

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the cloned repository directory.

3. Create a virtual environment:

   ```sh
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:
     ```sh
     venv\Scripts\activate
     ```
   - On MacOS/Linux:
     ```sh
     source venv/bin/activate
     ```

5. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

6. Run Jupyter notebook:

   ```sh
   jupyter notebook
   ```

7. Open `CustomerChurnPrediction.ipynb` in Jupyter Notebook to view the analysis.

## Analysis Workflow
The analysis consists of several stages:

1. Data Understanding: Explored the dataset to understand the distribution and relationships of various features.
2. Data Preprocessing: Handled missing values, encode categorical variables, and remove outliers.
3. Exploratory Data Analysis (EDA): Visualized the data to uncover insights and trends that influence churn.
4. Feature Engineering: Created new features that could improve the predictive poIr of our models.
5. Predictive Modeling: Built machine learning models to predict customer churn and evaluate their performance.
