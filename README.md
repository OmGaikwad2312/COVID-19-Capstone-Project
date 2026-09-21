COVID-19 Data Analysis and Forecasting

A Python capstone project that explores global COVID-19 data, compares countries, maps active cases worldwide, and forecasts confirmed cases for the next 7 days.

Dataset
File: covid_19_clean_complete.csv
Size: 49,068 rows and 10 columns
Columns: Province/State, Country/Region, Lat, Long, Date, Confirmed, Deaths, Recovered, Active, WHO Region
Period: daily records up to 27 July 2020

What This Project Does
Data preparation: loads the data, checks its structure with info() and shape, renames columns (Province/State to State, Country/Region to Country), and converts dates to datetime format.
Global trends: aggregates confirmed and recovered cases by date and plots them as line charts.
Country rankings: finds the top 10 countries by recovered cases and by deaths, shown as bar charts.
Country comparison: compares recovered cases and deaths for the US, India, and China using point plots.
Forecasting: uses Prophet to predict global confirmed cases 7 days ahead.
World map: builds an interactive Plotly choropleth map of active cases by country.

Tools and Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
Plotly
Prophet
Google Colab / Jupyter Notebook

How to Run
Download COVID19_CapstoneProject.ipynb and the dataset covid_19_clean_complete.csv.
Open the notebook in Google Colab or Jupyter Notebook.
Upload the CSV file and update the file path in the first data-loading cell (the notebook currently reads from /content/).
Install Prophet if needed: pip install prophet
Run all cells in order.

Author
Om Gaikwad LinkedIn | GitHub
