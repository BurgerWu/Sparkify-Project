# Sparkify-Project

## Motivation
In this project, we try to capture user intention to churn (which means cancelling the whole service) using user activity log. Trying to predict whether a usr is at risk of churning is critical for company providing services nowadays. If we could accurately predict potentially churning users, we could provide promotion or special offer to those users to have them turn their mind.

## Introduction
In order to get better efficiency, we apply pyspark, which is a Spark API designed for Python as our framework. In our analysis, we follow the pipeline as follows:
- Data cleaning 
- Exploratory data analysis
- Feature engineering
- Modeling
- Evaluation


## Dataset
In this notebook, we use a subset of the full dataset for modeling. The schema of this dataframe is as below.
```
|-- artist: string (nullable = true) <br>
|-- auth: string (nullable = true) <br>
|-- firstName: string (nullable = true) <br>
|-- gender: string (nullable = true) <br>
|-- itemInSession: long (nullable = true) <br>
|-- lastName: string (nullable = true) <br>
|-- length: double (nullable = true) <br>
|-- level: string (nullable = true) <br>
|-- location: string (nullable = true) <br>
|-- method: string (nullable = true) <br>
|-- page: string (nullable = true) <br>
|-- registration: long (nullable = true) <br>
|-- sessionId: long (nullable = true) <br>
|-- song: string (nullable = true) <br>
|-- status: long (nullable = true) <br>
|-- ts: long (nullable = true) <br>
|-- userAgent: string (nullable = true) <br>
|-- userId: string (nullable = true) <br>
```
## Libraries Used
- pyspark
- pandas
- matplotlib
- seaborn

## Files and Folders
- mini_sparkify_event_data.json (Subset of dataset for modeling)
- Sparkify.ipynb (Notebook for the project)

## Summary



## Acknowledgement

This is repository for Sparkify project 
