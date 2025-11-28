# Pandas Tutorials

This directory contains comprehensive tutorials and examples for Pandas, a powerful data manipulation and analysis library for Python.

## What is Pandas?

Pandas is an open-source library built on top of NumPy that provides:
- Data structures for efficient data analysis (DataFrame and Series)
- Tools for reading and writing data in various formats
- Data cleaning and preprocessing capabilities
- Powerful data manipulation and transformation functions
- Time series analysis tools
- SQL integration for database operations

## Why Use Pandas?

Pandas significantly increases productivity when working with data by providing:
- Excel-like operations in Python
- Efficient handling of large datasets
- Powerful grouping and aggregation capabilities
- Easy data merging and joining
- Built-in time series functionality
- Seamless integration with other data science libraries

## Directory Structure

The tutorials are organized into numbered directories covering specific topics:

### Core Concepts
- **1_intro/**: Introduction to Pandas, its benefits, and basic usage
- **2_dataframe_basics/**: Understanding DataFrames, rows, columns, and basic operations
- **3_different_ways_of_creating_dataframe/**: Creating DataFrames from various sources

### Data I/O
- **4_read_write_to_excel/**: Reading and writing CSV and Excel files, including Flask integration examples

### Data Cleaning
- **5_handling_missing_data_fillna_dropna_interpolate/**: Handling missing data with fillna, dropna, and interpolate
- **6_handling_missing_data_replace/**: Using replace methods for data cleaning

### Data Manipulation
- **7_group_by/**: Grouping data and performing aggregations
- **8_concat/**: Concatenating DataFrames
- **9_merge/**: Merging and joining DataFrames (SQL-like joins)

### Advanced Operations
- **10_pivot/**: Creating pivot tables
- **11_melt/**: Melting/unpivoting data
- **12_stack/**: Stacking and unstacking data
- **13_crosstab/**: Creating cross-tabulations

### Time Series
- **14_ts_datetimeindex/**: Working with DateTimeIndex
- **15_ts_date_range/**: Creating date ranges
- **16_ts_holidays/**: Handling holidays and custom business days
- **17_ts_to_date_time/**: Converting to datetime
- **18_ts_period/**: Working with periods
- **19_ts_timezone/**: Timezone handling
- **20_shift_lag/**: Shifting and lagging time series data

### Integration
- **21_sql/**: SQL database integration with Pandas

## Getting Started

### Prerequisites

Install Pandas and required dependencies:

```bash
pip install pandas openpyxl xlrd
```

For SQL integration:
```bash
pip install sqlalchemy
```

For Flask examples:
```bash
pip install flask
```

### Running the Tutorials

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate through the directories in numerical order for a structured learning path

3. Each directory contains notebooks and example data files (CSV, Excel) for practice

## Key Topics Covered

### DataFrame Basics
- Creating and manipulating DataFrames
- Accessing rows and columns
- Statistical operations (mean, max, std, describe)
- Conditional selection
- Setting and using indices

### Data Input/Output
- Reading from CSV and Excel files
- Writing to CSV and Excel files
- Handling different file formats
- Web integration examples (Flask)

### Missing Data Handling
- Identifying missing values (isnull, notnull)
- Dropping missing data (dropna)
- Filling missing values (fillna)
- Interpolation methods
- Replacing values

### Data Selection
- Column selection (df['A'] or df.A)
- Row selection by index
- Label-based selection (loc)
- Position-based selection (iloc)
- Boolean indexing
- Conditional filtering

### Data Transformation
- Sorting data
- Filtering data
- Adding/removing columns
- Renaming columns
- Handling duplicates

### Data Combination
- Concatenating DataFrames
- Merging DataFrames (inner, outer, left, right joins)
- Joining operations
- Handling merge keys

### Grouping and Aggregation
- GroupBy operations
- Split-apply-combine pattern
- Multiple aggregations
- Grouping by multiple columns

### Reshaping Data
- Pivot tables
- Melting data (wide to long format)
- Stacking and unstacking
- Cross-tabulations

### Time Series Analysis
- DateTimeIndex creation and manipulation
- Date range generation
- Holiday calendars
- Period handling
- Timezone conversions
- Shifting and lagging data

### SQL Integration
- Reading from SQL databases
- Writing to SQL databases
- Querying databases with Pandas
- Connection string management

## Best Practices

1. **Import Convention**: Import Pandas as `pd`:
   ```python
   import pandas as pd
   ```

2. **Use Vectorized Operations**: Leverage Pandas' vectorized operations instead of loops

3. **Handle Missing Data Early**: Address missing values early in your data pipeline

4. **Use Appropriate Data Types**: Convert columns to appropriate dtypes (category, datetime) for efficiency

5. **Index Management**: Understand when to use index vs. reset_index

6. **Memory Efficiency**: Use chunking for large files and appropriate dtypes to save memory

## Data Files

Many tutorials include sample data files:
- CSV files (weather data, stock data, survey data)
- Excel files (multi-sheet workbooks)
- Example datasets for practice

## Additional Resources

- [Pandas Official Documentation](https://pandas.pydata.org/docs/)
- [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)
- [10 Minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Pandas API Reference](https://pandas.pydata.org/docs/reference/index.html)

## Next Steps

After completing the Pandas tutorials, proceed to the Matplotlib tutorials in the `4-matplotlib/` directory to learn how to visualize your data.

