# Explainable AI-Based Energy Efficiency Optimization Framework

## Overview

This project develops a machine learning-based framework for predicting energy demand and identifying important engineering parameters affecting energy efficiency.

The objective is to demonstrate how artificial intelligence and data-driven methods can support sustainable engineering decision-making.

The framework combines:

- Engineering data analysis
- Machine learning prediction
- Explainable Artificial Intelligence (XAI)
- Optimization-based design analysis


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

Optimization Study


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

SHAP (Shapley Additive Explanations) was used to identify:

- Important engineering variables
- Contribution of each parameter to model predictions
- AI decision interpretation


This improves trust and usability of AI models in engineering applications.


---

# Optimization Study

The trained machine learning model was used as a surrogate model for design analysis.

Example:

Changing building parameters

↓

AI prediction

↓

Estimate energy impact

↓

Support engineering decisions


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

✓ AI-assisted optimization approach


---

# Future Extensions

Possible future developments:

- Physics-informed machine learning
- Digital twin development
- Hybrid AI-process models
- Real-time engineering optimization


---

# Author

Palash Dey

Chemical Engineer & Researcher

Research Interests:

- AI-enabled process systems engineering
- Sustainable energy systems
- Data-driven engineering
- Risk and reliability analysis

