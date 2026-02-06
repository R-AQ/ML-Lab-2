# ML-Lab-2: Tesla Insider Trading Analysis

## 1. Dataset Description
This work utilizes a Tesla Insider Trading dataset to understand the stock market behavior of big investors and insiders such as CEOs and directors, By examining transaction movements such as selling, buying, and optional actions.

* **Key Features:**
    * `Relationship`: Status of the person in the company (e.g., CEO, Director).
    * `Cost`: The stock price during the transaction.
    * `Shares`: The number of stocks involved.
    * `Value ($)`: Total monetary value of the trade.

## 2. Defining the Machine Learning Problem

* **Problem Type:** Classification
* **Target Variable:** `Transaction` to categorize a record into specific trade types (sale vs option exercise).
* **Model Goal:** to identify the financial patterns that lead to different insider actions. The model is expected to learn how the scale of a trade and the current stock cost influence whether an insider decides to accumulate more shares or liquidate their current holdings.


## 4. Contents
The methodology and initial data exploration are contained within this repository:
* **Notebook:** The Python code used to load the dataset, display its dimensions, and preview the data types and column headers.
* **Methodology Diagram:** A visual representation of the workflow, from data ingestion to the formal definition of the machine learning task.
