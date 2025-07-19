🌦️ Weather Data Analysis and Temperature Prediction

This project uses historical weather data to analyze trends and predict future temperatures using a Linear Regression machine learning model. It also includes visualizations for Exploratory Data Analysis (EDA) and model evaluation.


📊 Project Overview

- 📅 Dataset: Daily weather records (from Kaggle)
- 📈 Goal: Predict future air temperature using historical patterns
- 🧠 Model: Linear Regression
- 📍 Platform: Google Colab


📁 Files Included

| File Name                | Description                                |
|-------------------------|--------------------------------------------|
| `weather_prediction.ipynb` | Jupyter Notebook with full project code  |
| `daily_weather.csv`     | Weather dataset (input file)               |
| `README.md`             | Project explanation and usage guide        |


🧪 Features

- ✔️ Data cleaning and preprocessing
- ✔️ Exploratory Data Analysis (EDA)
- ✔️ ML model training with `scikit-learn`
- ✔️ Visualizations:
  - Actual vs Predicted temperatures
  - Residuals distribution
  - Temperature trend over time
- ✔️ Predict future temperatures


🚀 How to Run in Google Colab

1. Open `weather_prediction.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload the `daily_weather.csv` file when prompted
3. Run all cells (Shift + Enter)
4. View predictions and plots
5. (Optional) Download trained model using `joblib`


⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
