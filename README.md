# Wind Energy Forecasting – ProjectGroup5

A data science group project developed at The Hague University of Applied Sciences (THUAS).

## About
This project analyses Dutch weather and energy data to predict daily wind power generation in the Netherlands for 2022. We built a machine learning pipeline using Orange Data Mining with a Random Forest model, trained on historical data from 2017–2021.

## Tech Stack
- Python / Jupyter Notebook
- Orange Data Mining
- Pandas, NumPy, Matplotlib
- MongoDB

## My Contributions
- Data cleaning and preprocessing
- Dual-axis visualisation of predictions vs actual output
- contribution on dashboard, api, MongoDB database
  -comming up with useful dashboard features 
- Scrum Master responsibilities
- Chapter 4,5,7 of the final report
 
 
 # Project description in detail

 Project 1: Wind Energy Forecasting Using Dutch Weather Data
Stakeholder & Problem Context
Imagine you are working as a junior data scientist for a Dutch renewable energy company (e.g., a
regional wind farm operator or grid partner such as TenneT). Your primary stakeholders are grid
operators, energy traders, and wind farm operators. They need better short-term forecasts of wind
energy production to support operational decisions such as balancing supply and demand, scheduling
maintenance, and planning energy trading. Currently, they rely on limited forecasts and want a datadriven prototype that links weather conditions to energy output.
Project Objective
Design and implement an end-to-end data prototype that uses Dutch weather data (e.g., from KNMI)
to analyze and estimate short-term wind energy generation.
Your solution should:
• Help stakeholders understand how weather influences wind energy output
• Provide a simple, interpretable estimate of short-term wind energy generation
• Make results accessible through interpretable visualizations and an API
Main Question
How can weather conditions be used to explain and estimate wind energy production in the
Netherlands?
Core Example Tasks
1. Combine and align relevant weather and wind energy datasets to create a unified dataset that
represents conditions and outcomes over time.
2. Explore relationships between key weather variables (e.g., wind speed, wind direction, air
pressure, temperature) and wind energy production, and identify patterns, trends, and
correlations using appropriate analysis and visualizations.
3. Derive meaningful features that capture underlying behavior in the data, such as transformed
wind direction variables, time-based lag features, and simplified representations of wind–
power relationships.
4. Use or develop an ML model to estimate short-term wind energy output and interpret which
factors have the strongest influence on the predictions.
5. Design a small data pipeline that stores processed data in MongoDB and exposes a simple API
to retrieve insights, summaries, or predictions for stakeholders.
6. Evaluate and reflect on Responsible AI aspects such as data quality, bias, dataset
representativeness, and model limitations, and explain their impact on the reliability, fairness,
and interpretation of the results.
Key Expectation:
There is no single correct model or approach. Your task is to select appropriate data science methods,
justify your choices, and interpret your results in the context of the problem.
Bonus Points:
• Compare multiple models (e.g., linear vs. tree-based models)
• Include uncertainty or confidence intervals in predictions
• Build a simple dashboard (e.g., showing real vs predicted output over time)
• Extend forecasting horizon (e.g., 24h vs 6h predictions) 
