# 🚀 SpaceX Launch Data Analysis - IBM Data Science Capstone Project

## 📌 Overview

This repository contains my final capstone project completed as part of the **IBM Data Science Professional Certificate**.

The project is a comprehensive analysis of historical SpaceX Falcon 9 launch records. It focuses on identifying key factors that influence launch success, developing interactive data visualizations, and building predictive machine learning models to estimate mission success probability.

## 🎯 Project Objectives

| Phase | Goal |
| :--- | :--- |
| **Data Acquisition** | Perform data collection from SpaceX APIs and supplementary web scraping. |
| **Data Prep** | Conduct thorough data wrangling, cleaning, and preprocessing. |
| **Exploratory Analysis (EDA)** | Perform EDA using data visualization (Matplotlib, Seaborn, Plotly) and advanced SQL queries. |
| **Visualization** | Build interactive geographic maps with **Folium** and a full analytical dashboard with **Plotly Dash**. |
| **Predictive Modeling** | Develop and evaluate machine learning models (Logistic Regression, SVM, Decision Trees, KNN) to classify mission success. |
| **Insights** | Deliver actionable insights and conclusions on critical factors affecting launch success. |

## 🛠️ Methodology

### 1. Data Collection & Wrangling

* Collected raw SpaceX launch data using **REST APIs** and augmented it via **web scraping** with `BeautifulSoup` and `Requests`.
* Cleaned the dataset, handled missing values, and engineered the target variable (`class`: 1 for success, 0 for failure).

### 2. Exploratory Data Analysis (EDA)

* Utilized **SQL** for complex data aggregation and retrieval (e.g., finding maximum payload, success counts by booster).
* Visualized launch success patterns based on `Launch Site`, `Payload Mass`, and `Orbit Type`.

### 3. Interactive Visualization

* **Folium Maps:** Created interactive maps to geographically visualize launch sites and their success/failure outcomes using color-coded markers.
* **Plotly Dash Dashboard:** Developed a dynamic dashboard allowing users to filter success rates by launch site and analyze payload correlations interactively.

### 4. Predictive Analysis

* Trained and evaluated four classification models: **Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN).**
* Optimized model performance using **`GridSearchCV`** for hyperparameter tuning.
* Evaluated models based on validation accuracy on a test set.

## 📊 Results & Key Insights

* **Launch Sites:** The launch site **KSC LC-39A** demonstrated the highest overall success rate in the historical data.
* **Payload Influence:** Analysis showed that specific **heavier payload masses** had a measurable influence on launch success probability.
* **Modeling:** The **Support Vector Machine (SVM) with an RBF kernel** achieved the highest accuracy score, proving to be the best model for predicting mission success.
* **Data Accessibility:** Interactive dashboards significantly enhance the accessibility and dynamic analysis of launch correlations.

## 📈 Tools & Technologies

| Category | Tools & Libraries |
| :--- | :--- |
| **Core** | Python (Pandas, NumPy, Scikit-learn) |
| **Visualization** | Plotly, Matplotlib, Seaborn, Folium, Plotly Dash |
| **Data Acquisition** | Requests, BeautifulSoup (Web scraping) |
| **Database** | SQL (SQLite, SQL magic) |
| **Environment** | Jupyter Notebook / JupyterLab / Cloud IDE |

## 📑 Deliverables

* ✔ Final Project Report / Executive Summary
* ✔ Data Wrangling and Preprocessing Notebook
* ✔ Comprehensive EDA (Visualization & SQL Queries) Notebook
* ✔ Interactive Folium Map Notebook
* ✔ Plotly Dash Dashboard Application Code
* ✔ Predictive Modeling and Evaluation Notebook
* ✔ Project Presentation Slides
