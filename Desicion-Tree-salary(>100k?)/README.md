# 🌳 Decision Tree Classifier – Salary Prediction  

📌 A Machine Learning mini project demonstrating a **Decision Tree Classifier**
to predict whether a person’s **salary is over 100K or not** based on categorical features.

---

## 📖 About  
This project uses a **Decision Tree Classifier** to solve a **binary classification**
problem where the goal is to predict salary category using information such as
company, job role, and education level.

Since Machine Learning models work with numbers, **categorical features are converted
into numerical form using Label Encoding** before training the model.

---

## 📊 Dataset  
The project uses a CSV dataset (`tree.csv`) containing:
- 🏢 **Company** *(categorical)*  
- 💼 **Job role** *(categorical)*  
- 🎓 **Degree** *(categorical)*  
- 💰 **Salary** *(target: over 100K or not)*  

---

## ✨ Concepts Covered  
- 🌳 Decision Tree Classifier  
- 🔤 Handling categorical variables  
- 🔁 Label Encoding  
- 🧮 Feature transformation  
- 🎯 Binary classification  

---

## 🛠️ Approach  
1. Load dataset using Pandas  
2. Separate input features and target variable  
3. Convert categorical features into numerical values using **LabelEncoder**  
4. Train a **Decision Tree Classifier**  
5. Predict salary category for new input data  

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Encode categorical features  
   - Train the decision tree model  
   - Predict salary class  

---

## 🧠 Model  
- Algorithm: **Decision Tree Classifier**  
- Input features: company, job, degree (label-encoded)  
- Output: salary **>100K or ≤100K**

---

## 📈 Results  
The model successfully predicts whether a person’s salary is above 100K based on
categorical input features, demonstrating how Decision Trees can handle encoded
categorical data effectively.

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
