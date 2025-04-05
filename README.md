# 🌍 Air Quality Prediction

This project aims to predict the **Air Quality Index (AQI)** using machine learning models, based on environmental factors like temperature, humidity, wind speed, and particulate matter. The goal is to forecast pollution levels to help understand and mitigate air quality impacts on public health.

## 🔍 Problem Statement
Air pollution poses significant health risks, especially in urban areas. By predicting AQI, we can help governments and organizations take proactive measures to protect public health. This project uses historical air quality data and environmental factors to predict future AQI trends.

## 🧪 Features
- **Historical Air Quality Data**: PM2.5, PM10, CO, NO2, and AQI measurements
- **Weather Data**: Temperature, humidity, wind speed, and weather conditions
- **Prediction Models**: Machine learning models such as Random Forest and Linear Regression

## 📊 Dataset
The dataset includes the following columns:
- **date**: Date of the measurement
- **temp**: Temperature (°C)
- **humidity**: Humidity percentage
- **windspeed**: Wind speed (m/s)
- **pm2.5**: PM2.5 concentration
- **pm10**: PM10 concentration
- **co**: Carbon monoxide concentration
- **no2**: Nitrogen dioxide concentration
- **aqi**: Air Quality Index (target variable)

The dataset can be downloaded from the Zindi platform.

## 🎯 Objective
- Preprocess the data and handle missing values
- Build machine learning models to predict AQI
- Evaluate model performance using metrics like RMSE, MAE, and R-squared

## 🧠 Insights and Findings
After training the model with various machine learning algorithms, I found that the **Random Forest model** gave the best performance. The **Root Mean Squared Error (RMSE)** for the model was **38.25**, which indicates that the model's predictions are reasonably close to the actual AQI values. 

While this is a decent score, there’s room for improvement, especially in refining the feature engineering process and considering more complex models or additional external factors like time of year or location-specific trends that could impact AQI.

## 🛠️ Technologies Used
- **Python**: Core programming language
- **pandas**: Data manipulation and cleaning
- **numpy**: Numerical operations
- **scikit-learn**: Machine learning models and evaluation
- **matplotlib & seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development

---

## 👩🏾‍💻 About Me
**Ingrid Nyakerario**  
📎 [LinkedIn](https://www.linkedin.com/in/ingrid-ong-uti-43a93361/)
