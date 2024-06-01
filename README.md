### Home Sales Analysis with SparkSQL

#### Overview:
In this project, we utilize SparkSQL to analyze home sales data and derive key metrics. We perform various operations such as creating temporary views, partitioning data, caching and uncaching temporary tables, and evaluating query runtimes.

#### Instructions:

1. **Set Up Environment:**
   - Clone the repository "Home_Sales" to your local machine.
   - Ensure PySpark is installed and configured.

2. **Import Libraries:**
   - Import necessary PySpark SQL functions.

3. **Read Data:**
   - Read the provided home_sales_revised.csv data into a Spark DataFrame.

4. **Create Temporary Table:**
   - Create a temporary table called `home_sales` from the DataFrame.

5. **Perform SparkSQL Queries:**
   - Answer the following questions using SparkSQL:
     - Average price for a four-bedroom house sold for each year.
     - Average price of homes for each year built, with three bedrooms and three bathrooms.
     - Average price of homes for each year built, with specific criteria.
     - Average price of homes per "view" rating with average price greater than or equal to $350,000.

6. **Caching Data:**
   - Cache the `home_sales` temporary table.
   - Check if the temporary table is cached.

7. **Query Runtime Comparison:**
   - Run the query from step 5 using cached data and determine runtime. Compare with uncached runtime.

8. **Partition Data:**
   - Partition the formatted parquet home sales data by the "date_built" field.
   - Create a temporary table for the partitioned parquet data.

9. **Query Runtime Comparison (Parquet Data):**
   - Run the query from step 5 using partitioned parquet data and determine runtime. Compare with previous runtimes.

10. **Uncache Data:**
    - Uncache the `home_sales` temporary table.
    - Verify that the temporary table is uncached using PySpark.

#### Resources:
- Documentation: [Apache SparkSQL](https://spark.apache.org/docs/latest/sql-programming-guide.html)
- Stack Overflow: [SparkSQL Questions](https://stackoverflow.com/questions/tagged/spark-sql)
- Previous Assignments: Refer to previous project repositories for insights and examples.

---
