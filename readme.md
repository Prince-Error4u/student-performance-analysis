# Student Performance Analysis

## Project Overview

This project explores student performance in mathematics, reading, and writing using SQL Server and Python. The goal is to identify patterns in exam scores and examine how performance varies across student groups and educational factors.

## Objectives

- Explore and validate the student performance dataset.
- Use SQL to filter, group, and summarize data.
- Use Python, pandas, and NumPy for data analysis.
- Visualize score distributions and relationships using Matplotlib and Seaborn.
- Communicate findings and limitations clearly.

## Tools and Technologies

- **SQL Server:** Data querying, aggregation, and grouping.
- **Python:** Analysis workflow.
- **Pandas:** Data manipulation and descriptive statistics.
- **NumPy:** Numerical calculations.
- **Matplotlib:** Charts and plots.
- **Seaborn:** Statistical visualizations.
- **Jupyter Notebook:** Interactive analysis.

## Dataset

The dataset contains student demographic and educational attributes, including:

- Gender
- Race/ethnicity group
- Parental level of education
- Lunch type
- Test preparation course status
- Math, reading, and writing scores

The analysis uses the dataset imported into SQL Server. See the original dataset source and its license before redistributing the data.

## Project Workflow

1. Imported the CSV dataset into SQL Server.
2. Explored records, columns, and data quality.
3. Queried and aggregated data using SQL.
4. Loaded query results into pandas.
5. Calculated descriptive statistics using pandas and NumPy.
6. Explored score distributions and correlations.
7. Compared average scores across selected categories.
8. Documented findings and limitations.

## Research Questions

- Which subject has the highest average score?
- How do scores differ by test preparation status?
- How are math, reading, and writing scores correlated?
- How do score patterns vary by gender?
- How are scores associated with parental education and lunch type?
- Are there potential outliers in the score distributions?

## Key Findings

*Replace this section with conclusions supported by the actual results from the notebook.*

- **Overall performance:** [Insert your finding.]
- **Test preparation:** [Insert your finding.]
- **Subject correlations:** [Insert your finding.]
- **Group comparisons:** [Insert your finding.]
- **Data quality:** [Insert your finding.]

## Limitations

This is an observational dataset. Differences between groups do not establish causation. The available variables do not capture every factor that may influence student performance. Potential outliers require investigation and should not automatically be removed.

## How to Run

1. Clone or download this repository.
2. Install Python and the required libraries.
3. Open `student.ipynb` in VS Code or Jupyter.
4. Configure a connection to your own SQL Server instance and database.
5. Import the dataset into the expected SQL table.
6. Update any local file paths and connection settings.
7. Run the notebook cells in order.

Install the Python libraries with:

```bash
python -m pip install pandas numpy matplotlib seaborn pyodbc sqlalchemy jupyter
```

## Skills Demonstrated

SQL querying, data validation, data cleaning, exploratory data analysis, descriptive statistics, data visualization, Python–SQL integration, and analytical communication.