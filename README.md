# Thyroid Cancer Risk Prediction Dataset

## Overview
This dataset contains **212,691 records** related to **thyroid cancer risk factors**, including demographic details, medical history, lifestyle influences, and key thyroid hormone levels. It can be used to assess the probability of thyroid cancer based on various risk indicators.

### **Potential Applications**
- Exploratory Data Analysis (EDA) & Visualization
- Data Preprocessing (Encoding, Scaling, Handling Missing Data)
- Machine Learning for Thyroid Cancer Risk Prediction
- Statistical Analysis on Risk Factors
- Deep Learning Models for Advanced Classification
- Healthcare Analytics & Risk Assessment Tool Development

## **Dataset Description**

| Column Name           | Data Type | Description |
|----------------------|-----------|-----------------------------------------------------------|
| **Patient_ID**       | int       | Unique identifier for each patient |
| **Age**              | int       | Age of the patient |
| **Gender**           | object    | Patient’s gender (Male/Female) |
| **Country**          | object    | Country of residence |
| **Ethnicity**        | object    | Patient’s ethnic background |
| **Family_History**   | object    | Family history of thyroid cancer (Yes/No) |
| **Radiation_Exposure** | object  | History of radiation exposure (Yes/No) |
| **Iodine_Deficiency** | object  | Presence of iodine deficiency (Yes/No) |
| **Smoking**          | object    | Whether the patient smokes (Yes/No) |
| **Obesity**          | object    | Whether the patient is obese (Yes/No) |
| **Diabetes**         | object    | Whether the patient has diabetes (Yes/No) |
| **TSH_Level**        | float     | Thyroid-Stimulating Hormone level (µIU/mL) |
| **T3_Level**         | float     | Triiodothyronine level (ng/dL) |
| **T4_Level**         | float     | Thyroxine level (µg/dL) |
| **Nodule_Size**      | float     | Size of thyroid nodules (cm) |
| **Thyroid_Cancer_Risk** | object | Estimated risk of thyroid cancer (Low/Medium/High) |
| **Diagnosis**        | object    | Final diagnosis (Benign/Malignant) |

## **How to Use This Dataset**
### **1. Exploratory Data Analysis (EDA)**
- Visualize distributions of **age, hormone levels, and nodule size**.
- Identify trends in **risk factors vs. final diagnosis**.
- Examine correlation between **lifestyle factors and thyroid cancer risk**.

### **2. Data Preprocessing**
- Encode categorical variables (e.g., **Gender, Family_History, Risk Levels**).
- Scale numerical features (e.g., **TSH, T3, T4 Levels, Nodule Size**).
- Handle missing values and balance data for better model performance.

### **3. Machine Learning & Deep Learning**
- Train classification models (**Logistic Regression, Decision Trees, Random Forest, XGBoost**).
- Build deep learning models (**ANN, CNN for pattern recognition in thyroid diagnosis**).
- Compare model performance using **accuracy, precision, recall, F1-score, and AUC-ROC**.

### **4. Statistical Testing & Healthcare Analytics**
- Conduct hypothesis tests on **risk factors and diagnosis outcomes**.
- Develop **risk assessment dashboards** for healthcare professionals.

## **Installation & Dependencies**
You can start by installing necessary dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras
```

## **Example Usage**
```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("thyroid_cancer_risk.csv")

# Check data structure
df.info()

# Visualize TSH level distribution
sns.histplot(df['TSH_Level'], bins=30, kde=True)
plt.title("Distribution of TSH Levels")
plt.show()
```

## **Contributing**
Contributions are welcome! Feel free to submit a pull request with improvements, bug fixes, or new insights from this dataset.

## **License**
This dataset is made available for **educational and research purposes**. Ensure ethical use and follow data privacy guidelines.

---


### **Contact**
For inquiries, contact: **arifmiahcse@gmail.com**

