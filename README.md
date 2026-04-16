# 🪐 NASA Planetary Surface AI Classifier

## 📌 Overview
This project is a deep learning image classifier that identifies planetary surface types using real NASA images.

It classifies:
- Craters
- Dunes
- Rocks
- Dust

## 🚀 How it works

1. Downloads real images from NASA Images API
2. Builds an automatic labeled dataset
3. Uses MobileNetV2 (transfer learning)
4. Trains a CNN classifier
5. Predicts surface type from images
6. Saves trained model for reuse

## 🧠 Model architecture
- Base: MobileNetV2 (ImageNet pretrained)
- Pooling: GlobalAveragePooling2D
- Dense layer: 128 neurons
- Output: Softmax classification

## 📊 Output example

Real: dust
Predicted: dust


## 💾 Model export

The model is saved in `.keras` format:

nasa_planetary_classifier.keras


## 📦 Requirements
See requirements.txt

## 🌌 Dataset
NASA Images API:
https://images.nasa.gov/

## ⚙️ Run on Google Colab
Just copy the notebook and run all cells.

---

## 🧪 Future improvements
- Add HiRISE Mars dataset
- Add segmentation instead of classification
- Improve accuracy with EfficientNet
- Deploy as web API

---

## 👨‍🚀 Author
Angelo Sorte
