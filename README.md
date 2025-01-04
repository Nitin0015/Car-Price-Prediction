# **Car Price Prediction**

This repository contains a Jupyter Notebook that demonstrates how to predict the selling price of used cars based on their features using machine learning techniques. The dataset used in this project provides information about various car attributes and their corresponding selling prices.

---

## **Overview**

The goal of this project is to predict the selling price of a used car based on its features such as age, present price, kilometers driven, fuel type, and more. This project uses **Linear Regression** and **Lasso Regression** models to perform the prediction. 

The dataset includes features like car model, year of manufacture, and seller type, with the target variable (`Selling_Price`) representing the price at which the car was sold.

---

## **Dataset**

- **Source**: The dataset appears to be related to publicly available car price datasets.
- **Features**:
  - `Car_Name`: Name of the car.
  - `Year`: Year of manufacture.
  - `Selling_Price`: Price at which the car was sold (target variable).
  - `Present_Price`: Current ex-showroom price of the car.
  - `Kms_Driven`: Distance in kilometers driven by the car.
  - `Fuel_Type`: Type of fuel used by the car (e.g., Petrol, Diesel).
  - `Seller_Type`: Whether the seller is a dealer or an individual.
  - `Transmission`: Type of transmission (Manual/Automatic).
  - `Owner`: Number of previous owners.

---

## **Project Workflow**

1. **Data Loading**:
   - The dataset (`car data.csv`) is loaded into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics and visualizations are used to understand relationships between features and the target variable.
3. **Data Preprocessing**:
   - Categorical variables are encoded into numerical values for machine learning models.
4. **Model Training**:
   - Two models are trained:
     - Linear Regression
     - Lasso Regression
   - The dataset is split into training and testing sets using `train_test_split`.
5. **Model Evaluation**:
   - Performance metrics such as Mean Absolute Error (MAE) and R² score are calculated to evaluate model performance.

---

## **Dependencies**

To run this project, you need the following Python libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/CarPricePrediction.git
   cd CarPricePrediction
   ```

2. Ensure that the dataset file (`car data.csv`) is in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Car-Price-Pred.ipynb
   ```

4. Run all cells in the notebook to execute the code.

---

## **Results**

The Linear Regression and Lasso Regression models provide predictions for car selling prices based on their features. Evaluation metrics such as MAE and R² score indicate how well each model performs in predicting prices.

---

## **Acknowledgments**

- The dataset was sourced from publicly available car price datasets or competitions.
- Special thanks to Scikit-learn for providing robust machine learning tools.

---
