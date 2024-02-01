# Divvy Bikes Data Analysis

## Overview

This project involves the analysis of Divvy bike-sharing data using Python. The primary goal is to explore ridership patterns, compare member and casual users, and visualize key insights.

## Project Structure

The project is organized into the following steps:

1. **Data Collection**
   - Divvy Trips datasets for Q1 2019 and Q1 2020 are loaded using Pandas.

2. **Data Wrangling**
   - Columns are renamed to ensure consistency.
   - Dataframes are stacked to create a unified dataset.
   - Unnecessary fields are removed.

3. **Data Cleaning and Preparation**
   - Labels in the "member_casual" column are consolidated.
   - Additional columns for date, month, day, year, day_of_week, and ride_length are added.
   - "Bad" data (e.g., negative ride lengths) is removed.

4. **Descriptive Analysis**
   - Descriptive statistics are calculated for ride lengths.
   - Comparison between member and casual users is conducted.
   - Average ride times by day and user type are analyzed.

5. **Data Visualization**
   - Bar charts are created to visualize the number of rides and average duration by day and user type.

6. **Export Summary File**
   - A CSV file containing average ride lengths is generated for further analysis.

## Instructions

### Prerequisites
- Ensure you have Python installed on your machine.
- Install the required libraries using: `pip install pandas numpy matplotlib seaborn`.

### Running the Code
1. Clone the repository: `git clone https://github.com/your-username/divvy-bikes-analysis.git`
2. Navigate to the project directory: `cd divvy-bikes-analysis`
3. Run the Jupyter Notebook: `jupyter notebook`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
