# 📊 K-Means Clustering – Unsupervised Learning  

📌 A Machine Learning mini project demonstrating **K-Means Clustering**
to discover patterns in data **without knowing target labels**.

---

## 📖 About  
Unlike supervised learning, **unsupervised learning** works with data where
the target variable is unknown.  
In this project, K-Means is used to **group data points based on similarity**
using only feature values such as **age** and **income**.

The project also highlights the importance of **feature scaling** and
**choosing the optimal number of clusters**.

---

## 📊 Dataset  
The project uses a CSV dataset (`clustering.csv`) containing:
- 🎂 **Age**  
- 💰 **Income**  

No target variable is provided.

---

## ✨ Concepts Covered  
- 🔍 Unsupervised Learning  
- 📦 K-Means Clustering  
- 📐 Distance-based clustering  
- ⚖️ Feature Scaling using **MinMaxScaler**  
- 📍 Cluster centroids  
- 📉 Elbow Method for choosing optimal **K**

---

## 🛠️ Approach  
1. Load dataset using Pandas  
2. Visualize data using scatter plots  
3. Apply K-Means clustering without scaling  
4. Observe incorrect clustering due to feature range differences  
5. Scale features using **MinMaxScaler**  
6. Reapply K-Means clustering  
7. Visualize clusters and centroids  
8. Use **Elbow Method** to determine optimal number of clusters  

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to:
   - Perform clustering  
   - Visualize clusters  
   - Apply feature scaling  
   - Generate elbow plot  

---

## 🧠 Model  
- Algorithm: **K-Means Clustering**  
- Type: **Unsupervised Learning**  
- Distance metric: Euclidean  
- Optimal K selected using **Elbow Method**

---

## 📈 Results  
After feature scaling, K-Means successfully groups data into meaningful clusters.
The elbow plot clearly indicates **K = 3** as the optimal number of clusters.

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
