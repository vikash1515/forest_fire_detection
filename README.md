# 🌲🔥 Forest Fire Detection & Early Warning System

An AI-powered Streamlit dashboard for predicting forest-fire risk from environmental conditions such as temperature, humidity, wind speed, and precipitation.

## Features

- Predicts forest-fire risk using a trained machine-learning model
- Supports manual environmental input
- Displays fire-risk probability and risk category
- Shows model feature importance when available
- Visualizes historical fire-prone regions using map data
- Includes Uttarakhand FIRMS and weather datasets
- Includes the model-training notebook

## Technology Stack

- Python
- Streamlit
- Pandas and NumPy
- Scikit-learn
- Joblib
- Plotly

## Project Files

- `app.py` — Streamlit application
- `best_model.pkl` — trained model
- `firms_uttarakhand.csv` — FIRMS fire-detection data
- `weather_data.csv` — weather data
- `Untitled4.ipynb` — model-training and data-processing notebook
- `requirements.txt` — Python dependencies

## Run Locally

1. Clone this repository:

```bash
git clone https://github.com/vikash1515/forest_fire_detection.git
cd forest_fire_detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the Streamlit app:

```bash
streamlit run app.py
```

## Important Data Note

The dashboard's historical map section expects a file named `merged_dataset.csv`. It was not included in the current upload, so the map section will display an informational message until that file is added.

## Model Inputs

The prediction model uses:

- Mean temperature
- Maximum temperature
- Minimum temperature
- Mean relative humidity
- Mean wind speed
- Precipitation
- Dryness index
- Temperature range

## Disclaimer

This project is an academic/prototype system. Its predictions should not be treated as an official emergency or public-safety warning system.
