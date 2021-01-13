# Data Lake with AWS

## Introduction
A music streaming startup, Sparkify, has grown their user base and song database even more and want to move their data warehouse to a data lake. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

As their data engineer, you are tasked with building an ETL pipeline that extracts their data from S3, processes them using Spark, and loads the data back into S3 as a set of dimensional tables. This will allow their analytics team to continue finding insights in what songs their users are listening to.

## Project Description
In this project, I am applied what I've learned on Spark and data lakes to build an ETL pipeline for a data lake hosted on S3. To complete the project, I needed to load data from S3, process the data into analytics tables using Spark, and load them back into S3. I've deploy this Spark process on a cluster using AWS.

##Project Datasets
I've been working with two datasets that reside in S3. Here are the S3 links for each:

Song data: s3://udacity-dend/song_data
Log data: s3://udacity-dend/log_data

