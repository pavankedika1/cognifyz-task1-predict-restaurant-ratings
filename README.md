# 🍽️ Restaurant Rating Prediction Using Machine Learning
## 📌 Project Overview
This project aims to predict the **Aggregate Rating** of restaurants using Machine Learning techniques. 
The model is trained on restaurant-related features such as cuisines, cost, votes, online delivery, and table booking availability.
The project demonstrates the complete Machine Learning workflow, including data preprocessing, model training, evaluation, and feature importance analysis.
---
## 🎯 Objective
Build a Machine Learning model to predict restaurant aggregate ratings based on various restaurant features.
--
## 📂 Dataset
The dataset contains information about restaurants, including:
* Restaurant Name
* City
* Country Code
* Cuisines
* Average Cost for Two
* Currency
* Has Table Booking
* Has Online Delivery
* Price Range
* Votes
* Aggregate Rating (Target Variable)
---

## 🛠️ Project Workflow
### 1. Data Preprocessing
* Loaded the dataset using Pandas.
* Handled missing values using imputation techniques.
* Encoded categorical variables using One-Hot Encoding.
* Split the dataset into training and testing sets.

### 2. Model Training
* Selected **Decision Tree Regression** as the prediction algorithm.
* Trained the model on the training dataset.

### 3. Model Evaluation
The model performance was evaluated using:
* Mean Squared Error (MSE)
* R² Score

### 4. Feature Importance Analysis
* Identified the most influential features affecting restaurant ratings.
* Analyzed how different restaurant characteristics impact customer ratings.
---

## 💻 Technologies Used
* Python
* Pandas
* NumPy
* Scikit-Learn
---

## 📊 Machine Learning Algorithm
* Decision Tree Regressor
---

## 📈 Results
The model successfully learned patterns from the restaurant dataset and predicted aggregate ratings based on restaurant features.

Important factors influencing ratings include:
* Votes
* Price Range
* Average Cost for Two
* Online Delivery Availability
* Table Booking Availability
* Cuisines
---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/cognifyz-task1-predict-restaurant-ratings.git
```
2. Navigate to the project directory:
```bash
cd cognifyz-task1-predict-restaurant-ratings
```
3. Install required libraries:
```bash
pip install pandas numpy scikit-learn
```
4. Run the Python script:
```bash
python restaurant_rating_prediction.py
```

## 🎓 Learning Outcomes
Through this project, I gained practical experience in:'
* Data Preprocessing
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Feature Importance Analysis
* End-to-End Machine Learning Workflow
---

## 👨‍💻 Author
Pavan Kedika
Machine Learning Internship Project
