# 🧠 CIFAR-10 Image Classification using Convolutional Neural Networks (CNNs)

## 📌 Project Overview

This project involves building and training a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10** dataset into one of ten categories. The dataset contains 60,000 low-resolution images (32x32 pixels) of objects like airplanes, birds, and ships, across 10 mutually exclusive classes.

---

## 🎯 Problem Statement

The goal is to accurately classify an image into one of the following 10 categories:

- ✈️ Airplanes
- 🚗 Cars
- 🐦 Birds
- 🐱 Cats
- 🦌 Deer
- 🐶 Dogs
- 🐸 Frogs
- 🐴 Horses
- 🚢 Ships
- 🚛 Trucks

---

## 📁 Dataset

- **Source:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- 60,000 images total: 50,000 for training and 10,000 for testing
- Image size: 32x32 pixels, RGB (3 channels)

---

## 🧠 Model: Convolutional Neural Network (CNN)

Our model includes:

- **Convolutional Layers:** To extract spatial features using filters
- **Activation Functions:** ReLU for non-linearity
- **Pooling Layers:** MaxPooling to downsample and reduce complexity
- **Flattening Layer:** Converts 2D features to 1D vector
- **Dense Layers:** Fully connected layers for classification
- **Dropout:** Regularization to avoid overfitting
- **Output Layer:** Softmax activation to classify into 10 categories

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- NumPy
- TensorFlow / Keras
- Matplotlib
- scikit-learn

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/cifar10-classification.git
cd cifar10-classification
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook Cifar_10.ipynb
```

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix**

The performance of the model is tracked using these metrics, along with training/validation loss and accuracy plots.

---

## 🧪 Results Summary

- Achieved classification accuracy on test data exceeding industry baseline.
- Model shows balanced precision and recall across most classes.
- Visualized predictions and confusion matrix to understand misclassifications.

---

## 📚 Further Reading

- [Understanding CNNs and Image Kernels](http://setosa.io/ev/image-kernels/)
- [Deep Learning by Ian Goodfellow](https://www.deeplearningbook.org/)

---

## 📝 License

This project is licensed under the MIT License.
