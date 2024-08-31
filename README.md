# IPL Matches Analysis with Apache Spark on Databricks
This project involves analyzing IPL matches data using Apache Spark within a Databricks environment. The datasets are imported from an AWS S3 bucket, and various operations are performed to extract insights from the data.

## Project Overview
This project demonstrates how to:
* Import datasets from an AWS S3 bucket into Databricks.
* Perform data processing and analysis using Apache Spark.
* Explore and analyze IPL match data to extract meaningful insights.
  
## Datasets
The datasets used in this project include:
1. Ball_By_Ball.csv - Contains ball-by-ball details of each match.
2. Match.csv - Contains information about each IPL match.
3. Player.csv - Contains details of players.
4. Player_match.csv - Contains performance details of players in each match.
5. Team.csv - Contains details of IPL teams.

## Notebook Details
The Databricks notebook in this repository performs the following tasks:
* Data Ingestion: Loads the IPL datasets from the S3 bucket.
* Data Cleaning: Cleans and preprocesses the data for analysis.
* Data Analysis: Performs various analyses, such as Top scoring batsman, Dismissal types, and toss_impact.

## How to Run
To run this project:
1. Clone this repository to your local machine.
2. Upload the datasets to an AWS S3 bucket.
3. Set up a Databricks environment and connect it to your S3 bucket.
4. Import the Databricks notebook into your Databricks workspace.
5. Run the notebook to perform the analysis.

## Prerequisites
1. Databricks Account: You need a Databricks account to run the notebook.
2. AWS S3 Bucket: Store the datasets in an S3 bucket accessible to your Databricks environment.
3. Apache Spark: The analysis is done using Apache Spark, which is natively supported in Databricks.

## Files in the Repository
* IPL_Matches_Analysis.ipynb - The main Databricks notebook for the project.
* IPL_Matches_Analysis.zip - This zip file contains:
  1. Ball_By_Ball.csv - Dataset containing ball-by-ball details.
  2. Match.csv - Dataset containing match details.
  3. Player.csv - Dataset containing player details.
  4. Player_match.csv - Dataset containing player performance details.
  5. Team.csv - Dataset containing team details.

## Acknowledgments
The IPL datasets used in this project are publicly available and were sourced from [data.world](https://data.world/raghu543/ipl-data-till-2017/).
