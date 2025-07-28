# Netflix Movies & TV Shows Clustering & EDA (2019)

This repository contains a complete machine learning and analytics project on **Netflix’s worldwide content catalog as of 2019**. The project investigates content distribution across countries, analyzes strategic shifts between TV shows and movies, and applies unsupervised clustering to group similar shows/movies—enabling actionable insights for business stakeholders.

## 📈 Project Overview

**Objective:**  
- Perform in-depth Exploratory Data Analysis (EDA) of Netflix’s 2019 content.
- Understand content type availability in different countries.
- Analyze changes in Netflix’s focus between TV shows and movies over time.
- Cluster similar content based on text and metadata (unsupervised ML).
- Generate practical findings for content and strategy teams.

**Dataset:**  
- `Netflix_Clustering.csv` (available in the repo)
- Contains metadata for all Netflix global titles as of 2019, including title, type, year, genre, description, country, rating, etc.

## 🛠️ Features

- **Full Python pipeline** (`.py` script and Jupyter notebook):
  - EDA & visualizations (Matplotlib, Seaborn)
  - Data cleaning, missing values/outliers, feature engineering
  - Trend analysis for content type, rating, country, year
  - Text preprocessing with TF-IDF and NLP
  - KMeans & Agglomerative Clustering (scikit-learn)
  - Cluster explainability: top terms, genre/country breakdown
  - Export of results with cluster labels

## 🔍 Project Architecture

1. **Data Loading:**  
   - Direct download and import of Netflix 2019 data

2. **EDA:**  
   - Content counts by type, year, rating, country, and genre  
   - Visualizations for strategic decision-making

3. **Cleaning & Engineering:**  
   - Handle missing data, deduplication  
   - Split multi-value fields (country, genre)  
   - Feature generation: year added, rating categories

4. **Text-Based Clustering Workflow:**  
   - TF-IDF vectorization of description fields  
   - Optimal cluster selection (Elbow/Dendrogram)  
   - KMeans and Agglomerative clustering, profiling each cluster

5. **Insights & Recommendations:**  
   - Profiling clusters to identify content gaps/opportunities  
   - Actionable recommendations for regional/genre strategies

6. **Reporting:**  
   - Visualizations embedded in code/notebook  
   - Labeled datasets for stakeholder hand-off




