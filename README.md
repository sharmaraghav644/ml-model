# ML Model Project - Predict the Chance of Cardiovascular Disease (CVD)

## Description

Cardiovascular diseases (CVDs) are the leading cause of death worldwide, making it crucial to identify risk factors and develop effective prediction systems for heart attacks. In this project, we use historical health data to predict the likelihood of CVD based on various factors such as age, blood pressure, cholesterol, and more. The goal is to build a predictive model that can accurately determine the risk of heart attacks and help in timely interventions.

## Table of Contents

1. [Description](#description)
2. [Technology Used](#technology-used)
3. [Dependencies](#dependencies)
4. [Project Insights](#project-insights)

## Technology Used

- **Pandas**: For data manipulation, cleaning, and exploration.
- **Numpy**: For handling numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization and exploratory data analysis.
- **Scikit-learn**: For building machine learning models (Logistic Regression, Random Forest).
- **Statsmodels**: For advanced statistical modeling, including logistic regression with p-values and standard errors.
- **Jupyter Notebooks**: For an interactive analysis environment.

## Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
- `jupyter`

## Project Insights

### Preliminary Data Inspection and Analysis:

- **Structure of the Data**: The dataset consists of various health metrics that might influence cardiovascular health, including demographic factors (e.g., age, sex), physiological measures (e.g., blood pressure, cholesterol), and lifestyle-related factors.
- **Missing Values**: We handled missing values using appropriate strategies such as mean/median imputation for numerical variables and mode imputation for categorical variables.
- **Duplicates**: Any duplicate records were removed to ensure the integrity of the analysis.

### Statistical Summary:

- A preliminary statistical summary was generated to explore the measures of central tendency (mean, median) and spread (variance, standard deviation) for numerical variables.
- **Categorical Variables**: Categorical variables like `sex`, `thalassemia`, and `target` (indicating the presence of heart disease) were explored using count plots to visualize the distribution.

### Exploratory Data Analysis (EDA):

- **Age vs CVD**: We analyzed the occurrence of CVD across different age groups and observed trends in the data.
- **Sex Distribution**: We studied the composition of patients with CVD based on gender to identify any significant patterns.
- **Resting Blood Pressure**: The relationship between resting blood pressure (`trestbps`) and the occurrence of CVD was examined to detect any anomalies that may indicate a risk of heart attack.
- **Cholesterol Levels**: We analyzed how varying cholesterol levels correlate with the occurrence of CVD.
- **Exercise and CVD**: The relationship between peak exercise (`thalach`) and heart disease occurrence was studied to see if exercise level plays a role in heart health.
- **Thalassemia**: We investigated if thalassemia is a major cause of CVD and its impact on heart disease prediction.
- **Pair Plot**: A pair plot was created to understand the relationships between all variables and visually detect patterns or correlations.

### Model Building:

- **Baseline Model**: We built a baseline predictive model using **Logistic Regression** and **Random Forest** to predict the likelihood of heart attacks.
- **Correlation Analysis**: A correlation analysis was performed to identify highly correlated features and reduce multicollinearity.
- **Feature Selection**: Using **Logistic Regression** with **p-values** and **standard errors** (via Statsmodels), we performed feature selection to retain only the most relevant features for model tr

