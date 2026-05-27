# Exploratory Data Analysis (EDA) using Python

## Project Overview
This project demonstrates Exploratory Data Analysis (EDA) using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The analysis is performed on a Wine Quality dataset stored in an Excel file. The project focuses on understanding the dataset structure, analyzing statistical information, identifying missing and duplicate values, and visualizing relationships between variables using different plots.

## Objectives
- Understand the structure of the dataset
- Perform statistical analysis
- Detect missing and duplicate values
- Visualize distributions and correlations
- Analyze relationships between variables

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- OpenPyXL

## Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Dataset Information

The dataset contains the following columns:

| Column Name | Description |
|-------------|-------------|
| quality | Wine quality rating |
| alcohol | Alcohol percentage |
| sugar | Sugar content |

Dataset file used: wine_data.xlsx

## Project Workflow

### 1. Import Libraries
Imported required Python libraries for data analysis and visualization.

### 2. Read Dataset
Loaded the Excel dataset using:

```python
df = pd.read_excel("wine_data.xlsx")
```

### 3. Data Inspection
Performed:
- Dataset shape analysis
- Dataset information
- Statistical summary
- Column analysis

### 4. Data Cleaning
Checked:
- Missing values
- Duplicate values

### 5. Univariate Analysis
Generated:
- Count Plot
- Histogram with KDE

### 6. Bivariate Analysis
Generated:
- Swarm Plot
- Pair Plot
- Violin Plot
- Box Plot

### 7. Multivariate Analysis
Generated:
- Correlation HeatmaP

## Visualizations Included
- Bar Plot
- Histogram Plot
- Swarm Plot
- Pair Plot
- Violin Plot
- Box Plot
- Heatmap

## Output
The project provides:
- Statistical summaries
- Data distribution analysis
- Correlation analysis
- Visual insights using plots

## Conclusion
Exploratory Data Analysis (EDA) helps in understanding the dataset before applying machine learning or statistical models. This project demonstrates how Python visualization libraries can be used to analyze patterns, relationships, distributions, and correlations effectively.

## Author
KAVYA SHREE BALI