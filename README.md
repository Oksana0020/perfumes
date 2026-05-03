# Perfume Recommendation System

## Overview

This project uses machine learning to analyse perfumes based on their fragrance notes.  
The system groups similar perfumes into categories and recommends perfumes with similar scent profiles.  
Users can also filter recommendations by price range.

---

## Features

- Clean and prepare perfume and price datasets
- Convert fragrance notes into numerical features using **TF-IDF**
- Cluster perfumes into scent categories using **KMeans**
- Visualise clusters using **PCA**
- Recommend similar perfumes using **Nearest Neighbours**
- Filter recommendations by budget

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Dataset Information

The project uses two datasets:

1. **Fragrance dataset**
   - Perfume name
   - Brand
   - Top notes
   - Middle notes
   - Base notes
   - Main accords

2. **Price dataset**
   - Product title
   - Brand
   - Price

---

## Project Stages

### Stage 1 – Business Understanding
Define the problem and project goal.

### Stage 2 – Research Question
Can perfume similarity be modelled using fragrance notes, and can recommendations be filtered by price?

### Stage 3 – Data Preparation
- Clean text columns
- Merge notes into one field
- Clean prices
- Match perfume and price datasets

### Stage 4 – Modelling
- TF-IDF vectorization
- KMeans clustering
- Cluster labels (woody, floral, spicy, etc.)
- Build recommendation system

### Stage 5 – Evaluation
- Silhouette score
- PCA cluster visualisation
- Test recommendations
- Price filter testing

### Stage 6 – Conclusion
This system successfully recommends similar perfumes and supports budget filtering.

---

### Project was created as part of Artificial Intelligence (AI) coursework.
