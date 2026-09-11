# SpaceX Falcon 9 Launch Success Analysis & Prediction

## Project Overview

This project presents an end-to-end data science analysis of SpaceX Falcon 9 launch data to explore the factors associated with successful first-stage landings and develop a machine learning model for predicting launch outcomes.

The project combines exploratory data analysis, SQL, data visualization, geospatial mapping, interactive analysis, and predictive modeling to transform historical launch data into meaningful insights.

## Project Objectives

- Analyze Falcon 9 launch and landing performance
- Examine the relationship between payload mass and launch success
- Compare landing success across different launch sites and orbit types
- Perform exploratory data analysis using Python and SQL
- Visualize launch sites geographically using Folium
- Create interactive visualizations using Plotly
- Build a machine learning model to predict first-stage landing success

## Analysis Performed

The project covers:

- Flight Number vs. Launch Success
- Payload Mass vs. Launch Success
- Launch Success Rate by Orbit
- Launch Success Rate by Launch Site
- SQL-based exploratory analysis
- Geographic analysis of Falcon 9 launch sites
- Interactive launch performance visualization
- Predictive classification of landing outcomes

## Machine Learning

A Logistic Regression classification model was developed using the following features:

- Flight Number
- Payload Mass
- Launch Site
- Orbit

The model achieved a test accuracy of approximately **77.78%**.

This provides a baseline for predicting whether a Falcon 9 first stage will land successfully based on historical launch characteristics.

## Key Insight

The analysis indicates that Falcon 9 landing success is better understood through a combination of mission characteristics rather than a single variable.

Launch site, orbit, payload mass, and flight experience collectively provide useful information for analyzing and predicting landing outcomes.

## Technologies Used

- Python
- Pandas
- NumPy
- SQL / SQLite
- Matplotlib
- Seaborn
- Plotly
- Folium
- Scikit-learn
- Jupyter Notebook

## Project Workflow

Data Preparation → Exploratory Data Analysis → SQL Analysis → Data Visualization → Geospatial Analysis → Interactive Visualization → Machine Learning → Insights

## Main Project File

`SpaceX_Falcon9_Launch_Success_Analysis.ipynb`

The notebook contains the complete analysis, visualizations, SQL queries, mapping, and machine learning workflow.
