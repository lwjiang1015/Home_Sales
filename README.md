# Home_Sales

## Overview of the Analysis

This project uses Spark create temporrary views, partition the home sales data, cache and uncache a temporary table, and verify that the table has been uncached. The primary requirement for using this project is the knowledge of SparkSQL. 

## Project Structure

-   `home_sales_colab.ipynb`: Jupyter Notebook containing the codings and providing the output/metrics.
-   `Images/`: Folder containing screenshots of:
    -   `the average price for a four-bedroom house sold in each year`.
    -   `the average price of a home with 3 bedrooms and 3 bathrooms per year built`.
    -   `the average price of a home with 3 bedrooms, 3 bathrooms, 2 floors, and is greater than or equal to 2000sqf per year built`. 
    -   `the average price of a home per view rating having a average home price greater or equal $350,000 with runtime`.
    -   `the average price of a home per view rating having a average home price greater or equal $350,000 with runtime from tempView`
    -  `the average price of a home per view rating having a average home price greater or equal $350,000 with runtime from parquet temporary table`

## To use the project

1.  Clone this repository to your local machine.
2.  Navigate to the cloned directory to check the content/directory.
3.  Open 'home_sales_colab.ipynb' from https://colab.research.google.com/notebooks/welcome.ipynb.
4.  Follow the steps to run the codes.

## References

- University of Adelaide. (2023). Module 22 contents in particular.
https://bootcampspot.instructure.com/courses/4781/pages/22-big-data?module_item_id=1163587
- The help from the instruction team, the Expert Learning Assistant are acknowledged as always.
