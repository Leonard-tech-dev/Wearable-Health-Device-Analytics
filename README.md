# Wearable Health Device Analytics

## Predicting Customer Satisfaction Using Statistical Analysis and Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Project Overview

This project investigates the key factors influencing customer satisfaction with wearable health devices using statistical analysis and machine learning techniques.

The analysis evaluates how product characteristics such as device price, battery life, heart rate accuracy, GPS accuracy, health sensor capabilities, and overall performance influence user satisfaction.

The project demonstrates an end-to-end analytics workflow, including data preparation, exploratory data analysis (EDA), predictive modeling, clustering, statistical testing, and business recommendations.

---

## Business Problem

As wearable technology continues to grow rapidly, manufacturers introduce increasingly sophisticated devices at premium prices. However, higher prices do not necessarily translate into greater customer satisfaction.

This project answers the following questions:

- Does device price significantly influence customer satisfaction?
- Which product characteristics contribute most to customer satisfaction?
- Which machine learning model provides the most accurate predictions?
- Can wearable devices be grouped into meaningful customer segments?

---

## Dataset

The analysis uses a publicly available wearable health device dataset containing information such as:

- Device Price
- Battery Life
- Heart Rate Accuracy
- Step Count Accuracy
- Sleep Tracking Accuracy
- GPS Accuracy
- Health Sensor Count
- Performance Score
- User Satisfaction Rating

Source: Kaggle – Wearable Health Device Performance Dataset.

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Google Colab
- Jupyter Notebook

---

## Project Workflow

### Data Preparation

- Imported and explored the dataset
- Selected relevant variables
- Examined missing values
- Prepared features for modeling

### Exploratory Data Analysis

- Summary statistics
- Histograms
- Scatter plots
- Correlation analysis

### Machine Learning Models

- Multiple Linear Regression
- Decision Tree Regression
- K-Nearest Neighbors Regression
- K-Means Clustering

### Model Evaluation

Models were compared using:

- Root Mean Square Error (RMSE)
- R² Score
- Model Accuracy
- Statistical Significance Tests

---

## Key Findings

- Performance Score was the strongest predictor of customer satisfaction.
- Device price demonstrated a positive relationship with customer satisfaction.
- Multiple Linear Regression produced the lowest prediction error.
- Higher-priced devices generally delivered better performance, although improvements in satisfaction diminished at higher price levels.

---

## Repository Contents

```
Wearable-Health-Device-Analytics

│── Wearable_Health_Device_Analytics.ipynb
│── wearable_health_device_performance.csv
│── README.md
│── LICENSE
│── .gitignore
```

---

## Future Improvements

Future enhancements include:

- Random Forest Regression
- XGBoost
- Feature Importance Analysis
- Interactive Power BI Dashboard
- Streamlit Web Application
- Automated ETL Pipeline

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Machine Learning
- Regression Modeling
- Clustering
- Data Visualization
- Business Intelligence
- Predictive Analytics

---

## Author

**Leonard Amoako**

M.S. Applied Economics and Data Intelligence

University of Nevada, Las Vegas

---

## License

This project is licensed under the MIT License.
