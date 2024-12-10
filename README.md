#Flight Data Analysis with MapReduce#

This project performs efficient flight data analysis using the MapReduce programming model. It processes large datasets of flight information to extract meaningful insights, such as the most popular routes, flight delays, and airline performance.

#Features#
Scalable Data Processing: Designed to handle large-scale flight datasets using Hadoop's MapReduce framework.
Customizable Analysis: Includes mappers and reducers tailored for key metrics like delays, popular routes, and airline performance.
Comprehensive Results: Summarizes insights with detailed counts, averages, and trends for actionable analytics.

##Getting Started##
Prerequisites
Hadoop: Installed and configured.
Java Development Kit (JDK): Required for compiling Java files.
Flight Dataset: A CSV file with columns such as flight number, airline, origin, destination, delay, etc.

##Files in the Repository##
workflow.xml: Defines the Hadoop workflow for automating the MapReduce job.

Specifies the sequence of tasks and dependencies for the job execution.
Located in the config/ directory.
job.properties: Contains configuration properties for the Hadoop job.

Configures input and output paths, job settings, and parameters for the MapReduce job.
Used with workflow.xml.
FlightDataAnalysis.java: The core MapReduce implementation for flight data analysis.

Contains the Mapper, Reducer, and Driver classes.
Performs tasks like processing flight routes and calculating delays.

##Usage
Running the Workflow
Compile the Java code:
Place the workflow.xml and job.properties files in the appropriate directory in HDFS:
Execute the workflow using Oozie:
Check the output in HDFS

##Example Insights
Most Popular Routes: Identify top origin-destination pairs.
Average Delays: Determine airlines with the highest and lowest average delays.
Performance Metrics: Gain insights into airline performance based on flight data trends.

