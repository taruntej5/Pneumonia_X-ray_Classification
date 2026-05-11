# 🩺 Pneumonia Detection using Deep Learning

## 📌 Project Overview

This project focuses on detecting Pneumonia from Chest X-ray images using Deep Learning techniques.

Initially, a baseline CNN model was developed for image classification. Although the model achieved good training accuracy, it suffered from:
- Overfitting
- Unstable validation accuracy
- Poor generalization on unseen images

To address these challenges, Transfer Learning using MobileNetV2 was implemented to improve feature extraction and overall model performance.

---

# 🚀 Project Workflow

1. Dataset Loading
2. Data Preprocessing
3. Baseline CNN Model
4. Model Training & Evaluation
5. Overfitting Analysis
6. Regularization Techniques
7. Transfer Learning with MobileNetV2
8. Final Model Evaluation

---

# 📂 Dataset

The dataset contains Chest X-ray images categorized into:
- Pneumonia
- Normal

Dataset split:
- Training Set
- Validation Set
- Test Set

---

# 🧠 Baseline CNN Model

A custom CNN architecture was initially developed using:
- Convolution Layers
- MaxPooling Layers
- Dense Layers
- Dropout

## ⚠️ Problems Observed

- Overfitting during training
- Validation accuracy fluctuations
- Poor generalization capability
- Limited feature extraction performance

Validation accuracy remained around ~75%.

---

# 🛠️ Techniques Applied

To reduce overfitting, the following techniques were explored:
- Dropout
- Data Augmentation
- Early Stopping
- Hyperparameter Tuning

---

# 🔥 Transfer Learning with MobileNetV2

To improve performance, MobileNetV2 pretrained on ImageNet was adopted.

## Benefits:
- Better feature extraction
- Improved generalization
- Reduced overfitting
- Faster convergence

---

# 📊 Results

| Model | Observation |
|---|---|
| Baseline CNN | Overfitting & unstable validation accuracy |
| MobileNetV2 | Improved validation performance and generalization |

---

# 🧰 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV

---

# 📌 Future Improvements

- Fine-tuning pretrained layers
- Using EfficientNet / ResNet
- Model explainability with Grad-CAM
- Hyperparameter optimization

---

# 👨‍💻 Author

T TARUN TEJA
