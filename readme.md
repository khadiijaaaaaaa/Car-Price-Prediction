# Used Car Price Analysis and Prediction

This project involves analyzing a dataset of used cars to understand factors influencing their selling prices and preparing the data for predictive modeling. Visualizations and machine learning techniques are employed to derive insights and create a model to predict the selling prices of cars.

---

## Table of Contents
- [Dataset Description](#dataset-description)
- [Project Workflow](#project-workflow)
- [Libraries Used](#libraries-used)
- [Installation](#installation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Visualization Examples](#visualization-examples)

---

## Dataset Description

The dataset contains information about 301 used cars with the following features:
- `Car_Name`: Name of the car (removed during preprocessing).
- `Year`: Year of manufacturing.
- `Selling_Price`: Price the car was sold for (target variable).
- `Present_Price`: Current market price of the car.
- `Driven_kms`: Kilometers driven by the car.
- `Fuel_Type`: Type of fuel used (`Petrol`, `Diesel`, or `CNG`).
- `Selling_type`: Selling method (`Dealer` or `Individual`).
- `Transmission`: Type of transmission (`Manual` or `Automatic`).
- `Owner`: Number of previous owners.

## Project Workflow

1. Load and explore the dataset.
2. Perform exploratory data analysis (EDA) to identify patterns and trends.
3. Preprocess the data:
   - Remove unnecessary columns.
   - Encode categorical variables.
   - Derive additional features.
4. Visualize relationships and distributions.
5. Split the data into training and testing sets.
6. Train and test machine learning models.

---

## Libraries Used

- `pandas`: Data manipulation and preprocessing.
- `numpy`: Mathematical operations.
- `seaborn`: Data visualization.
- `matplotlib`: Plotting graphs.
- `scikit-learn`: Splitting data and machine learning.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/used-car-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd used-car-analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Exploratory Data Analysis (EDA)

Perform EDA to uncover patterns and relationships in the data. Key steps include:
1. Inspecting the dataset structure and summary statistics.
2. Visualizing distributions and correlations.
3. Identifying missing or inconsistent data.

---

## Data Preparation

Preprocess the data for analysis and modeling:
1. Remove the `Car_Name` column (irrelevant for prediction).
2. Convert the `Year` column into car age.
3. Encode categorical columns (`Fuel_Type`, `Selling_type`, `Transmission`) using one-hot encoding or label encoding.
4. Normalize or scale features if needed.
5. Split the dataset into training and test sets.

---

## Modeling

1. Train multiple regression models, such as:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
2. Evaluate model performance using metrics like:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

---

## Visualization Examples

- **Price vs. Driven Kilometers**: Understand how usage affects the price.
- **Fuel Type Distribution**: Analyze the popularity of different fuel types.
- **Correlation Heatmap**: Visualize relationships among numerical features.


```
