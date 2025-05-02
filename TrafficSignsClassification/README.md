# 🚦 Traffic Sign Classification using LeNet (CNN)

## 📌 Project Overview

This project focuses on classifying **traffic signs** using the **LeNet Convolutional Neural Network** architecture. This is a crucial task for **autonomous vehicles**, helping them interpret and respond appropriately to road signage. The dataset contains 43 traffic sign classes, each with thousands of labeled images.

---

## 🗂️ Dataset Summary

- 43 distinct traffic sign categories
- Images are **32x32** pixels in size
- Dataset includes examples like:
  - Speed limit signs (20–120 km/h)
  - Stop, Yield, No entry
  - Road work, Children crossing, Slippery road
  - Roundabout, Pedestrian crossing, etc.

---

## 🧠 Model: LeNet Architecture

We use a classic CNN model—**LeNet**—designed by Yann LeCun. The network consists of:

1. **Conv Layer 1**: 5x5 filters, output 28x28x6 + ReLU
2. **Pooling Layer 1**: Downsampling to 14x14x6
3. **Conv Layer 2**: 5x5 filters, output 10x10x16 + ReLU
4. **Pooling Layer 2**: Downsampling to 5x5x16
5. **Flatten Layer**: Transforms 5x5x16 → 400 units
6. **Fully Connected Layer 1**: 400 → 120 + ReLU
7. **Fully Connected Layer 2**: 120 → 84 + ReLU
8. **Output Layer**: 84 → 43 (softmax for class probabilities)

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- NumPy / Pandas
- TensorFlow / Keras
- OpenCV / PIL
- scikit-learn
- Matplotlib / Seaborn

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/traffic-sign-classification.git
cd traffic-sign-classification
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook TrafficSignsClassification.ipynb
```

4. Train the model and evaluate predictions.

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Confusion Matrix**
- **Precision & Recall**
- **Misclassification Rate**

We evaluate model performance on the test set and visualize results using a confusion matrix.

---

## 📚 Further Reading

- [LeNet by Yann LeCun](http://yann.lecun.com/exdb/lenet/)
- [Traffic Sign Dataset on Kaggle](https://www.kaggle.com/datasets)

---

## 📝 License

This project is licensed under the MIT License.
