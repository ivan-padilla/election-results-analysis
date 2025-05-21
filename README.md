# 2025 Midterm Election Results Visualization

## Overview
### This repository provides tools for visualizing the results of the 2025 Midterm elections. It includes a Python notebook for data preprocessing and visualization, along with an election dataset and a GeoJSON map of the Philippines.
Contents
- electionAnalysis.ipynb – Jupyter Notebook for processing and visualizing election data.
- senate25-final.csv – Election results dataset.
- regionalMap.json – GeoJSON file mapping electoral boundaries in the Philippines.
### Dependencies
Ensure you have the following Python libraries installed before running the notebook:
- pandas – Data manipulation and analysis.
- seaborn – Statistical data visualization.
- matplotlib – Plotting library.
- plotly – Interactive data visualization.
- dash – Web-based dashboards for interactive election result visualization.
You can install them using:
'''Bash
pip install pandas seaborn matplotlib plotly dash
'''
## Usage
- Load the election dataset in the jupyter notebook.
- Preprocess the data using pandas, filtering and structuring it as needed.
- Utilize seaborn and matplotlib for static plots.
- Generate interactive choropleth maps using plotly.
- Use dash to create a web-based interface for exploring election results.
## Scaling to Barangay-Level Analysis
The visualization can be scaled down to barangay-level results by:
- Using a GeoJSON file containing barangay boundaries and their unique IDs.
- Ensuring the election dataset is grouped by barangay.
- Modifying the data processing pipeline to reflect barangay-level granular results.
