# Coursera-Project-
🚀 SpaceX Launch Data Analysis using API
📌 Overview

This repository contains a series of Jupyter notebooks focused on collecting, cleaning, and analyzing SpaceX launch data using the SpaceX public API.
The project is part of a hands-on learning exercise to understand API-based data collection, data wrangling, and exploratory data analysis (EDA) using Python.

The workflow follows a structured, real-world data science pipeline—from raw API responses to a cleaned analytical dataset ready for visualization and modeling.

📂 Repository Structure
├── API Lab 1.ipynb
├── API Lab 2.ipynb
├── API Lab 3.ipynb
└── README.md

🔹 API Lab 1 – Data Collection

Connects to the SpaceX public API

Fetches launch data in JSON format

Converts API responses into Pandas DataFrames

Introduces API requests, JSON parsing, and normalization

🔹 API Lab 2 – Data Wrangling & Feature Engineering

Cleans and filters launch data

Handles nested JSON structures (cores, payloads, launch sites)

Extracts key features such as:

Booster version

Payload details

Launch site information

Launch dates

Removes irrelevant or inconsistent records

🔹 API Lab 3 – Data Preparation for Analysis

Finalizes the cleaned dataset

Applies logical filters (e.g., date restrictions, valid launches)

Prepares data for exploratory analysis and visualization

Ensures consistency and correctness of features

🛠️ Technologies Used

Python

Pandas

Requests

Jupyter Notebook

SpaceX REST API

🎯 Key Learning Outcomes

Working with REST APIs in Python

Handling complex and nested JSON data

Converting raw API data into structured datasets

Applying data cleaning and preprocessing techniques

Understanding differences between API versions and schemas

Building reusable, analysis-ready datasets

📊 Use Case

This project demonstrates how real-world datasets are rarely clean or flat and highlights the importance of:

Schema inspection

Defensive coding

Version-aware API usage

Step-by-step data preparation

The processed dataset can be further used for:

Exploratory Data Analysis (EDA)

Data visualization

Machine learning modeling

Predictive analysis of launch success
