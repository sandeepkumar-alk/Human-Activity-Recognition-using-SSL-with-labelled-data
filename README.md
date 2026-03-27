# Human-Activity-Recognition-using-SSL-with-labelled-data

## 📌 Overview
This project focuses on **Human Activity Recognition (HAR)** using the **UCI HAR Dataset**, which contains smartphone sensor data (accelerometer and gyroscope). The goal is to classify human activities such as walking, sitting, standing, and laying using multiple machine learning and deep learning approaches.

---

## 🎯 Objectives
- Compare traditional ML models and deep learning models
- Improve classification accuracy using hybrid approaches
- Explore self-supervised learning for reduced label dependency
- Analyze performance using metrics and visualizations

---

## 📂 Dataset
- Dataset: **UCI HAR Dataset**
- Features: 561 engineered features
- Raw Data: 128 time steps × 9 sensor channels
- Activities:
  - Walking
  - Walking Upstairs
  - Walking Downstairs
  - Sitting
  - Standing
  - Laying

---

## ⚙️ Workflow

### 🔹 Step 1: Data Loading
- Loaded dataset from Google Drive
- Extracted `.zip` file
- Read train and test data

---

### 🔹 Step 2: Data Preprocessing
- Normalized data using StandardScaler
- Converted labels to categorical format
- Used two types of data:
  - Engineered features (561)
  - Raw sensor signals (128×9)

---

### 🔹 Step 3: Exploratory Data Analysis (EDA)
- Checked data distribution
- Visualized activity frequency
- Applied PCA for dimensionality reduction

📊 **EDA Visualization Placeholder**

---

### 🔹 Step 4: Machine Learning Models
- Random Forest
- Support Vector Machine (SVM)

✔ Used 561 feature dataset  
✔ Achieved strong baseline performance  

📊 **ML Results Table Placeholder**

---

### 🔹 Step 5: Deep Learning Model (CNN)
- Built 1D CNN model
- Applied Batch Normalization & Dropout
- Used raw sensor data for better performance

📊 **Training Graph Placeholder**

---

### 🔹 Step 6: Hybrid Model (CNN + SVM)
- Extracted deep features from CNN
- Combined with original features
- Used SVM for classification

✔ Achieved highest accuracy (~95%)

📊 **Hybrid Model Results**

---

### 🔹 Step 7: Self-Supervised Learning (SSL)
- Implemented Denoising Autoencoder (DAE)
- Learned feature representations without labels
- Used encoder features for classification

📊 **SSL Results**

---

## 📈 Results Summary

| Model               | Accuracy |
|--------------------|----------|
| Random Forest      | ~92%     |
| CNN                | ~90–93%  |
| Hybrid (CNN + SVM) | ~94–95%  |
| SSL Model          | ~88–92%  |

📊 **Final Comparison Table**


---

-
---

## 🧠 Key Learnings
- CNN performs better with raw time-series data
- Hybrid models improve accuracy significantly
- Feature engineering still strong for ML models
- Self-supervised learning reduces label dependency

---

## 🚀 Future Work
- Implement Transformer-based models
- Improve SSL accuracy further
- Deploy model as real-time application

---

## 💾 Model Saving
- Models saved to Google Drive
- Includes:
  - CNN model
  - Random Forest
  - SVM (Hybrid)
  - SSL models

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy / Pandas
- Matplotlib / Seaborn

---

## 👨‍🎓 Author
**Sandeep Kumar**  
Student ID: 24098245  

---

## 🔗 Colab Notebook
[Open in Google Colab](https://colab.research.google.com/drive/11eHhZuLgSlvM9WZ9lSGua3yo7_ttjJP1?usp=sharing)

---
