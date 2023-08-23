# Leverage Spark Connect for interactive data analysis in Jupyter Notebooks

Google Summer of Code 2023 with CERN-HSF by Muhammad Aditya Hilmy <mhilmy@hey.com>

## Introduction

### Project Brief

This project aims to build a JupyterLab extension to integrate JupyterLab with Apache Spark and exploit Apache Spark's new feature called Spark Connect. This extension is meant to replace the current SparkConnector extension. With this extension, instead of having one Spark cluster connection for every open notebook, the extension will manage only one connection, and uses the Spark Connect API to comunicate with the PySpark instance in each notebook.

## Work Results

### Spark Connect Labextension

The extension's source code is available in [https://github.com/didithilmy/spark-connect-labextension](didithilmy/spark-connect-labextension). Documentations on how to install and use the package is available on the repo README.

#### Pull Request

This extension is in the process of being merged to SWAN's monorepo. Pull request here: https://github.com/swan-cern/sparkconnect/pull/1

#### Features
1. Create Spark Connect connection from the Lab sidebar
2. Allow users to configure the Spark connection from the UI
3. View Spark connection logs
4. Access Spark Web UI from the lab interface

#### Screenshots

![](img/s1.png)
![](img/s2.png)
![](img/s3.png)
![](img/s4.png)
![](img/s5.png)