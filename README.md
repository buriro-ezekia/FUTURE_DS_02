# IPL Data Analysis Using Python

This repository contains an analysis of IPL (Indian Premier League) data using Python for data preprocessing and analysis. The project aims to uncover key insights from IPL matches, players, and teams through interactive visualisations and statistical analysis.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Insights and Visualisations](#key-insights-and-visualisations)
3. [Technologies Used](#technologies-used)
4. [How to Run the Project](#how-to-run-the-project)
5. [File Structure](#file-structure)
6. [Future Enhancements](#future-enhancements)

---

## Project Overview

The IPL data analysis project focuses on providing interactive and visually appealing insights into cricket matches. Using Python, I created dashboards and visualisations that explore various aspects of IPL, such as:
- **Player performance** (e.g., runs scored by individual players).
- **Team statistics** (e.g., number of matches won by each team).

The preprocessing, feature engineering, and statistical computations were carried out in Python, ensuring clean and reliable data was loaded for visualisation.

---

## Key Insights and Visualisations

### 1. Distribution of Runs Scored
- Visualised the frequency of runs scored by individual players.
- Histogram-style visualisation shows peaks in run ranges for better analysis of player consistency.

### 2. Team Performance
- Bar chart showing the number of matches won by each team.
- Highlighted top-performing teams such as Mumbai Indians and Chennai Super Kings.

---

## Technologies Used

### 1. Python
- Used for data preprocessing, cleaning, and statistical analysis.
- Libraries utilised:
  - **pandas**: Data cleaning and manipulation.
  - **matplotlib**/**seaborn**: Exploratory data visualisation.
    
---

## How to Run the Project

### Prerequisites
- Install Python (>=3.8) and necessary libraries listed in `requirements.txt`.
- Download and install Power BI Desktop.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/buriro-ezekia/ipl-data-analysis.git
   ```
2. Preprocess the dataset using the Python script provided:
   ```bash
   python preprocess_data.py
   ```
   This will generate a clean dataset (`processed_data.csv`) for visualisation.
3. Open `IPL_Analysis.pbix` in Power BI Desktop.
4. Explore the interactive dashboards to derive insights from the data.

---

## File Structure

```
ipl-data-analysis/
|
|-- data/
|   |-- raw_data.csv                # Original dataset
|   |-- processed_data.csv          # Preprocessed dataset
|
|-- visuals/
|   |-- screenshots/               # Visualisations from Power BI
|
|-- scripts/
|   |-- preprocess_data.py         # Python script for data cleaning
|   |-- analysis.ipynb             # Jupyter notebook for analysis
|
|-- IPL_Analysis.pbix              # Power BI file
|-- requirements.txt               # Python dependencies
|-- README.md                      # Project documentation (this file)
```

---

## Future Enhancements

- Add predictive analytics to forecast match outcomes or player performances.
- Automate dataset updates and integrate real-time analysis in Power BI.
- Enhance the Power BI dashboard with additional filters and KPI indicators.

---

Feel free to contribute by submitting issues or pull requests. For queries, contact ezekia.buriro1810@gmail.com.
