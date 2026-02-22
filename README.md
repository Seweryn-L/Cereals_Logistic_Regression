# Cereal Nutrition Analysis & Low-Calorie Classification

## Project Overview
This project performs an exploratory data analysis (EDA) and binary classification on a dataset of breakfast cereals. The primary objective is to identify "low-calorie" products and evaluate the classification performance using advanced metrics like the Precision-Recall curve.

## Key Features

### 1. Data Processing & Exploration
* **Nutritional Analysis**: The project processes data including calories, sugars, and manufacturer information for various cereal brands.
* **Target Labeling**: A binary classification target is created where cereals with calories below a certain threshold (e.g., 100 kcal) are labeled as "low-calorie".

### 2. Statistical Analysis & Visualization
* **Correlation Study**: Analysis of the relationship between different nutritional values (e.g., how sugar content affects calorie count).
* **Data Distribution**: Visualizing the distribution of calories across different manufacturers and product types.

### 3. Classification & Performance Metrics
The project goes beyond simple accuracy to evaluate the model's ability to identify healthy options:
* **Precision-Recall Curve**: A detailed visualization of the trade-off between precision (exactness) and recall (completeness).
* **Average Precision (AP)**: Calculation of the AP score to summarize the weighted mean of precisions achieved at each threshold.
* **Step-fill Visualization**: Implementation of a shaded step plot to represent the area under the Precision-Recall curve.

## Technologies Used
* **Python** (Jupyter Notebook)
* **Pandas**: For data cleaning and feature engineering.
* **Matplotlib & Seaborn**: For generating professional statistical plots and the Precision-Recall curve.
* **Scikit-learn**: For calculating `average_precision_score` and `precision_recall_curve` metrics.

## How to Run
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn