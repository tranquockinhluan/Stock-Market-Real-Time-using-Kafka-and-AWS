# Stock Market Real Time Using Kafka Project

## Introduction 
In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), AWS Glue, AWS Athena, Apache Kafka and SQL.

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Open Source: Apache Kafka
- Amazon Web Service (AWS):

1. AWS EC2 (most of environment install here)
2. AWS Glue Crawler (Craw Data)
3. AWS S3 (Catch Data)
4. AWS Athena (SQL Data)


## Dataset Used
You can use any dataset, it would be better if you have access to the real-time Stock Market API which generally paid

Here is the dataset i used:
https://github.com/conmeo111/Project1/blob/master/indexProcessed.csv

## Connect to EC2 from local computer
When you create instance on EC2, remember to create Key pair and download it

Make sure you are on the directory where Kay pair has downloaded

Run SSH client: 
From EC2> Instances> Instance Id> Connect to instance

Copy SSH client and run it, example:
  ```
  $ ssh -i "key-pair-name.pem" ec2-user@ec2-12-345-67-890.ap-region.compute.amazonaws.com
  ```


Now you can download and install things you need on this virtual computer, such as: Apache Kafka, Java Enviroment.





