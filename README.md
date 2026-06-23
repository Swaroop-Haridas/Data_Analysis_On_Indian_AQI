# Data Analysis on Indian Air Quality Index (AQI)

## Overview

This project focuses on analyzing and predicting Air Quality Index (AQI) levels across different regions in India using data analysis and machine learning techniques. The study includes data preprocessing, exploratory data analysis (EDA), visualization of pollutant levels, AQI categorization, and predictive modeling.

The objective is to gain insights into air pollution trends and build models capable of predicting AQI categories based on environmental pollutant measurements.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* AQI Calculation and Categorization
* Visualization of Air Pollution Trends
* State-wise Pollutant Analysis
* Machine Learning-Based AQI Prediction
* Classification of Air Quality Categories
* Performance Evaluation of Multiple Models

---

## Dataset

The dataset contains air quality measurements collected from various locations in India.

### Attributes

* SO₂ (Sulphur Dioxide)
* NO₂ (Nitrogen Dioxide)
* RSPM (Respirable Suspended Particulate Matter)
* SPM (Suspended Particulate Matter)
* State Information
* AQI Category

Dataset file:

```text
AQI.xlsx
```

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Collection

Load and inspect the air quality dataset.

### 2. Data Preprocessing

* Handle missing values
* Remove inconsistencies
* Prepare data for analysis

### 3. Exploratory Data Analysis

* Pollutant distribution analysis
* State-wise pollutant comparison
* AQI trend visualization

### 4. Feature Engineering

* Selection of relevant pollutant indicators
* AQI categorization

### 5. Model Training

Machine learning algorithms are used to predict AQI categories based on pollutant concentrations.

### 6. Model Evaluation

Evaluate performance using classification metrics and accuracy scores.

---

## Visualizations

The notebook includes various visualizations such as:

* State-wise SO₂ Levels
* State-wise NO₂ Levels
* AQI Category Distribution
* Pollutant Comparisons
* Correlation Analysis

---

## Results

The analysis identifies major pollution patterns and demonstrates how machine learning can be used to classify air quality levels based on environmental parameters.

Key outcomes include:

* Identification of pollutant trends across states
* AQI category prediction
* Comparative evaluation of classification models

---

## Repository Structure

```text
Data_Analysis_On_Indian_AQI/
│
├── AQI.xlsx
├── IndianAQIanalysis.ipynb
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Swaroop-Haridas/Data_Analysis_On_Indian_AQI.git
```

Navigate to the project directory:

```bash
cd Data_Analysis_On_Indian_AQI
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
IndianAQIanalysis.ipynb
```
---

