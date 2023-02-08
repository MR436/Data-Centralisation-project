# Data-Centralisation-project

Multinational Data Centralisation project, a comprehensive project aimed at transforming and analysing large datasets from multiple data sources. Utilising the power of Pandas, the project  clean the data, and produce a STAR based database schema for optimised data storage and access. Builds complex SQL-based data queries, allowing  to extract valuable insights and make informed decisions. This project provided the experience of building a real-life complete data solution, from data acquisition to analysis, all in one place. 

# Milestone 1
Developed a system that to extract and clean data.   
Three classes were initialised to manage the different acspects of data extraction and cleaning. 

Step 1: A new Python script named data_extraction.py and within it, create a class named DataExtractor. This class will work as a utility class, which contain  methods that help extract data. These methods extracts retail sales data from five different data sources; 
  PDF documents
  An AWS RDS database
  RESTful API
  JSON 
  CSV files

Step 2: Another script named database_utils.py and within it, created a class DatabaseConnector which  used to connect with and upload data to the database.

Step 3:Finally,  a script named data_cleaning.py this script  contain a class DataCleaning with methods to clean data from each of the data sources.


