# Hospital-Inpatient-Discharge-Pneumonia-Dataset-
 Pneumonia Mortality Prediction Project

 Business Understanding

Background Research
Global Health Concern: Pneumonia affects individuals of all ages, particularly young children, the elderly, and those with compromised immune systems. 
Mortality Rates: In 2017, pneumonia caused over 800,000 deaths among children under five globally.
Causes and Treatment: Caused by bacteria, viruses, or fungi, treated with antibiotics, antiviral medications, and preventative measures like vaccinations.
Public Health Challenge in NYC: High incidence in NYC, particularly during colder months, with efforts focusing on vaccinations and improving healthcare access.

 Importance of Predicting Pneumonia Mortality
Early Identification: Helps in prioritizing and tailoring interventions to prevent fatalities.
Resource Allocation: Enables effective allocation of healthcare resources.
Improving Outcomes: Guides clinical decision-making to enhance patient outcomes and healthcare efficiency.

 Problem Statement

Healthcare providers in New York State aim to predict in-hospital mortality among pneumonia patients to implement targeted interventions and improve survival rates.

 Objectives

1. Identify High-Risk Populations: Determine demographic and clinical factors associated with higher pneumonia hospitalization rates.

2. Evaluate Quality of Care: Assess metrics like length of stay, patient disposition, and mortality rates.
3. Assess Economic Burden: Investigate costs associated with pneumonia hospitalizations.
4. Reduce Readmissions: Identify factors contributing to pneumonia-related readmissions and suggest strategies to minimize them.

 Data Understanding

 Dataset Overview
Source: Statewide Planning and Research Cooperative System (SPARCS) 
Inpatient De-identified dataset.
Period: 2009 to 2017.
Scope: Pneumonia patients in New York State.
Privacy: Complies with HIPAA, ensuring de-identified health information.

 Key Features
Patient Characteristics: Age, gender, race, ethnicity.
Diagnoses: Primary and secondary diagnosis codes and descriptions.
Treatments and Procedures: Details of medical procedures performed.
Services: Healthcare services provided during the hospital stay.
Charges and Costs: Financial data on total charges and costs.

 Data Preparation
Handling Missing Values: Imputation with mean values or placeholders like 'unknown'.
Removing Duplicates: Ensuring data integrity.
Correcting Errors: Addressing data entry errors, inconsistencies, and anomalies.
Standardizing Data Types: Ensuring consistency across the dataset.
Normalizing Numerical Features: Bringing features to a common range.
Managing Outliers: Preventing skewing of the analysis.

 Data Exploration

 Univariate Analysis
Histograms: Visualizing distribution of continuous variables.
Bar Plots: Analyzing frequency distributions of categorical variables.

 Bivariate Analysis
Target Variable Exploration: Assessing how each feature relates to the target variable.
Feature Interactions: Exploring interactions between different features using cross-tabulations.

 Multivariate Analysis
Correlation Matrix: Assessing relationships between numerical features.
Principal Component Analysis (PCA): Reducing dimensionality while retaining key variance.
Clustering: Grouping similar records based on multiple features to identify distinct patient segments.

 Code Repository
The code repository includes scripts for data preparation, exploratory data analysis, and model development. 

 Installation
1. Clone the repository: `git clone <repository_url>`
2. Install the required packages: `pip install -r requirements.txt`

 Results
- Predictive Model: Developed to forecast in-hospital mortality among pneumonia patients.
- Key Insights: Identified high-risk populations, assessed quality of care, evaluated economic burden, and provided strategies to reduce readmissions.

