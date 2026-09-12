# 🚲 Bike Rental Demand Prediction

A Machine Learning project that predicts daily bike rental demand using **Linear Regression** and real-world data from the UCI Bike Sharing Dataset.

The project focuses on understanding the relationship between weather, seasonal, and calendar-related factors and the total number of bike rentals.

---

## 📌 Project Overview

Bike-sharing systems generate large amounts of data containing information about weather conditions, seasons, working days, and bike rental counts.

The objective of this project is to build a **Linear Regression model** that predicts the total number of bike rentals (`cnt`) based on relevant features.

### Problem Statement

> Can we predict the number of bikes rented on a given day using weather and calendar-related information?

---

## 📊 Dataset

The dataset used in this project is the **Bike Sharing Dataset** from the UCI Machine Learning Repository.

It contains daily bike rental information along with:

- Date
- Season
- Year
- Month
- Holiday
- Weekday
- Working day
- Weather condition
- Temperature
- Feeling temperature
- Humidity
- Windspeed
- Total bike rentals

### Target Variable

`cnt` — Total number of bike rentals.

The `cnt` variable is calculated as:

```text
cnt = casual + registered
