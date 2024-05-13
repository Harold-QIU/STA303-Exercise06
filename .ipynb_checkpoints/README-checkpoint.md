
# Exercise: Data-Centric AI

## Overview

This series of exercises explores the distinctions between data-centric and model-centric approaches in machine learning and demonstrates the application of data-centric AI techniques to improve model performance by addressing label errors.

## Exercise 6.1: Data-Centric vs Model-Centric Approaches

### Description

In this exercise, we introduce the foundational concepts of data-centric and model-centric strategies in machine learning. We focus on building a classifier for product reviews, specifically in the magazine category, to illustrate how refining data can lead to better model performance compared to extensive model tuning alone.

### Example Reviews

- **Good Review:** "Excellent! I look forward to every issue. I had no idea just how much I didn't know. The letters from the subscribers are educational, too." 
  - Label: ⭐️⭐️⭐️⭐️⭐️
  
- **Bad Review:** "My son waited and waited, it took the 6 weeks to get delivered that they said it would but when it got here he was so disappointed, it only took him a few minutes to read it."
  - Label: ⭐️

### Objectives

1. **Model Tuning:** Begin by trying to maximize the classifier's performance using various models and hyperparameters.
2. **Data Analysis:** Analyze the dataset to identify and understand inherent issues.
3. **Data Improvement:** Implement simple strategies to enhance data quality.
4. **Performance Comparison:** Observe the impact of data improvements on model effectiveness.

## Exercise 6.2: Label Errors and Confident Learning

### Description

This exercise highlights the use of data-centric AI techniques, specifically confident learning, to detect and correct label errors in a dataset used to train an XGBoost classifier. This approach focuses on refining the dataset to improve model accuracy.

### Objectives

1. **Establish Baseline Accuracy:** Use an XGBoost model to determine initial performance on the noisy dataset.
2. **Identify Mislabeled Data:** Utilize confident learning to find and rank potential label errors.
3. **Data Correction:** Remove problematic data points based on the analysis.
4. **Model Retraining:** Observe the improvement in test accuracy after retraining the XGBoost model on the corrected dataset.

## Getting Started

**Run the exercise:** Follow the lab instructions, starting with exercise 6.1 on data-centric vs model-centric approaches and then proceeding to exercise 6.2 on label error correction using confident learning.
