# 📉 Gradient Descent – From Scratch Implementation  

📌 A Machine Learning mini project demonstrating **Gradient Descent**
implemented **from scratch using NumPy** to fit a linear regression model.

---

## 📖 About  
This project focuses on understanding how **Gradient Descent** works internally.
Instead of using any ML library, the algorithm is implemented manually to learn
the optimal values of **slope (m)** and **intercept (b)** by minimizing the
**Mean Squared Error (MSE)**.

---

## 📊 Dataset  
The project uses a simple numeric dataset:
- **Input (x):** `[1, 2, 3, 4, 5]`  
- **Output (y):** `[5, 7, 9, 11, 13]`

This represents a linear relationship used to demonstrate convergence.

---

## ✨ Concepts Covered  
- 📐 Linear Regression  
- 📉 Gradient Descent optimization  
- 🔁 Iterative parameter updates  
- ⚡ Learning rate  
- 🧮 Mean Squared Error (MSE)  
- 🧠 Convergence intuition  

---

## 🛠️ Approach  
1. Initialize slope (`m`) and intercept (`b`) to zero  
2. Predict output values using current parameters  
3. Compute gradients with respect to `m` and `b`  
4. Update parameters using learning rate  
5. Calculate loss using Mean Squared Error  
6. Repeat for multiple iterations until error decreases  

---

## ▶️ Usage  
1. 📥 Clone the repository  
2. 📓 Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. ▶️ Run all cells to observe:
   - Parameter updates (`m` and `b`)  
   - Decreasing cost after each iteration  

---

## 🧠 Model  
- Optimization Algorithm: **Gradient Descent**  
- Parameters learned: `m` (slope), `b` (intercept)  
- Loss function: **Mean Squared Error**

---

## 📈 Results  
The cost decreases with each iteration, showing that Gradient Descent
successfully minimizes error and converges toward optimal parameters.

---

🚀 *Part of my Machine Learning mini projects focused on building strong fundamentals!*  
