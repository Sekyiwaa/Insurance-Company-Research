# Classification and Prediction of Heart Diseases Using Machine Learning Algorithms

**Author:** Akua Sekyiwaa Osei-Nkwantabisa

**Institution:** University of Ghana

**Degree:** Bachelor of Arts in Mathematics and Statistics

**Submission Date:** October 2022

## Table of Contents

1. [Declaration](#declaration)
2. [Acknowledgement](#acknowledgement)
3. [Dedication](#dedication)
4. [Abstract](#abstract)
5. [Introduction](#introduction)
    1. [Background Study](#background-study)
    2. [Problem Statement](#problem-statement)
    3. [Objectives](#objectives)
        1. [Main Objectives](#main-objectives)
        2. [Specific Objectives](#specific-objectives)
    4. [Methodology](#methodology)
        1. [Source of Data](#source-of-data)
        2. [Description of Data](#description-of-data)
        3. [Analytic Technique and Tools](#analytic-technique-and-tools)
    5. [Significance of Study](#significance-of-study)
    6. [Organisation of Study](#organisation-of-study)
6. [Literature Review](#literature-review)
7. [Methodology](#methodology)
    1. [Source of Data/Data Acquisition](#source-of-datadata-acquisition)
    2. [Machine Learning Techniques](#machine-learning-techniques)
        1. [K-Nearest Neighbor](#k-nearest-neighbor)
        2. [Logistic Regression](#logistic-regression)
        3. [Support Vector Machine](#support-vector-machine)
        4. [Artificial Neural Networks](#artificial-neural-networks)
    3. [Analytic Tools](#analytic-tools)
8. [Results from Data Analysis and Interpretation](#results-from-data-analysis-and-interpretation)
9. [Summary, Conclusions, Limitations, and Recommendations](#summary-conclusions-limitations-and-recommendations)
10. [References](#references)

## Declaration

With the exception of citations made by writers whose work has been properly acknowledged, I declare that this project is the outcome of my own research, conducted under the direction of Dr. Louis Asiedu of the Department of Statistics and Actuarial Science, University of Ghana, Legon.

**Akua Sekyiwaa Osei-Nkwantabisa** (Student)  
**Dr. Louis Asiedu** (Supervisor)

## Acknowledgement

I would like to express my gratitude to the Almighty God for providing me with the skills and strength required to complete my assignment. Additionally, I want to thank Dr. Louis Asiedu for his guidance and assistance. I am grateful for the encouragement and assistance provided by my family, friends, and colleagues, particularly Ms. Ama Konadu Appau, Mr. Andrews Kwasi Boahen, and Mr. Redeemer Ntumy.

## Dedication

I dedicate this study to my supervisor, Dr. Louis Asiedu, and to the Department of Statistics and Actuarial Science for their guidance and support throughout the research process.

## Abstract

Heart disease is a serious worldwide health issue because it claims the lives of many people who might have been treated if the disease had been identified sooner. The leading cause of death in the world is cardiovascular disease, usually referred to as heart disease. Creating reliable, effective, and precise predictions for these diseases is one of the biggest issues facing the medical world today. This study examined various machine learning approaches to determine the most effective algorithm for predicting heart disease using the UCI heart disease dataset. The K-Nearest Neighbor technique was found to be the most effective. Further research on additional machine learning algorithms for heart disease prediction is recommended.

**Keywords:** Machine Learning, Logistic Regression, Heart Disease, Cardiovascular Disease, K-Nearest Neighbor, Support Vector Machine, Artificial Neural Networks.

## Introduction

### Background Study

Cardiovascular diseases (CVDs) and cardiac disorders affect the heart and blood vessels. These conditions include deep vein thrombosis, coronary heart disease, peripheral arterial disease, and rheumatic heart disease. The World Health Organization estimates that CVDs account for 17.9 million deaths annually, making them the leading cause of death worldwide. Early detection of cardiovascular diseases is essential for taking preventative actions and avoiding the damage they can cause.

### Problem Statement

The biggest issue facing the medical industry today is making accurate and dependable predictions for disease diagnosis and treatment. The goal of this project is to design and implement a system for heart disease detection and prediction using machine learning techniques.

### Objectives

#### Main Objectives

Finding the best classifier for predicting and diagnosing cardiac issues is the major goal of this study.

#### Specific Objectives

- Determine the most effective classification system for cardiac ailments.
- Identify the key criteria for categorizing heart disorders.

### Methodology

#### Source of Data

The data set used in this study was obtained from Kaggle, combining various heart disease datasets. The data set consists of 1190 records with 11 attributes and 1 target variable.

#### Description of Data

| Feature                | Description                                | Data Type |
|------------------------|--------------------------------------------|-----------|
| Age                    | Patients’ years of age                     | Numeric   |
| Sex                    | Gender of Patient (Male - 1, Female - 0)   | Nominal   |
| Chest pain type        | Chest pain type                            | Nominal   |
| Resting BP             | Level of blood pressure at resting mode    | Numeric   |
| Cholesterol            | Serum cholesterol in mg/dl                 | Numeric   |
| Fasting blood sugar    | Fasting blood sugar (0 = < 120 mg/dl, 1 = > 120 mg/dl) | Nominal   |
| Resting ECG            | Resting electrographic result              | Nominal   |
| Max Heart rate         | Maximum heart rate achieved                | Numeric   |
| Exercise angina        | Exercise induced angina (0 = No, 1 = Yes)  | Nominal   |
| Old peak               | Exercise induced ST-depression             | Numeric   |
| ST slope               | Slope of the peak exercise ST segment      | Nominal   |
| Target                 | Heart risk (0 = No, 1 = Yes)               | Nominal   |

#### Analytic Technique and Tools

The study utilized Python for data analysis and classification using various machine learning algorithms including Logistic Regression, Support Vector Machine, K-Nearest Neighbor, and Artificial Neural Networks.

### Significance of Study

The heart disease prediction system is beneficial globally because it helps lower the high global death rate, opens the door to early heart disease diagnosis, reduces the burden on healthcare facilities, and reduces the cost of money spent each year on heart-related diseases.

### Organisation of Study

This project effort consists of five chapters. The first chapter provides an introduction to the topic. Chapter two reviews related research papers. Chapter three details the machine learning methods and data analysis tools used. Chapter four presents the key conclusions and discussions. Chapter five summarizes the project, covers its weaknesses, and offers suggestions for potential improvements.

## Literature Review

### Introduction

Machine learning is a technique for automatically identifying patterns in data. There are three main categories: supervised, unsupervised, and reinforcement learning. It is essential to identify and anticipate heart disorders early because doing so can lower mortality rates and overall consequences.

### Related Works

Various studies on heart disease prediction using machine learning and data mining techniques have been conducted. This section reviews those related works and their findings.

## Methodology

### Source of Data/Data Acquisition

The data for this model was sourced from the UCI Machine Learning Repository. The Heart Disease Data Set employed is a popular resource consisting of datasets from different institutions, combined for analysis.

### Machine Learning Techniques

#### K-Nearest Neighbor

The K-Nearest Neighbor (K-NN) algorithm is a supervised machine learning method used for classification and regression problems. It works by finding the most similar data points (neighbors) and classifying new data based on their characteristics.

#### Logistic Regression

Logistic Regression is used to predict a categorical dependent variable from a set of independent variables. It provides probabilistic values between 0 and 1.

#### Support Vector Machine

Support Vector Machine (SVM) is used for classification and regression by finding a hyperplane that can effectively divide an n-dimensional space into different classes.

#### Artificial Neural Networks

Artificial Neural Networks (ANNs) are modeled after biological neural networks and consist of interconnected units that mimic neuron behavior.

### Analytic Tools

The project utilized Python (version 3.9) and various libraries including Matplotlib, Numpy, Pandas, Scikit-learn, and Tensorflow for data analysis.

## Results from Data Analysis and Interpretation

This section presents the findings from the data analysis and the performance of different machine learning algorithms used in the study.

## Summary, Conclusions, Limitations, and Recommendations

### Summary

The study aimed to find the best classifier for predicting and diagnosing heart issues using machine learning algorithms.

### Conclusions

The K-Nearest Neighbor algorithm was found to be the most effective for predicting heart disease.

### Recommendations

Further research on additional machine learning algorithms for heart disease prediction is recommended.

### Limitations

The study's limitations and potential improvements are discussed in this section.

## References

A list of all references used in the study.
