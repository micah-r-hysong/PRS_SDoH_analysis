# PRS_SDoH_analysis

## Summary
When using the All of Us Research Program to explore the relationship between various social determinants of health (SDoH) and nine chronic conditions we discovered that diseases have distinct “social architectures,” where the predictive strength, the most relevant SDoH, and the relative contributions of individual- versus area-level SDoH differ by trait. This prompted the development of disease-specific polysocial risk scores (PsRS) using elastic net models to select relative parameters and shrink estimates from related measures. Initial evidence in All of Us indicates that joint modeling of PsRS with PRS improves disease prediction for 8/9 conditions (e.g., Type 2 Diabetes AUC: 0.82 vs. 0.76 for PRS alone, p=2.64e-317). However, there is likely some overfitting within the All of Us cohort and we do not know about the generalizability of PsRS across healthcare systems. 

## Question
Are PsRS generalizable across healthcare systems? We will test this question for 6/9 of our conditions: asthma, breast cancer, chronic kidney disease (CKD), coronary heart disease (CHD), prostate cancer, and type 2 diabetes (T2D).

### Step 1
Implement disease algorithms. Make case control table (0 control, 1 case, NA neither)

### Step 2
Calculate record depth (number of visits) and visit frequency  (record depth / length of record in days (last encounter - first encounter)) for everyone

### Step 3
Get SDoH metrics for everyone 
5-level semi-continous education variable [Less than high school = 5, High school graduate = 4, 1 to 3 years after high school = 3, 4 or more years college = 2, Advance degree = 1]
3 digit zip code 
Income
Use code XXX

### Step 4 
Calculate PRS. PRS weights files for asthma, breast cancer, chronic kidney disease (CKD), coronary heart disease (CHD), prostate cancer, and type 2 diabetes (T2D) have been provided in the PRS folder. 

### Step 5
PRS mean and variance PC adjustment. Code is XXX in PRS folder. 



