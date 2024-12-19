# Crime Analysis 2021-2022

## Overview
This project analyzes crime data from March 2021 to March 2022 for the West Midlands, UK. Using clustering techniques and data visualization, we explore spatial crime patterns, identify high-risk areas, and provide actionable insights for resource allocation and crime prevention strategies.

## Dataset
- **Source:** [Police API](https://data.police.uk/data/)
- **Data Description:**
  - Crime reports from March 2021 to March 2022.
  - Geographic focus: West Midlands Police jurisdiction.
  - Includes details such as crime type, location, and time of occurrence.

## Objectives
1. Analyze monthly crime trends and spatial distribution.
2. Perform clustering to classify areas into high-risk, moderate-risk, and low-risk zones.
3. Identify crime hotspots and their unique patterns.
4. Create visualizations to support evidence-based decision-making.

## Features
### 1. Data Processing
- Data cleaning, normalization, and feature engineering using Python and pandas.
- Combined datasets into a unified structure for analysis.

### 2. Clustering Analysis
- **Algorithm:** Agglomerative Hierarchical Clustering.
- Visualized clusters using dendrograms and mapped results with `folium`.
- Experimented with different cluster counts (e.g., 3 vs. 5 clusters).

### 3. Visualizations
- Crime type distribution by month and area.
- Maps indicating cluster regions and risk levels.
- Dendrograms illustrating hierarchical clustering.

## Results
### Key Findings:
- Cluster ID 1: High-risk areas with diverse and frequent crimes.
- Cluster ID 0: Low-risk areas with minimal criminal activity.
- Cluster ID 2: Moderate-risk areas requiring targeted interventions.

### Impact of Cluster Count:
- Increasing the number of clusters (e.g., from 3 to 5) provided a finer understanding of specific crime patterns but required careful interpretation to avoid overfitting.

## Files
- **`chay-source-code.ipynb`**: Python notebook for data preprocessing, analysis, and visualization.
- **`chay.csv`**: Combined dataset for analysis.
- **`REPORT.docx`**: Summary of findings, methods, and insights.
- **`chay-PDF.pdf`**: Reference material for dataset details and methodology.

## Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `folium`, `scikit-learn`, `scipy`.

## Getting Started
### Clone the Repository
```bash
git clone https://github.com/mewz1k/Crime-Analysis-2021-2022.git
cd Crime-Analysis-2021-2022
