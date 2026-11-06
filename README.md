# Spotify Dataset Milestone 1


## Overview

This repository contains the solution for **Milestone 1 – CIE: Data Transformation, Null Value Handling, Insight Generation, and Visualization**.

The project focuses on analyzing a Spotify tracks dataset using Python and various data analysis libraries, including Pandas, NumPy, and Matplotlib.

## Files

- `milestone1.ipynb` – Jupyter Notebook containing data understanding, preprocessing, missing-value analysis, data transformation, insight generation, and visualizations.
- `data_rename.csv` – Spotify tracks dataset used for the analysis.
- `README.md` – Project description and instructions.

## Dataset

The dataset contains Spotify track information, including:
- Artist and track names
- Release year and release date
- Track popularity
- Duration
- Audio features such as danceability, energy, acousticness, valence, tempo, and speechiness.

## Operations Performed

1. **Data Understanding:** Loaded the dataset using Pandas and explored its shape, columns, data types, and statistical summaries.
2. **Missing Value Handling:** Identified missing values and applied mean imputation to numerical columns wherever required.
3. **Data Transformation:** Parsed release dates, converted track duration from milliseconds to minutes, and extracted release decades.
4. **Duplicate Handling:** Checked for duplicate records in the dataset.
5. **Outlier Detection:** Used the Interquartile Range (IQR) method to identify potential outliers.
6. **Insight Generation:** Analyzed track popularity, release trends, duration, and audio features.
7. **Data Visualization:** Created visualizations using Matplotlib to understand patterns, distributions, and relationships between audio features.

## Key Observations

- The original dataset contains 170,653 rows and 19 columns.
- No missing values were initially present in the original dataset.
- Release dates contain mixed formats, including entries with only the year.
- Outlier detection was performed using the IQR method.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Ensure that `data_rename.csv` and `milestone1.ipynb` are in the same folder.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

4. Open the notebook using Jupyter Notebook or JupyterLab.
5. Run all cells sequentially to reproduce the analysis and visualizations.

---

**Project:** Milestone 1 – Data Transformation and Visualization  
**Repository:** 4SF25CI069_Milestone
