# 🌿 Plant Disease Detection using CNN

A deep learning project that detects plant diseases from leaf images using a Convolutional Neural Network (CNN). The model classifies images into 38 different categories based on plant type and disease type.

---

## 📌 Overview

Plant diseases can drastically affect crop yield and quality. Early and accurate detection can help farmers take timely action. This project utilizes a CNN-based image classification model to identify plant diseases from images of leaves.

---

## 📂 Dataset

- **Source**: PlantVillage Dataset from [Kaggle]
- **Classes**: 38 categories (e.g., Apple Scab, Tomato Mosaic Virus, Potato Blight, etc.)
- **Structure**:
```

dataset/
├── train/      # Training data
└── valid/      # Validation data

````
- Images are organized into subdirectories named after the plant and disease (e.g., `Tomato___Early_blight/`, `Apple___Scab/`).

---

## 🧠 Model Architecture

The CNN model is designed with the following components:

- Multiple **Convolutional Layers**
- **Batch Normalization** to stabilize and accelerate training
- **Max Pooling Layers** for downsampling
- **Dropout Layers** to prevent overfitting
- **Fully Connected Layers** for classification

**Training Details:**
- **Loss Function**: `categorical_crossentropy`
- **Optimizer**: `Adam`
- **Framework**: `TensorFlow` with `Keras`

---

## 📊 Performance Visualization

- Accuracy and loss plots are provided in the notebook
- Training vs validation performance over epochs
- Sample predictions displayed with corresponding class names

---

## ▶️ How to Run

1. Clone the repository:
 ```bash
 git clone https://github.com/yourusername/Plant_Disease_Detection_CNN.git
 cd Plant_Disease_Detection_CNN
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook Plant_Disease_Detection_CNN.ipynb
   ```

---

## 🧰 Requirements

```text
Python 3.8+
tensorflow
keras
numpy
pandas
matplotlib
seaborn
scikit-learn
```


---

## 📈 Language

* Jupyter Notebook: 100%

---

