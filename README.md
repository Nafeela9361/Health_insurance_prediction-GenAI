# 🏥 Health Insurance Premium Prediction

## 📌 Project Overview

This project focuses on predicting **health insurance premiums** using **Machine Learning**. The notebook demonstrates a complete end-to-end regression workflow, starting from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and prediction on new data.

The objective is to estimate an individual's insurance premium based on demographic and lifestyle-related features such as age, gender, BMI, smoking status, number of dependents, and region. Accurate premium prediction can help insurance companies streamline pricing strategies while enabling customers to better estimate their expected insurance costs.

---

## 🎯 Objectives

* Analyze the health insurance dataset.
* Clean and preprocess the data.
* Perform Exploratory Data Analysis (EDA).
* Encode categorical variables for machine learning.
* Train a Random Forest Regressor model.
* Evaluate model performance using regression metrics.
* Predict insurance premiums for new customer data.

---

## 📂 Dataset Features

The dataset contains the following features:

| Feature             | Description                                |
| ------------------- | ------------------------------------------ |
| Age                 | Age of the customer                        |
| Gender/Sex          | Gender of the customer                     |
| BMI                 | Body Mass Index                            |
| Children/Dependents | Number of dependents covered               |
| Smoker              | Smoking status                             |
| Region              | Residential region                         |
| Charges             | Health insurance premium (Target Variable) |

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook / Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Project Workflow

1. Import the required libraries.
2. Load the dataset.
3. Explore the data.
4. Handle missing values (if any).
5. Perform Exploratory Data Analysis (EDA).
6. Encode categorical variables.
7. Split the dataset into training and testing sets.
8. Train the Random Forest Regressor model.
9. Evaluate the model using regression metrics.
10. Predict insurance premiums for unseen customer data.

---

## 🤖 Machine Learning Model

The project uses the **Random Forest Regressor**, an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting. It is well-suited for regression tasks involving complex, non-linear relationships between features and the target variable.

---

## 📈 Model Evaluation

The model performance is evaluated using the following regression metrics:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**

These metrics help measure how accurately the model predicts insurance premiums.

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes several visualizations to better understand the dataset, including:

* Distribution of insurance charges
* Age distribution
* BMI distribution
* Smoking status analysis
* Correlation heatmap
* Feature relationships
* Box plots for outlier detection

---

## 🚀 Prediction on New Data

After training, the model can predict insurance premiums for new customer records. This demonstrates how the trained model can be used in real-world applications to estimate expected insurance costs.

---

## 📁 Repository Structure

```text
Health-Insurance-Prediction/
│
├── Health_Insurance_Prediction.ipynb
├── insurance.csv
├── README.md
```

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Run all cells sequentially.
5. Train the model and make predictions on new data.

---

## 💡 Future Improvements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Compare multiple regression algorithms.
* Deploy the model using Flask or FastAPI.
* Build an interactive web application using Streamlit.
* Integrate real-time prediction through a REST API.

---

## 📚 Learning Outcomes

Through this project, you will learn:

* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Feature encoding
* Regression model development
* Model evaluation
* Predicting unseen data using machine learning

---

## 📜 License

This project is intended for educational and learning purposes. Feel free to fork, modify, and enhance the project for your own learning.
