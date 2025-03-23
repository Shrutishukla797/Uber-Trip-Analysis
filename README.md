# Uber Trip Demand Analysis and Forecasting (2014)

<hr>

### Introduction
This project analyzes Uber trip data from 2014 to explore patterns in ride demand and develop predictive models. By leveraging time series decomposition and machine learning algorithms, the project aims to forecast Uber trip counts and extract actionable insights.

### Objective
* Perform in-depth data exploration and visualization of Uber trip data.

* Engineer lagged features to capture temporal patterns.

* Train and evaluate XGBoost, Random Forest, and GBRT models.

* Develop an ensemble model to combine the strengths of individual models.

* Compare models using MAPE (Mean Absolute Percentage Error) as the key evaluation metric.

* Visualize model predictions versus actual trip counts to assess performance.

### Technologies Used
* python (Jupyter Notebook)

* Pandas

* NumPy

* Matplotlib & Seaborn

* Scikit-learn

* XGBoost


### DataSet:
The dataset used for this project is available in the file named " CSV Files". You can view or download the dataset from there.

### Results Summary

* XGBoost achieved the lowest MAPE of 7.67%, performing best on the test set.

* Random Forest and GBRT followed closely with MAPE scores of 8.02% and 8.69% respectively.

* The Ensemble model further improved stability with a combined MAPE of 7.76%.

### Visual Insights
The project visualizes how each model tracks real-world Uber demand, highlighting seasonal trends, peak hours, and weekday vs weekend variations.

### Conclusion
This project demonstrates the effectiveness of combining machine learning with time series analysis for forecasting Uber demand. The XGBoost model proved to be the most accurate, while the ensemble model provided robust and stable predictions. The approach and insights derived can help optimize ride-sharing services through improved demand forecasting.

### Application of this Project:
We use machine learning algorithms to predict the price of Uber, so that it is easy for the company to do analysis on price based on certain features.
