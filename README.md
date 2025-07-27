# 🚖 Uber Fares Dataset Analysis – Power BI Report

Course: INSY 8413 – Introduction to Big Data Analytics  
Instructor: Eric Maniraguha  
Student Name:Ishimwe Joyeuse [ishimwejoyeuse177@gmail.com]

Assignment Type: Data Analysis Project using Power BI  
Submission Date: Sunday, 27 July 2025  
Group: E

---

## 📌 Introduction

This project explores the Uber Fares Dataset from Kaggle to uncover trends and patterns in fare amounts, ride durations, and trip times. Using Python for data preparation and Power BI for visualization, the goal is to deliver actionable insights through an interactive dashboard.

---

## 🛠 Methodology

### 1. **Data Collection**
- Dataset: `uber.csv` (downloaded from Kaggle)
- Source: Public Uber ride data

### 2. **Data Cleaning (Python)**
- Removed negative and zero fare amounts.
- Filtered out unrealistic fare values (e.g., above $100).
- Converted date/time fields to `datetime` objects.
- Handled missing values.

### 3. **Feature Engineering**
- Extracted new columns:
  - `hour`, `day_of_week`, `month`
  - `peak_hour` (True/False indicator for 7–9 AM, 4–7 PM)
- Final dataset saved as: `uber_cleaned_for_powerbi.csv`

---

## 📊 Analysis & Visualizations

Visuals were created using **Power BI Desktop** and exported as screenshots in the `screenshots/` folder. The `.pbix` dashboard file is included as `uber_dashboard.pbix`.

| Visual | Description |
|--------|-------------|
| **Bar Chart** | Average fare by hour|
| **Line Chart** | Fare trends over time |
| **Table** | Detailed ride information |
| **Map** | Pickup coordinates visualization |
| **Slicer** | Interactive filters (hour, day, peak time) |
| **Card Visual** | Key KPIs (average fare, total rides, busiest hour) |

---

## 📈 Results

- **Total Cleaned Rides:** `XX,XXX`  
- **Average Fare:** `$XX.XX`  
- **Most Common Passenger Count:** `1`  
- **Peak Hours:** 7–9 AM and 4–7 PM  
- **Busiest Hour of Day:** `HH:00`

---

## 🔍 Insights

- Fares are higher during **rush hours**.
- Weekends have **fewer rides** but longer distances.
- Most pickups happen in urban centers based on latitude/longitude distribution.
- Significant number of rides occur in **early evening hours**, indicating demand for after-work transportation.

---

## 💡 Recommendations

- **Dynamic Pricing** should be optimized for peak hours.
- Consider adding more availability during **early evenings**.
- **Zone-based pricing** could help manage urban hotspots more efficiently.
- Further analysis could integrate **weather data** to analyze its impact on ride frequency and fare changes.

---

## 📎 Project Files

- `uber.csv` – Raw dataset (https://drive.google.com/file/d/1yCwpngPKNYfMMi-psWvDj1EmSkot7Z46/view?usp=sharing)
- `uber_analysis.py` – Python cleaning + EDA + feature engineering (https://drive.google.com/file/d/1oA7Av1eXA74gzg3jSKL8mb06qHWPAEdP/view?usp=sharing)
- `uber_cleaned_for_powerbi.csv` (https://drive.google.com/file/d/1_ZiJEnDD5xk4mjBGyK2vrLWCq8v3SqbB/view?usp=sharing)
- `uber_dashboard.pbix` – Final Power BI Dashboard (https://drive.google.com/file/d/13phcHJ4f9ARQsXywiVAhzMpScHCEfGkK/view?usp=sharing)
- `screenshots/` – Folder of all visuals
  

---

## ✅ Submission Confirmation

All project deliverables have been uploaded to this public GitHub repository and submitted by the deadline.

📂 [**GitHub Repository**](https://github.com/ishimwe-joyeuse/uber-fare-powerbi) 

📧 Submitted to: [eric.maniraguha@auca.ac.rw](mailto:eric.maniraguha@auca.ac.rw)


