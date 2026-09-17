# Mobile Price Prediction

A machine learning project that predicts **mobile phone price ranges** using hardware specifications such as RAM, battery power, and pixel height.
---

## Project Overview
This project classifies smartphones into **four price categories (0–3)** based on their specifications.
Two classification algorithms were evaluated:
- Logistic Regression
- Support Vector Machine (SVM)

Both achieved similar performance, with **Logistic Regression** selected as the final model.

## Dataset
- Source: Kaggle Mobile Price Classification
- Classes: 0, 1, 2, 3
- Balanced dataset with 500 samples in each class.

## Features
The most influential features include:
- RAM
- Battery Power
- Pixel Height
- 
## Methodology
1. Exploratory Data Analysis
2. Data Cleaning
3. Feature Engineering
4. Train/Test Split (75% / 25%)
5. Standard Scaling
6. Model Training
7. Model Evaluation

## Results
| Model | Macro F1 Score |
|-------|---------------:|
| Logistic Regression | **89%** |
| SVM | 89% |

Final selected model: **Logistic Regression**
