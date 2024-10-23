# Python and SQL E-commerce Analysis Project

This project involves analyzing an eCommerce dataset using Python for data manipulation and SQL for querying a MySQL database. The analysis explores various aspects of the data, including customer locations, sales, order statistics, and payment trends.

## Project Structure

- **`Questions.txt`**: Contains questions or tasks that guided the analysis.
- **`csv_to_sql.py`**: A Python script for converting CSV files into SQL tables.
- **`dataset_link.txt`**: A link to the dataset used.
- **`python+sql_ecommerce.ipynb`**: A Jupyter notebook integrating Python and SQL for data analysis.

## Features

1. **Data Connection and Setup**: The project connects to a MySQL database named "ecommerce" using the `mysql.connector` library.

2. **Data Analysis with SQL Queries**:
   - Retrieving unique customer cities.
   - Counting orders for specific years (e.g., 2017).
   - Calculating total sales by product category.
   - Determining the percentage of orders paid in installments.

3. **Data Manipulation with Pandas**: SQL query results are loaded into Pandas DataFrames for further analysis and visualization.

## How to Run the Project

1. **Prerequisites**:
   - MySQL database with the required schema.
   - Python environment with libraries: `pandas`, `matplotlib`, `seaborn`, and `mysql-connector-python`.

2. **Steps**:
   - Set up the MySQL database and import the data using the `csv_to_sql.py` script.
   - Run the Jupyter notebook `python+sql_ecommerce.ipynb` to perform the analysis.

## License

This project is open-source and available under the [MIT License](LICENSE).


