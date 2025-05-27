# Restaurant-Data-Analysis-and-Prediction

This project involves in-depth analysis of restaurant data, aiming to extract meaningful insights and build predictive models to support customer decisions and business strategy.

## 📊 Project Overview

The dataset contains details of restaurants including their locations, cuisines, prices, and customer ratings. This project explores the dataset to:

- Understand key patterns in the food industry
- Predict ratings based on restaurant features
- Classify restaurant cuisines
- Perform location-based analysis of restaurant distribution

## 🧠 Tasks and Methodologies

### 1. 📈 Rating Prediction (Regression)
- **Goal**: Predict restaurant ratings using features like price, cuisine, votes, etc.
- **Techniques Used**: Data preprocessing, encoding, feature selection, regression models (Linear Regression, Random Forest)
- **Evaluation**: Accuracy Score, MAE, RMSE

### 2. 🍽️ Cuisine Classification (Multiclass Classification)
- **Goal**: Classify restaurants based on their cuisine category
- **Challenges**: Imbalanced classes, high-cardinality labels
- **Techniques**: Label encoding, One-vs-Rest Classifier, Random Forest, Confusion Matrix

### 3. 🗺️ Location-based Analysis
- **Goal**: Visualize and analyze the geographical distribution of restaurants
- **Methods**: Grouping by city/locality, plotting using latitude & longitude, computing average ratings & prices
- **Tools**: Pandas, Folium/Plotly/Seaborn

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Plotly)
- Jupyter Notebook
- Git & GitHub

## 📌 Key Insights

- Certain localities are food hubs with high rating concentrations
- Cuisine classification is challenging due to overlapping styles and naming inconsistencies
- Rating prediction models perform moderately well when cleaned and balanced data is used
