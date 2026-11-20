# food-delivery-time-prediction
Machine Learning project to predict food delivery time using Linear Regression and Logistic Regression.
#  Food Delivery Time Prediction Using Machine Learning

##  Project Overview

The **Food Delivery Time Prediction** project uses Machine Learning techniques to analyze food delivery data and predict the time required to complete a delivery.

The project explores how factors such as distance, traffic conditions, weather, delivery person experience, and order priority influence delivery time.

Two Machine Learning algorithms are explored:
- Linear Regression – To predict numerical delivery time.
- Logistic Regression – To classify deliveries into categories such as Fast and Delayed.

# Project Objectives

- Analyze food delivery data using Exploratory Data Analysis (EDA).
- Identify factors affecting delivery time.
- Perform data preprocessing and feature engineering.
- Build predictive models using Machine Learning.
- Evaluate model performance using appropriate metrics.
- Generate actionable insights to improve delivery operations.

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Project Structure

```text
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Prediction.ipynb
├── Food_Delivery_Time_Prediction.csv
├── Food_Delivery_Prediction_Report.pdf
└── README.md
```

# Project Workflow

## 1. Data Collection and Preprocessing
- Imported the dataset using Pandas.
- Checked missing and inconsistent values.
- Examined data types and dataset structure.
- Prepared categorical and numerical features.

## 2. Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical variables.
- Calculated descriptive statistics.
- Studied relationships between different features.
- Used visualizations to understand patterns and distributions.

## 3. Feature Engineering
- Encoded categorical variables.
- Applied One-Hot Encoding to Order_Time.
- Created a new feature called `peak_period` to distinguish peak and non-peak delivery periods.

## 4. Predictive Modeling

**Linear Regression**

Used to predict `Delivery_Time` based on features including:
- Distance
- Traffic_Conditions
- Order_Priority

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared (R²)

**Logistic Regression**

Used for classifying deliveries into Fast and Delayed categories.

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve

## 5. Model Evaluation

Compared actual and predicted delivery times and evaluated model performance using regression and classification metrics.

## Linear Regression Results

The following results were obtained during model evaluation:

| Evaluation Metric | Result |
|---|---:|
| Mean Squared Error | 915.37 |
| Mean Absolute Error | 25.48 |
| R-squared Score | 0.0103 |

The low R-squared score indicates that the Linear Regression model explains only a small proportion of the variation in delivery time. Further feature engineering and model improvement are required.

# Actionable Insights

Based on the project analysis, the following improvements can be considered:

- Optimize delivery routes to reduce travel time.
- Adjust delivery staffing during high-traffic periods.
- Improve delivery personnel training.
- Consider traffic and weather conditions when estimating delivery times.

# How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project directory:

```bash
cd food-delivery-time-prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Food_Delivery_Prediction.ipynb` and run the cells sequentially.

**Note:** Keep the CSV dataset in the same directory as the notebook. Update the dataset path in `pd.read_csv()` if necessary.

# Project Report

The detailed project report is available in the repository as a PDF file. It includes the project objectives, methodology, preprocessing, model evaluation, visualizations, and insights.

# Future Improvements

- Improve model performance through additional feature engineering.
- Experiment with Random Forest and Gradient Boosting algorithms.
- Perform hyperparameter tuning.
- Develop an interactive web application for delivery time prediction.
- Explore more advanced machine learning techniques.

# Author

Aditya Sachdev**

Machine Learning | Python | Data Science

---

⭐ If you find this project interesting, consider giving this repository a star!
