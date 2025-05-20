# 🧠 Breast Cancer Classification and Segmentation using CNN

This project presents a deep learning-based solution to detect, classify, and segment breast cancer from histopathology images using **Convolutional Neural Networks (CNN)**. It integrates image segmentation (via U-Net) and classification (via ResNet) to support early diagnosis and aid clinical decisions.

---

## 📌 Project Overview

- **Domain**: Medical Image Analysis
- **Techniques Used**: CNN, Image Segmentation (U-Net), Transfer Learning (ResNet)
- **Dataset**: Kaggle – Histopathology Breast Cancer Images
- **Platform**: Google Colab (with GPU support)
- **Accuracy**: Classification – 80%, Segmentation Precision – 98%

---

## 🔧 Features

- ✅ Breast tissue segmentation using U-Net
- 🩺 Tumor classification (Benign vs Malignant) using ResNet
- ⚡ Optimized training using Google Colab with T4 GPU
- 📊 Visualized outputs for classification and segmentation
- 🔐 Efficient model convergence and performance validation

---

## 🛠️ Tools & Libraries

- **Google Colab** – Cloud-based Python development
- **TensorFlow & Keras** – Model building and training
- **Matplotlib** – Visualization
- **Numpy, Sklearn, OpenCV** – Data preprocessing and handling

---

## 📂 Directory Structure

BreastCancer_CNN_Project/
├── data/ # Dataset (or Kaggle API download script)

├── models/ # Saved model weights and architectures

├── notebooks/ # Jupyter notebooks for training and testing

├── outputs/ # Sample outputs - segmented images, graphs

├── README.md # Project documentation

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BreastCancer_CNN_Project.git
   cd BreastCancer_CNN_Project
2.Install dependencies: pip install -r requirements.txt

3.Open and run the notebook in Google Colab.

📊 Results
Classification Accuracy: ~80%

Segmentation Precision: ~98%

Training Time: ~10-12 minutes with T4 GPU

Visual outputs:

1. 📷 Correctly classified histopathology images

2. 🧬 Segmented cancerous regions using U-Net

🔍 Validations

1.✅ Reliable performance in classifying and segmenting tumor regions

2.🕒 Efficient training after switching from CPU to GPU in Colab

3.🛠️ Custom ResNet performed better than pre-imported models


🔮 Future Scope

1.Integration with patient metadata for better predictions

2.Real-time diagnostic tools in telemedicine platforms

3.Application of transfer learning on larger datasets

4.Expansion into multi-class tumor analysis

👥 Contributors
Rushikesh K

Maanasa Pamarthy

Mansi Talla



