# 🧠 AI Driven Kidney Stone Detection using DIP & CNN

## 📌 Project Overview
Kidney stones are a common and painful medical condition. Early and accurate detection is crucial for effective treatment.  
This project presents an **AI-driven kidney stone detection system** using **Digital Image Processing (DIP)** techniques and **Convolutional Neural Networks (CNN)** to automatically detect kidney stones from medical images.

The system enhances medical images, segments stone regions, extracts texture features, and classifies them using deep learning to achieve high accuracy.

---

## 🎯 Objectives
- Automate kidney stone detection from medical images  
- Reduce dependency on invasive diagnostic procedures  
- Improve accuracy and efficiency in medical diagnosis  
- Assist healthcare professionals with AI-based decision support  

---

## 🛠️ Technologies Used
- **MATLAB (2013a)**
- **Digital Image Processing (DIP)**
- **Convolutional Neural Networks (CNN)**
- **Fuzzy C-Means (FCM) Clustering**
- **Gray-Level Co-occurrence Matrix (GLCM)**

---

## 🧪 Methodology
1. **Image Acquisition**  
   - MRI / CT / Ultrasound kidney images

2. **Pre-processing**
   - Noise removal using Median Filter  
   - Contrast enhancement  
   - Image normalization  

3. **Segmentation**
   - Fuzzy C-Means (FCM) clustering to isolate kidney stone regions  

4. **Feature Extraction**
   - Texture features extracted using GLCM:
     - Contrast  
     - Correlation  
     - Energy  
     - Homogeneity  

5. **Classification**
   - Deep CNN model to classify stone vs non-stone regions  

6. **Performance Evaluation**
   - Accuracy  
   - Sensitivity  
   - Precision  
   - Specificity  

---

## 📊 Results
- Achieved **high accuracy** in detecting kidney stones  
- Improved sensitivity and specificity compared to traditional methods  
- Effective segmentation and classification of stone regions  

---

## 💻 System Requirements

### Hardware
- RAM: Minimum 4 GB  
- Hard Disk: 1 GB  
- Laptop/Desktop  

### Software
- Windows OS  
- MATLAB 2013a or later  
- Image Processing Toolbox  

---

## 📂 Project Structure
```text
├── dataset/
│   └── kidney_images/
├── preprocessing/
│   └── noise_removal.m
├── segmentation/
│   └── fcm_segmentation.m
├── feature_extraction/
│   └── glcm_features.m
├── classification/
│   └── cnn_model.m
├── results/
│   └── output_images/
├── README.md
🚀 How to Run the Project
Install MATLAB with Image Processing Toolbox

Clone this repository

Load the dataset into MATLAB workspace

Run preprocessing scripts

Execute segmentation and feature extraction

Train and test CNN model

View detection results

🔮 Future Scope
Integration with real-time hospital systems

Support for multi-modal medical images

Web-based or mobile diagnostic application

Enhanced CNN architectures for better accuracy

👩‍💻 Team Members
M Poojitha

J Bhavya Sree

K Sowmya

P Chandini

🏫 Institution
Sreenivasa Institute of Technology and Management Studies (SITAMS)
Department of Computer Science and Engineering

📜 License
This project is developed for academic and research purposes.









