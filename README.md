# SCD_DS_1

# 📊World population Analysis (2023) using bar chart

This repository contains a Python project that performs data cleaning and visualization on a world population dataset. The goal is to extract useful insights by cleaning the dataset and creating a bar chart of population distribution by age groups.

---

## 🔍 Project Objective

- Load the raw `world_population_data.csv` dataset
- Clean and retain only the necessary columns: `Age Group` and `Population`
- Convert population values to numeric format
- Handle missing values and formatting issues
- Visualize the cleaned data using a bar chart

---

## 🗂️ Files Included

| File Name                     | Description                                      |
|------------------------------|--------------------------------------------------|
| `world_population_data.csv`  | Original raw dataset                             |
| `cleaned_population_data.csv`| Cleaned version with only relevant columns       |
| `population_barchart.png`    | Output bar chart image showing age-wise population |

---

## How to Use


```bash
### Step 1: Clone the Repository
git clone https://github.com/your-username/world-population-age-barchart.git
cd world-population-age-barchart

### Step 2: Install Dependencies
pip install pandas matplotlib seaborn

### Step 3: Run the Script
python world_population_barchart.py

```

## 📝 Notes
```bash
- The population column may contain formatting characters like commas. The script handles those automatically.
- If column names have leading or trailing spaces (like `" Age Group "`), they are stripped during preprocessing.
- Missing values are dropped during cleaning to ensure smooth plotting.
- You can easily adapt this script to work with similar demographic datasets by adjusting column names.
- The bar chart uses Seaborn for a visually appealing, clean design.

---
