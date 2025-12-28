# 🏘️ Multiple Linear Regression with Categorical Encoding  

📌 A Machine Learning mini project demonstrating **Multiple Linear Regression**
using both **numerical and categorical features**, handled through
**Dummy Variables, Label Encoding, and One-Hot Encoding**.

---

## 📖 About  
This project focuses on **Multiple Linear Regression**, where **more than one independent
variable** is used to predict house prices.  
Along with numerical features (area), the project handles **categorical data (town)**
using different encoding techniques so it can be used by ML models.

---

## 📊 Dataset  
The project uses a CSV dataset (`dummy.csv`) containing:
- 🏡 **Area** of the house *(numerical feature)*  
- 🏙️ **Town** *(categorical feature)*  
- 💰 **Price** *(target variable)*  

---

## ✨ Concepts Covered  
- 📐 Multiple Linear Regression  
- 🔤 Categorical variables in Machine Learning  
- 🧩 Dummy Variables using `pd.get_dummies()`  
- 🚫 Avoiding **dummy variable trap / multicollinearity**  
- 🔁 Label Encoding  
- 🧠 One-Hot Encoding using `ColumnTransformer`  

---

## 🛠️ Approach  
1. Load dataset using Pandas  
2. Convert categorical feature (`town`) into dummy variables  
3. Drop one dummy column to avoid multicollinearity  
4. Train a **Multiple Linear Regression** model  
5. Make predictions using multiple input features  
6. Apply Label Encoding and One-Hot Encoding using `sklearn` utilities  

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Encode categorical variables  
   - Train the regression model  
   - Predict house prices  

---

## 🧠 Model  
- Algorithm: **Multiple Linear Regression**  
- Feature handling:
  - Numerical feature: area  
  - Categorical feature: town (encoded using dummy & one-hot encoding)

---

## 📈 Results  
The model successfully predicts house prices using **multiple variables**, demonstrating
how categorical encoding techniques enable regression models to work with real-world data.

---

🚀 *Part of my journey to master Machine Learning through hands-on mini projects!*  

