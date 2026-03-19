# 🧠 Deep Learning Case Studies using CNN

## 📌 Overview
This repository contains three deep learning case studies implemented using Convolutional Neural Networks (CNN):

1. MNIST Digit Recognition  
2. CIFAR-10 Image Classification  
3. Brain Tumor Detection with CAM (Explainable AI)  

These projects demonstrate the application of CNNs on simple, complex, and real-world medical datasets.

---

# 📂 Case Studies

---

## 🧠 1. MNIST Digit Recognition

### 📌 Description
Classifies handwritten digits (0–9) using a CNN model.

### 📂 Dataset
- MNIST dataset  
- 70,000 grayscale images (28×28)  
- 10 classes (digits 0–9)

### ⚙️ Steps
1. Load dataset using Keras  
2. Normalize pixel values (0–1)  
3. Reshape for CNN input  
4. Build CNN model  
5. Train and evaluate  

### 🧠 Key Concepts
- Basic image classification  
- CNN feature extraction (edges, strokes)

### 📊 Result
- Accuracy: ~98–99%

---

## 🖼️ 2. CIFAR-10 Image Classification

### 📌 Description
Classifies images into 10 categories (animals, vehicles).

### 📂 Dataset
- CIFAR-10 dataset  
- 60,000 color images (32×32)  
- 10 classes  

### ⚙️ Steps
1. Load dataset  
2. Normalize images  
3. Build deeper CNN  
4. Train model  
5. Evaluate performance  

### 🧠 Key Concepts
- Multi-class classification  
- Feature hierarchy: edges → shapes → objects  

### 📊 Result
- Accuracy: ~70–85%

---

## 🧬 3. Brain Tumor Detection + CAM

### 📌 Description
Detects brain tumors from MRI images and highlights important regions using Class Activation Maps (CAM).

### 📂 Dataset
- Brain MRI dataset (Kaggle)  
- Classes:
  - Yes (Tumor)  
  - No (Normal)  

### ⚙️ Steps
1. Load dataset using directory loader  
2. Normalize images  
3. Build CNN model  
4. Train model  
5. Load test MRI image  
6. Generate CAM heatmap  

### 🧠 Key Concepts
- Binary classification  
- Medical image analysis  
- Explainable AI (CAM)

### 📊 Output
- Tumor prediction (Yes/No)  
- Heatmap showing tumor region  

---

# 🧠 What is CAM?

Class Activation Map (CAM) highlights regions in an image that influence the model’s prediction.

👉 Helps answer:
- *Why did the model predict tumor?*
- *Where is the tumor located?*

---

# ⚙️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- OpenCV  

---

# ▶️ How to Run

## 1. Install Dependencies
```bash
pip install tensorflow numpy matplotlib opencv-python
