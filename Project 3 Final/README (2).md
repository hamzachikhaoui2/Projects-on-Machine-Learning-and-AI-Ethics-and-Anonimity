
# ECSE 557 Assignment 3
# Hamza Chikhaoui 260912960

## Installation

To run this code, you need to install the required libraries. You can use the following commands for installation:

```bash
pip install 'aif360[all]'
pip install tabulate
pip install pandas==2.2.1
pip install seaborn==0.13.1
pip install matplotlib==3.7.1
pip install torch==2.1.0+cu121
pip install scikit-learn
```

## Description

The main sections  of this code are:

1. **Imports and Setup:** Installing necessary libraries and importing required modules. **IMPORTANT : In the last line of this section, you will be able to change the directory to the dataset submitted alongside this report**

2. **Part 1: Fairness Concerns:**
   - Visualizing the number of samples per gender and the distribution of heart disease across genders.
   - Visualizing the number of samples per race and the distribution of heart disease across races.

3. **Part 2: Fairness Metrics - Preprocessing:**
   - Creating a logistic regression model, fitting it, and visualizing the confusion matrix.

4. **Part 3: Assess Fairness Using Fairness Metrics:**
   - Computing fairness metrics on the original model predictions.

5. **Part 4: Pre-processing for Fairness (Reweighting):**
   - Applying reweighing techniques to address fairness concerns.
   - Evaluating fairness metrics on the reweighted predictions and comparing them with the original model metrics.

