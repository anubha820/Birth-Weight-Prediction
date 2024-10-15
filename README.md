# Birth-Weight-Prediction
A Jupyter Notebook to predict a baby's birth weight.

### Purpose: 
- <b> Babies who are underweight can have complications (low birth weight): </b> Underweight is less than 5 lbs, 8 ounces.  It is usually caused by being born too early (premature). Complications for being underweight include short term / long term complications like low oxygen levels at birth, breathing problems, nervous system problems, digestive problems, developmental delays. 
- <b> Babies who are overweight can cause problems for the mother: </b> over 8 lbs, 13 ounces at birth. For the mother, it increases the need of a c-section, Type 2 diabetes, heart disease, asthma and obesity. If you have gestational diabetes, your baby could have problems with breathing, low glucose levels and jaundice.

### Inputs:
- test.csv: test dataset
- train.csv: train dataset

### This Jupyter Notebook walks through...
<b> 1. Exploratory Data Analysis </b>
- Factors before pregnancy (not pregnancy related)
- Factors before pregnancy (pregnancy related)
- Factors during pregnancy
- Factors on the delivery day
- Analysis on the Target Variable (Birth Weight)

<b> 2. Feature Engineering </b>

<b> 3. Preprocessing </b> - One Hot Encoding, Removing Null Values, Splitting Data into Test and Training

<b> 4. Model Selection </b> - Lasso Regression, XGB Regression, Ridge Regression

<b> 5. Feature Importance </b>

<b> 6. Model Improvements </b>
- Using Selected Features
- Upsampling Underweight and Overweight Babies
- Splitting Model into Male and Female
- Using One-Hot Encoded Features

<b> 7. Model Evaluation </b>
- Create a Prediction Interval

<b> 8. Case Studies </b>
- Underweight Baby
- Normal Baby

