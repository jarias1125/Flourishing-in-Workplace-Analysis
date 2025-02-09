# Flourishing Data Analysis - Machine Learning Project

## Overview
This project analyzes the **Flourishing Dataset**, which focuses on measuring various aspects of **employee well-being** in both professional and personal life. The dataset includes **248 individuals**, with key variables representing **professional flourishing, private life flourishing, and positivity**, alongside demographic attributes. The analysis leverages **machine learning and statistical methods** to explore relationships between these variables and predict key indicators of well-being.

---

## Project Objectives
- Understand the relationship between **professional and private flourishing**.
- Identify key factors influencing **positivity** in employees.
- Perform **statistical and machine learning modeling** to predict **flow and positivity**.
- Provide insights for organizations to improve **employee satisfaction and productivity**.

---

## Dataset Description
### **Main Variables**
- **Quantitative Variables**:
  - `Age` - Participant's age.
  - `pro_quant` - Professional flourishing score.
  - `priv_quant` - Private life flourishing score.
  - `flow` - Deep focus and immersion measure.
- **Categorical Variables**:
  - `Sex` - Male or Female.
  - `famstatus` - Family status (single, married, divorced, etc.).
  - `education` - Highest education level achieved.
  - `pro_cat` - Professional category.
  - `priv_cat` - Private category.
  - `positivity` - General emotional outlook.

### **Target Variables**
- **Flow**: Measures the ability to thrive under challenging conditions.
- **Positivity**: Captures an individual's general outlook on life.

---

## Methodology
### **1. Data Preprocessing**
- Imported and cleaned the dataset using **Pandas and NumPy**.
- Transformed categorical variables using **label encoding and mapping techniques**.
- Handled missing values and ensured **data consistency**.

### **2. Exploratory Data Analysis (EDA)**
- **Univariate Analysis**:
  - Distribution of key variables and their impact on well-being.
- **Bivariate Analysis**:
  - Statistical tests such as **Chi-Square, Cramer’s V, correlation tests** to determine significant relationships.

### **3. Machine Learning Models**
#### **Linear Regression**
- Used to predict **flow** based on positivity, professional flourishing, and age.
- Achieved an **R² of 0.423**, indicating that 42.3% of the variability in **flow** can be explained by the model.

#### **Logistic Regression**
- Developed to predict **positivity** as a binary outcome (high vs. low).
- Achieved **74% accuracy**, showing the model is reliable in identifying positive individuals.

### **4. Key Predictors**
- **Professional flourishing** is a significant factor in predicting both **flow and positivity**.
- **Age and education level** contribute to increased flow states.

---

## Key Outcomes
- **Professional flourishing significantly impacts positivity**, confirming that workplace well-being contributes to a positive mindset.
- **Education and career development programs** can **enhance positivity and work performance**.
- **Predictive models** provide insights for companies to implement **personalized well-being strategies**.
- The findings can be used to **design better work environments**, improving overall employee satisfaction.

---

## Repository Contents
-  **Flourishing.ipynb** - Jupyter Notebook containing the full analysis and machine learning models.
-  **Flourishing_248_HD.xlsx** - Dataset used for analysis.
-  **Report on the Flourishing Data Set.pdf** - Detailed documentation of findings and insights.

---

## How to Use
### **1. Run the Jupyter Notebook**
- Open `Flourishing.ipynb` and execute the cells step by step.

### **2. Analyze the Dataset**
- Use **EDA visualizations** to explore key insights.

### **3. Train the Models**
- Run the regression and classification models to predict **flow and positivity**.

### **4. Interpret Results**
- Use statistical outputs to guide workplace well-being decisions.

---

This project provides actionable insights into **employee well-being** and how **professional and personal factors influence productivity and positivity**.

