# Exploratory Data Analysis on Google Play Store Dataset

**Author:** Emre Demirbaş  
**Course:** CENG463 — Machine Learning  
**Institution:** Ankara Yıldırım Beyazıt University  
**Date:** 2025  

---

## Overview

This repository contains a complete Exploratory Data Analysis (EDA) project based on the Google Play Store dataset.  
The goal is to explore relationships between app features such as category, rating, price, content rating, and popularity, and to derive meaningful insights into app market trends.

The project includes:
- Clean and well-documented Python code (`eda_project.py`)
- A detailed LaTeX report with integrated figures (`EDA_Report_GooglePlayStore.tex`)
- A compiled PDF version of the report (`EDA_Report_GooglePlayStore.pdf`)
- Visualizations generated during analysis (in the `figures/` directory)

---

## Repository Structure
├── eda_project.py # Final Python script version of the EDA notebook
├── EDA_Report_GooglePlayStore.tex # Full LaTeX report with figures and analysis
├── EDA_Report_GooglePlayStore.pdf # Compiled PDF report
├── figures/ # Folder containing all visualizations
│ ├── fig1_ratings_distribution.png
│ ├── fig2_reviews_distribution.png
│ ├── ...
│ └── fig17_installs_by_android_version.png
└── LICENSE # MIT License


---

## Key Analytical Topics

1. **Data Preprocessing and Cleaning**
   - Handled missing values and duplicates  
   - Converted non-numeric data (e.g., "10,000+", "19M") into numeric format  
   - Normalized column types and categories

2. **Descriptive Analysis**
   - Distribution of ratings, reviews, app size, and prices  
   - Analysis of free vs. paid apps  
   - Overview of dominant app categories

3. **Research Queries and Insights**
   - Relationship between app type and rating  
   - Content rating vs. user satisfaction  
   - Total installs by Android version  
   - Word frequency in app names  
   - Popularity vs. user satisfaction trends  

4. **Visualization**
   - 17 detailed plots (bar plots, box plots, heatmaps, scatter plots)  
   - Figures integrated into the LaTeX report  

---

## Example Findings

- Most apps are rated between 4.0 and 4.5, showing strong overall user satisfaction.  
- Family, Game, and Tools are the dominant categories, together representing over 60% of all apps.  
- Paid apps receive slightly higher and more consistent ratings compared to free apps.  
- Popularity (installs) and quality (ratings) are weakly correlated; less popular apps can still achieve high satisfaction.  
- The majority of apps support older Android versions (4.x) to reach a wider audience.

---

## Report

The full written report (`EDA_Report_GooglePlayStore.pdf`) provides:
- A structured overview of methods and results  
- Captions and explanations for each figure  
- Clean formatting for academic or professional submission  

You can also edit or compile the LaTeX version (`EDA_Report_GooglePlayStore.tex`) in Overleaf.

---

## Technologies Used

- **Python 3.10+**
  - pandas, numpy, seaborn, matplotlib  
- **LaTeX (Overleaf)**
  - For structured report writing and figure inclusion  
- **Google Colab / Jupyter Notebook**
  - Used during exploratory phase before exporting to `.py`

---

## License

This project is licensed under the [MIT License](LICENSE) © 2025 Emre Demirbaş.  
You are free to use, modify, and distribute the material with proper attribution.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Acknowledgments

Dataset source: [Google Play Store Apps Dataset (Kaggle)](https://www.kaggle.com/datasets/lava18/google-play-store-apps)  
