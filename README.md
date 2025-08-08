Workspace and Lakehouse Setup:

First, a workspace was created within the environment to manage all resources and collaborate efficiently.

A Lakehouse was then established to store and process raw data, enabling data exploration and transformation. Seven datasets were uploaded into the Files section of the Lakehouse for further processing.

Data Transformation:

Using a Notebook environment, necessary data transformations were applied to the raw datasets.

The Silver Layer tables were created, representing cleansed and enriched data, by handling missing values, standardizing column names, and performing initial aggregations.

The Gold Layer tables were then developed by further enriching the Silver data with more business-specific insights, such as aggregating transactional data and creating more detailed, enriched dimensions for reporting.

Data Warehouse Creation:

A Data Warehouse was created to centralize and structure the transformed data for use in reporting and analytics. This provided a robust and optimized data storage solution that can handle both transactional and analytical workloads.

SQL Queries for Table Creation:

Using T-SQL queries, the Gold and Silver layer tables were created within the data warehouse. These tables are now ready for querying and integration into reporting solutions.

Reporting and Analysis:

The Gold and Silver layer tables are now available for use in reporting and analytical purposes, providing clean, enriched, and structured data for business intelligence and decision-making.
