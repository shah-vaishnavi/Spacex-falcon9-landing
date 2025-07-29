SpaceX Falcon 9 Landing Prediction

A data science capstone project focused on predicting the success of Falcon 9 rocket landings using machine learning and dashboard analytics.

Table of Contents
	•	Project Overview
	• Directory Structure
	•	Problem Statement
	•	Methodology
	•	Tools & Technologies
	•	Exploratory Data Analysis
	• Interactive Mapping
	•	Dashboard with Plotly Dash
	•	Model Building & Evaluation
	•	Results
	•	Conclusion
	•	Appendix
	• Contact

Project Overview

SpaceX, founded by Elon Musk, is revolutionizing the space industry through reusable rocket technology. This project predicts the landing success of Falcon 9 rocket boosters, helping SpaceX improve mission planning and reduce operational costs. It includes data collection, EDA, machine learning modeling, and an interactive dashboard for insight discovery.

Problem Statement
  Predicting Falcon 9 booster landing success using historical mission data, to support decision-making in launch planning and reusability analysis.

Landing a booster depends on:
	•	Launch Site
	•	Orbit Type
	•	Payload Mass
	•	Booster Version


Methodology
	1.	Data Collection
	•	SpaceX API
	•	Kaggle datasets
	•	Web scraping (BeautifulSoup)
	2.	Data Wrangling
	•	Cleaned missing values
	•	Encoded categorical variables
	•	Created engineered features
	3.	EDA
	•	Visual insights using Seaborn & SQL
	•	Geo-mapping using Folium
	4.	Modeling
	•	Classification with Logistic Regression, Decision Tree, SVM, and KNN
	•	Hyperparameter tuning (Grid Search)
	5.	Dashboard
	•	Built with Plotly Dash for interactive filtering and visualization


Tools & Technologies
	•	Languages: Python, SQL
	•	Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Plotly, Folium
	•	Web Tools: Dash, BeautifulSoup, Requests
	•	Data Sources: SpaceX API, Wikipedia, Kaggle


Exploratory Data Analysis

  EDA included:
	  •	Success vs. Launch Site (catplot)
	  • Payload Mass vs. Landing Outcome (scatterplot)
	  •	Orbit Type vs. Success Rate (barplot)
	  •	Yearly Trends in Success Rate
	  •	SQL queries for grouping, filtering, aggregation

Key Insights:
	•	CCAFS SLC 40 and KSC LC 39A showed higher success rates
	•	Payload mass impacts landing success
	•	Missions after 2014 showed consistent improvements


Interactive Mapping

  Folium maps were used to:
	  •	Visualize global launch site locations
	  •	Show success/failure using color-coded markers
	  •	Display proximity to highways, railroads, and coastlines
	  •	Include popups for site info


Dashboard with Plotly Dash

  The interactive dashboard includes:
	  •	Dropdown Selector: Choose launch site
	  •	Slider: Filter by payload mass range
	  •	Pie Chart: Landing success rate per site
	  •	Scatter Plot: Payload vs. Landing Outcome
  
 
 Model Building & Evaluation

  Models Used:
	  •	Logistic Regression
	  •	Decision Tree Classifier (Best performing)
	  •	SVM
	  •	K-Nearest Neighbors

Evaluation:
	•	Accuracy, F1-Score, Confusion Matrix
	•	Grid Search for hyperparameter tuning

Best Model Accuracy: 0.875 (Decision Tree)


Results
	•	Most influential features: Launch Site, Orbit, Payload
	•	High-performing dashboard for data interaction
	•	Steady improvement in landing success over time
	•	Classification accuracy visualized via bar chart
	•	Confusion matrix for the best model included


Conclusion

  This project demonstrates an end-to-end machine learning pipeline from data extraction to model deployment with dashboard interaction. It validates the hypothesis that       launch characteristics significantly affect landing outcomes.


Appendix
	•	SQL Queries for filtering/grouping (launch site, payload, orbit, etc.)
	•	Confusion Matrices & Accuracy Charts
	•	Dash & Folium screenshots
	•	Data Source Links

  Ppt:[ds-capstone-template-coursera (1).pptx](https://github.com/user-attachments/files/21486266/ds-capstone-template-coursera.1.pptx)
