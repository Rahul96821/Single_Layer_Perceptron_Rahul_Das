# 🧠 Simple Binary Classification using TensorFlow

## 📘 Introduction

This project demonstrates how to build a simple **binary classification model** using **TensorFlow and Keras**.
We use **`make_classification()`** from scikit-learn to generate a synthetic dataset with two features and two output classes.
The data is **standardized** using **`StandardScaler`**, and a basic **neural network** with a sigmoid activation function is trained to classify the data points.

This is a great beginner-friendly example to understand the full machine learning workflow — **data creation, preprocessing, model building, training, and evaluation**.

---

## 🧩 Project Structure

```
📁 Binary-Classification-TensorFlow
│
├── 📄 main.py              # Main Python script
├── 📄 requirements.txt     # List of dependencies
└── 📄 README.md            # Project documentation
```

---

## ⚙️ Requirements

Make sure you have the following Python packages installed:

```bash
pip install tensorflow scikit-learn numpy
```

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/binary-classification-tensorflow.git
   cd binary-classification-tensorflow
   ```

2. Run the script:

   ```bash
   python main.py
   ```

---

## 🧠 Model Overview

* **Input:** 2 numerical features
* **Architecture:**

  * 1 Dense layer with sigmoid activation
* **Loss Function:** Binary Crossentropy
* **Optimizer:** Adam
* **Metric:** Accuracy

---

## 📊 Results

After training for 50 epochs on a synthetic dataset of 1000 samples, the model achieved:

> **✅ Test Accuracy:** 87.5%

---

## 🔍 Conclusion

This simple project shows that even a **single-layer neural network** can effectively solve binary classification problems when the data is well-prepared. It highlights the importance of **data scaling** and **proper model evaluation**.
