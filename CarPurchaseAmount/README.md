# 🚗 Car Purchase Amount Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project aims to predict the **car purchasing amount** a customer is likely to spend, based on key demographic and financial features. Using **Artificial Neural Networks (ANNs)**, we model this as a **regression problem**, training the network to learn from historical data and predict continuous values accurately.

---

## 📊 Problem Statement

You are working as a car salesperson. You want to develop a model that predicts the total dollar amount a customer is willing to pay for a car based on:

- Customer Name
- Customer Email
- Country
- Gender
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

🎯 **Target Variable:** `Car Purchase Amount`

---

## 🧠 Model: Artificial Neural Network (ANN)

We used a deep learning model (ANN) built with **TensorFlow** and **Keras**, incorporating the following:

- Input layer: 5 normalized features
- Hidden layers: Multiple dense layers with ReLU activation
- Output layer: 1 neuron (regression output)
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

---

## 📁 Dataset

The dataset contains real-world customer data. Key preprocessing steps include:

- Dropping non-numeric columns (`Customer Name`, `Email`, `Country`)
- Normalizing numerical features (MinMaxScaler)
- Splitting into training and testing sets (75% / 25%)

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/car-purchase-prediction.git
cd car-purchase-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook:

```bash
jupyter notebook CarPurchaseAmount.ipynb
```

4. Run all cells to train the model and view results.

---

## 📈 Results

- Training Loss decreased steadily indicating successful learning
- Model generalizes well to the test set
- Regression curve fit closely to actual values

📌 Example visualization:

- Training Loss Curve
- Prediction vs Actual values

---

## 📚 Further Reading

- [Understanding Machine Learning](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf)
- [ISLR: An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf)

---

## 📝 License

This project is licensed under the MIT License.
