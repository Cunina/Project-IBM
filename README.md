# Project-IBM

This capstone project focuses on analysing SpaceX’s Falcon 9 rocket launches to predict whether the first stage will successfully land. Because first-stage reuse significantly reduces launch costs—from roughly $165M with other providers to SpaceX’s $62M—the ability to forecast reuse directly supports cost estimation. Acting as a data scientist for a fictional competitor, Space Y, I gather publicly available SpaceX launch data, explore factors influencing landing outcomes, and build machine learning models and dashboards to support launch pricing decisions.

# Project Structure

The project is organised into 8 sprints following a data science workflow from data collection to predictive modelling.

Sprint 1 Data Collection (API)  
Collect and parse SpaceX launch data from the REST API and structure it into a dataset.

Sprint 2 Data Collection (Web Scraping)  
Extract and clean launch records from Wikipedia tables to complement the dataset.

Sprint 3 Data Wrangling and Initial EDA  
Clean data, create the target variable (landing success), and explore basic patterns.

Sprint 4 EDA with SQL  
Query the dataset using SQL to analyse launch sites, payloads, and mission outcomes.

Sprint 5 EDA and Feature Engineering  
Visualise relationships between variables and prepare features for modelling.

Sprint 6 Geospatial Analysis  
Map launch sites and analyse geographical factors affecting launch outcomes.

Sprint 7 Interactive Dashboard  
Build a Plotly Dash application to explore launch success, payload, and booster performance.

Sprint 8 Machine Learning  
Train and evaluate classification models to predict landing success.

# Methodology

The project follows a standard data science process:
Data collection  
Data wrangling  
Exploratory data analysis  
Feature engineering  
Interactive analytics  
Predictive modelling  

# Notes

Folium maps do not render directly on GitHub because JavaScript execution is blocked. The notebook can be executed locally or viewed using NBViewer:
https://nbviewer.org/github/Cunina/Project-IBM/blob/main/6_lab-jupyter-launch-site-location-v2.ipynb
