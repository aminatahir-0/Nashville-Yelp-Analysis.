# Market Analysis and Success Modeling of the Nashville Business Ecosystem

## Overview
This project implements a data-driven risk assessment framework to identify optimal business investment opportunities in the Nashville urban ecosystem. By utilizing the Yelp Business dataset, the analysis transitions from simple descriptive statistics to a weighted mathematical model designed to quantify competitor strength and identify market gaps.

## Key Methodologies
* **Exploratory Data Analysis (EDA):** Applied spatial aggregation to pinpoint high-traffic commercial zones exhibiting quality deficits relative to the city-wide benchmark of 3.64 stars.
* **Feature Engineering & Mathematical Modeling:** Developed a custom mathematical "Success Score" model using logarithmic weighting: `Success Score = Stars × ln(Reviews)`. This approach mitigates sample-size bias and accurately quantifies the proven success of established competitors.
* **Strategic Recommendations:** Combined geographic filtering with weighted metrics to translate raw data into actionable business investment strategies.

## Tools & Technologies
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Code Repository
You can view and run the full interactive notebook in Google Colab here:
[Open Interactive Google Colab Notebook](https://colab.research.google.com/github/aminatahir-0/Nashville-Yelp-Analysis./blob/main/Nashville%20yelp%20Dataset.ipynb)
