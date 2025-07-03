# solar-energy-prediction
Prediction of photovoltaic energy production based on meteorological data.

# ☀️ Solar Energy Production Prediction

This project aims to build a predictive model to estimate photovoltaic solar energy production based on meteorological data. The model can support grid operators, energy analysts, or energy startups in managing supply more efficiently and improving forecast accuracy.

https://www.data.gouv.fr/datasets/courbes-de-production-mensuelles-eolien-solaire-complement-de-remuneration/

---

## 📌 Context

With the increasing integration of renewable energy sources into modern power grids, accurate forecasting of solar energy production is becoming crucial. Variations in weather conditions affect photovoltaic (PV) system output significantly. This project explores how meteorological features such as solar irradiance, temperature, humidity, wind speed, and time data can be used to predict energy production.

---

## 🎯 Objective

- Perform exploratory analysis of historical solar and weather data.
- Build regression models (Linear Regression, Random Forest, XGBoost) to predict solar energy output.
- Evaluate model performance using appropriate metrics (MAE, RMSE, R²).
- Optionally implement a deep learning model using TensorFlow/Keras.
- Present the results with visualizations and interpretation.

---

## 🛠 Tools and Libraries

- Python (3.x)
- Jupyter Notebook / Google Colab
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn
- xgboost
- tensorflow (optional)

---

## 🗂 Repository Structure
````markdown
```
solar-energy-prediction/
│
├── data/                  # Raw or cleaned datasets
│   └── solar_weather_data.csv
│
├── notebooks/             # Jupyter notebooks
│   └── analysis_modeling.ipynb
│
├── requirements.txt       # List of Python libraries
├── README.md              # Project description and instructions
```
````

---

## 📈 Dataset

The dataset contains time series data on weather conditions and the corresponding solar energy production values. Features include:

- Timestamp (Date, Hour)
- Irradiance (W/m²)
- Temperature (°C)
- Humidity (%)
- Wind speed (m/s)
- Solar production (kWh)

(📌 Add source or license if public — otherwise specify that it's a simulated dataset.)

---

## 🚀 Future Improvements

- Test LSTM models for time series forecasting.
- Deploy a Streamlit app for interactive prediction.
- Integrate real-time weather data via API.

---

## 👩🏻‍💻 Author

**Monica Buitrago**  
_Doctor in Computer Science –  Data Scientist_  
[LinkedIn](https://www.linkedin.com/in/monicabuitrago/)  
GitHub: [`monicabuitrago-ai`](https://github.com/monicabuitrago-ai)

---

## 📄 License

This project is open-source and available under the MIT License.


