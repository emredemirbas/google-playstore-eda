# Exploratory Data Analysis on Google Play Store Dataset
> A comprehensive analysis of Google Play Store apps to uncover insights on user ratings, categories, pricing, and popularity trends.

## Overview

This repository presents an Exploratory Data Analysis (EDA) of the **Google Play Store dataset**.  
The objective is to explore relationships between key app attributes — such as category, rating, price, content rating, and popularity — and to derive meaningful insights about user engagement and market trends.

The project includes:
- A clean and well-documented Jupyter Notebook (`google_play_store_eda.ipynb`)
- A compiled LaTeX report with figures and commentary (`google-playstore-eda-report.pdf`)
- Visualizations generated during analysis (in the `figures/` directory)

---

## Repository Structure
```
├── google_play_store_eda.ipynb # Final EDA notebook
├── google-playstore-eda-report.pdf # Final LaTeX report (compiled)
├── figures/ # Folder containing all visualizations
│ ├── fig1_ratings_distribution.png
│ ├── fig2_reviews_distribution.png
│ ├── ...
│ └── fig17_installs_by_android_version.png
├── googleplaystore.csv # Dataset used for analysis
└── LICENSE # MIT License
```

---

## Key Analytical Topics

1. **Data Preprocessing and Cleaning**
   - Handled missing values and duplicates  
   - Converted non-numeric data (e.g., `"10,000+"`, `"19M"`) into numeric form  
   - Normalized column types and standardized categories

2. **Descriptive Analysis**
   - Distribution of ratings, reviews, app size, and prices  
   - Analysis of free vs. paid apps  
   - Identification of dominant app categories

3. **Research Queries and Insights**
   - Relationship between app type and user ratings  
   - Content rating vs. satisfaction levels  
   - Total installs by Android version  
   - Word frequency in app titles  
   - Popularity vs. satisfaction correlations  

4. **Visualization**
   - 17 detailed plots (bar plots, box plots, heatmaps, scatter plots)  
   - Figures integrated into the final LaTeX report  

---

## Example Findings

- Most apps receive ratings between **4.0 and 4.5**, indicating strong user satisfaction.  
- **Family**, **Game**, and **Tools** categories dominate the store, making up over **60%** of all apps.  
- Paid apps show **slightly higher and more stable ratings** compared to free apps.  
- **App popularity and rating** are weakly correlated — lesser-known apps can still achieve high satisfaction.  
- Most apps maintain compatibility with **older Android versions (4.x)** for wider user reach.

---

The full written report is available here:  
[View the LaTeX Report (google-playstore-eda-report.pdf)](google-playstore-eda-report.pdf)

It provides:
- A structured overview of the methods and results  
- Captions and detailed interpretations for each figure  
- Academic-level formatting suitable for reports and portfolios    

---

## License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute the material with proper attribution.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Acknowledgments

Dataset source: [Google Play Store Apps Dataset (Kaggle)](https://www.kaggle.com/datasets/lava18/google-play-store-apps)  
