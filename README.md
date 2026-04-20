# 🚑 Collision Risk Prediction in Autonomous Ambulance System

---

## 📌 Project Overview
This project focuses on predicting collision risk in an Autonomous Ambulance System using machine learning. The model analyzes traffic conditions and classifies scenarios as **High Risk** or **Low Risk**, helping improve safety in emergency navigation.

---

## 🎯 Objective
To develop a data-driven model that predicts collision risk using traffic density and distance-based features, enhancing decision-making in autonomous vehicles.

---

## 📂 Dataset
- Dataset: KITTI Vision Benchmark Suite (Object Detection Dataset)  
- Samples Used: 500  

### Features:
- `num_objects` → Traffic density  
- `min_distance` → Closest object distance  
- `avg_distance` → Average distance  

### Target:
- `0` → Low Risk  
- `1` → High Risk  

---

## ⚙️ Methodology
1. Data Collection (KITTI dataset)  
2. Data Preprocessing (cleaning & structuring)  
3. Feature Engineering  
4. Exploratory Data Analysis (EDA)  
5. Model Development (Classification)  
6. Model Evaluation  
7. Prediction & Risk Classification  

---

## 📊 Exploratory Data Analysis (EDA)
- Histogram → Object count distribution  
- Boxplot → Distance vs risk  
- Heatmap → Feature correlations  
- Confusion Matrix → Model performance  

👉 Key Insight:  
Lower distance and higher object density lead to higher collision risk.

---

## 🤖 Model Development
- Technique: Classification  
- Algorithm: Random Forest Classifier  

### Output:
- `0 → Low Risk`  
- `1 → High Risk`  

---

## 📈 Model Evaluation
- Train-Test Split: 80% training, 20% testing  

### Metrics:
- Accuracy: **1.00**  
- Precision: **1.00**  
- Recall: **1.00**  
- F1-score: **1.00**  

### Support:
- Low Risk: 73  
- High Risk: 27  

### Cross-Validation:
- Scores: [1.0, 1.0, 1.0, 1.0, 1.0]  
- Average Accuracy: **1.00**  

---

## 📊 Results & Insights
- Model achieves perfect classification on test data  
- Confusion matrix shows zero misclassification  
- ROC Curve AUC = **1.0**  
- Feature Importance:
  - `min_distance` → most important  
  - `num_objects` → second important  

---

## ⚠️ Limitations
- Simplified rule-based labeling  
- No temporal (time-series) analysis  
- No sensor fusion (LiDAR, radar, camera)  

---

## 🚀 Future Work
- Real-time data integration  
- LSTM / deep learning models  
- Sensor fusion implementation  
- Real-time deployment in AV systems  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 📌 Conclusion
This project demonstrates how machine learning can effectively predict collision risk in autonomous ambulance systems. The model highlights the importance of distance and object density in ensuring safety and supports data-driven decision-making in autonomous vehicles.

---
