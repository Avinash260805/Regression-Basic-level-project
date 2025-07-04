# 📊 Linear Regression: Predicting Student Exam Scores

This project applies **Linear Regression** using `scikit-learn` to predict student exam scores based on the number of hours they studied. It's a beginner-friendly ML project that covers the complete model building pipeline — from loading data to evaluating the model and visualizing results.

---

## 📁 Dataset

- **Columns:**  
  - `Hours`: Number of study hours  
  - `Scores`: Corresponding exam scores

- **Source:** Public dataset for educational purposes (uploaded manually)

---

## 🚀 Project Workflow

### 1. 📦 Importing Libraries
- `pandas` for data handling  
- `matplotlib` for visualization  
- `sklearn` for machine learning model

### 2. 🔍 Exploratory Data Analysis (EDA)
- Checked dataset structure with `head()`  
- Verified data types and confirmed it's clean

### 3. 🔁 Data Splitting
- Used `train_test_split()` to divide the data  
- **80% training**, **20% testing**  
- Set `random_state=42` for reproducibility

### 4. 🤖 Model Training
- Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`

### 5. 📈 Prediction & Evaluation
- Calculated model predictions using `predict()`  
- Evaluated using **R² score** and **MSE**

### 6. 📊 Visualization
- Plotted **actual vs predicted** scores  
- Saved the regression plot as `images/regression_plot.png`

---

## 📊 Results

- **R² Score:** `0.96` (96% accuracy)
- The model fits the data very well with minimal error
- Visualization confirms strong linear relationship


---

## 🧠 What I Learned

- Basics of supervised learning (regression)
- How to use `scikit-learn` for training models
- Importance of train-test split and evaluation
- Visualizing ML results for better understanding

---

