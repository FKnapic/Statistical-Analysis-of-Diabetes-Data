# Diabetes Data Analysis Project

## Overview
This project was developed as part of the course **Statistical Data Analysis**. The project team “Boksači” focused on analyzing a dataset of diabetic patients to explore relationships between patient characteristics, disease types, and health indicators. The main goal was to answer specific research questions using descriptive and inferential statistics.

---

## Dataset
- **Name:** `diabetes_dataset00.csv`
- **Number of rows:** 70,000
- **Number of columns:** 34
- **Features include:** Age, BMI, Blood Pressure, Cholesterol Levels, Waist Circumference, Physical Activity, Dietary Habits, Genetic Markers, Type of Diabetes (Target), Pancreatic Health, Smoking Status, and more.

The dataset contains both numerical and categorical variables. Categorical variables were converted to factors for statistical analysis.


---

## Research Questions and Methods

### 1. Can we estimate the age of a patient based on given parameters?
- **Goal:** Predict patient age using selected variables.
- **Predictors:** BMI, Blood Pressure, Cholesterol Levels, Waist Circumference, and Physical Activity.
- **Methods:** 
  - Scatter plots and boxplots to explore relationships  
  - Linear regression and multiple linear regression  
  - Residual analysis and confidence intervals for predictions
- **Key Insight:** Certain variables, such as BMI, Blood Pressure, Cholesterol, and Waist Circumference, showed strong linear relationships with age, allowing reasonably accurate age predictions.

---

### 2. Are there differences in disease types between smokers and non-smokers?
- **Goal:** Examine the relationship between diabetes type (`Target`) and smoking status (`Smoking Status`).  
- **Methods:** 
  - χ² test of independence  
  - Bar plots and mosaic plots for visualization  
- **Key Insight:** The p-value was greater than 0.05, indicating no statistically significant association between smoking status and disease type.

---

### 3. Is there a difference in pancreatic health among different diabetes types?
- **Goal:** Determine if `Pancreatic Health` differs across diabetes categories.  
- **Methods:** 
  - ANOVA test to compare mean values between groups  
  - Normality and homogeneity checks for each group  
- **Key Insight:** Differences in pancreatic health were analyzed per diabetes type, considering statistical assumptions for valid ANOVA testing.

---

## Visualization
- Scatter plots, boxplots, bar plots, and mosaic plots were used to visualize relationships between variables.  
- Residuals and confidence intervals were checked to validate regression models.  

---

## Conclusion
The project demonstrates the use of statistical methods for exploring relationships in a large clinical dataset.  
Key outcomes:
- Multiple linear regression can estimate age based on physiological indicators.  
- Smoking status does not significantly affect disease type distribution.  
- Differences in pancreatic health across diabetes types can be statistically analyzed with ANOVA.

