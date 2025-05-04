# 🏠 IoT-based Indoor Occupancy Detection

A machine learning project for predicting indoor room occupancy using IoT sensor data. This system analyzes environmental variables to determine whether a room is occupied, helping to optimize energy usage in smart buildings.

---

## 📌 Overview

This project leverages IoT sensor readings—such as temperature, humidity, light, and CO₂ levels—to classify room occupancy using supervised machine learning models. Accurate occupancy detection can be used to enhance building automation systems, reduce energy consumption, and improve occupant comfort.

---

## 🎯 Objectives

- Load and preprocess time-series IoT data
- Perform exploratory data analysis (EDA) to understand key features
- Train multiple classification models
- Compare model performance using standard evaluation metrics
- Identify the best-performing model for real-time occupancy prediction

---

## 📂 Dataset

The dataset used is `Occupancy.csv`, containing time-stamped sensor data:

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `date`         | Timestamp of the reading                    |
| `Temperature`  | Room temperature (°C)                        |
| `Humidity`     | Humidity percentage (%)                     |
| `Light`        | Light intensity (lux)                       |
| `CO2`          | Carbon dioxide concentration (ppm)          |
| `HumidityRatio`| Ratio of absolute humidity to air mass      |
| `Occupancy`    | Target variable (1 = Occupied, 0 = Not)     |

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **pandas** – Data handling
- **numpy** – Numerical operations
- **matplotlib** & **seaborn** – Data visualization
- **scikit-learn** – Machine learning models and evaluation

Install all dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
