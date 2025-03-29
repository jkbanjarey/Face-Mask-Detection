# **Face Mask Detection using Deep Learning** 😷  

## 📌 Overview  
This project implements a **Face Mask Detection Model** using **deep learning techniques**. The model is trained to detect whether a person is:  
✔ **Wearing a mask properly**  
❌ **Not wearing a mask**  
⚠️ **Wearing a mask improperly**  

This solution can be applied in **public safety, healthcare, and access control** systems.  

---

## ✨ Features  
- 🎭 **Classifies individuals based on mask usage (Proper, No Mask, Improper).**  
- 🤖 **Utilizes Convolutional Neural Networks (CNNs) for accurate classification.**  
- 🔄 **Data Augmentation** - enhances model generalization.  
- 📊 **Real-time face mask detection using OpenCV.**  

---

## 📂 Dataset  
The dataset consists of images categorized into three classes:  
- ✅ **With Mask**  
- ❌ **Without Mask**  
- ⚠️ **Improper Mask**  

Each image undergoes:  
✔ **Resizing** to **224x224** pixels.  
✔ **Normalization** for consistent pixel values.  
✔ **Augmentation** to improve model robustness.  

---

## 🛠 Requirements  
Ensure you have the following dependencies installed:  
```sh
pip install tensorflow numpy pandas matplotlib opencv-python scikit-learn
