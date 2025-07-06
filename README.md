# Delivery-Time-Analysis

# Delivery Time Optimization using Customer Order Data

This project analyzes a simulated food delivery dataset to identify key factors affecting delivery times, with the goal of optimizing operations and improving customer experience.

## Objective
To explore patterns in food delivery delays and build a simple linear regression model to predict delivery time based on features such as:
- Traffic level
- Weather conditions
- Pickup delay
- Delivery distance
- Cuisine type

## Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- CSV (simulated dataset)

## Key Steps
1. **Data Cleaning & Preparation** – Handled time fields and engineered features
2. **Exploratory Data Analysis (EDA)** – Visualized delay patterns across traffic, weather, and cuisine
3. **Feature Engineering** – Converted categorical variables for modeling
4. **Predictive Modeling** – Trained a Linear Regression model with:
   - **R² Score:** 0.94
   - **RMSE:** ~4.2 minutes

## Sample Insights
- High traffic and rainy weather increased delivery times significantly
- Long pickup delays contributed more to delivery delay than distance
- Certain cuisines showed consistent delivery lag (e.g., Chinese during peak hours)

## Files Included
- `Swiggy_Delivery_Dataset.csv`: Simulated dataset
- `Delivery_Time_Analysis.ipynb`: Jupyter Notebook with full analysis

## How to Run
1. Clone this repo or download the files
2. Install required Python packages (`pandas`, `seaborn`, `scikit-learn`)
3. Open `Delivery_Time_Analysis.ipynb` and run the notebook step by step

## Author Notes
This is a beginner-friendly data analytics project built for practice. Ideal for anyone learning EDA, regression modeling, or trying to understand how real-world logistics data can be analyzed.
