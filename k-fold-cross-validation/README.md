# 🔁 K-Fold Cross Validation – Model Evaluation & Selection  

📌 A Machine Learning mini project demonstrating **K-Fold Cross Validation**
to compare multiple models and obtain **reliable performance estimates**.

---

## 📖 About  
When using a simple **train–test split**, model accuracy can change every time
the data is split randomly.  
This makes it unreliable to judge a model based on a **single score**.

This project introduces **K-Fold Cross Validation** to:
- Reduce randomness
- Compare multiple models fairly
- Select the best-performing algorithm
- Prepare for parameter tuning

---

## 📊 Dataset  
Dataset source: `sklearn.datasets.load_digits`

### Data Details:
- 🔢 Handwritten digit images (0–9)  
- 📈 Each image is converted into numerical pixel features  
- 🎯 Multi-class classification problem  

---

## ✨ Models Compared  
- 📉 **Logistic Regression**  
- 📐 **Support Vector Machine (SVM)**  
- 🌲 **Random Forest Classifier**

---

## 🧠 Concepts Covered  
- 🔀 Train–test split instability  
- 🔁 K-Fold Cross Validation  
- 🧮 Stratified K-Fold (balanced class distribution)  
- 📊 Cross-validation scores  
- ⚖️ Model comparison  
- 🎛️ Parameter tuning  

---

## 🛠️ Approach  
1. Train multiple models using train–test split  
2. Observe accuracy variation due to random data splitting  
3. Introduce **K-Fold Cross Validation**  
4. Evaluate models across multiple folds  
5. Store and compare scores from each model  
6. Use `cross_val_score()` for cleaner comparison  
7. Compare models and tune parameters (e.g., number of trees in Random Forest)

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Train different models  
   - Apply K-Fold and Stratified K-Fold  
   - Compare model performance  
   - Perform parameter tuning  

---

## 🧠 Evaluation Techniques  
- **K-Fold Cross Validation**  
- **Stratified K-Fold** (preferred for classification tasks)  
- **cross_val_score()** for concise evaluation  

---

## 📈 Results  
Cross-validation provides **more stable and trustworthy accuracy scores**
compared to a single train–test split.  
It helps identify the best-performing model and guides **parameter tuning**
for improved performance.

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
