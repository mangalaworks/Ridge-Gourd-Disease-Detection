# 🌿 Ridge Gourd Disease Detection Using Deep Learning

## 📘 Project Overview

This project presents a deep learning-based image detection system to identify **Downy Mildew disease** in **Ridge Gourd (Luffa acutangula)** leaves. Downy Mildew is a major fungal disease in cucurbits, leading to 40–60% yield loss. Traditional detection methods are time-consuming and error-prone.

By building an automated disease detection system, this project helps improve early-stage identification and supports smart, AI-powered agriculture.

---

## 🏆 Published At

Presented at  
Global Conference on Smart Horticulture for Prosperity and Nutritional Security (GCSH-2025)  
University of Horticultural Sciences, Bagalkot  
Date: January 28, 2025

---

## 📂 Dataset Summary

- Collected at: RHREC, COH Bengaluru experimental field  
- Captured using: Sony digital camera under natural lighting  
- Image resolution: 4000×6000 and 6000×4000  
- Total images: 2500 leaf images  
- Classes:
  - Healthy leaves
  - Downy Mildew – Early Stage
  - Downy Mildew – Final Stage  
- Split:
  - 1750 for training
  - 500 for validation
  - 250 for testing  
- Annotation tool: Roboflow  
- Annotation type: Polygon-based  
- Preprocessing: Cropping, resizing to 640×640, flipping, grayscale conversion

---

## ✅ What I Did – Step by Step

### 1. Field Data Collection  
Captured high-resolution images of ridge gourd leaves from a real field using natural lighting to reflect real farming conditions.

### 2. Annotation  
Annotated images using Roboflow with polygon-based masks for precise disease labeling in three classes.

### 3. Image Preprocessing  
Cropped unwanted regions, resized to 640×640, and applied data augmentation techniques (flipping, grayscale) for better generalization.

### 4. Model Development  
Developed a custom deep learning-based object detection model using a convolutional neural network. Optimized through hyperparameter tuning and validation.

### 5. Model Evaluation  
Tested the model using:
- Accuracy
- Precision & Recall
- F1 Score
- Confusion Matrix
- Mean Average Precision (mAP@0.5)

---

## 🎯 Results

| Class                    | Accuracy |
|--------------------------|----------|
| Healthy                 | 99%      |
| Early-Stage Downy Mildew| 95%      |
| Final-Stage Downy Mildew| 97%      |

- Mean Average Precision (mAP@0.5): 0.992  
- Minimal confusion between early-stage and healthy leaf detection

---

## 🗂 Project Structure

Ridge-Gourd-Disease-Detection/
├── model/
│ └── best.pt → Trained model file
├── dataset/
│ └── ridge_gourd_dataset.zip → Full dataset (82MB)
├── presentation/
│ ├── final_ppt.pptx → Conference presentation
│ └── abstract.png 
├── results/
│ └── confusion_matrix.png, plots
├── README.md
└── abstract.txt

---

## 🧠 Tools & Technologies Used

- Python  
- PyTorch  
- OpenCV  
- Roboflow (for annotation)  
- Matplotlib  

---

## 💡 Project Impact

- Enables fast, accurate, and scalable disease detection in crops  
- Can be adapted for use in field devices (mobile, drone-based systems)  
- Supports sustainable agriculture and early intervention  
- Combines AI with real-world agricultural practices

---

## 👩‍💻 Author

**Mangalanageshwari**  
Bachelor of Engineering – Electronics & Telecommunication  
University of Horticultural Sciences, Bagalkot  
Email: diseaseai24@gmail.com

