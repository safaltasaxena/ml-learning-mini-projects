# 🚢 Logistic Regression – Titanic Survival Prediction  

📌 A Machine Learning mini project demonstrating **Logistic Regression**
to predict passenger survival on the Titanic using **binary classification**.

---

## 📖 About  
This project uses the famous **Titanic dataset** to build a **Logistic Regression**
model that predicts whether a passenger survived or not based on personal
and travel-related features.

The focus is on **data preprocessing, categorical encoding, and model evaluation**.

---

## 📊 Dataset  
Dataset used: `Titanic-Dataset.csv`

### Features used:
- 👤 Pclass  
- 🎂 Age  
- 🧍 Sex *(categorical)*  
- 👨‍👩‍👧 SibSp  
- 👶 Parch  
- 💰 Fare  
- 🚢 Embarked *(categorical)*  

### Target:
- ❤️ **Survived** (0 = No, 1 = Yes)

---

## ✨ Concepts Covered  
- 📉 Logistic Regression  
- 🔢 Binary classification  
- 🧩 Handling categorical variables using **Dummy Encoding**  
- 🚫 Avoiding dummy variable trap  
- 🧹 Handling missing values (median imputation)  
- 🔀 Train–test split  
- 📊 Model evaluation using **Classification Report**

---

## 🛠️ Approach  
1. Load the dataset using Pandas  
2. Drop irrelevant columns (`PassengerId`, `Name`, `Ticket`, `Cabin`)  
3. Convert categorical features (`Sex`, `Embarked`) into dummy variables  
4. Drop one dummy column per feature to avoid multicollinearity  
5. Handle missing values in `Age` using median  
6. Split data into training and testing sets  
7. Train a **Logistic Regression** model  
8. Evaluate model performance using precision, recall, and F1-score  

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Preprocess the data  
   - Train the logistic regression model  
   - Evaluate predictions  

---

## 🧠 Model  
- Algorithm: **Logistic Regression**
- Type: **Binary Classification**
- Evaluation: `classification_report`

---

## 📈 Results  
The model successfully predicts passenger survival and demonstrates
how Logistic Regression can be applied to real-world classification problems
after proper data preprocessing.

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
