# Explainable Machine Learning-Based Building Energy Performance Analysis

## Overview

This project explores the application of machine learning and explainable artificial intelligence (XAI) to building energy performance analysis.

The objective is to develop data-driven models for predicting building heating demand and to investigate the influence of building design parameters on energy performance.

The project combines:

- Engineering data analysis
- Machine learning-based prediction
- Model evaluation
- Explainable Artificial Intelligence (XAI) using SHAP
- Sensitivity analysis of building design parameters


---

# Research Motivation

Modern engineering systems require intelligent tools capable of analyzing complex relationships between design parameters and system performance.

Although machine learning models can provide accurate predictions, engineering applications require transparency and interpretability.

Therefore, this project integrates explainable AI methods to understand how engineering parameters influence energy performance.


---

# Research Question

Can machine learning models predict energy demand from engineering design parameters, and can explainable AI identify the dominant factors affecting energy efficiency?


---

# Dataset

Dataset:

UCI Energy Efficiency Dataset

Dataset Link : https://archive.ics.uci.edu/dataset/242/energy+efficiency


The dataset contains 768 building samples with:

## Input Variables

|Parameter|Description|
|-|-|
|X1|Relative Compactness|
|X2|Surface Area|
|X3|Wall Area|
|X4|Roof Area|
|X5|Overall Height|
|X6|Orientation|
|X7|Glazing Area|
|X8|Glazing Distribution|

## Output
- Heating Load (Y1)
---

# Methodology

The workflow consists of:

Engineering Dataset
 
   ↓

Data Analysis
   
   ↓

Machine Learning Models
   
   ↓

Prediction Evaluation
   
   ↓

Explainable AI Analysis
   
   ↓

Sensitivity analysis of selected building parameters

   ↓

Identification of potential directions for future optimization


---

# Machine Learning Models

The following regression models were investigated:


## 1. Linear Regression

Baseline statistical model.


## 2. Random Forest Regression

Ensemble learning approach for nonlinear engineering relationships.


## 3. Gradient Boosting Regression

Advanced ensemble prediction method.


## 4. Artificial Neural Network

Deep learning-based nonlinear model.


---

# Explainable AI

SHAP (SHapley Additive exPlanations) was used to identify:

- Important engineering variables
- Contribution of each parameter to model predictions
- AI decision interpretation


This improves trust and usability of AI models in engineering applications.


---

# Sensitivity Analysis and Future Optimization

To understand the influence of individual building design parameters on energy performance, a sensitivity analysis was performed using the trained Random Forest model.

The glazing area parameter was systematically varied while keeping other building characteristics constant. The resulting predictions were analyzed to investigate how changes in building design parameters affect heating demand.

This approach provides engineering insight into feature influence beyond model prediction.

Future extensions of this work may include integrating advanced optimization techniques, such as Bayesian optimization or evolutionary algorithms, to identify optimal building design configurations for minimizing energy consumption.


---

# Tools and Technologies

Python

Libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- shap
- scipy


Platform:

Google Colab


---

# Key Outcomes

The project demonstrates:

✓ Energy demand prediction using machine learning

✓ Comparison of multiple AI models

✓ Explainable AI for engineering interpretation

✓ Sensitivity Analysis and Future Optimization Scope


---

# Future Extensions

Possible future developments:

- Real-time engineering optimization
- Physics-informed machine learning
- Digital twin development
- Hybrid AI-process models



---

# Author

Palash Dey

Chemical Engineer & Researcher

Research Interests:

- AI-enabled process systems engineering
- Sustainable energy systems
- Data-driven engineering
- Risk and reliability analysis

