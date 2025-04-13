# AWS-Snowflake-PowerBI1
Project Overview:
This project focuses on performing data analysis on Indian seasonal agriculture data using a modern data pipeline powered by Amazon Web Services (AWS), Snowflake, and Microsoft Power BI. The dataset includes information about rainfall, temperature, humidity, and crop yield across various locations, seasons, and years.
The main goal was to ingest raw data from AWS S3 into Snowflake, perform data transformation and cleansing, and build interactive visualizations in Power BI to derive meaningful insights that can aid in agricultural planning and decision-making.

Tech Stack:
* Amazon S3 – Cloud object storage to store raw CSV data
* AWS IAM – To create secure access roles
* Snowflake – Cloud data warehouse for transformation and analysis
* Power BI Desktop – Visualization and dashboard building
* SQL – For data manipulation and transformation in Snowflake

Project Workflow:
AWS Setup
* Created an Amazon S3 Bucket and uploaded the data_season.csv dataset.
* Set up an IAM Role and updated trust policy for secure integration between AWS and Snowflake.
Snowflake Integration
* Created an Integration Object in Snowflake to connect with the AWS S3 bucket.
* Used Snowflake SQL scripts to:
    * Create a new database and table.
    * Load the CSV data from S3 into Snowflake.
    * Perform data transformation (e.g., adding new columns, updating values, modifying existing columns).
Power BI Reporting:
* Imported the cleaned and transformed data from Snowflake into Power BI Desktop.
* Created multiple visualizations to analyze key variables:
 Rainfall Analysis
 Temperature Analysis
 Humidity Analysis
 Yield Analysis

Key Insights:
* Identified seasonal trends in rainfall, temperature, and humidity.
* Mapped crop yield patterns across locations and years.
* Enabled interactive filtering for deeper insight across key agricultural parameters.

 Dataset:
* File Name: data_season.csv
* Source: Indian agricultural data
* Fields: Year, Season, Crop, Location, Rainfall, Temperature, Humidity, Yield

Learning Outcomes:
* Gained hands-on experience in integrating AWS S3 with Snowflake.
* Performed advanced SQL-based transformations in Snowflake.
* Leveraged Power BI for intuitive and dynamic data visualization.
* Understood the importance of cloud-based data pipelines in analytics.


