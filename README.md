# Medical Data Visualizer

A data analysis and visualization project using Python, pandas, seaborn, and matplotlib. Built as part of the freeCodeCamp Data Analysis with Python certification.

## Overview

This project analyzes a dataset of medical examination records and visualizes the relationships between various health indicators and cardiovascular disease. It includes:

- Data cleaning and normalization
- A **categorical plot** showing feature distributions by cardiovascular disease status
- A **heatmap** illustrating the correlation between medical measurements

## Features

- BMI-based overweight classification
- Normalization of cholesterol and glucose indicators
- Outlier filtering for height, weight, and blood pressure values
- Visualizations built with seaborn:
- `catplot()` to compare categorical features
- `heatmap()` to show correlation matrix

## Skills Demonstrated

- Data preprocessing with pandas
- Logical condition filtering and value mapping
- Exploratory data analysis (EDA)
- Seaborn data visualization techniques

## Files Included

- `medical_data_visualizer.py`: The main Python script
- `medical_examination.csv`: Dataset used for analysis
- `catplot.png`: Output of the categorical plot
- `heatmap.png`: Output of the heatmap

## How to Run

1. Install dependencies:
```bash
pip install pandas seaborn matplotlib
```

2. Run the script:
```bash
python medical_data_visualizer.py
```

3. Check the output images:
- `catplot.png`
- `heatmap.png`

## Dataset Source

The dataset comes from the freeCodeCamp Data Analysis certification project, based on medical examination data of patients.

---

Created by Carlos Ortiz
