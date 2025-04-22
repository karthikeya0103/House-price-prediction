# 🏡 Housing Price Prediction using Linear Regression

This project demonstrates how to use **Linear Regression** to predict housing prices based on various features such as location, number of rooms, and area. The analysis includes **exploratory data analysis (EDA)**, model training, performance evaluation, and interpretation.

---

## 📊 Dataset: `housing.csv`

The dataset contains historical housing data including:

- Number of rooms
- Area (square footage)
- Distance from city center
- Crime rate
- Tax rate
- And other regional or structural features

Each row represents a unique housing instance.

---

## 🎯 Project Objective

> Use linear regression to predict the **median housing price** based on available features, and evaluate the model’s accuracy and assumptions.

---

## 🧠 Machine Learning Workflow

1. Load and preprocess the housing data
2. Visualize feature distributions and relationships
3. Split data into training and testing sets
4. Train a **Linear Regression** model
5. Evaluate using **MSE** and **R² score**
6. Analyze residuals to validate assumptions

---

## 📈 Model Performance

| Metric | Value (example) |
|--------|-----------------|
| **R² Score** | 0.74 |
| **Mean Squared Error (MSE)** | 21.89 |

> These metrics may vary based on feature selection and scaling.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `housing.csv` | The dataset used for training and testing |
| `linear_regression.ipynb` | Full notebook with EDA, model training, and results |
| `README.md` | Documentation for the project |

---

## 🚀 How to Run This Project

1. Clone the repository
2. Install required libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
```
3.Launch the notebook:
```bash
jupyter notebook
```
4.Open and run linear_regression.ipynb