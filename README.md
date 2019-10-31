# Exploratory-Data-Analysis

Explore association in biomarker and  cardiac MRI  in women with ischemia and no obstructive coronary artery disease

## Background

Women with ischemia and no obstructive CAD were enrolled. Some had cardiac cath. However, all of them had cardiac MRI and most of them had follow up cardiac MRI. Additionally, these women had urine hsTNI and blood BNP. 

## Study Aims

### Aim 1: 
to investigate whether women with coronary endothelial dysfunction have higher urine hsTNI 

### Aim 2: 
to explore if women with higher left ventricular strain rate (at baseline) have higher urine hsTNI and higher BNP levels 

### Aim 3: 
to explore if women with higher urine hsTNI at baseline have worsened LV strain rate on follow up cardiac MRI 

## Analysis Plan:

### Aim 1: 
a) Scatter plot of hsTNI (or log hsTNI) vs. ACHDIARES to see if there is any specific pattern or a potential cut point

b) Scatter plot of hsTNI (or log hsTNI) vs. ACHCBF_BEST to see if there is any specific pattern or a potential cut point

c) Compare hsTNI (or log hsTNI) between those with ACHDIARES<0 vs. ACHDIARES>=0 using Wilcoxon or t test 

d) Compare hsTNI (or log hsTNI) between those with ACHCBF_BEST < 20 vs. ACHCBF_BEST>=20 using Wilcoxon or t test 

e) Compare hsTNI (or log hsTNI) between those with ACHCBF_BEST < 50 vs. ACHCBF_BEST>=50 using Wilcoxon or t test 

f) Compare hsTNI (or log hsTNI) between those with ACHCBF_BEST < median vs. ACHCBF_BEST >=median using Wilcoxon or t test

### Aim 2: 
a) Scatter plot of hsTNI (or log hsTNI) vs. each cMRI variable

b) Correlation matrix of all cMRI variables

c) Determine PCA or FA on cMRI variables

d) Extract principal components of factors and then examine the association with hsTNI and BNP (possibly adjusted for age)


### Aim 3: to explore if women with higher urine hsTNI at baseline have worsened LV strain rate on follow up cardiac MRI
