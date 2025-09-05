# 🏨 GTC ML Project 1 - Hotel Booking

## 📌 Overview

Hotels often lose revenue due to last-minute booking cancellations.
This project prepares raw hotel booking data to help predict which bookings are likely to be cancelled.
The focus here is *not model building, but creating a **clean, machine-learning-ready dataset** through data exploration, cleaning, and feature engineering.

---
## 📂 Dataset

* *Source:* Property Management System (PMS).
* *File:* hotel_bookings.csv
* *Size:* \~119,000 rows, 32 columns.

---

## 🎯 Objectives

- Explore and analyze raw hotel booking data.
- Identify and handle missing values, duplicates, and outliers.
- Create new meaningful features to enrich the dataset.
- Encode categorical variables efficiently.
- Prevent data leakage by dropping leakage-prone columns.
- Prepare a final cleaned dataset, ready for predictive modeling.

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy** → data manipulation  
- **Seaborn, Matplotlib, Missingno** → visualization  
- **Scikit-learn** → preprocessing & train/test split
  
---
## 🛠 Steps Implemented

1. *Exploratory Data Analysis (EDA):*

   * Summary statistics (.describe(), .info()).
   * Visualized missing values and outliers.

2. *Data Cleaning:*

   * Imputed missing values using mode/median/placeholder.
   * Removed duplicates.
   * Handled outliers (e.g., capping extreme ADR values).
   * Fixed data types for consistency.

3. *Feature Engineering:*

   * Created total_guests, total_nights, and is_family.

4. *Preprocessing:*

   * One-Hot Encoding for low-cardinality features.
   * Frequency for high-cardinality features.
   * Removed data leakage columns (reservation_status, reservation_status_date).
   * Split data into training & testing sets.

---

## 📑 Deliverables

* Cleaned dataset (ready for ML).
* Notebook containing all steps (EDA, cleaning, preprocessing, feature engineering).

---

### ✅  Dataset is now **machine-learning ready**.  
