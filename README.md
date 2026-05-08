# IBM_Capstone_spaceY
## Editing the file 

This is mark down file in repository.


This repository contains my final IBM Applied Data Science Capstone project. The objective is to predict whether the SpaceX Falcon 9 first stage will land successfully using historical launch data.

Successful first-stage landing allows SpaceX to reuse boosters and reduce launch costs. A competitor can use a landing-success prediction model to estimate launch cost and support bidding decisions.

Business Problem
The project is based on a fictional business scenario in which a competing space company wants to estimate the likelihood of a successful Falcon 9 first-stage landing. Since booster recovery can significantly affect launch cost, predicting landing success can support cost estimation and competitive bidding decisions.

Data Sources
SpaceX REST API
Wikipedia Falcon 9 / Falcon Heavy launch records
Cleaned datasets generated during the IBM capstone labs
Dashboard and geospatial datasets provided in the IBM lab environment
Project Workflow
Data collection using the SpaceX API
Web scraping from Wikipedia
Data wrangling and creation of the Class target variable
Exploratory data analysis with SQL
Exploratory data analysis with visualization
Interactive launch-site mapping with Folium
Interactive dashboard with Plotly Dash
Machine learning classification for landing prediction
Final presentation of results
Repository Structure
notebooks/ - Solved Jupyter notebooks for each capstone lab
dashboard/ - Plotly Dash dashboard notebook
images/ - Dashboard screenshots and visual assets
presentation/ - Final PowerPoint and PDF presentation
data/ - Generated CSV files used during the capstone labs
Main Results
KSC LC-39A had the largest number of successful launches in the dashboard analysis.
KSC LC-39A also had the highest launch success rate.
Payloads around 3,000-4,000 kg showed the highest success-rate band in the dashboard dataset.
Booster category B5 showed the highest observed success rate.
Classification models compared included Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors.
All four classification models achieved the same test accuracy of approximately 83.3%.
Since the models tied on test accuracy, cross-validation accuracy was used as an additional comparison metric.
The Decision Tree model achieved the highest cross-validation accuracy at approximately 87.7%.
Tools and Libraries
Python
Pandas
NumPy
SQLite / SQL
Matplotlib
Seaborn
Folium
Plotly Dash
Scikit-learn
Jupyter Notebook
GitHub
Final Deliverables
Final presentation PDF
Final presentation PowerPoint
Solved Jupyter notebooks
Generated CSV datasets
Dash dashboard screenshots
Dash application file/notebook
Folium map output
GitHub repository URL for Coursera submission
Author
Sai Bhavya 


