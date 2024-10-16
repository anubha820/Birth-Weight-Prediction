# Birth-Weight-Prediction
A Jupyter Notebook to predict a baby's birth weight. Inspired by this [Kaggle Challenge](https://www.kaggle.com/competitions/prediction-interval-competition-i-birth-weight).

Presented at the Grace Hopper Celebration (GHC) '24. [Click here](https://github.com/anubha820/Birth-Weight-Prediction/blob/main/GHC%20Presentation.pdf) view the presentation.

### Purpose: 
- <b> Babies who are underweight can have complications (low birth weight): </b> Underweight is less than 5 lbs, 8 ounces.  It is usually caused by being born too early (premature). Complications for being underweight include short term / long term complications like low oxygen levels at birth, breathing problems, nervous system problems, digestive problems, developmental delays. 
- <b> Babies who are overweight can cause problems for the mother: </b> over 8 lbs, 13 ounces at birth. For the mother, it increases the need of a c-section, Type 2 diabetes, heart disease, asthma and obesity. If you have gestational diabetes, your baby could have problems with breathing, low glucose levels and jaundice.

<img width="211" alt="Newborn baby on weight scale." align="center" src="https://thumbs.dreamstime.com/z/weight-scale-infant-icon-digital-scales-measure-weight-pounds-weight-scale-infant-icon-127015201.jpg?w=768">

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

<img width="600" alt="Histogram of Father vs. Mother's education." src="https://github.com/user-attachments/assets/68ccdf83-a3e8-4b7f-ad44-a872845b4b6f">

<b> 2. Feature Engineering </b>

<b> 3. Preprocessing </b> - One Hot Encoding, Removing Null Values, Splitting Data into Test and Training

<b> 4. Model Selection </b> - Lasso Regression, XGB Regression, Ridge Regression

<b> 5. Feature Importance </b>

<img width="600" alt="Feature Importance" src="https://github.com/user-attachments/assets/0690522e-58b5-418a-9922-e71152b7a5de">

<b> 6. Model Improvements </b>
- Using Selected Features
- Upsampling Underweight and Overweight Babies
- Splitting Model into Male and Female
- Using One-Hot Encoded Features

<b> 7. Model Evaluation </b>
- Create a Prediction Interval
<img width="600" alt="Actual vs. Predicted Values" src="https://github.com/user-attachments/assets/d2ba61d6-ac2a-4592-bd1e-6d1952e43536">

- Evaluate Model with Metrics
<img width="211" alt="Metrics for Evaluation - MSE, RMSE" src="https://github.com/user-attachments/assets/aeb428a5-1268-406b-a747-f98dacd4947a">

<b> 8. Case Studies using Shapley Values </b>
- Underweight Baby
- Normal Baby

