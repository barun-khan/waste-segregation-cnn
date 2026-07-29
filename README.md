# ♻️ Waste Segregation using Convolutional Neural Networks (CNN)

> An AI-powered image classification system that automatically categorizes waste into seven different classes using Deep Learning and Computer Vision.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red?logo=keras)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📌 Project Overview

Waste segregation is one of the most important steps in effective recycling and sustainable waste management. Manual segregation is often time-consuming, expensive, and prone to human error.

This project demonstrates how **Artificial Intelligence**, **Deep Learning**, and **Computer Vision** can automate waste classification using a **Convolutional Neural Network (CNN)** built with **TensorFlow** and **Keras**.

The model is capable of classifying waste images into **seven different categories**, helping improve recycling efficiency and environmental sustainability.

---

# 🎯 Problem Statement

Develop a Convolutional Neural Network (CNN) capable of accurately classifying waste images into their respective categories.

The objective is to build an image classification model that can distinguish between multiple waste types and evaluate its performance using standard classification metrics.

---

# ♻️ Waste Categories

The model classifies waste into the following categories:

- 📦 Cardboard
- 🍎 Food Waste
- 🍾 Glass
- 🛠 Metal
- 📄 Paper
- 🧴 Plastic
- 📌 Other

---

# 📂 Dataset

The dataset contains approximately **7,000 images** distributed across seven different waste categories.

Each category is stored in a separate folder.

```
Dataset
│
├── Cardboard
├── Food_Waste
├── Glass
├── Metal
├── Other
├── Paper
└── Plastic
```

> **Note:** The dataset is not included in this repository due to licensing and repository size considerations.

---

# 🚀 Features

✔ Image preprocessing

✔ Data visualization

✔ CNN model development

✔ Image normalization

✔ Label Encoding

✔ One-Hot Encoding

✔ Data Augmentation

✔ Model Training

✔ Model Evaluation

✔ Confusion Matrix

✔ Classification Report

✔ Accuracy, Precision, Recall & F1 Score

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Data Manipulation | NumPy, Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Image Processing | Pillow |
| Development Environment | Jupyter Notebook |

---

# 🔄 Project Workflow

```text
Dataset
    │
    ▼
Load Images
    │
    ▼
Image Preprocessing
    │
    ├── Resize Images
    ├── RGB Conversion
    ├── Normalize Pixel Values
    ▼
Label Encoding
    │
    ▼
One-Hot Encoding
    │
    ▼
Train-Test Split
    │
    ▼
Data Augmentation
    │
    ▼
CNN Model
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Prediction
```

---

# 🧠 CNN Architecture

The CNN model consists of:

```
Input Layer

↓

Conv2D (32 Filters)

↓

Batch Normalization

↓

MaxPooling

↓

Conv2D (64 Filters)

↓

Batch Normalization

↓

MaxPooling

↓

Conv2D (128 Filters)

↓

Batch Normalization

↓

MaxPooling

↓

Flatten

↓

Dense (128)

↓

Dropout

↓

Softmax Output Layer
```

---

# 📊 Data Preprocessing

The following preprocessing steps were performed before model training:

- Image Loading
- RGB Conversion
- Image Resizing
- Pixel Normalization
- Label Encoding
- One-Hot Encoding
- Train-Test Split

---

# 🔄 Data Augmentation

To improve model generalization and reduce overfitting, image augmentation techniques were applied.

Techniques used:

- Rotation
- Horizontal Flip
- Zoom
- Width Shift
- Height Shift

---

# 📈 Model Evaluation

The model performance was evaluated using multiple classification metrics.

### Metrics Used

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix

These metrics provide a comprehensive evaluation of the model beyond simple accuracy.

---

# 📁 Repository Structure

```
waste-segregation-cnn
│
├── CNN_Waste_Segregation_Barun_Khan.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/barun-khan/waste-segregation-cnn.git
```

Move into the project directory

```bash
cd waste-segregation-cnn
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Run

```
CNN_Waste_Segregation_Barun_Khan.ipynb
```

---

# 📦 Required Libraries

```
tensorflow
keras
numpy
pandas
matplotlib
seaborn
scikit-learn
Pillow
jupyter
```

---

# 📈 Future Improvements

This project can be enhanced further by incorporating:

- Transfer Learning (EfficientNet, ResNet50)
- MobileNet Deployment
- Streamlit Web Application
- Real-Time Webcam Classification
- Mobile App Integration
- Cloud Deployment (AWS/GCP/Azure)
- Smart Recycling Bin Integration

---

# 🌱 Learning Outcomes

This project provided practical experience in:

- Deep Learning
- Computer Vision
- CNN Model Design
- Image Classification
- Data Preprocessing
- TensorFlow
- Keras
- Machine Learning Model Evaluation
- AI for Sustainable Development

---

# 🤝 Acknowledgements

This project was developed as part of a Deep Learning assignment focused on applying Convolutional Neural Networks to real-world environmental challenges.

The project demonstrates how AI can contribute to smarter waste management and sustainable recycling solutions.

---

# 👨‍💻 Author

## Barun Khan

QA Automation Engineer | AI & Machine Learning Enthusiast

### Connect with me

- 💼 LinkedIn: https://www.linkedin.com/in/barun-khan-129007232/
- 💻 GitHub: https://github.com/barun-khan

---

# ⭐ Support

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates me to build more open-source AI and Automation projects.

---

## 📬 Feedback

Suggestions, improvements, and contributions are always welcome!

Feel free to open an issue or submit a pull request.

Happy Coding! 🚀
