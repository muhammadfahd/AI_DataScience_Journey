
# Essentials Concepts Day 09 
Data science is a field that combines statistics, computer science, and domain expertise to extract insights from data. <br> This document covers some essential concepts in data science, including data frames, dataset types, levels of measurement, data analytics types, and the data science life cycle.

- [Essentials Concepts Day 09](#essentials-concepts-day-09)
  - [Data Frame \& Dataset](#data-frame--dataset)
  - [Types of Data Set \& Formats of Datasets](#types-of-data-set--formats-of-datasets)
    - [1. Types of DataSet](#1-types-of-dataset)
    - [2. Dataset Formats](#2-dataset-formats)
  - [Rows \& Coloumns](#rows--coloumns)
  - [Levels of Measurements](#levels-of-measurements)
  - [Data Analyitics Types](#data-analyitics-types)
  - [Data Science Life Cycle](#data-science-life-cycle)

---
## Data Frame & Dataset
In data science, a data frame and a dataset are often used interchangeably, but here's a subtle distinction:

|Data Frame | DataSet |
|----------|----------|
|**Data Frame**: A data frame is a specific data structure used to store and manipulate tabular data, typically in a two-dimensional format with rows and columns. Examples include Pandas DataFrames in Python |  **Dataset**: A dataset is a broader term that refers to a collection of data, which can be in various formats, such as tabular, image, text, or audio. A dataset can be thought of as a container for data, which can be used for analysis, modeling, or other purposes.

---
## Types of Data Set & Formats of Datasets
### 1. Types of DataSet
Datasets can be classified into various types based on their characteristics, format, or source. Here are some common types of datasets:

1. **Tabular datasets**: These datasets are organized into tables with rows and columns.
2. **Image datasets**: These datasets consist of images, which can be used for tasks like image classification, object detection, or image segmentation.
3. **Text datasets**: These datasets contain text data, which can be used for tasks like natural language processing, sentiment analysis, or text classification.
4. **Time-series datasets**: These datasets contain data that varies over time, which can be used for tasks like forecasting, anomaly detection, or trend analysis.
5. **Audio datasets**: These datasets consist of audio recordings, which can be used for tasks like speech recognition, music classification, or audio analysis.

### 2. Dataset Formats
Datasets can be stored in various formats, including:

1. **CSV (Comma Separated Values)**: A plain text format where each row is a single observation, and columns are separated by commas.
2. **JSON (JavaScript Object Notation)**: A lightweight, human-readable format for exchanging data between systems.
3. **Excel files**: A binary format used by Microsoft Excel to store tabular data.
4. **SQL databases**: A structured format for storing and querying large datasets using SQL (Structured Query Language).

These are just a few examples of dataset types and formats. The specific format and type of dataset used will depend on the problem being addressed, the tools and technologies being used, and the requirements of the project.

---


## Rows & Coloumns 
In Data Science, Machine Learning, and AI, columns and rows in a dataset are often referred to by different names, depending on the context. Here are some common alternative names:

**Columns:**

1. **Features**: In Machine Learning, columns are often referred to as features, which are the individual variables or attributes used to describe the data.
2. **Variables**: Columns can also be referred to as variables, which are the individual characteristics or attributes being measured or observed.
3.**Attributes**: In some cases, columns are referred to as attributes, which are the specific characteristics or properties of the data.

**Rows**:

1. **Instances**: In Machine Learning, rows are often referred to as instances, which are individual examples or observations in the dataset.
2. **Samples**: Rows can also be referred to as samples, which are individual data points or observations.
3. **Observations**: In some cases, rows are referred to as observations, which are individual data points or records.

---
## Levels of Measurements
**Levels of Measurement**
In statistics and data analysis, there are four levels of measurement that describe the properties of data:

1. **Nominal**: Nominal data is **categorical data** that has **no inherent order** or ranking. Examples include:
    - Colors (red, blue, green)
    - Sex (male, female)
    - Nationality (American, Canadian, Mexican)
2. **Ordinal**: Ordinal data is c**ategorical data** that has a **natural order** or ranking. Examples include:
    - Education level (high school, college, graduate degree)
    - Job satisfaction (very dissatisfied, dissatisfied, neutral, satisfied, very satisfied)
    - Movie ratings (1 star, 2 stars, 3 stars, 4 stars, 5 stars)
3. **Interval**: Interval data is **numerical data** where the differences between values are **meaningful**, but there is no true zero point. Examples include:
    - Temperature in Celsius or Fahrenheit
    - IQ scores
    - Time of day (in hours, minutes, and seconds)
4. **Ratio**: Ratio data is **numerical data**where there is a true zero point, and the **ratios between values are meaningful**. Examples include:
    - Weight in kilograms or pounds
    - Height in meters or feet
    - Age in years

**Key differences between levels of measurement**:

Measurement | Difference | 
---------|----------|
**Nominal and ordinal data** | These levels of measurement are categorical and do not have numerical values that can be used for mathematical operations. | C1
 **Interval and ratio data** | These levels of measurement are numerical and can be used for mathematical operations like addition and subtraction. |

**Importance of levels of measurement:**
Understanding the level of measurement of your data is important because it determines the types of statistical analyses that can be performed on the data. <br>**For example**, nominal data can only be analyzed using non-parametric methods, while interval and ratio data can be analyzed using parametric methods.

![Data & Its Types](https://i.ytimg.com/vi/7bsNWq2A5gI/sddefault.jpg?sqp=-oaymwEmCIAFEOAD8quKqQMa8AEB-AHUBoAC4AOKAgwIABABGDkgYShyMA8=&rs=AOn4CLCzlADCU0qk3YEfmd6HTHX-5w656w)

---
## Data Analyitics Types
**Types of Data Analytics**
Data analytics can be categorized into **four main types**, each with its own unique purpose and methodology:

1. **Descriptive Analytics**: Descriptive analytics focuses on summarizing and describing historical data to understand what happened. It provides insights into past events, trends, and patterns.
    - Example: Analyzing sales data to determine the best-selling products or regions.
2. **Diagnostic Analytics**: Diagnostic analytics aims to identify the root causes of problems or opportunities. It drills down into data to understand **why** something happened.
    - Example: Analyzing customer complaints to identify the most common issues or pain points.
3. **Predictive Analytics**: Predictive analytics uses statistical models and machine learning algorithms to forecast future events or outcomes. It predicts **what might happen** based on historical data and trends.
    - Example: Predicting customer churn or forecasting sales for the next quarter.
4. **Prescriptive Analytics**: Prescriptive analytics provides recommendations on **what actions to take** to achieve a specific goal or outcome.
    - Example: Recommending personalized product offers to customers based on their purchase history and behavior.

**Importance of understanding analytics types**:
Understanding the different types of data analytics is crucial for businesses and organizations to make informed decisions, optimize operations, and drive growth. 
<br>By applying the right type of analytics, organizations can gain valuable insights, identify opportunities, and stay ahead of the competition.

---
## Data Science Life Cycle
The data science life cycle is a process that involves several stages, from acquiring data to gaining insights and making decisions. Here's a brief overview:

1. **Acquire Data**: Collecting data from various sources, such as databases, APIs, or files.
2. **Clean Data**: Preprocessing and cleaning the data to remove errors, inconsistencies, and missing values.
3. **Explore Data**: Analyzing and visualizing the data to understand patterns, trends, and relationships.
4. **Model Data**: Building models using machine learning or statistical techniques to identify insights and make predictions.
5. **Interpret Results**: Interpreting the results of the analysis and models to gain insights and make decisions.
6. **Deploy**: Deploying the insights and models into production to drive business decisions or automate processes.