# 🖼️ Image Classification using Convolutional Neural Networks (CNN)

## 📌 Project Overview

Image Classification is one of the most important applications of Computer Vision and Deep Learning. It involves automatically identifying and assigning labels to images based on their visual content.

In this project, a **Convolutional Neural Network (CNN)** is developed using **TensorFlow** and **Keras** to classify images from the **CIFAR-10 dataset** into one of ten categories. The model learns meaningful image features through convolution and pooling operations and performs multi-class classification with good accuracy.

---

## 🎯 Objective

The objective of this project is to:

* Build a Deep Learning model for image classification.
* Understand the working of Convolutional Neural Networks (CNNs).
* Learn feature extraction from image data.
* Perform multi-class classification on real-world image datasets.
* Evaluate model performance using testing data.

---

## 🛠️ Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| TensorFlow       | Deep Learning Framework |
| Keras            | Neural Network API      |
| NumPy            | Numerical Computation   |
| Matplotlib       | Data Visualization      |
| Jupyter Notebook | Development Environment |

---

## 🧠 Deep Learning Concepts Implemented

* Convolutional Neural Networks (CNN)
* Feature Extraction
* Image Processing
* ReLU Activation Function
* Max Pooling
* Flatten Layer
* Dense Neural Networks
* Softmax Classification
* Model Training & Evaluation

---

## 📂 Dataset

### CIFAR-10 Dataset

The CIFAR-10 dataset contains 60,000 RGB images belonging to 10 different classes.

### Dataset Statistics

| Feature           | Value          |
| ----------------- | -------------- |
| Total Images      | 60,000         |
| Training Images   | 50,000         |
| Testing Images    | 10,000         |
| Image Size        | 32 × 32 Pixels |
| Channels          | RGB            |
| Number of Classes | 10             |

---

## 🏷️ Classes in CIFAR-10

| Class ID | Category   |
| -------- | ---------- |
| 0        | Airplane   |
| 1        | Automobile |
| 2        | Bird       |
| 3        | Cat        |
| 4        | Deer       |
| 5        | Dog        |
| 6        | Frog       |
| 7        | Horse      |
| 8        | Ship       |
| 9        | Truck      |

---

## 🔄 Project Workflow

1. Load CIFAR-10 Dataset
2. Preprocess and Normalize Images
3. Visualize Sample Images
4. Build CNN Architecture
5. Train the Model
6. Evaluate Performance
7. Predict Image Classes
8. Visualize Predictions

---

## 🏗️ CNN Architecture

```text
Input Layer (32x32x3)
        │
Conv2D (32 Filters, 3x3, ReLU)
        │
MaxPooling2D (2x2)
        │
Conv2D (64 Filters, 3x3, ReLU)
        │
MaxPooling2D (2x2)
        │
Flatten Layer
        │
Dense Layer (64 Neurons, ReLU)
        │
Output Layer (10 Neurons, Softmax)
```

---

## 🚀 Model Training

### Optimizer

```text
Adam
```

### Loss Function

```text
Sparse Categorical Crossentropy
```

### Evaluation Metric

```text
Accuracy
```

---

## 📈 Model Performance

After training, the CNN achieved approximately:

```text
Test Accuracy: ~69%
```

The model successfully learned visual patterns and was able to classify images into ten different categories with reliable performance.

---

## 🔍 Sample Prediction

### Input

```text
Image: Automobile
```

### Predicted Output

```text
Predicted Class: Automobile
```

---

## ✨ Features

* CNN-based Image Classification
* Automatic Feature Extraction
* Multi-Class Classification
* Training and Validation Monitoring
* Model Evaluation
* Prediction Visualization
* Deep Learning Implementation

---

## 🌍 Real-World Applications

* Object Detection & Recognition
* Autonomous Vehicles
* Medical Image Analysis
* Facial Recognition Systems
* Smart Surveillance
* Security Systems
* Industrial Automation

---

## 📁 Project Structure

```text
Task1_Project3_Image_Classification/
│
├── Task1_Project3_Image_Classification.ipynb
├── README.md
├── requirements.txt
└── saved_model/
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Image-Classification-CNN.git
```

Navigate to the project directory:

```bash
cd Image-Classification-CNN
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Task1_Project3_Image_Classification.ipynb
```

---

## 🎓 Learning Outcomes

This project helped in understanding:

* Deep Learning Fundamentals
* Convolutional Neural Networks
* Image Preprocessing
* Computer Vision Concepts
* Feature Extraction
* Model Training
* Model Evaluation
* Multi-Class Classification

---

## 🔮 Future Enhancements

* Data Augmentation
* Transfer Learning (VGG16, ResNet50)
* Hyperparameter Tuning
* Higher Accuracy Models
* Web Application Deployment
* Real-Time Image Prediction

---

## 🏁 Conclusion

This project demonstrates the successful implementation of a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset.

The model effectively learns image features and classifies images into multiple categories with good accuracy. It provides a strong foundation for understanding Computer Vision and Deep Learning applications in real-world scenarios.

---

## 👨‍💻 Author

**Armi Sherathiya**

Machine Learning Intern – HexSoftwares

2025
