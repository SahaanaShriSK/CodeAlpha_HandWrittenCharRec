# 🧠 Handwritten Character Recognition (MNIST)

A deep learning project that recognizes handwritten digits (0–9) from the MNIST dataset using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

---

## 📘 Overview

This project trains a CNN model to classify grayscale images of handwritten digits into one of ten classes (0–9).  
The MNIST dataset contains **70,000 labeled images** (60,000 for training and 10,000 for testing).

The notebook walks through:
- Dataset download using **KaggleHub**
- CNN model creation and training
- Model evaluation with accuracy, confusion matrix, and classification report
- Visualization of predictions and performance

---

## ⚙️ Tech Stack

- **Language:** Python 3  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Dataset:** MNIST (via [hojjatk/mnist-dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset))  
- **Environment:** Jupyter Notebook / Google Colab  

---
## 🧩 Model Architecture

The CNN includes:

- **Conv2D layers** for feature extraction  
- **MaxPooling2D** for downsampling  
- **Flatten + Dense layers** for classification  
- **Dropout** to reduce overfitting  


---

## 📊 Results

| Metric | Score |
|:--------|:-------|
| **Accuracy** | 98.97% |
| **Precision** | 98.81% |

Confusion Matrix and prediction visualizations are generated within the notebook.

---

## 👩‍💻 Author
Sahaana Shri S K  

📧 sahaanashrisk@gmail.com 
🌐 [GitHub Profile](https://github.com/SahaanaShriSK)


