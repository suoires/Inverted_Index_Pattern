## Introduction

The inverted indexing project is Thien Nghiem's submission for MSDS Data Engineering class of Spring 2018.

This Jupyter Notebook contains the solution for the inverted index summarization of the Stack Overflow dataset. The objective of this project is to index large datasets on keywords for conveniency in tracing terms back to records that contain specific values. This process is similar to how indexes were built by search engines to improve search performance.

In the context of big data, I will use Apache Spark to perform the MapReduce component of this project. Next, I will use Spark SQL and dataframe for querying and displaying the indexing results from the MapReduce job. This project illustrates the integration of various Data Engineering components such as Python, HDFS, Spark, SQL, MapReduce, to solve the problem of inverted indexing on large datasets.

## Dependencies:

### Install dependencies via unix ternimal:

xcode-select --install

brew cask install java

brew install scala

brew install apache-spark

pip install findspark 

pip install pyspark


### Credit: Regis University - College of Computer and Information Science
