# Movies-Data-Analysis-Income-Prediction-EDA-Machine-Learning
This project analyzes movie datasets to extract insights on trends, genres, budgets, and revenues. It applies machine learning models to predict a movie’s income based on its attributes. Includes in-depth Exploratory Data Analysis (EDA), feature engineering, visualization, and predictive modeling with hyperparameter tuning.
# 🎬 Movies Data Analysis & Income Prediction

## 📊 Project Overview
The film industry generates massive data about movies, their production budgets, ratings, and revenue. This project explores a movie dataset to uncover patterns and uses **machine learning models** to predict **movie income** (box office revenue).

The workflow includes:
- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA) with visualization
- Feature engineering for categorical & numerical attributes
- Building regression & classification models
- Hyperparameter tuning for improved accuracy
- Model evaluation & comparison

---

## 📂 Dataset
Dataset used: **movies.csv**

Key features include:
- Title, Genre, Language
- Budget & Runtime
- Director & Cast info
- Ratings (IMDB, etc.)
- Revenue (Target variable for prediction)

---

## ⚙️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data preprocessing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning models)
- **XGBoost / RandomForest** (Advanced models)
- **Jupyter Notebook**

---

## 🧠 Machine Learning Models
The following algorithms were explored:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting / XGBoost
- Support Vector Regression (SVR)

**Hyperparameter tuning** was applied using GridSearchCV & RandomizedSearchCV.

---

## 📈 Key Insights
- High budget does not always guarantee high income — genres and audience ratings matter significantly.
- **Genre** and **IMDB ratings** were strong predictors of revenue.
- Ensemble models like **Random Forest** and **XGBoost** gave the most reliable performance.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/movies-income-prediction.git
   pip install -r requirements.txt
   jupyter notebook movies-data-analysis-and-income-prediction.ipynb

jupyter notebook movies-data-analysis-and-income-prediction.ipynb
jupyter notebook movies-data-analysis-and-income-prediction.ipynb
