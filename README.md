# Air Quality Analysis & AQI Prediction

This repository contains an end-to-end **Air Quality Index (AQI) analysis and prediction project** developed as part of **MSCI 623**. The project applies **machine learning techniques** to analyze air pollution data, predict AQI categories, and discover patterns in pollutant concentrations.

---

## Project Overview

Air pollution is a major global concern with serious health and environmental impacts. Monitoring and predicting air quality helps individuals, policymakers, and regulators make informed decisions.

This project focuses on:

* Predicting **AQI Buckets** (categorical AQI levels) instead of raw AQI values for better interpretability
* Identifying **key pollutants** that influence air quality
* Comparing **supervised ML models** based on performance
* Applying **unsupervised learning (K-Means)** to discover pollutant-based clusters
* Analyzing the **impact of COVID-19 lockdowns** on air pollution levels

---

## Machine Learning Techniques Used

### Supervised Learning

Used to predict **AQI_Bucket (categorical variable)**:

* Logistic Regression
* Decision Trees
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machines (SVM)

Models are evaluated and compared using **prediction accuracy** and other relevant metrics.

### Unsupervised Learning

* **K-Means Clustering** to group regions based on pollutant concentration patterns

---

## 📁 Repository Structure

```
├── notebooks/          # Jupyter notebooks for analysis & modeling
├── data/               # Dataset files (if applicable)
├── report/             # Final project report (PDF)
├── README.md           # Project documentation
```

---

## 📄 Project Report

A detailed explanation of methodology, experiments, results, and conclusions is available in the **project report (PDF)** included in this repository.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/anjalianadkat/air_quality_analysis.git
```

2. Open the notebooks in **Jupyter Notebook / VS Code**
3. Install required dependencies (if not already installed)
4. Run cells sequentially
