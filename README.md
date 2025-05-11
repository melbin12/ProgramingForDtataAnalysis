# 🌫️ PM2.5 Air Quality Prediction App

This is an interactive Streamlit web application that allows users to explore Beijing's air quality data (2013–2017), perform detailed Exploratory Data Analysis (EDA), and predict PM2.5 pollutant levels using a machine learning model.

---

## 🚀 Features

### 📄 Overview Page
- Displays a snapshot of the dataset.
- Shows the shape of the data.
- Highlights missing values with a bar chart.

### 📊 EDA (Exploratory Data Analysis)
- PM2.5 distribution with histogram and KDE.
- Correlation heatmap between pollutants and weather features.
- Monthly trend of PM2.5.
- Dynamic pollutant trend visualizations.
- Boxplot for outlier detection.

### 📈 Prediction Page
- Use sliders to simulate environmental conditions.
- Predict PM2.5 levels using a trained Random Forest Regressor.
- Features include PM10, SO2, NO2, CO, O3, temperature, pressure, dew point, and wind speed.

---

## 🧠 Technologies Used

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Data Analysis**: pandas, matplotlib, seaborn
- **Machine Learning**: scikit-learn (RandomForestRegressor)
- **Styling**: Custom CSS for dark theme and responsive design
- **Menu Navigation**: `streamlit-option-menu` plugin

---

## 🗂️ Project Structure

Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run app.py

📦 Requirements
Make sure to include the following packages in your requirements.txt:
streamlit
pandas
matplotlib
seaborn
scikit-learn
streamlit-option-menu

****
