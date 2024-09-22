
# Bike Sharing Dashboard

This project provides an interactive dashboard for visualizing bike sharing data. It displays trends related to bike rentals based on various factors such as time, weather, seasons, and user categories.

## Overview
The dashboard visualizes several aspects of bike sharing data, including:
- Total casual vs registered users over time
- Bike rentals based on months, hours, holidays, working days, seasons, weather conditions, and temperature categories
- Average bike rentals based on temperature categories

The dashboard is built using **Streamlit** and the visualizations are powered by **Matplotlib** and **Seaborn**.

## Features
- **Filter by date range:** Users can select a date range to filter the dataset and explore trends for specific periods.
- **Casual vs Registered Rentals:** A comparison between the total number of casual and registered users over the years.
- **Bike Rentals by Month and Hour:** Insights into rental patterns across different months and hours.
- **Impact of Holidays and Working Days:** Explore how rentals vary between holidays and working days.
- **Seasonal Trends:** Visualize rental numbers across different seasons.
- **Weather Conditions:** Understand the impact of different weather conditions on bike rentals.
- **Temperature Categories:** View average rentals based on categorized temperature ranges (cold, moderate, hot).

## Setup and Requirements
To run the project, ensure you have the following dependencies installed:
- pandas
- matplotlib
- seaborn
- streamlit

You can install these dependencies using:
```bash
pip install pandas matplotlib seaborn streamlit
```

## How to Run
1. Clone the repository or download the source code.
```bash
https://github.com/halimsajidi/Bike-Sharing-Analysis.git
```
2. Setup Environment
```bash
conda create --name main-ds python
conda activate main-ds
```
3. Install the required Python packages
```bash
cd Dashboard
```
```bash
pip install -r requirements.txt
```
4. Run the Streamlit app using:
```bash
streamlit run app.py
```
4. Open the link provided by Streamlit to access the dashboard in your web browser.

## Data
- `dataset_day.csv`: Contains the day-level data of bike rentals.
- `dataset_hour.csv`: Contains the hour-level data of bike rentals.

Ensure these datasets are placed in the correct file paths before running the app.

## Visualizations
The dashboard includes the following visualizations:
1. **Casual vs Registered Users Over Time**
2. **Bike Rentals by Month**
3. **Bike Rentals by Hour**
4. **Rentals on Holidays vs Working Days**
5. **Rentals by Season**
6. **Rentals by Weather Condition**
7. **Average Rentals by Temperature Category**

Each visualization is interactive and updates based on the date range selected by the user.

## Notes
- The year labels in the data have been replaced: `0` corresponds to 2011, and `1` corresponds to 2012.
- Temperature categories are divided into three groups: **Cold**, **Moderate**, and **Hot**.
