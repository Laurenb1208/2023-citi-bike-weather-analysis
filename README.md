# Weather vs. Citi Bike Usage in NYC (2023)

## Introduction
This project explores the relationship between weather conditions and Citi Bike usage in New York City. It aims to analyze how factors such as rain, temperature, and wind impact daily usage.

## File Structure
**Data:**  
  - `NYC_citibike_2023.csv`: Full NYC 2023 Citi Bike dataset
 [Download it here (Google Drive)](https://drive.google.com/file/d/1Z6TtwEiiS1gXGgsxzyYDBJkUAuh6GwNH/view?usp=sharing)  
  *(Note: This file is over GitHub's 100MB file size limit and is hosted externally)* 
- [`final_weather_data_scraped.csv`](Data/final_weather_data_scraped.csv): Scraped and cleaned 2023 NYC weather data  
- [`final_merged_data.csv`](Data/final_merged_data.csv): Final merged dataset used for analysis

**Notebooks:**  
- [`Scrapped_Clean_NYC_Weather_2023.ipynb`](Notebooks/Scrapped_Clean_NYC_Weather_2023.ipynb): Scrapes and cleans NYC weather data from 2023
- [`Merging and cleaning Citi Bike data.ipynb`](Notebooks/Merging%20and%20cleaning%20Citi%20Bike%20data.ipynb): Aggregates Citi Bike trip data and merges it with the cleaned weather data
- [`Final Analysis.ipynb`](Notebooks/Final%20Analysis.ipynb): Performs the final analysis, including visualizations, hypothesis testing, machine learning models and forecasting
  
**Other Files:**  
- `README.md`: Overview of the project  
- [`data_dictionary.md`](data_dictionary.md): Descriptions of key fields in the merged dataset
- [`Final Report.pdf`](Final%20Report.pdf): Full project report detailing the project's motivation, methodology, and key findings
  
## Dataset Sources
- Citi Bike data: [NYC Citi Bike Ride Share System Data 2023 on Kaggle](https://www.kaggle.com/datasets/hassanabsar/nyc-citi-bike-ride-share-system-data-2023?resource=download)
- Weather data: [New York City Weather History on Weather Underground](https://www.wunderground.com/history/daily/us/ny/new-york-city/KLGA/date/2023-1-1)
