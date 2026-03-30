# Diabetes Onset Prediction — Pima Indians Dataset

## Overview
Predicting diabetes probability in Pima Indian women using Logistic 
Regression and Random Forest, with MICE imputation for missing data.
MSc Health Data Science · University of Galway · 2026

## Dataset
- Source: UCI Machine Learning Repository / NIDDK
- 768 observations × 8 predictors
- Outcome: Binary — Diabetic (35%) vs Non-diabetic (65%)

## Key Methods
- Missing data: MICE with PMM (Insulin: 48.7% missing)
- Models: Logistic Regression vs Random Forest (10-fold CV)
- Evaluation: AUC, Brier Score, Calibration Slope, DCA

## Results: run the analysis

Logistic Regression selected as final model — better performance 
and full interpretability via odds ratios.

## How to Run
1. Open `Preditictive analysis of PIMA data.Rmd` in RStudio
2. Install packages:
   install.packages(c("mice","VIM","caret","pROC",
                      "dcurves","randomForest","rsample"))
3. Knit to HTML

## R Libraries Used
mice · VIM · caret · pROC · dcurves · randomForest · rsamp
