# breast-cancer-gan-cnn
Breast cancer detection using GAN-based synthetic image augmentation and CNN classification
# Breast Cancer Detection using GAN and CNN

## 📌 Overview
This project evaluates the impact of GAN-based synthetic image generation on breast cancer classification using Convolutional Neural Networks (CNNs).

## 🧠 Methodology
- Dataset: CBIS-DDSM
- Data preprocessing: resizing and normalization
- Baseline CNN model
- GAN for synthetic image generation
- GAN-enhanced CNN model

## 📊 Results

### Baseline CNN Performance
![Baseline](images/baseline_accuracy_loss.png)

### GAN-Enhanced CNN Performance
![GAN](images/gan_enhanced_accuracy_loss.png)

## 📈 Key Findings
- Baseline Accuracy: ~56%
- GAN Accuracy: ~48
- Recall decreased for malignant class
- Synthetic images were low quality (black images)

## ⚠️ Limitations
- GAN training instability
- Poor quality synthetic images
- Small dataset size

## 🚀 Future Work
- Conditional GAN (cGAN)
- Transfer learning (ResNet, EfficientNet)
- Larger datasets

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## 🎓 Academic Context
This project was developed as part of an MSc Computer Science dissertation at Glasgow Caledonian University.
