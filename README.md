# Sleep Disorder Prediction Using Multiple Machine Learning Algorithms

## Overview
This project performs a **comparative analysis of machine learning algorithms** for predicting sleep disorders based on health and lifestyle data.  
We evaluate **XGBoost, K-Nearest Neighbors (KNN), Gradient Boosting, and Logistic Regression** to determine which model performs best in identifying **Insomnia, Sleep Apnea, and No Disorder** cases.  

**Disclaimer**: This tool is strictly for **educational and research purposes**. It is **not intended for medical diagnosis**.

---

## Dataset
- **Name:** Sleep Health and Lifestyle Dataset  
- **Size:** 374 individuals (professionals)  
- **Features:** Age, Gender, Occupation, BMI Category, Sleep Duration, Stress Level, Blood Pressure, Physical Activity, etc.  
- **Target:** Sleep Disorder (No Disorder, Insomnia, Sleep Apnea)  

Preprocessing steps include:  
- Handling missing values  
- Encoding categorical features  
- Standardizing BMI categories  
- Balancing classes using **SMOTE**

---

## Models Implemented
- **XGBoost**  
- **K-Nearest Neighbors (KNN)**  
- **Gradient Boosting**  
- **Logistic Regression**  

Each model is evaluated using:  
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- Cross-Validation

---

## Results
- **XGBoost, Gradient Boosting, and KNN** achieved the most consistent performance (~90–92% accuracy).  
- **Logistic Regression** sometimes diverged due to non-linear patterns in the data.  
- Model comparison plots and detailed metrics are included in the notebooks.  

There was strong agreement among models in **clear cases** (e.g., no disorder), while **borderline cases** resulted in mixed predictions, highlighting the need for clinical validation.

---

## Interactive Prediction Tool
The project includes an **interactive interface** (via `ipywidgets`) where users can:  
- Adjust inputs (Age, Sleep Duration, Stress Level, BMI, etc.)  
- Select different ML models  
- View predictions and probabilities  
- Receive general lifestyle recommendations  

---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
