# Face-Mask-Detection
# 😷 Face Mask Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify whether a person is wearing a face mask or not from an image. It is built using TensorFlow and Keras, and trained on an image dataset split into two categories: `with_mask` and `without_mask`.

---

## 📂 Project Structure

- `Face_Mask_Classification_using_CNN.ipynb`: Main Jupyter notebook with code and outputs
- Dataset: Structured as:
├── Dataset/
├── with_mask/
└── without_mask/



---

## 🔍 Objective

To develop a binary image classifier that can distinguish between:
- `with_mask`
- `without_mask`

Using CNN architecture trained on labeled image data.

---

## ⚙️ Features

- Image preprocessing (resizing, rescaling)
- Train/validation split
- CNN model built using `Keras Sequential API`
- Training with metrics visualization (accuracy & loss)
- Final accuracy and evaluation summary

---

## 🛠️ Dependencies

Install the following libraries to run this project:

```bash
pip install tensorflow keras numpy matplotlib sklearn
```

## 🧠 Model Architecture
Conv2D layers with ReLU activation

MaxPooling2D

Flatten

Dense layers for classification

Softmax output layer

## 📈 Results
Model trained for 10 epochs

Achieved over 97% accuracy on validation data

Plotted training/validation loss and accuracy curves

## 📌 Example Use Case
This model can be used in:

Real-time surveillance systems to detect face mask usage

Embedded in mobile or edge devices for COVID-19 safety compliance

Integrated into security checkpoints for automated monitoring


## 🌐 Acknowledgements
Inspired by real-world need for pandemic response tech
