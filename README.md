# Breast-Cancer-Analytics-And-Risk-Prediction

## Project Overview

Breast cancer remains one of the leading causes of cancer-related deaths worldwide. Early diagnosis significantly improves treatment outcomes and survival rates. This project applies data analytics and machine learning techniques to analyze breast cancer diagnostic data, uncover critical health indicators, and predict tumor diagnosis outcomes.

The project demonstrates an end-to-end analytics workflow, including data cleaning, exploratory data analysis (EDA), feature analysis, visualization, and predictive modeling.

---

## Business Problem

Healthcare professionals generate large volumes of diagnostic data during cancer screening procedures. Identifying the most influential diagnostic measurements can help support early detection and improve clinical decision-making.

This project aims to:

* Analyze diagnostic characteristics associated with breast cancer.
* Identify patterns differentiating benign and malignant tumors.
* Generate actionable insights through data visualization.
* Develop predictive models for diagnosis classification.

---

## Dataset

The dataset contains diagnostic measurements collected from breast cancer screenings.

### Key Attributes

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension
* Additional diagnostic measurements

### Target Variable

* **Malignant (M)** – Cancerous tumor
* **Benign (B)** – Non-cancerous tumor

---

## Project Structure

```text
breast-cancer-risk-prediction/
│
├── data/
│   ├── breast_cancer_data.csv
│   ├── breast_cancer_data_clean.csv
│   └── breast_cancer_data_clean_id.csv
│
├── notebook/
│   └── breast_cancer_prediction.ipynb
│
└── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Data Analytics Workflow

### 1. Data Cleaning

* Removed unnecessary columns and identifiers
* Handled missing values
* Validated data quality
* Prepared data for analysis

### 2. Exploratory Data Analysis (EDA)

* Class distribution analysis
* Statistical summary analysis
* Correlation analysis
* Distribution visualization
* Outlier detection
* Feature relationship exploration

### 3. Feature Analysis

* Identification of highly correlated variables
* Evaluation of influential diagnostic features
* Analysis of feature impact on diagnosis outcomes

### 4. Predictive Modeling

* Data preprocessing and feature scaling
* Model training and testing
* Performance comparison across classification algorithms

---

## Key Insights

* Several diagnostic measurements show strong correlation with tumor diagnosis.
* Malignant tumors exhibit distinct measurement patterns compared to benign tumors.
* Feature correlation analysis helps identify the most significant diagnostic indicators.
* Predictive models can accurately classify tumors based on diagnostic measurements.

---

## Machine Learning Models Evaluated

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## Evaluation Metrics

Model performance was assessed using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

---

## Results

The project successfully demonstrates how healthcare data analytics can support early breast cancer diagnosis by combining statistical analysis, visualization, and predictive modeling techniques.

---

## Future Improvements

* Hyperparameter optimization
* Advanced ensemble models
* Interactive Power BI/Tableau dashboard
* Real-time prediction application using Streamlit
* Explainable AI techniques for healthcare decision support

---

## Author

**Hariharan Sabapathi**
