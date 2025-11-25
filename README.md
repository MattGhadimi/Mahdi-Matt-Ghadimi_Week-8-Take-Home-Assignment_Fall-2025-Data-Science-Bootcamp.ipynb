# Week 8 Take-Home Assignment – Fall 2025 Data Science Bootcamp

Hello!  

I'm **Mahdi (Matt) Ghadimi**  
N14369173 | mg8786@nyu.edu  

This repository contains my **Machine Learning Assignment** for **Week 8**, focusing on the **sigmoid function, logistic regression probability calculations, confusion matrix evaluation, and classification metrics**.

## Files

- `Mahdi-Matt-Ghadimi_Week-8-Take-Home-Assignment_Fall-2025-Data-Science-Bootcamp.ipynb`  
  Contains full solutions for the following exercises:

---

## Exercise 1 — Sigmoid Function Implementation

- Implemented the **sigmoid function** from scratch.  
- Generated values from **−10 to 10** and computed corresponding sigmoid outputs.  
- Created a **matplotlib plot** visualizing the S-shaped activation curve.  
- Tested the function on sample numerical inputs to verify correctness.

---

## Exercise 2 — Logistic Regression Probability Calculation

- Calculated the linear combination  
  \[
  z = w_1 x_1 + w_2 x_2 + b
  \]
  using given coefficients and feature values.  
- Applied the sigmoid function to compute  
  \[
  P(y = 1 \mid x)
  \]
- Used a **0.5 decision threshold** to convert probabilities into predicted classes.  
- Implemented a reusable function returning both **probability** and **prediction**.

---

## Exercise 3 — Confusion Matrix Implementation

- Computed the four core components of the confusion matrix from scratch:  
  - **TP** — True Positives  
  - **TN** — True Negatives  
  - **FP** — False Positives  
  - **FN** — False Negatives  
- Wrote a custom function looping through predictions and true labels.  
- Visualized the final confusion matrix with a **seaborn heatmap**.

---

## Exercise 4 — Classification Metrics Calculation

- Implemented key evaluation metrics directly using TP, TN, FP, FN:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
  - **F1-Score**  
- Handled potential division-by-zero cases safely.  
- Printed metrics with formatted output for cleaner interpretation.

---
