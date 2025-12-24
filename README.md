# Music Artist Collaboration Prediction  
**COGS 108 – Data Science in Practice | Final Project (Group 165)**

## Overview
Music collaborations have become increasingly common across genres and platforms, but what actually predicts whether two artists will collaborate?

This project investigates **which factors best predict artist collaborations**, focusing on:
- Artist background
- Fame and popularity
- Musical characteristics

Using a combination of music metadata and collaboration data, we frame this as a **binary classification problem** and evaluate multiple machine learning models to determine which features are the strongest predictors.

---

## Research Question
**What factor is the strongest predictor of whether or not a song features a collaboration between artists — the artist’s background, fame, or the music they create?**

---

## Data
We combined multiple datasets related to music artists and songs, including:
- Artist popularity and fame metrics
- Song-level audio features
- Collaboration indicators

All datasets were cleaned, merged, and processed to create a unified modeling dataset suitable for supervised learning.

> This repository remains private for course purposes. Data sources and preprocessing steps are fully documented in the project notebooks.

---

## Methodology
The project followed a standard data science workflow:

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Feature selection and normalization
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis of artist popularity
   - Feature correlations
   - Comparison of collaborative vs. non-collaborative songs

3. **Modeling**
   We evaluated several classification models, including:
   - Logistic Regression
   - Decision Trees
   - Random Forests

4. **Evaluation**
   - Accuracy
   - Precision & recall
   - Model comparison across feature groups

---

## Results
- Models achieved **moderate predictive performance**, with accuracy scores in the **50–60% range**
- **Artist fame and popularity metrics** were the most informative predictors of collaboration
- Musical/audio features alone were less predictive than expected
- Results suggest collaborations are driven more by **social and popularity factors** than purely musical similarity

---

## Key Takeaways
- Popularity plays a significant role in predicting collaborations
- Audio features are useful but insufficient on their own
- Collaboration prediction is a challenging task with inherent uncertainty

---


---

## Contributions
This project was completed collaboratively for COGS 108.

**Matthew Paoletta** contributed to:
- Data preprocessing and feature engineering
- Exploratory data analysis (EDA)
- Model development and evaluation
- Interpretation of results
- Writing and editing analysis notebooks

---

## Portfolio & Sharing
After course completion, this project may be forked and shared publicly for portfolio use.  
Please ensure all contributors are credited appropriately.

---

## Acknowledgments
Completed as part of **COGS 108: Data Science in Practice**.
