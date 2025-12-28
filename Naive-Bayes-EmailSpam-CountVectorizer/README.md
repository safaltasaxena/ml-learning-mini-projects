# 📧 Naive Bayes Classifier – Titanic Survival & Spam Detection  

📌 A Machine Learning mini project demonstrating **Naive Bayes Classification**
on both **numerical data** and **text data**, covering real-world use cases.

---

## 📖 About  
This project explores the **Naive Bayes algorithm** using two different datasets:

1️⃣ **Titanic Survival Prediction** using **Gaussian Naive Bayes**  
2️⃣ **Spam Email Detection** using **Multinomial Naive Bayes**

The project highlights how different Naive Bayes variants are used depending on
the **nature of the data**.

---

## 📊 Datasets Used  

### 🚢 Titanic Dataset (`Titanic-Dataset.csv`)
Features:
- 🎂 Age  
- 🚻 Sex *(categorical)*  
- 💰 Fare  
- 🎯 Target: Survived (0 or 1)

Irrelevant features are dropped and missing values are handled before training.

---

### 📧 Spam Dataset (`spam.csv`)
Features:
- ✉️ Message (text data)  
- 🎯 Target: Spam (1) / Ham (0)

---

## ✨ Concepts Covered  
- 📐 Naive Bayes algorithm  
- 📊 **Gaussian Naive Bayes** for numerical data  
- 📨 **Multinomial Naive Bayes** for text classification  
- 🔤 Dummy variable encoding  
- 🧹 Handling missing values  
- 🧠 Probability-based classification  
- 🧾 Text vectorization using **CountVectorizer**  
- 🔗 ML Pipelines using `sklearn`

---

## 🛠️ Approach  

### 🚢 Titanic Survival Prediction
1. Drop irrelevant features  
2. Convert categorical variables into numeric form  
3. Handle missing values using mean imputation  
4. Split data into training and testing sets  
5. Train **Gaussian Naive Bayes** model  
6. Evaluate predictions and probabilities  

---

### 📧 Spam Email Detection
1. Convert labels into binary values (spam / ham)  
2. Split dataset into training and testing sets  
3. Transform text data using **CountVectorizer**  
4. Train **Multinomial Naive Bayes** model  
5. Predict spam emails  
6. Simplify workflow using **Pipeline**

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Train Naive Bayes models  
   - Predict outcomes  
   - Evaluate model accuracy  

---

## 🧠 Models Used  
- **GaussianNB** → Numerical features (Titanic dataset)  
- **MultinomialNB** → Text data (Spam detection)

---

## 📈 Results  
- Gaussian Naive Bayes successfully predicts Titanic survival probabilities  
- Multinomial Naive Bayes accurately classifies spam and non-spam emails  
- Pipelines simplify preprocessing and model training  

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
