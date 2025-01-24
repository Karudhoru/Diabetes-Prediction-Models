# **Diabetes Prediction Models: Logistic Regression vs Decision Tree**

## **Project Overview**

Diabetes is a chronic condition that affects millions of individuals worldwide. Early detection and effective management can significantly improve patient outcomes. This project focuses on developing and comparing two predictive models—**Logistic Regression** and **Decision Tree**—to evaluate their performance in predicting diabetes risk based on various health indicators. The dataset used for this analysis was sourced from Kaggle and contains health records of **768 individuals**.

---

## **Problem Statement**

The goal of this project is to build and compare machine learning models to predict the likelihood of diabetes in individuals based on key health-related parameters. These models aim to assist healthcare professionals in identifying high-risk individuals for timely intervention.

---

## **Dataset Description**

The dataset consists of **768 rows and 9 columns**, including features and the target variable. Each column represents critical health metrics used to predict diabetes.

### **Column Details**
- **Pregnancies**: Number of pregnancies (numeric).  
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test (numeric).  
- **BloodPressure**: Diastolic blood pressure in mmHg (numeric).  
- **SkinThickness**: Triceps skinfold thickness in mm (numeric).  
- **Insulin**: 2-hour serum insulin in µU/mL (numeric).  
- **BMI**: Body mass index (weight in kg/(height in m²)) (numeric).  
- **DiabetesPedigreeFunction**: A score indicating genetic predisposition to diabetes (numeric).  
- **Age**: Age of the individual (numeric).  
- **Outcome**: Target variable indicating diabetes presence (categorical: 0 = No, 1 = Yes).  

---

## **Tools and Technologies**

- **Programming Language**: Python (Jupyter Notebook)  
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  

---

## **Models Used**

1. **Logistic Regression**: A statistical model used for binary classification tasks.  
2. **Decision Tree**: A machine learning algorithm that uses a tree-like structure for decision-making.

---

## **Workflow**

### **1. Data Preprocessing**
- Handled missing values by imputing the median for numerical features.
- Normalized and scaled numeric features to improve model performance.
- No encoding was required for categorical data since the target variable is binary.

### **2. Model Development**
- Split the dataset into training and validation sets (80:20 ratio).  
- Developed two predictive models: **Logistic Regression** and **Decision Tree**.  

### **3. Model Evaluation**
- Evaluated the models based on accuracy, precision.  
- Compared the performance of the models to identify the most reliable one for diabetes prediction.

---

## **Conclusion**

Both models demonstrated effective predictive performance, but **Logistic Regression** provided more consistent results with higher precision and recall compared to the **Decision Tree**. These models can serve as valuable tools for healthcare professionals to assess diabetes risk and initiate early interventions.
