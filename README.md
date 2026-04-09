Global CO2 Emissions Analysis and Prediction

Overview

In this project, I analyzed global CO2 emissions trends over time and built a machine learning model to predict future emissions. The goal was to understand how emissions have evolved and demonstrate how simple regression models can be used for forecasting.

---

Dataset

The dataset contains global CO2 emissions data across multiple countries and years. It includes:

- Country
- Year
- CO2 emissions

For this project, I focused on analyzing emissions trends from the year 2000 onwards and aggregated the data at a global level.

---

Problem

This is a regression problem where the objective is to predict future CO2 emissions based on historical trends.

---

What I did

Data preprocessing

- Selected relevant columns (country, year, CO2 emissions)
- Removed missing values
- Filtered data from the year 2000 onwards

---

Exploratory Data Analysis

- Aggregated emissions data by year
- Analyzed overall global emission trends

---

Visualization

- Plotted global CO2 emissions over time
- Identified increasing trends in emissions

---

Model

I used a Linear Regression model to learn the relationship between year and total CO2 emissions.

Why Linear Regression?

- Simple and interpretable
- Suitable for identifying overall trends
- Good baseline model for forecasting

---

Training and Evaluation

- Split the data into training and testing sets
- Trained the model on historical data
- Evaluated performance using Mean Squared Error (MSE)

---

Results

The model was able to capture the general trend of increasing emissions and provide reasonable predictions for future years.

---

📊 Visualizations

Global Emissions Trend

"Trend" (trend_plot.png)

Prediction vs Actual

"Prediction" (prediction_plot.png)

---

Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

Why this project matters

Understanding CO2 emissions trends is critical for environmental monitoring and policy-making. This project demonstrates how data analysis and machine learning can be applied to study global environmental challenges.

---

Future Improvements

- Use more advanced models (Random Forest, LSTM)
- Include additional variables (population, energy usage)
- Perform country-level analysis
- Improve forecasting accuracy

---
About me

Dr Divya Pragna MULLA
I am building practical skills in data science and machine learning by working with real-world datasets, focusing on environmental and analytical applications.
About me

I am building practical skills in data science and machine learning by working on real-world datasets, with a focus on environmental and analytical applications.
