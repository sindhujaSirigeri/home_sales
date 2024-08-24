# Home Sales Analysis

## Overview

This project involved analyzing a dataset of home sales using PySpark to extract valuable insights about average home prices based on various criteria such as the number of bedrooms, bathrooms, square footage, and view ratings. The dataset was processed using various SparkSQL queries, and performance optimization techniques like caching and partitioning were implemented.

## Tools and Technologies Used

-   **PySpark**: Used for data processing and SQL-based querying.
-   **SparkSQL**: Utilized to run SQL queries on the dataset.
-   **Google Colab**: Environment where the code was executed.
-   **GitHub**: Repository for version control and project storage.
-   **CSV and Parquet**: Data formats used for input and partitioned output.

## Skills Learned

Throughout this project, I learned and applied the following skills:

-   **PySpark DataFrame Operations**: I gained proficiency in reading, transforming, and querying large datasets using PySpark DataFrames.
-   **SparkSQL**: I developed the ability to write complex SQL queries to derive insights from the dataset.
-   **Performance Optimization**: I learned how to optimize query performance through techniques like caching DataFrames and partitioning data.
-   **Data Caching and Partitioning**: I practiced caching tables to speed up repeated queries and partitioning data to enhance query efficiency when working with large datasets.
-   **Data Analysis**: I performed detailed data analysis to extract average home prices based on multiple criteria.
-   **Time Complexity Analysis**: I compared the runtimes of queries on cached vs. uncached data and on partitioned vs. non-partitioned data, deepening my understanding of computational efficiency.
-   **File Handling**: I worked with CSV and Parquet files, learning the benefits of different file formats in distributed computing environments.
-   **Collaboration and Version Control**: I practiced version control by uploading and managing the project on GitHub.

## Project Tasks

1.  **File Renaming**: The starter code file was renamed from `Home_Sales_starter_code.ipynb` to `Home_Sales.ipynb`.
2.  **Data Loading**: The home sales data (`home_sales_revised.csv`) was loaded into a PySpark DataFrame.
3.  **Temporary Table Creation**: A temporary table named `home_sales` was created from the DataFrame.
4.  **Data Analysis**:
    -   Average price of four-bedroom houses sold each year.
    -   Average price of homes with three bedrooms and three bathrooms for each year they were built.
    -   Average price of homes with specific features (three bedrooms, three bathrooms, two floors, ≥ 2,000 sqft).
    -   Average price of homes per view rating, filtered by an average price ≥ $350,000.
5.  **Caching**: The temporary table `home_sales` was cached to improve query performance.
6.  **Query Optimization**: The runtime of queries was compared before and after caching and partitioning the data.
7.  **Data Partitioning**: The dataset was partitioned by the `date_built` field and stored in Parquet format.
8.  **Verification**: Ensured that the caching was correctly applied and removed when no longer needed.
9.  **Final Upload**: The completed notebook was downloaded and uploaded to the GitHub repository.

## Conclusion

This project provided hands-on experience with PySpark and SparkSQL, focusing on data analysis and performance optimization in a distributed computing environment. The skills gained in this project are crucial for handling large datasets efficiently and deriving meaningful insights from them.# Home Sales Analysis

## Overview

This project involved analyzing a dataset of home sales using PySpark to extract valuable insights about average home prices based on various criteria such as the number of bedrooms, bathrooms, square footage, and view ratings. The dataset was processed using various SparkSQL queries, and performance optimization techniques like caching and partitioning were implemented.

## Tools and Technologies Used

-   **PySpark**: Used for data processing and SQL-based querying.
-   **SparkSQL**: Utilized to run SQL queries on the dataset.
-   **Google Colab**: Environment where the code was executed.
-   **GitHub**: Repository for version control and project storage.
-   **CSV and Parquet**: Data formats used for input and partitioned output.

## Skills Learned

Throughout this project, I learned and applied the following skills:

-   **PySpark DataFrame Operations**: I gained proficiency in reading, transforming, and querying large datasets using PySpark DataFrames.
-   **SparkSQL**: I developed the ability to write complex SQL queries to derive insights from the dataset.
-   **Performance Optimization**: I learned how to optimize query performance through techniques like caching DataFrames and partitioning data.
-   **Data Caching and Partitioning**: I practiced caching tables to speed up repeated queries and partitioning data to enhance query efficiency when working with large datasets.
-   **Data Analysis**: I performed detailed data analysis to extract average home prices based on multiple criteria.
-   **Time Complexity Analysis**: I compared the runtimes of queries on cached vs. uncached data and on partitioned vs. non-partitioned data, deepening my understanding of computational efficiency.
-   **File Handling**: I worked with CSV and Parquet files, learning the benefits of different file formats in distributed computing environments.
-   **Collaboration and Version Control**: I practiced version control by uploading and managing the project on GitHub.

## Project Tasks

1.  **File Renaming**: The starter code file was renamed from `Home_Sales_starter_code.ipynb` to `Home_Sales.ipynb`.
2.  **Data Loading**: The home sales data (`home_sales_revised.csv`) was loaded into a PySpark DataFrame.
3.  **Temporary Table Creation**: A temporary table named `home_sales` was created from the DataFrame.
4.  **Data Analysis**:
    -   Average price of four-bedroom houses sold each year.
    -   Average price of homes with three bedrooms and three bathrooms for each year they were built.
    -   Average price of homes with specific features (three bedrooms, three bathrooms, two floors, ≥ 2,000 sqft).
    -   Average price of homes per view rating, filtered by an average price ≥ $350,000.
5.  **Caching**: The temporary table `home_sales` was cached to improve query performance.
6.  **Query Optimization**: The runtime of queries was compared before and after caching and partitioning the data.
7.  **Data Partitioning**: The dataset was partitioned by the `date_built` field and stored in Parquet format.
8.  **Verification**: Ensured that the caching was correctly applied and removed when no longer needed.
9.  **Final Upload**: The completed notebook was downloaded and uploaded to the GitHub repository.

## Conclusion

This project provided hands-on experience with PySpark and SparkSQL, focusing on data analysis and performance optimization in a distributed computing environment. The skills gained in this project are crucial for handling large datasets efficiently and deriving meaningful insights from them.
