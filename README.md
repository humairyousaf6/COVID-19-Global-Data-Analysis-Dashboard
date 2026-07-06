# COVID-19 Global Data Analysis Dashboard

A data analysis project exploring global COVID-19 trends using the Our World in Data dataset, with visualizations and an interactive Streamlit dashboard.

## Dataset

Uses the Our World in Data COVID-19 dataset, loaded directly from its public URL. It includes daily records for each country covering cases, deaths, vaccinations, and related metrics.

## Steps Covered

- Loading the dataset directly from the Our World in Data URL
- Selecting relevant columns: date, location, total cases, new cases, total deaths, new deaths, and total vaccinations
- Converting the date column to datetime format
- Handling missing values using forward fill
- Aggregating data by date to analyze global trends
- Visualizing global total cases and deaths over time
- Visualizing global new cases and new deaths over time
- Visualizing global vaccination progress over time
- Building an interactive Streamlit dashboard that lets users select a country and view its case, death, and vaccination trends

## Requirements

- Python 3
- pandas
- numpy
- seaborn
- matplotlib
- streamlit

Install with:

```
pip install pandas numpy seaborn matplotlib streamlit
```

## Usage

### Notebook

1. Open the notebook in Jupyter or Google Colab.
2. Run all cells in order. The dataset is loaded automatically from the Our World in Data URL.

### Dashboard

1. Save the dashboard code to a file, for example `app.py`.
2. Run it with:

```
streamlit run app.py
```

3. Use the sidebar to select a country and view its COVID-19 statistics.

## Possible Improvements

- Add comparison view for multiple countries at once
- Include additional metrics such as testing rates or hospital admissions
- Add date range filtering in the dashboard
- Cache data loading to improve dashboard performance
- Deploy the dashboard using Streamlit Community Cloud
