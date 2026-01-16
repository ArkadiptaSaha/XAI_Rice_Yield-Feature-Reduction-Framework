# XAI_Rice_Yield-Feature-Reduction-Framework  
### *An Explainable AI-Driven Feature Reduction Framework for Enhanced Agricultural Yield Prediction*

**Authors:**  
Dey, Anamika; **Saha, Arkadipta**; Sarkar, Somrita; Mondal, Arijit; Mitra, Pabitra  

---

## 📌 Project Overview

Agricultural yield prediction is critical for food security, resource planning, and economic decision-making. However, traditional machine learning models often struggle with **high-dimensional, heterogeneous agricultural datasets**, leading to computational inefficiencies and limited interpretability.

This project presents an **Explainable AI (XAI)-driven feature reduction framework** that improves rice yield prediction by:
- Enhancing model interpretability  
- Reducing unnecessary and negatively contributing features  
- Improving prediction accuracy  
- Lowering computational cost and training time  

The framework integrates **machine learning, deep learning, and explainability techniques** to build a scalable and practical solution for real-world agricultural applications.

---

## 🎯 Objective

The primary goal of this work is to:
- Develop accurate rice yield prediction models using advanced ML and DL techniques  
- Apply **SHAP-based Explainable AI** to interpret model behavior  
- Systematically remove negatively contributing features  
- Improve prediction performance while reducing model complexity  

---

## 📊 Dataset

This study uses a **multivariate public dataset from rice fields in An Giang province, Mekong Delta, Vietnam**, which includes:

### 🔹 Satellite Data Sources:
- **Landsat (Optical Data)** – captures vegetation and crop health information  
- **Sentinel-1 (Radar Data)** – provides surface backscatter insights  

### 🔹 Key Radar Features Used:
- **VV (Vertical-Vertical) polarization**
- **VH (Vertical-Horizontal) polarization**

Among all features, **`min_vh` consistently emerged as the most important predictor**, capturing critical information related to:
- Crop structure  
- Growth stages  
- Soil conditions after harvest  

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Data normalization  
- Feature engineering  
- Missing value handling  
- Data cleaning and transformation  

### 2️⃣ Model Development
We evaluated multiple predictive models, including:
- **Random Forest**
- **Gradient Boosting Machines**
- **Convolutional Neural Networks (CNNs)**
- **LSTM with Attention Mechanism**

### 3️⃣ Hyperparameter Optimization
- Applied **Grid Search** to optimize model performance  
- Reduced risks of overfitting and underfitting  

### 4️⃣ Explainable AI (XAI) using SHAP
- Used **SHAP (SHapley Additive exPlanations)** to analyze feature importance  
- Identified negatively contributing features  
- Provided transparent insights into model decision-making  

### 5️⃣ Feature Reduction Strategy
- Removed **15–20 negatively contributing features**
- Achieved:
  - **3–5% improvement in prediction accuracy**
  - Significant reduction in computational cost
  - Faster training time
  - Maintained model interpretability  

---

## 🚀 Key Contributions

✔ Developed an interpretable ML/DL framework for rice yield prediction  
✔ Introduced a SHAP-based systematic feature reduction method  
✔ Improved prediction accuracy while reducing model complexity  
✔ Demonstrated effectiveness using real satellite-based agricultural data  
✔ Created a scalable framework adaptable to other agricultural prediction tasks  

---

## 🛠 Technologies Used

| Component | Tools / Techniques |
|------------|-------------------|
| Programming | Python |
| ML Models | Random Forest, Gradient Boosting |
| Deep Learning | CNN, LSTM with Attention |
| Explainability | SHAP |
| Satellite Data | Landsat, Sentinel-1 |
| Optimization | Grid Search |
| Data Processing | NumPy, Pandas |

---

---

## 📊 Results

- Feature reduction of **15–20 variables**
- **3–5% improvement in yield prediction accuracy**
- Reduced computational overhead  
- Improved interpretability using SHAP  
- Identified `min_vh` as the most influential predictor  

---

## 🔮 Future Scope

- Extend framework to other crops (wheat, maize, etc.)  
- Apply to different geographical regions  
- Integrate real-time satellite data streams  
- Explore transformer-based time-series models  

---

## 📬 Contact

For collaboration or queries:

**Arkadipta Saha**  
Department of Electrical Engineering  
IIT Kharagpur  
📧 arkadiptasaha04@gmail.com  
🔗 https://github.com/ArkadiptaSaha

---
