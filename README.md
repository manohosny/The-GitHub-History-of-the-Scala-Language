# README for Pull Request Analysis Project

## Overview

This project provides an analysis of pull requests using data from CSV files. The analysis includes:

- Merging and preprocessing data.
- Visualizing the number of pull requests over time.
- Identifying the top developers for specific files.
- Analyzing pull requests by specific developers.

## Dependencies

- Python 3.x
- pandas
- matplotlib

## How to Run

1. Ensure you have the required dependencies installed.
2. Place the following datasets in a folder named `datasets`:
    - `pulls_2011-2013.csv`
    - `pulls_2014-2018.csv`
    - `pull_files.csv`
3. Run the provided script.

## Project Structure

The script performs the following operations:

1. **Data Loading**: Loads data from CSV files.
2. **Data Preprocessing**: Merges datasets, appends data, and converts date columns.
3. **Visualization**: Plots the number of pull requests over time and histograms of pull requests by user.
4. **Analysis**:
    - Identifies the last 10 pull requests.
    - Joins datasets to identify unique files.
    - Identifies pull requests that changed a specific file.
    - Counts the number of changes made by each developer.
    - Identifies the top 3 developers for a specific file.
    - Finds the users of the last 10 most recent pull requests.
    - Analyzes pull requests by specific developers for a specific file.

## Datasets

**Note**: The datasets are not provided in this repository. Ensure you have the datasets mentioned above in the `datasets` folder.

- `pulls_2011-2013.csv`: Contains pull request data from 2011 to 2013.
- `pulls_2014-2018.csv`: Contains pull request data from 2014 to 2018.
- `pull_files.csv`: Contains information about the files involved in each pull request.

## Contribution

Feel free to contribute to this project by providing additional analysis or visualizations. Ensure you maintain the structure and clarity of the code.

## License

This project is open-source and available to everyone. Please ensure you provide proper attribution if you use or modify the code.
