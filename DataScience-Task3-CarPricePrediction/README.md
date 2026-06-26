# Car Price Prediction with Machine Learning

## Overview

This project develops and evaluates machine learning regression models to predict the selling price of used cars based on vehicle characteristics. The workflow covers data preprocessing, feature engineering, exploratory data analysis, model development, performance evaluation, and model persistence using Python and Scikit-learn.

---

## Objective

Build a regression model capable of estimating the selling price of a used car using features such as vehicle brand, age, present price, kilometers driven, fuel type, seller type, transmission, and ownership history.

---

## Dataset

The project uses the **Vehicle Dataset from CarDekho**, containing historical information about used cars listed for sale.

### Features

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Workflow

1. Import Required Libraries
2. Dataset Loading
3. Initial Data Inspection
4. Data Cleaning and Feature Engineering
5. Exploratory Data Analysis
6. Data Preprocessing
7. Model Development
8. Model Evaluation
9. Feature Importance Analysis
10. Model Persistence
11. Dataset Summary
12. Conclusion

---

## Data Preprocessing

The following preprocessing steps were performed:

- Standardized column names
- Standardized categorical values
- Removed duplicate records
- Extracted vehicle brand from the car name
- Calculated car age from the manufacturing year
- Removed unnecessary features after feature engineering

---

## Exploratory Data Analysis

The project includes:

- Selling Price Distribution
- Selling Price by Fuel Type
- Selling Price vs. Car Age
- Feature Correlation Heatmap
- Top 10 Brands by Average Selling Price

Each visualization is accompanied by observations describing the underlying trends.

---

## Feature Engineering

Additional predictive features were created to improve model performance.

- Brand extracted from the vehicle name
- Car Age calculated using the manufacturing year

---

## Machine Learning Models

The following regression algorithms were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

## Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was selected based on overall predictive performance.

---

## Model Persistence

The final trained model is stored using Joblib for future predictions.

```
outputs/models/car_price_prediction_model.pkl
```

Model comparison results are exported as:

```
outputs/model_comparison.csv
```

---

## Project Structure

```text
DataScience-Task3-CarPricePrediction
│
├── data
│   └── car data.csv
│
├── notebooks
│   └── Car_Price_Prediction.ipynb
│
├── outputs
│   ├── images
│   │   ├── selling_price_distribution.png
│   │   ├── price_vs_fuel_type.png
│   │   ├── price_vs_car_age.png
│   │   ├── correlation_heatmap.png
│   │   ├── top_brands.png
│   │   └── feature_importance.png
│   │
│   ├── models
│   │   └── car_price_prediction_model.pkl
│   │
│   └── model_comparison.csv
│
└── README.md
```

---

## How to Run

1. Clone the repository.

2. Create and activate a Python virtual environment.

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Open:

```
DataScience-Task3-CarPricePrediction/notebooks/Car_Price_Prediction.ipynb
```

5. Run all notebook cells sequentially.

---

## Key Outcomes

- Developed a complete machine learning regression workflow.
- Engineered additional predictive features from raw data.
- Compared multiple regression algorithms using standard evaluation metrics.
- Identified the best-performing model through quantitative evaluation.
- Saved the trained model for future inference.
- Produced professional visualizations and analytical insights from the dataset.

---

## Future Improvements

- Perform hyperparameter optimization for improved prediction accuracy.
- Deploy the trained model using Flask or FastAPI.
- Build an interactive web interface using Streamlit.
- Integrate real-time vehicle market data.
- Expand the model using larger and more diverse automobile datasets.
