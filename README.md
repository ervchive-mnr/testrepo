Project Overview
This repository contains a full-stack data science project aimed at predicting the successful landing of the SpaceX Falcon 9 first-stage booster. SpaceX advertises Falcon 9 rocket launches at a significantly lower cost than competitors. This cost advantage is primarily due to the reusability of the first stage. Therefore, determining whether the first stage will land successfully is crucial for estimating launch costs and informing competitive bidding strategies.

Methodology and Workflow
This project encompasses an end-to-end data science pipeline, managing the full lifecycle of data from extraction to predictive modeling:

Data Collection: Automated data extraction using the SpaceX REST API and web scraping technical specifications from Wikipedia using BeautifulSoup.

Data Engineering: Cleaned and transformed raw JSON and HTML data using Pandas, performing feature engineering and handling missing values.

Exploratory Data Analysis (EDA): Conducted multidimensional analysis using SQL (SQLite) and data visualization libraries (Matplotlib, Seaborn) to uncover statistical correlations between launch sites, payload mass, orbit trajectories, and mission success.

Interactive Visual Analytics: * Developed interactive geospatial maps using Folium to analyze launch site proximity to coastlines, highways, and cities.

Built a real-time web dashboard using Plotly Dash to monitor performance metrics dynamically.

Predictive Modeling: Built a suite of machine learning classification models (Logistic Regression, SVM, KNN, Decision Tree) optimized through cross-validation and GridSearchCV hyperparameter tuning to accurately predict booster reusability.

Technologies and Tools
Languages: Python, SQL

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn, Folium, Plotly Dash

Machine Learning: Scikit-Learn

Data Extraction: Requests (REST API), BeautifulSoup

Repository Structure
jupyter-labs-spacex-data-collection-api.ipynb: Data collection via SpaceX API.

jupyter-labs-webscraping.ipynb: Web scraping Falcon 9 launch records from Wikipedia.

jupyter-labs-eda-sql-coursera_sqllite.ipynb: Exploratory Data Analysis using SQL queries.

edadataviz.ipynb: Visual EDA finding correlations between variables.

lab_jupyter_launch_site_location.ipynb: Geospatial analysis of launch sites using Folium.

spacex-dash-app.py: Interactive Plotly Dash web application code.

SpaceX_Machine_Learning_Prediction_Part_5.ipynb: Machine learning pipeline, hyperparameter tuning, and model evaluation.

Author
Erv Mainar BS Mathematics, Polytechnic University of the Philippines

Completed as the Capstone Project for the IBM Data Science Professional Certificate.
