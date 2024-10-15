# Birth-Weight-Prediction
A Jupyter Notebook to predict a baby's birth weight.

### Purpose: 
- <b> Babies who are underweight can have complications (low birth weight): </b> Underweight is less than 5 lbs, 8 ounces.  It is usually caused by being born too early (premature). Complications for being underweight include short term / long term complications like low oxygen levels at birth, breathing problems, nervous system problems, digestive problems, developmental delays. 
- <b> Babies who are overweight can cause problems for the mother: </b> over 8 lbs, 13 ounces at birth. For the mother, it increases the need of a c-section, Type 2 diabetes, heart disease, asthma and obesity. If you have gestational diabetes, your baby could have problems with breathing, low glucose levels and jaundice.

![]([https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png](https://www.dreamstime.com/weight-scale-infant-icon-digital-scales-measure-weight-pounds-weight-scale-infant-icon-image127015201) | width=100)

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

Example Histogram of Father's vs. Mother's Education:
![image](https://github.com/user-attachments/assets/68ccdf83-a3e8-4b7f-ad44-a872845b4b6f | width=100)

<b> 2. Feature Engineering </b>

<b> 3. Preprocessing </b> - One Hot Encoding, Removing Null Values, Splitting Data into Test and Training

<b> 4. Model Selection </b> - Lasso Regression, XGB Regression, Ridge Regression

<b> 5. Feature Importance </b>
![Feature Importance](https://github.com/user-attachments/assets/0690522e-58b5-418a-9922-e71152b7a5de | width=100)

<b> 6. Model Improvements </b>
- Using Selected Features
- Upsampling Underweight and Overweight Babies
- Splitting Model into Male and Female
- Using One-Hot Encoded Features

<b> 7. Model Evaluation </b>
- Create a Prediction Interval
![image](https://github.com/user-attachments/assets/d2ba61d6-ac2a-4592-bd1e-6d1952e43536 | width=100)
<img width="211" alt="Screenshot 2024-10-15 at 4 22 54 PM" src="https://github.com/user-attachments/assets/aeb428a5-1268-406b-a747-f98dacd4947a">


<b> 8. Case Studies using Shapley Values </b>
- Underweight Baby
- Normal Baby

