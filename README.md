Weather ETL Pipeline (OpenWeather API)

                   Project Overview:
   This project demonstrates an end to end ETL (Extract Transform Load) pipeline using real time weather data from the OpenWeather API.
The goal is to simulate how data is collected from external APIs, processed, and stored for analysis in a structured format.

Tools Used:
Python
Pandas
Requests
Jupyter Notebook
OpenWeather API

ETL Process:

1. Extract

Weather data was collected in real time from the OpenWeather API for multiple cities:

Lagos
Abuja
Port Harcourt

Data fields extracted:

City name
Temperature
Humidity
Weather condition
Wind speed
Timestamp

2. Transform

The raw JSON data was cleaned and structured using Pandas:

Converted into a DataFrame
Renamed columns for clarity
Converted timestamp to readable datetime format

3. Load

The cleaned dataset was saved as:

CSV file for further analysis and reporting

               Key Insights:

Lagos recorded the highest temperature (25.62°C)
Abuja had the highest humidity (22.36%)
Average temperature across cities was 24.31°C
Weather conditions were mostly light rain and overcast

               Deliverables:

├── weather_etl_pipeline.ipynb
├── weather_etl_output.csv
