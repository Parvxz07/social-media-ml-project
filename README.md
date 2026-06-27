# Predicting Mental Health Impact from Social Media Usage Patterns

## Project Overview
This project uses supervised machine learning to predict whether a person is negatively affected mentally based on their social media usage habits. The dataset is a survey of 481 respondents covering social media behavior, emotional patterns, and mental health indicators.

## Dataset
- **Name:** Social Media & Mental Health
- **Source:** [Kaggle — souvikahmed071](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health)
- **Rows:** 481 | **Columns:** 20
- **File name:** `smmh.csv`

## Task Type
Classification — predicting whether a respondent shows signs of mental health impact (1 = affected, 0 = not affected)

## Research Questions
1. Does daily social media usage time correlate with higher mental health impact?
2. Which features are most important in predicting mental health impact?
3. Can we accurately classify users as mentally affected or not from survey responses?
4. How do age and gender influence social media's effect on mental health?
5. Does seeking validation online predict higher depression levels?
6. Are sleep issues strongly associated with mental health impact?
7. Which ML model performs best for this classification task?

## Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

## Evaluation Metrics
- Accuracy
- F1 Score
- Confusion Matrix
- Classification Report

## Figures Generated
| Figure | Description |
|---|---|
| fig1_target_distribution.png | Distribution of target variable |
| fig2_age_distribution.png | Age distribution of respondents |
| fig3_sleep_vs_impact.png | Sleep issues vs mental health impact |
| fig4_correlation_heatmap.png | Correlation heatmap of all features |
| fig5_validation_vs_depression.png | Seek validation vs depression scatter |
| fig6_model_comparison.png | Model accuracy and F1 score comparison |
| fig7_confusion_matrix.png | Confusion matrix for best model |
| fig8_feature_importance.png | Feature importance from Random Forest |

## How to Run

### Step 1 — Install required libraries
```
pip install -r requirements.txt
```

### Step 2 — Download the dataset
Download `smmh.csv` from [Kaggle](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health) and place it in the same folder as the notebook.

### Step 3 — Run the notebook
Open `notebook.ipynb` in Jupyter Notebook and run all cells from top to bottom.

## Requirements
See `requirements.txt`

## Results Summary
Random Forest achieved the best performance among all tested models. Key predictors of mental health impact include daily usage time, depression scores, sleep issues, and tendency to seek validation online.
