# Teaching Effectiveness Evaluation using Machine Learning

## Overview

This project applies **machine learning, sentiment analysis, and time series analysis** to student Performance Evaluation System (PES) data in order to support a more **objective and data-driven assessment of teaching effectiveness**. Both numerical ratings and unstructured student feedback are analyzed to extract meaningful indicators that can aid academic decision-making.

The analytical workflow is implemented in Python, while the final results are presented through an **interactive Power BI dashboard**.

---

## Problem Statement

Although PES evaluations are widely used, institutions often lack a systematic and objective way to interpret numerical ratings alongside unstructured student comments. This project addresses the challenge of transforming raw PES data into **interpretable insights and performance indicators** that reflect teaching effectiveness.

---

## Objectives

* Preprocess and analyze numerical student evaluation ratings
* Perform sentiment analysis on written student feedback
* Apply supervised machine learning techniques to evaluate performance patterns
* Analyze temporal trends in evaluation data using time series methods
* Extract key performance indicators (KPIs) related to teaching effectiveness
* Present results in an interpretable form through visualizations and dashboards

---

## Dataset

The dataset consists of:

* **Numerical PES ratings** (quantitative evaluation scores)
* **Textual student comments** (unstructured feedback)
* **Time-based records** for trend analysis

> ⚠️ The complete dataset is not included in this repository due to privacy and confidentiality constraints. A sample or anonymized dataset may be provided for demonstration purposes.

---

## Methodology

### 1. Data Preprocessing

* Data cleaning and handling of missing values
* Feature preparation for numerical and textual data
* Text normalization and preprocessing for sentiment analysis

### 2. Sentiment Analysis

* Sentiment extraction from student comments using:

  * NLTK Sentiment Intensity Analyzer
  * Transformer-based sentiment models
* Conversion of qualitative feedback into quantitative sentiment indicators

### 3. Supervised Machine Learning

* Application of supervised classification techniques
* Train-test data splitting
* Model evaluation using:

  * Confusion Matrix
  * Classification Report

### 4. Time Series Analysis

* Stationarity testing using Augmented Dickey-Fuller (ADF)
* Autocorrelation and partial autocorrelation analysis (ACF/PACF)
* Time series modeling using:

  * ARIMA / SARIMAX
  * Auto ARIMA for parameter selection

### 5. Evaluation Metrics

* Accuracy and classification performance metrics
* Error metrics for time series forecasting:

  * Mean Squared Error (MSE)
  * Mean Absolute Percentage Error (MAPE)

---

## Key Outputs

* Identified **patterns and indicators** influencing teaching effectiveness
* Quantified sentiment trends from student feedback
* Temporal insights into evaluation performance over time
* Structured KPIs to support academic and instructional decision-making

---

## Dashboard (Power BI)

The final insights are visualized using **Power BI**, providing:

* Teaching effectiveness KPIs
* Sentiment distribution and trends
* Performance comparisons and time-based patterns

> Due to file size and data privacy considerations, the Power BI (.pbix) file is not included. Screenshots of the dashboard are provided in the `powerbi/` directory for reference.

---

## Repository Structure

```
├── notebooks/
│   └── pes_teaching_effectiveness_analysis.ipynb
├── data/
│   └── README.md
├── powerbi/
│   └── dashboard_screenshots/
├── outputs/
│   └── figures/
└── README.md
```

---

## Tools & Technologies

* Python
* Scikit-learn
* NLTK
* Transformers (Hugging Face)
* Statsmodels
* pmdarima
* Power BI

---

## Notes

This project emphasizes **interpretability and decision support**, bridging machine learning outputs with practical academic evaluation needs. It demonstrates an end-to-end workflow from data preprocessing to insight visualization.

---

## Author

Leslie
