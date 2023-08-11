# Data processing for Big Data - Analysing Flight-delays Data
## Background
The flight-delays prediction dataset has become one popular dataset used by the aviation industry to predict the delay given the historical flight data. Learning from data can be beneficial for the companies, e.g. aviation industry, so that they can minimize the delay to improve customer satisfaction. The insight of the data can be obtained by conducting some steps, including pre-processing, visualization, and data modelling. In this project, we use Spark to visualize, and manipulate historical flight-delays data using Spark RDD and Spark SQL.

## Information on Dataset
The flight-delays and cancellation data was collected and published by the U.S. Department of Transportation’s (DOT) Bureau of Transportation Statistics. This data records the flights operated by large air carriers and tracks the on-time performance of domestic flights. This data
summarises various flight information such as the number of on-time, delayed, cancelled, and diverted flights published in DOT's monthly in 2015.
* A folder 'flights' containing 20 _flight*.csv_ files
* _airports.csv_

## Tasks
### Assignment 1:
_Focus on manipulating data using Spark RDD, Spark DataFrames and Spark SQL_
* **Part 1:** Work with RDDs in PySpark to implement specific queries related to flight delays data analysis.
* **Part 2:** Work with Dataframes in PySpark to implement specific queries related to flight delays data analysis.
* **Part 3:** Implement a query and compare three different approaches: RDD, DataFrame, and SparkSQL.

### Assignment 2 - Part A: Preprocessing, Visualization, Data Modelling
_Use Spark DataFrames, Spark SQL, MLlib/ML packages to do the pre-processing, visualization, and data modelling steps. The data modelling task aims to create the machine learning models utilizing MLlib/ML APIs to predict both departure and arrival delays from the testing data using classification tasks. Build models to predict the classes._
* **Part 1:** Data Loading, Cleaning, Labelling, and Exploration
* **Part 2:** Feature extraction and ML Training

### Assignment 3 - Part A: Real-time stream processing on big data
_Simulate the streaming data production using Kafka, then show some basic streaming classification to display the prediction accuracy and total number of flight records after consuming the data. Build a streaming application that integrates the machine learning model that can classify the flight-delays data stream._
* **Task 1:** Kafka Producer - Producing the streaming data, where you can use csv modules to read and publish the data to the Kafka stream.
* **Task 2:** Kafka Consumer - Consuming the streaming data using Kafka consumer, process and visualize the ingested data from Kafka.
* **Task 3:** Streaming application - Using Spark Structured Streaming together with Spark ML/SQL to process data streams.
