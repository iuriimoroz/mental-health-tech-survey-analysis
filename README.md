# Mental Health in Tech Survey Analysis

## Project Overview
This project analyzes mental health trends in tech workplaces using the [OSMI Mental Health in Tech Survey](https://www.kaggle.com/osmi/mental-health-in-tech-survey) dataset. The analysis explores relationships between company support structures and employee mental health outcomes through data visualization and statistical analysis.

## Key Insights
1. **Age Distribution:** Employees seeking mental health treatment tend to be slightly older (median age 32) compared to the non-treatment group (median age 31).
2. **Company Benefits Impact:** Companies offering mental health benefits have 32.12% higher treatment rates among employees.
3. **Work Impact:** 48.37% of respondents report that mental health issues sometimes or often interfere with their work.

## Data Preparation & Cleaning
- Selected relevant columns for analysis
- Cleaned age outliers (limited to range 18-80)
- Simplified gender categories
- Handled missing values in work interference data

## Visualizations
The project includes three main visualizations:
1. **Age Distribution by Treatment Status:** Scatter plot showing the age distribution of employees who have and haven't sought mental health treatment.
2. **Mental Health Benefits vs Treatment Rates:** Bar chart comparing treatment rates between companies with and without mental health benefits.
3. **Work Interference Distribution:** Bar chart showing how frequently mental health issues interfere with work performance.

## Technologies Used
- **Python:** Data processing and analysis
- **Pandas & NumPy:** Data manipulation and numerical operations
- **Bokeh:** Interactive data visualization

## How to Run
1. Ensure you have Python and the required libraries installed:
   ```
   pip install pandas numpy bokeh
   ```
2. Download the dataset from [Kaggle](https://www.kaggle.com/osmi/mental-health-in-tech-survey) and save as `survey.csv` in the project directory
3. Run the Jupyter notebook:
   ```
   jupyter notebook
   ```

## Future Work
Potential areas for expanding this analysis:
- Incorporating geographic data to analyze regional differences
- Time series analysis if historical data becomes available
- Machine learning models to predict likelihood of mental health issues based on workplace factors

## License
This project uses publicly available data from OSMI. Please refer to their licensing terms for data usage.

## Acknowledgments
- [Open Sourcing Mental Illness (OSMI)](https://osmihelp.org/) for providing the survey data
- Kaggle for hosting the dataset
