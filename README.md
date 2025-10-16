# Apache Spark Tutorial with Python (PySpark)

This tutorial provides a comprehensive introduction to Apache Spark using Python.

## Prerequisites

Before running this tutorial, you need to install PySpark:

```bash
pip install pyspark
```

Or if you want to install additional tools:

```bash
pip install pyspark pandas numpy
```

## Files in this Tutorial

- **sample_data.csv** - Sample employee dataset with 15 records
- **spark_tutorial.py** - Complete tutorial covering Spark basics
- **README.md** - This file

## What You'll Learn

1. **Initializing Spark Session** - Setting up your Spark environment
2. **Loading Data** - Reading CSV files into Spark DataFrames
3. **Data Exploration** - Understanding your data structure and content
4. **Selection & Filtering** - Querying specific data
5. **Aggregation** - Computing statistics and summaries
6. **Adding Columns** - Creating derived data
7. **Sorting** - Ordering your results
8. **SQL Queries** - Using SQL syntax with Spark
9. **Saving Data** - Exporting results to CSV and Parquet
10. **Advanced Operations** - Window functions and joins

## Running the Tutorial

Simply execute the main script:

```bash
python spark_tutorial.py
```

The script will:
- Load the sample employee data
- Demonstrate various Spark operations
- Create output files with processed data
- Display results in your terminal

## Expected Output

The tutorial will create two output directories:
- `output_data/` - CSV format output
- `output_parquet/` - Parquet format output (more efficient)

## Sample Dataset

The tutorial uses an employee dataset with the following fields:
- employee_id
- name
- department (Engineering, Marketing, Sales, HR, Finance)
- salary
- join_date
- age

## Next Steps

After completing this tutorial, you can:
1. Modify the filtering and aggregation queries
2. Try loading your own CSV files
3. Experiment with more complex transformations
4. Learn about Spark MLlib for machine learning
5. Explore Spark Streaming for real-time data processing

## Additional Resources

- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)
- [Spark SQL Guide](https://spark.apache.org/docs/latest/sql-programming-guide.html)
- [Spark Tutorial](https://spark.apache.org/docs/latest/quick-start.html)

## Troubleshooting

If you encounter Java-related errors, ensure you have Java 8 or 11 installed:
```bash
java -version
```

If Spark is slow to start, it's normal on the first run as it initializes the JVM.
# learnspark
