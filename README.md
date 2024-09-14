This project includes final project of the IBM DS Education completed by me and the related presentation.


Project Overview
This project is a practical exercise I developed while pursuing the IBM Data Science Certificate. The goal is to analyze and predict SpaceX launch successes using various data science methodologies learned throughout the certification program. The project covers the full data science pipeline, including data collection, wrangling, exploratory analysis, interactive visualization, and machine learning model development.

Project Components

Data Collection
Data was gathered using web scraping and APIs. SpaceX launch data was retrieved via requests.get() and processed using BeautifulSoup for parsing HTML content.
Dynamic data was also collected from APIs to gather details on payloads, launch success, and orbit types.

Data Wrangling
Basic data cleaning techniques were employed, such as handling missing values and outliers.
HTML parsing was used to extract information like column names and launch titles.
Operations such as searching and filtering ensured data quality and consistency.

Exploratory Data Analysis (EDA)
Visualization techniques were applied to explore trends in launch success, payloads, and orbit types.
Scatter plots, line plots, box plots, and correlation heatmaps were created to explore relationships between variables such as launch sites and success rates.
SQL queries were used to answer specific analytical questions, such as total payload carried and filtering launch sites by success.

Interactive Visualizations
An interactive map was created using Folium to display launch sites and outcomes, marked with color-coded markers for success and failure.
Proximity markers were added to display distances from launch sites to nearby infrastructure (cities, railways, highways).

Dashboard with Plotly Dash
A Plotly Dash dashboard was created to allow users to interactively explore the data. Dropdowns and sliders were added to filter launch sites, payload mass, and success outcomes.
The dashboard was enhanced with callback functions to dynamically update the plots based on user selections.

Predictive Analysis
Several machine learning models were developed, including Logistic Regression, SVM, and Decision Trees.
Hyperparameter tuning was performed using GridSearchCV and RandomizedSearchCV to optimize the models.
Model performance was evaluated using accuracy metrics, confusion matrices, and classification reports.

Key Findings
Launch Site Success: Launch sites like KSC LC 39A and VAFB SLV 4E showed higher success rates, while CCAFS SLC 40 had varying success over time.
Payload Influence: Higher payload masses generally had higher success rates, particularly at CCAFS SLC 40.
Orbit Success Rates: Orbits such as LEO and SSO had higher success rates, while others like ES-L1 and HEO had lower success.

Tools and Libraries Used
Python for scripting and model development
Pandas and SQL for data manipulation and analysis
Seaborn, Matplotlib, Folium, and Plotly Dash for visualizations and interactive dashboards
Scikit-learn for machine learning model development and evaluation
BeautifulSoup and Requests for web scraping and data collection
