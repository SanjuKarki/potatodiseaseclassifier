# 🥔 Potato Disease Classifier

This project uses a **Convolutional Neural Network (CNN)** to detect and classify **Early Blight** and **Late Blight** in potato leaves using image data. The goal is to provide a fast, accurate, and accessible solution for farmers and agricultural specialists to identify diseases early and minimize crop loss.

---

## 🔍 Project Overview

- **Model Type**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow + Keras
- **Dataset**: Collected from Kaggle (Potato Leaf Disease Dataset)
- **Classes**: Early Blight, Late Blight, Healthy

---

## 📁 Dataset

The dataset contains labeled images of potato leaves, categorized into:
- `Early Blight`
- `Late Blight`
- `Healthy`

> 🔗 [Kaggle Dataset Source](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)

---

## ⚙️ Tools & Libraries

- Python
- TensorFlow / Keras
- Matplotlib / Seaborn
- NumPy
- OpenCV (for image preprocessing)

---

## 🧠 Model Architecture

- Input Layer: 256x256x3 RGB images
- 3x Convolution + MaxPooling layers
- Flatten + Dense Layers
- Dropout layers for regularization
- Final Dense Layer with `Softmax` for multi-class output

---

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Loss vs. Accuracy Curves
- Test Predictions vs. Ground Truth Visualizations

---

## 📦 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/SanjuKarki/potatodiseaseclassifier.git
   cd potatodiseaseclassifier
