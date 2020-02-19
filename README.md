# practice-with-hive

**Group members:**  
- Farheen Mohammad 
- Azhar Alali 
- Manasa Ginjupalli


## What is Hive? 
Apache Hive is an open source, data warehousing tool that is built on top of Hadoop system to handle its unstructured, semi structured data.

## What is Hadoop? 
Hadoop is an open-source framework to store and process Big Data in a distributed environment. It contains two modules, one is MapReduce and another is Hadoop Distributed File System (HDFS).



MapReduce: It is a parallel programming model for processing large amounts of structured, semi-structured, and unstructured data on large clusters of commodity hardware.

HDFS:Hadoop Distributed File System is a part of Hadoop framework, used to store and process the datasets. It provides a fault-tolerant file system to run on commodity hardware.

The Hadoop ecosystem contains different sub-projects (tools) such as Sqoop, Pig, and Hive that are used to help Hadoop modules.

Sqoop: It is used to import and export data to and from between HDFS and RDBMS.

Pig: It is a procedural language platform used to develop a script for MapReduce operations.

Hive: It is a platform used to develop SQL type scripts to do MapReduce operations.


## Features of Hive
* Stores schema in a database and processed data into HDFS.
* Designed for OLAP.
* Provides SQL type language for querying called HiveQL or HQL.
* It is familiar, fast, scalable, and extensible.

## How Does Hive workk? 
Apache Hive translates the input program written in the HiveQL (SQL-like) language to one or more Java MapReduce, Tez, or Spark jobs. (All of these execution engines can run in Hadoop YARN.) Then Apache Hive organizes the data into tables for the Hadoop Distributed File System HDFS) and runs the jobs on a cluster to produce an answer.
## Datatypes
- Column Types
- Literals 
- Null Values 
- Complex Types
## Creating Database
  Create Database is a statement used to create a database in Hive.
## Syntax
CREATE DATABASE | SCHEMA [ IF NOT EXISTS ] <database name>
## Drop Database
  Drop Database is a statement that drops all the tables and deletes the database
  ## Syntax
  
  DROP  DATABASE StatementDROP ( DATABASE| SCHEMA ) [ IF EXISTS ] <database name>
  ## Create table Statement
  Create Table is a statement used to create a table in Hive
  ## Example
  hive>Create table if not exists employee (eid int,name String, salary String,destination String)
Comment ‘Employee details’
Row FORMAT DELIMITED
FIELDS TERMINATED BY ‘\t’
LINES TERMINATED BY ‘\n’
Stored as text file;






















Sources:
- https://www.tutorialspoint.com/hive/hive_introduction.htm 
- https://www.quora.com/How-does-Apache-Hive-work 


