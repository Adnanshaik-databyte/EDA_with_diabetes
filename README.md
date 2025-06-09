Diabetes Prediction - Exploratory Data Analysis (EDA)

-Overview:
This repository contains an exploratory data analysis (EDA) on the Pima Indians Diabetes Dataset. The dataset provides medical data related to diabetes diagnosis, including features     like glucose levels, BMI, insulin, and genetic predisposition.

Dataset
The dataset (diabetes.csv- https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data) consists of 768 rows and 9 features:

Pregnancies - Number of times a patient has been pregnant

Glucose - Blood glucose concentration (mg/dL)

BloodPressure - Diastolic blood pressure (mm Hg)

SkinThickness - Skin fold thickness (mm)

Insulin - Insulin levels (μU/mL)

BMI - Body Mass Index (kg/m²)

DiabetesPedigreeFunction - Genetic diabetes risk indicator

Age - Age of the patient

Outcome - 1 = Diabetes Positive, 0 = Non-Diabetic

-Exploratory Data Analysis (EDA)
  1. Data Cleaning & Preprocessing
  Handled missing values in Insulin and SkinThickness
  Checked for outliers using boxplots
  Normalized skewed distributions for better analysis
  
  2. Data Visualization
  Histograms show significant patterns in glucose and BMI distributions
  Boxplots reveal distinct differences in glucose levels among diabetic vs. non-diabetic individuals
  Pairplot & Heatmap identify key correlations among features
  3. Statistical Comparisons
  T-test on glucose levels confirms statistically significant differences between diabetic and non-diabetic groups
  Effect Size (Cohen’s d) indicates glucose as a strong predictor

  -Key Findings
  High glucose and BMI values are major indicators of diabetes
  Older individuals tend to show increased diabetes risk
  Insulin & Skin Thickness may need imputation due to missing values
  Diabetes Pedigree Function shows a moderate genetic influence

  ________________________________________________________________
  LinkedIn : (Adnan Shaik) www.linkedin.com/in/mohammed-adnan-shaik-310092366
