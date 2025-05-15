# 🌦️ Weather Data Analytics Project

This project explores historical weather data to uncover meaningful insights and predict temperature trends using machine learning. It is divided into structured phases that reflect a real-world data science workflow — from data preprocessing to model evaluation.

---

## 📁 Dataset Overview

The dataset consists of hourly weather recordings with features such as:
- Date/Time
- Temperature (°C)
- Dew Point
- Humidity
- Wind Speed
- Visibility
- Pressure
- Weather descriptions

---

## 🔍 Phase 1: Data Understanding & Cleaning

### Objective:
This phase focuses on importing and cleaning the raw dataset. The main goals are:
- Loading the dataset using Pandas
- Converting the `Date/Time` column to a datetime object
- Extracting useful temporal features such as Year, Month, Day, Hour, and Weekday
- Checking for and handling any missing or inconsistent values

Outcome: A clean and structured dataset ready for exploration.

---

## 📊 Phase 2: Exploratory Data Analysis (EDA)

### Objective:
EDA aims to explore the data visually and statistically to identify patterns, trends, and anomalies. In this phase:
- Various graphs and plots were created (line plots, scatter plots, count plots)
- Temperature and humidity trends were analyzed over different months
- The distribution of weather conditions was visualized

Outcome: Insights into seasonal patterns, humidity-temperature relationships, and frequency of weather conditions.

---

## 🏗️ Phase 3: Feature Engineering

### Objective:
This phase enhances the dataset by adding or transforming variables to improve predictive modeling:
- Weather descriptions were grouped into broader categories like "Clear", "Cloudy", "Snow/Rain"
- Seasonal flags (Winter, Summer, Spring) were added based on months
- Categorical features were encoded using one-hot encoding

Outcome: A refined dataset with meaningful features ready for modeling.

---

## 🤖 Phase 4: Machine Learning - Temperature Prediction

### Objective:
To predict the temperature using relevant weather features. This phase includes:
- Splitting the dataset into training and testing sets
- Training a Linear Regression model on selected numerical features
- Evaluating model performance using R² Score and Mean Squared Error (MSE)

Outcome: A working temperature prediction model with reasonable accuracy.

---

## 📈 Phase 5: Visualization & Conclusion Dashboard

### Objective:
To summarize and visualize key insights and model performance:
- Compared actual vs predicted temperatures
- Created seasonal and hourly trend plots
- Plotted temperature variation by weather condition
- Displayed model accuracy metrics in visual format

Outcome: A compelling dashboard that visually communicates the entire project’s findings and model efficiency.

---

## ✅ Project Highlights

- Extracted 5+ new features to enrich the dataset
- Handled textual weather data by creating simplified labels
- Built a regression model to predict temperature with good performance
- Created multiple charts to support data-driven conclusions

---

## 📌 Conclusion

This project demonstrates how weather data can be processed, visualized, and modeled using Python. It walks through all the essential stages of a data science pipeline and offers a strong foundation for further improvements such as:
- Trying advanced ML models (Random Forest, XGBoost)
- Hyperparameter tuning
- Deploying the model as a web application

---

## 💡 Tools & Libraries Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine Learning
- **Jupyter Notebook** – Interactive analysis

---

## 📬 Author

**Murchana Bharali**  
Computer Science Student @ Kaziranga University  
Passionate about Data Science, Machine Learning, and Web Development.

---

> *This project was completed as part of a learning and research exercise to understand practical machine learning and data visualization using real-world datasets.*
