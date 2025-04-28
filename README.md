
# Income Classification

This project focuses on building a **Logistic Regression** model to classify individuals' income levels based on various demographic and work-related features. The dataset undergoes preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Results](#results)


---

## Project Overview

The goal of this project is to predict whether an individual's income exceeds a certain threshold based on census data.  
We mainly use **Logistic Regression** for classification after performing necessary data preprocessing and analysis.

---

## Dataset

- **Source**: `income.csv`
- **Features**:  
  - Age
  - Workclass
  - Education
  - Marital Status
  - Occupation
  - Relationship
  - Race
  - Sex
  - Capital Gain
  - Capital Loss
  - Hours per Week
  - Native Country
- **Target**: `SalStat` (Salary Status)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (for Visualization)
- Scikit-Learn (for Modeling and Evaluation)

---

## Project Workflow

1. **Data Loading**
   - Import and duplicate the dataset for safe modifications.

2. **Data Preprocessing**
   - Handling missing values (dropping rows with null salary status).
   - Statistical description of numeric and categorical features.
   - Encoding categorical variables using Label Encoding.

3. **Exploratory Data Analysis (EDA)**
   - Distribution plots of features.
   - Correlation analysis using heatmaps.

4. **Model Building**
   - Split the dataset into training and testing sets (80:20 ratio).
   - Train a Logistic Regression model.

5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

---

## Results

- The Logistic Regression model achieves a reasonable accuracy on the test dataset.
- Insights into which features significantly affect income level.

---

