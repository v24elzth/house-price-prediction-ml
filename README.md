# 🏠 House Price Prediction using Machine Learning

A data-driven machine learning project designed to estimate fair house prices objectively. This project explores various regression models to predict property values based on physical attributes such as living area, lot size, number of bedrooms, and building age[cite: 2].

## 🌟 Project Overview
Determining the right selling price for a property is a complex challenge in the real estate industry[cite: 2]. This project aims to solve that by evaluating and comparing three different machine learning approaches:
*   **Univariate Regression:** Analyzing the impact of a single feature (`sqft_lot`) on the house price[cite: 2].
*   **Multivariate Regression:** Combining multiple features (living area, year built, bedrooms, bathrooms, floors) to improve prediction accuracy[cite: 2].
*   **Polynomial Regression:** Capturing non-linear patterns, such as the fluctuation of property value based on building age[cite: 2].

## 🗂️ Repository Structure
*   **`predict_housing_price.ipynb`**: The main Jupyter Notebook containing the data preprocessing, exploratory data analysis (EDA), data visualization, model training, and evaluation.
*   **`Housing.csv`**: The original raw dataset sourced from Kaggle.
*   **`dataset_housing-price.csv`**: The cleaned and filtered dataset (300 samples) used for model training.

## 🛠️ Technologies Used
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 📊 Model Evaluation Metrics
The models are evaluated and compared using comprehensive regression metrics to find the most optimal approach:
*   Mean Squared Error (MSE)
*   Root Mean Squared Error (RMSE)
*   Mean Absolute Error (MAE)
*   R-Squared ($R^2$)

## 🚀 How to Run
1. **Clone this repository** to your local machine.
2. **Install dependencies:** Ensure you have Python and Jupyter Notebook installed. You will also need the following libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. **Run the Notebook**: Open `predict_housing_price.ipynb` and run all cells sequentially to view the data processing, scatterplots, and model evaluation results[cite: 2].
