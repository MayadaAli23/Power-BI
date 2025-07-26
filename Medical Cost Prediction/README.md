# 🏥 Medical Insurance Cost Prediction

This project focuses on predicting individual medical insurance charges based on personal attributes such as age, BMI, smoking status, and region using supervised machine learning models.

---

## 📌 Objective

To build regression models that can accurately estimate **medical insurance costs**, and compare their performance using key evaluation metrics (MAE, RMSE, R²).

---

## 🧠 Steps Followed

1. **Data Understanding**
   - Loaded dataset and explored features.
   - Checked for missing values and data types.

2. **Data Cleaning & Preprocessing**
   - Removed duplicate records.
   - Checked and visualized outliers (especially in `bmi`, `age`, and `charges`).
   - Applied one-hot encoding on categorical features.
   - Split data into train/test sets.

3. **Exploratory Data Analysis (EDA)**
   - Visualized the relationship between:
     - `bmi` and `charges`
     - `smoking status` and `charges`
     - `age` and `charges`
   - Found smoking is the most influential feature on insurance costs.

4. **Model Building**
   - Trained 6 regression models:
     - Linear Regression
     - Random Forest (Before & After Tuning)
     - Gradient Boosting Regressor
     - XGBoost Regressor (Before & After Tuning)

5. **Model Evaluation**
   - Used:
     - MAE (Mean Absolute Error)
     - RMSE (Root Mean Squared Error)
     - R² Score (Coefficient of Determination)
   - Plotted residuals to assess model quality.
   - Compared models using a summary table & chart.

6. **📊 Power BI Dashboard**
   - Built 2 interactive dashboards:
     - **EDA Dashboard** – For data exploration and filtering.
     - **Model Comparison Dashboard** – Compare actual vs predicted charges & model performance.

---

## 🧪 Best Model Performance (After Tuning)

| Model                 | MAE     | RMSE     | R² Score |
|----------------------|---------|----------|----------|
| Random Forest (Tuned)| 2413.17 | 4231.91  | 0.90     |
| XGBoost (Tuned)      | 2530.86 | 4322.45  | 0.90     |
| Gradient Boosting    | 2517.47 | 4268.28  | 0.90     |

---

## 📂 Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib)
- **Power BI** (for data visualization and dashboarding)
- **Jupyter Notebook**
- **Git/GitHub**

---

## 📸 Snapshots

### 🔹 EDA Dashboard (Power BI)

<img width="1308" height="727" alt="image" src="https://github.com/user-attachments/assets/3f727676-ef66-4033-9ba1-f6cf986ac07c" />


### 🔹 Model Comparison Dashboard (Power BI)

<img width="1301" height="729" alt="image" src="https://github.com/user-attachments/assets/b90a40ac-72c8-4d38-97a2-1d5221892069" />

---

## 📎 Dataset Source

- [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## 💡 Insights

- **Smokers** pay significantly more than non-smokers.
- **BMI** has a noticeable impact on charges when it exceeds 30 (obesity).
- Age and number of children have moderate influence.

---


## 🙋‍♀️ Author


**Mayada Ali**  
_Data Analyst | Machine Learning Enthusiast_  
📫 [LinkedIn](https://www.linkedin.com/in/mayadaali23/) | [Email](mayada.ali.94@gmail.com)


