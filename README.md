# Air Quality Data Cleaning and Preprocessing

## Project Overview

This project demonstrates data acquisition, exploration, cleaning, preprocessing, and visualization using the UCI Air Quality dataset.

The main objective is to identify and handle missing values, duplicate records, inconsistent data, and outliers to produce a cleaner dataset suitable for further analysis.

## Dataset

Dataset: UCI Air Quality Dataset

The dataset contains hourly air-quality measurements including carbon monoxide (CO), nitrogen oxides (NOx), nitrogen dioxide (NO2), benzene (C6H6), temperature, relative humidity, and absolute humidity.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* VS Code

## Data Cleaning Process

The following preprocessing steps were performed:

1. Loaded the UCI Air Quality dataset.
2. Explored the dataset structure and data types.
3. Identified `-200` values representing missing sensor measurements.
4. Converted `-200` values into missing values.
5. Removed the `NMHC(GT)` column because approximately 90% of its values were missing.
6. Filled remaining numerical missing values using the median.
7. Identified and removed duplicate records.
8. Detected outliers using the Interquartile Range (IQR) method.
9. Capped extreme values using IQR limits.
10. Generated visualizations for the cleaned data.
11. Saved the final cleaned dataset as `air_quality_cleaned.csv`.

## Visualizations

The project includes:

* Carbon Monoxide distribution
* Nitrogen Oxides distribution
* Temperature distribution
* Correlation matrix

## Project Files

| File | Description |
|---|---|
| `air_quality_cleaning.ipynb` | Complete Python analysis and cleaning process |
| `air_quality_cleaned.csv` | Final cleaned dataset |
| `AirQualityUCI.xlsx` | Original dataset |
| `AirQualityUCI.xls` | Original dataset format |

## Visualizations

### Carbon Monoxide Distribution

![CO Distribution](screenshots/co_distribution.png)

### Nitrogen Oxides Distribution

![NOx Distribution](screenshots/nox_distribution.png)

### Temperature Distribution

![Temperature Distribution](screenshots/temperature_distribution.png)

### Correlation Matrix

![Correlation Matrix](screenshots/correlation_matrix.png)

## Outcome

The project demonstrates a complete data-cleaning workflow from raw data acquisition to a cleaned dataset ready for further analysis or machine-learning applications.

## Author

Keerthana Dhandapani