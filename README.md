# 🎬 Box Office Revenue Prediction Using Linear Regression

## 📘 Project Description
This project focuses on predicting **box office revenue** for movies using **Linear Regression**, a fundamental algorithm in Machine Learning. The goal is to analyze different movie-related features (like budget, runtime, popularity, and votes) and understand their correlation with revenue generation.  
Through this project, we aim to demonstrate how regression techniques can be applied to real-world business and entertainment data to forecast financial performance.

---

## 🎯 Project Objective
The main objective of this project is to build a **predictive model** that estimates a movie’s box office revenue based on historical data.  
This helps production companies, analysts, and marketers:
- Estimate potential earnings before release.  
- Identify key factors influencing movie success.  
- Make informed investment and marketing decisions.

---

## 🧠 Project Motive
Movies involve huge investments, and predicting their potential success can save millions.  
The motive behind this project is to apply **machine learning regression techniques** to understand:
- How much each feature contributes to movie revenue.
- The linear relationship between movie attributes and total revenue.
- The effectiveness of a simple linear regression model in making accurate predictions.

---

## 📊 Dataset Information
The dataset contains information about various movies, including:
- `budget` — Production budget of the movie  
- `popularity` — Popularity score based on public interest  
- `runtime` — Duration of the movie  
- `vote_average` — Average rating given by viewers  
- `vote_count` — Total number of votes received  
- `revenue` — Actual box office revenue (Target variable)

---

## ⚙️ Technologies Used
- **Python**  
- **Pandas** — For data handling  
- **NumPy** — For numerical operations  
- **Matplotlib & Seaborn** — For data visualization  
- **Scikit-learn** — For model building and evaluation

---

## 🔍 Exploratory Data Analysis (EDA)
The dataset was analyzed to understand patterns and relationships between features.  
Some key insights:
- Movies with **higher budgets** tend to earn more revenue.  
- **Popularity** and **vote count** also show positive correlations with box office performance.  
- Certain outliers indicate blockbuster hits that heavily influenced the dataset.

---

## 🧩 Model Building
A **Linear Regression** model was trained to predict the revenue based on input features.  
Steps involved:
1. Data Cleaning and Preprocessing  
2. Feature Selection  
3. Splitting data into Training and Testing sets  
4. Model Training using Linear Regression  
5. Model Evaluation using performance metrics  

---

## 📈 Model Evaluation
The performance of the Linear Regression model was evaluated using:
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R² Score**

**Result Summary:**  
The Linear Regression model achieved an **R² score of approximately 0.78**, indicating a good fit for the data.  
This means the model successfully explains around **78% of the variance** in movie revenue based on the given features.

---

## 💡 Key Findings
- **Budget** and **popularity** are the most influential predictors of revenue.  
- A simple **Linear Regression** model performs reasonably well for this dataset.  
- Adding advanced models (like Random Forest or XGBoost) could further improve accuracy.

---

## 🧾 Conclusion
This project demonstrates how **Linear Regression** can be used effectively to predict movie revenue using a limited set of features.  
Although real-world box office performance depends on many unpredictable factors (like competition, marketing, or audience mood), this model provides a solid foundation for data-driven decision-making in the film industry.

---
