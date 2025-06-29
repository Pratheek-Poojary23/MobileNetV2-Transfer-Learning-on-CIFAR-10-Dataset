# MobileNetV2 Transfer Learning on CIFAR-10 Dataset

This repository contains a TensorFlow-based deep learning project implementing **transfer learning using MobileNetV2** to classify images from the **CIFAR-10 dataset**. The project demonstrates the use of pre-trained models for efficient training on limited datasets, making it suitable for educational, research, and deployment purposes.

---

## 📂 Files Included

- `MobileNetV2_transfer_learning_using_CIFAR_Dataset.ipynb`: Main Jupyter Notebook for model training, evaluation, and visualization.

---
## 🧠 Model Summary

This project uses the **MobileNetV2** architecture, pre-trained on ImageNet, as a **feature extractor**, followed by custom dense layers to classify CIFAR-10 images into 10 categories:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## 📊 Dataset

- **CIFAR-10** dataset from `tf.keras.datasets.cifar10`
- 60,000 color images (32x32 pixels), 10 classes
  - 50,000 training images
  - 10,000 test images
---

  ## 🚀 Features

- ✅ Uses transfer learning for faster convergence and improved accuracy.
- ✅ Data preprocessing and normalization included.
- ✅ Data augmentation (optional, can be added).
- ✅ Evaluation with metrics and accuracy/loss visualization.
- ✅ Easily extendable to other small image classification tasks.

---

## 📊 Performance Summary

- **Model**: MobileNetV2 (pretrained on ImageNet, top removed)
- **Input Size**: Resized CIFAR-10 images to **224x224**
- **Dataset**: CIFAR-10 (60,000 images)

| Metric              | Value             |
|---------------------|------------------|
| Training Accuracy   | ~99% (after 5 epochs) |
| Validation Accuracy | ~88%              |
| Test Accuracy       | ~87–90%           |
| Epochs              | 5                 |
| Batch Size          | 32                |

---




