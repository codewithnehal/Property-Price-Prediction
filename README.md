# 🏡 Property-Price-Prediction  

This project predicts **median house values** using housing data. It includes **EDA, preprocessing, and regression models** (Linear, Ridge, Lasso) with evaluation using **MSE, RMSE, and R²**. The best model is saved for future predictions.  

---

## 📌 Project Overview  
The aim of this project is to build a **machine learning model** that can predict housing prices based on district-level features. It demonstrates the **end-to-end workflow** of a regression problem, starting from **data exploration** to **model training, evaluation, and saving the best model** for reuse.  

---

## 📂 Features Implemented  
- **Exploratory Data Analysis (EDA):**  
  - Distribution plots and histograms  
  - Correlation heatmaps  

- **Data Preprocessing:**  
  - Handling missing values  
  - Encoding categorical variables with **OneHotEncoder**  
  - Scaling numerical features with **StandardScaler**  

- **Regression Models:**  
  - **Simple Linear Regression** (using median income)  
  - **Multiple Linear Regression**  
  - **Regularized Models**: Ridge and Lasso with hyperparameter tuning  

- **Evaluation Metrics:**  
  - **Mean Squared Error (MSE)**  
  - **Root Mean Squared Error (RMSE)**  
  - **R² Score**  

- **Model Persistence:**  
  - The best-performing model is saved using **joblib** for future predictions  

---

## 📊 Dataset  
- The dataset contains district-level housing data.  
- Target column: **`median_house_value`**  
- Includes numerical and categorical features (e.g., income, population, location proximity)  
- Supports CSV/Excel/Google Sheets links  

---

## 🚀 Installation & Setup  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/Property-Price-Prediction.git
   cd Property-Price-Prediction
