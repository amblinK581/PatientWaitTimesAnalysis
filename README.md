Analyzing Factors Influencing Patient Wait Times in the Emergency Room

This repository contains the project “Decoding the Clock: Analyzing Factors Influencing Patient Wait Times in the Emergency Room”, which explores how various factors contribute to patient wait times using the 2013 National Hospital Ambulatory Medical Care Survey data.

Project Overview

The project aims to uncover key factors influencing patient wait times in emergency rooms, with a focus on racial disparities, holiday effects, and significant variables using statistical analysis techniques such as ANOVA, Mann-Whitney U test, and Lasso regression.

Table of Contents

	•	Introduction
	•	Data Source
	•	Hypotheses
	•	Methods
	•	Results
	•	Conclusion
	•	How to Use This Repository

Introduction

This project examines patient wait times in emergency rooms, a crucial aspect of healthcare delivery that has wide-reaching implications for social justice and healthcare system improvements. We analyzed real-world data from 2013 to explore what factors affect how long patients wait.

Data Source

The data used in this project comes from the 2013 National Hospital Ambulatory Medical Care Survey (NHAMCS), which is conducted by the National Center for Health Statistics. This dataset provides comprehensive national statistics on hospital outpatient and emergency department visits.

Hypotheses

We explored the following hypotheses:

	1.	There are significant disparities in patient wait times among different racial groups.
	2.	Wait times during holidays are longer than on regular weekdays.
	3.	The most important numeric and categorical variables that predict patient wait times can be identified using Lasso regression.

Methods

Statistical Analyses

	•	Exploratory Data Analysis (EDA): Identified distribution patterns and cleaned data for further analysis.
	•	ANOVA: Investigated disparities in wait times among racial groups.
	•	Mann-Whitney U Test: Compared wait times between holidays and weekdays.
	•	Lasso Regression: Identified the most important numeric and categorical variables affecting patient wait times.

Results

	1.	Racial Disparities: Minority groups tend to experience longer wait times compared to non-Hispanic whites, as demonstrated by Welch’s ANOVA and the Games-Howell test.
	2.	Holiday vs Weekday Wait Times: Using the Mann-Whitney U test and z-score analysis, we found that wait times are slightly shorter on holidays than on weekdays.
	3.	Key Variables: Lasso regression identified the top five numeric and categorical variables affecting patient wait times, including race/ethnicity, number of procedures, and heart rate.

Conclusion

The study provides evidence that racial minorities face longer wait times in emergency rooms and that holidays tend to have shorter wait times compared to weekdays. The Lasso regression model identified critical variables that contribute to predicting wait times, helping to inform future improvements in emergency room management.

How to Use This Repository

	1.	Data: The data/ folder contains the 2013 NHAMCS dataset.
	2.	Scripts: The scripts/ folder includes Python code for data cleaning, statistical analysis, and model building.
	3.	Results: The results/ folder contains visualizations and tables from the analysis.
	4.	Report: The final project report is available in the docs/ folder.

Requirements

	•	Python 3.x
	•	Required libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn

Install the required libraries by running:

pip install -r requirements.txt

License

This project is licensed under the MIT License - see the LICENSE file for details.

Authors

	•	Chih-Han Liu
	•	Xu-yan Zhang
	•	Tzu-Hsuan Lin
