# Daily Commute Time Prediction (ML Project)

This project predicts **daily commute travel time (in minutes)** using a realistic dataset and **Linear Regression**. It focuses on real-world variability rather than perfect accuracy.

---

## Files

```
data.csv              # Commute dataset stimulated dataset(10,000 rows) close to real data
model maker.ipynb     # Data analysis & model training notebook
```

---

## Dataset Overview (`data.csv`)

Each row represents one commute.

| Column          | Description                    |
| --------------- | ------------------------------ |
| distance_km     | Commute distance in km         |
| traffic_level   | Traffic intensity (1–10)       |
| rain_mm         | Rainfall in mm                 |
| departure_min   | Minutes after 6:00 AM          |
| vehicle_type    | 0 = Bike, 1 = Car              |
| travel_time_min | Target: travel time in minutes |

The dataset includes **noise, rush-hour effects, and overlapping values**, making it realistic.

---

## Model

* Algorithm: **Linear Regression**
* Train–test split used
* Performance evaluated using **R² and RMSE**

Expected R²: **0.65 – 0.80** (realistic for real-life data)

---

## Usage

1. Open `model maker.ipynb`
2. Run all cells sequentially
3. Analyze predictions and residuals

---

## Purpose

* ML mini-project
* Resume / portfolio project
* Understanding real-world regression problems

---
