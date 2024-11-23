# Advanced Machine Learning Project: Predicting Revenue

## 📌 Project Overview

This project leverages advanced machine learning techniques to analyze and predict **Revenue** based on a dataset of various features, including numerical and categorical data. The goal is to build a robust predictive model using ensemble methods, perform hyperparameter tuning, and evaluate the model's performance with appropriate metrics.  

The project demonstrates an end-to-end pipeline for preprocessing, feature engineering, model training, and evaluation using techniques like Gradient Boosting, GridSearchCV, and advanced feature transformations.

---

## 📂 Dataset Description

The dataset contains features from a business context, to predict the target variable: **Revenue generated**. It includes:

- **Numerical Features**: Price, Availability, Number of products sold, Revenue generated, Stock levels, Lead times, Order quantities, Shipping times, Shipping costs, Lead time, Production volumes, Manufacturing lead time, Manufacturing costs, Defect rates, Costs
- **Categorical Features**: Product type, SKU, Customer demographics, Shipping carriers, Supplier name, Location, Inspection results, Transportation modes, Routes

Ensuring to preprocess the dataset appropriately by handling missing values, encoding categorical features, and scaling numerical features.

---

## 🔧 Techniques and Tools Used

### Data Preprocessing
- **Scaling Numerical Data**: StandardScaler
- **Encoding Categorical Data**: OneHotEncoder
- **Handling Missing Values**: Drop or Impute strategies
- **Feature Engineering**: Polynomial and Interaction terms (if applicable)

### Machine Learning Techniques
- **Gradient Boosting**: A powerful ensemble learning technique for regression.
- **Hyperparameter Tuning**: GridSearchCV is used to optimize model performance.
- **Pipeline Implementation**: Automating preprocessing and model training.

### Libraries Used
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical computations.
- **Scikit-learn**: Machine learning models and utilities.
- **Matplotlib/Seaborn**: Data visualization.

---

## 💻 Project Workflow

### 1. Data Preprocessing
- Exploratory Data Analysis (EDA) to understand the data distribution and feature relationships.
- Handling missing data, encoding categorical variables, and scaling numerical features.
- Splitting the dataset into training and testing sets (80/20 split).

### 2. Model Training
- **Gradient Boosting Regressor** as the baseline model.
- Training the model with default parameters.
- Evaluate performance using metrics like Mean Squared Error (MSE) and R² Score.

### 3. Hyperparameter Tuning
- Tuning parameters such as:
  - Number of estimators.
  - Learning rate.
  - Maximum depth of trees.
  - Subsampling rate.
- Using **GridSearchCV** to find the best parameters.

### 4. Final Evaluation
- Testing the best model on the test dataset.
- Report improved metrics and compare them against baseline performance.

---

## 📊 Results and Evaluation

- **Baseline Performance**:
  - Mean Squared Error: `1.56`
  - R² Score: `-0.44`

- **After Hyperparameter Tuning**:
  - Mean Squared Error: `1.21`
  - R² Score: `-0.12`

---

## 🚀 How to Run the Project

### Prerequisites
Ensure you have Python installed along with the following libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
