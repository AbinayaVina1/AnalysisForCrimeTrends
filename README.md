# Visualization and Factor Analysis For Crime Trends

This project focuses on analyzing and predicting crime trends in Toronto using data from the Toronto Police Service's [Open Data Portal](https://data.torontopolice.on.ca/pages/open-data), specifically the "Major Crime Indicators Open Data" dataset. The project includes data preprocessing, exploratory data analysis, and predictive modeling techniques to understand and forecast crime patterns. This project also utilizes advanced machine learning techniques to help identify potential hotspots and trends, aiding law enforcement and urban planners.

## Project Structure

- **predicting_crime.py**: Contains code for preprocessing data, training machine learning models, and evaluating model performance.
- **visualize.py**: Contains code for data visualization, including charts and graphs to analyze crime trends over time.
- **Report.pdf**: Documentation explaining the objectives, methods, and results of the project.

## Data Source

The dataset used in this project was obtained from the [Toronto Police Service Public Safety Data Portal](https://data.torontopolice.on.ca/pages/open-data), specifically under the "Major Crime Indicators Open Data" section. This data includes information on various crime types and categories, providing a foundation for analyzing urban crime patterns.

## Results and Analysis

- The Random Forest model showed moderate accuracy, performing best on more common crime types such as assault.
- Encoding techniques (numeric and one-hot) were compared, with one-hot encoding slightly improving the prediction accuracy for certain crime types.
- Class weighting was explored to address imbalances in crime type occurrences but had limited impact on overall performance.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crime_prediction_analysis.git
