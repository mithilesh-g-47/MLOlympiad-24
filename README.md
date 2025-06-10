# ML Olympiad 2024 – Nashik Weather Condition Prediction

This repository contains my solution to the **ML Olympiad 2024**, where the task was to predict the weather condition in Nashik using historical meteorological data.

## 🎯 Problem Statement

Given past weather data, the goal was to classify the **weather condition** (target variable) as categories like `clear-day`, `rain`, etc. The dataset includes temperature, humidity, windspeed, visibility, solar radiation, and other features.

---

## 📊 Dataset Snapshot

| Month | Year | Temp Max | Temp Min | Temp | Humidity | Wind Speed | Solar Energy | Weather Condition |
|-------|------|----------|----------|------|----------|-------------|---------------|--------------------|
| 11    | 2022 | 79.9     | 50.1     | 65.3 | 46.2     | 13.9        | 19.9          | clear-day          |

---

## 🚀 Results

- **Validation Accuracy:** `0.9449`
- **Validation F1 Score:** `0.9451`
- **Public Test F1 Score:** `86.79`
- **Leaderboard Rank:** `44th`

---

## 🧠 Model Choice – Why Random Forest?

- Handles **mixed data types** well (temperature, humidity, etc.).
- Robust to **outliers and missing values**.
- Doesn’t require **feature scaling**.
- Offers **built-in feature importance**.
- Excellent performance for **classification** problems with tabular data.

---

## 📘 Notebook Overview

- **Data Loading**: Reading and inspecting data.
- **Preprocessing**: Handling missing values, encoding, and transformations.
- **EDA**: Distribution plots, correlations, and feature insights.
- **Modeling**: Training Random Forest, tuning hyperparameters.
- **Evaluation**: Accuracy, F1 score, confusion matrix.
- **Submission**: Generating predictions for public test set.


---

## 📂 Project Structure

```plaintext
ml-olympiad-2024-weather/
├── README.md
├── ml-olympiad-weather.ipynb
└── data/ (optional)
