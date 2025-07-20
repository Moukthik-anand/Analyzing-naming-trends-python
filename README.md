# 👶 Baby Name Trends Analysis using Python

This project analyzes baby name trends in the United States using data provided by the Social Security Administration (SSA). It demonstrates how to extract zipped data, manipulate it using pandas, and visualize naming patterns over time.

---

## 📂 Dataset

- *Source*: [SSA Baby Names Dataset](https://www.ssa.gov/oact/babynames/limits.html)
- *Format*: A ZIP file containing .txt files named like yob1880.txt, each representing a year.
- *Columns*: Name, Gender, Count

---

## 🛠 Technologies Used

- Python 3
- pandas
- matplotlib
- zipfile
- io.BytesIO

---

## 📊 Features Implemented

### ✅ Step 1: Extract ZIP Using BytesIO
Load names.zip using in-memory streams without unzipping manually.

### ✅ Step 2: Read and Merge All .txt Files
Combine all baby name files into a single pandas DataFrame with an added Year column.

### ✅ Step 3: Gender-wise Birth Trend Over Time
Line plot comparing total births for male vs female per year.

### ✅ Step 4: Top 10 Baby Names in a Specific Year
View the most popular names for a specific year like 2020.

### ✅ Step 5: Most Popular Names of All Time
Group names across all years and sort by total count.

### ✅ Step 6: Top 5 Names by Gender
Bar chart of top 5 male and top 5 female names using subplot layout.

### ✅ Step 7: Trend of a Specific Name
Input any name (e.g., "Emma") to see how its popularity changed over the years.

---

## 🚀 How to Run

1. Download names.zip from the [SSA Baby Names website](https://www.ssa.gov/oact/babynames/limits.html) by clicking on 'National Data' after opening the site.
2. Place it in your project folder.
3. Run the baby_name_trends.py script in your Python environment or Jupyter Notebook.

---

## 🧠 What You Learn

- How to read ZIP files directly into memory
- Real-world data wrangling using pandas
- Line plots, bar charts, and subplots with matplotlib
- How to analyze time-series patterns in names

---
