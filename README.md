# Crop-Disease-Detection
# 🌱 Crop Disease Detection using Deep Learning

## 📌 Introduction
Agriculture is vital for global food security, but crop diseases pose a significant threat to yield and quality. Traditional methods of disease identification rely on manual inspection, which is time-consuming and error-prone. To address this challenge, our project leverages **Convolutional Neural Networks (CNNs)** for automated image-based crop disease detection. This approach enhances accuracy, reduces reliance on human experts, and enables early disease intervention.

## 🎯 Problem Statement
Crop diseases can severely impact agricultural productivity, leading to financial losses for farmers. Manual disease detection is inefficient, especially for large-scale farming. Our goal is to build an **AI-driven system** that can:
- Accurately classify **healthy and diseased crops**.
- Differentiate between multiple plant diseases.
- Detect disease-affected areas using **image processing** techniques.
- Provide real-time insights to assist farmers and agricultural experts.

## 🏆 Objectives
- Develop a **deep learning-based classifier** to distinguish between healthy and diseased crops.
- Use **CNNs and transfer learning** to improve disease identification.
- Implement **data augmentation** techniques for better generalization.
- Build a **user-friendly web-based application** for practical usage.

## 📊 Dataset Description
We trained our model on a **comprehensive dataset of plant images**, categorized into healthy and diseased crops.

### ✅ Initial Dataset:
- **10,000+ images** of tomato leaves with **10 different disease classes**.
- Images captured under varied lighting, angles, and backgrounds.
- Image size: **255x255 pixels**.

### 📈 Augmented Dataset:
- Enhanced dataset with **18,345 training images** and **4,585 testing images**.
- Applied augmentation techniques like flipping, rotation, blur, and random cropping.
- Improved model robustness and reduced overfitting.

## 🏗️ Methodology
### 🔹 Data Preprocessing
- **Resizing & Normalization**: Standardizing images for consistent input.
- **Augmentation**: Rotation, scaling, and contrast adjustments for better generalization.

### 🔹 Model Development
We experimented with **multiple deep learning models** to achieve optimal results:
1. **CNN (Custom architecture)**
2. **Inception-v3**
3. **VGG-16**
4. **VGG-16 (Fine-Tuned)**
5. **VGG-19**

The models were evaluated based on **accuracy, precision, recall, and F1-score**.

### 🔹 Deployment
- A **web-based application** was developed for real-time disease classification.
- The model can be accessed via a **simple user interface**, allowing farmers to upload images and receive disease predictions.

## 🚀 Results
- The **VGG-16 Fine-Tuned model** achieved the **highest accuracy (~96%)**.
- Image augmentation **improved classification performance** on diverse datasets.
- The system effectively identifies **common crop diseases** with high precision.

## 🔮 Future Work
- Expand dataset to include **more crop species** and diseases.
- Improve **real-time detection** using edge computing and IoT.
- Integrate a **mobile application** for easy accessibility.

## 👥 Contributors
- **Ishan Jain** (Manipal University Jaipur)

## 📜 References
For detailed methodology, results, and future improvements, please refer to:
- 📄 **[Crop Disease Detection Report](./2025_MLL_Jishan__Crop_Disease.pdf)**
