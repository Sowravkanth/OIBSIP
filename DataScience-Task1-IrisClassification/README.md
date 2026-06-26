# Iris Flower Classification

## Overview

This project develops a supervised machine learning classification model to predict the species of an Iris flower using its sepal and petal measurements. The workflow includes data exploration, visualization, preprocessing, model training, evaluation, comparison, and model persistence.

---

## Objective

Develop and evaluate multiple machine learning classification models to accurately classify Iris flowers into one of the following species:

- Setosa
- Versicolor
- Virginica

---

## Dataset

The project uses the Iris dataset available through the `scikit-learn` library.

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

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
2. Load the Dataset
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Data Preprocessing
6. Model Development
7. Model Evaluation
8. Model Comparison
9. Model Persistence
10. Conclusion

---

## Machine Learning Models

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **93.33%** |
| K-Nearest Neighbors | **93.33%** |
| Decision Tree | **93.33%** |
| Random Forest | **90.00%** |

Three models achieved the highest accuracy of **93.33%**. Logistic Regression was selected as the persisted model due to its simplicity, computational efficiency, and strong generalization performance.

---

## Project Structure

```text
DataScience-Task1-IrisClassification
│
├── data
│   └── .gitkeep
│
├── notebooks
│   └── Iris_Flower_Classification.ipynb
│
├── outputs
│   ├── images
│   └── models
│       └── iris_classifier.pkl
│
└── README.md
```

---

## Output Files

### Visualizations

- Class Distribution
- Pair Plot
- Correlation Heatmap
- Model Accuracy Comparison

### Saved Model

- iris_classifier.pkl

---

## How to Run

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```
DataScience-Task1-IrisClassification/notebooks/Iris_Flower_Classification.ipynb
```

5. Run all cells sequentially.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust evaluation
- Additional classification algorithms
- Model deployment using Streamlit or Flask

---
