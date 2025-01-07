
# International Students in Canada (2015-2023) Analysis and Forecast (2024-2030)

## Project Description
This project analyzes the trends of international students in Canada from 2015 to 2023, with predictions for the years 2024 to 2030. The analysis utilizes data on student demographics, provinces, and study levels, and provides insights into how these trends have evolved over time. The project also includes forecasting using historical data to predict future trends and visualize these projections.

### Key Steps:
1. **Data Sources**: 
    The following datasets are used in the analysis:
    - International Students in Canada: A dataset containing the number of international students from different countries in Canada for the years 2015 to 2023.
    - International Students by Province: A dataset containing data about the number of international students across different provinces and territories in Canada, segmented by gender.
    - International Students by Study Level: A dataset detailing the distribution of international students in Canada by study level (e.g., undergraduate, graduate) over the years 2015-2023.
    
2. **Data Cleaning and Preprocessing**: 
   - Handling missing values, converting data types, and ensuring all columns are correctly formatted for analysis.
   - Renaming columns for consistency and readability.

3. **Exploratory Data Analysis (EDA)**:
   - Generating visualizations to identify trends in international student enrollment.
   - Analyzing the impact of the COVID-19 pandemic on student numbers in 2020.
   - Identifying the top countries and provinces with the highest number of international students.

4. **Forecasting**:
   - Using time series analysis and simple linear regression to predict future trends (2024-2030).
   - Implementing Monte Carlo simulations to predict possible student populations for future years.

5. **Data Export**: 
   - The processed data is exported in CSV format for further analysis or reporting.

### Use Cases:
- **Trend Analysis**: Examine how the number of international students has evolved over the years.
- **Forecasting**: Predict future international student trends in Canada.
- **Provincial Distribution**: Understand how international students are distributed across different provinces and territories.
- **Gender and Study Level Analysis**: Analyze gender distribution and trends in study levels (undergraduate vs graduate).

## Features
- Web scraping of international student data by country, province, and study level.
- Data cleaning, processing, and visualization.
- Forecasting future trends using simple linear regression and Monte Carlo simulations.
- Data exported in CSV format for further analysis.

## Technologies Used

The following technologies were utilized in this project:

## 1. **Python**
## 2. **Pandas**
## 3. **Matplotlib & Seaborn**
## 4. **NumPy**
## 5. **Jupyter Notebook**
## 6. **CSV**
## 7. **GitHub**

## Installation
To run the project, you need to install the required libraries. You can install them using pip:

```bash
pip install pandas matplotlib seaborn numpy jupyter
```

## Usage

1. Clone the repository or download the notebook.
2. Open the notebook in a Jupyter environment.
3. Execute the code cells to:
   - Install dependencies
   - Import necessary libraries
   - Analyze international student trends from 2015 to 2023
   - Generate predictions for 2024-2030
4. The results will be saved in CSV format for further analysis.

### Sample Output (CSV Format):

| Country/Territory | 2015 | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 | 2023 | Total |
|-------------------|------|------|------|------|------|------|------|------|------|-------|
| Afghanistan       | 95   | 115  | 95   | 80   | 95   | 90   | 80   | 170  | 140  | 770   |
| Albania           | 115  | 165  | 185  | 245  | 375  | 250  | 305  | 345  | 545  | 2385  |
| Algeria           | 1060 | 845  | 1020 | 1490 | 2690 | 2170 | 3165 | 5360 | 7180 | 14700 |
| ...               | ...  | ...  | ...  | ...  | ...  | ...  | ...  | ...  | ...  | ...   |

## Project Structure

```
International-Students-Canada-Analysis/
│
├── International_Students_in_Canada_Analysis.ipynb  # Jupyter notebook with the analysis and forecasting code
├── international_students_data.csv                   # The CSV file with the processed data
├── README.md                                          # Project documentation
└── requirements.txt                                   # List of required Python packages
```

## Contributing

Feel free to fork the repository, create an issue, or submit a pull request. Contributions are welcome!
