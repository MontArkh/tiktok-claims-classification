# TikTok Claims Classification

Machine Learning project developed as part of the **Google Advanced Data Analytics Professional Certificate**.

## Overview

Social media platforms process an enormous volume of user-generated content every day, making manual moderation increasingly challenging.

This project develops and evaluates machine learning models capable of distinguishing videos that contain factual claims requiring verification from those expressing opinions or other types of content. The objective is to support content moderation by prioritizing videos that may require human review.

The project follows the **PACE (Plan, Analyze, Construct, Execute)** framework proposed throughout the Google Advanced Data Analytics Professional Certificate.

---

## Project Structure

```
.
├── data/
├── images/
├── notebooks/
│   └── tiktok_claims_classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Dataset

The dataset contains metadata and textual information extracted from TikTok videos, including variables describing user engagement, account characteristics, and video content.

These features are used to build supervised machine learning models capable of classifying whether a video contains a claim requiring verification.

---

## Project Workflow

- Business Understanding
- Data Preparation
- Exploratory Data Analysis (EDA)
- Model Development
- Model Evaluation
- Business Insights

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Models Evaluated

- Random Forest

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

Given the moderation context, special attention is given to **Recall**, as failing to identify videos containing potentially misleading claims may have greater consequences than reviewing additional non-claim videos.

---

## Author

Victor Montandon
