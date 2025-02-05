# **Predictive Health Monitoring and Fault Classification of Rotating Bearings**

## **Project Overview**
This project focuses on **predictive maintenance** for rotating machinery by classifying bearing health conditions using **machine learning models**.

By leveraging **vibration data** collected from bearings under different failure conditions, the project aims to **detect and classify faults** such as:
- **Roller failure**
- **Inner race failure**
- **Outer race failure**
- **Combinations of the above failures** 

## **Technologies Used**
- **Python**  
- **NumPy & Pandas** – Data handling  
- **Scikit-learn** – Machine learning models  
- **Matplotlib** – Data visualization  
- **SciPy** – Signal processing  
- **Self-Organizing Maps (SOM)**  
- **Support Vector Machines (SVM)**  
- **Artificial Neural Networks (ANN - Multi-Layer Perceptron)**  

## **Methodology**
1. **Data Preprocessing**
   - Vibration signals collected using accelerometers at **50 kHz**
   - Time & frequency domain feature extraction
   - Dimensionality reduction using **Principal Component Analysis (PCA)**

2. **Machine Learning Models**
   - **Self-Organizing Map (SOM-MQE)** for anomaly detection
   - **Support Vector Machines (SVM-OvO & SVM-OvR)** for classification
   - **Artificial Neural Network (ANN-MLP)** for deep learning-based classification

3. **Model Evaluation**
   - Accuracy comparison of different models
   - Confusion matrices to assess misclassifications
   - Analysis of computational efficiency for real-time feasibility

## **Results**
| Model | Accuracy |
|--------|------------|
| **SOM-MQE** | ~85% |
| **SVM (OvO & OvR)** | **99.61%** |
| **ANN-MLP** | 98.24% |

**Best Model:** **SVM (OvR)** achieved **99.61% accuracy** with lower computational cost, making it ideal for real-time integration.
