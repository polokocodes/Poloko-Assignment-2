# Poloko-Assignment-2
Job Market Salary Analysis — EDA Project
Overview
Exploratory data analysis of a job market dataset containing 250 job postings, investigating salary compensation across job titles, locations, categories, experience levels, and in-demand skills.
Research Questions

How does salary differ across job types, locations, categories, and experience levels?
What is the relationship between experience and job title?
What skills are most in demand?

Dataset

Source: job_market.csv
Records: 250 job postings
Features: 10 columns including job_title, company, location, job_type, category, salary_min, salary_max, experience_required, publication_date, skills

Key Findings

Python, SQL, and Machine Learning are the top three most in-demand skills
Full Time roles command the highest average salary across all job types
San Francisco and Seattle offer the highest location-based salaries; Remote roles are surprisingly competitive
Experience level is a strong salary predictor, with each tier adding ~$15,000–$20,000
The dataset contains a significant data quality issue — it blends U.S. and German job listings with incompatible formatting, requiring extensive cleaning before analysis

Requirements:

pandas
numpy
matplotlib
seaborn

Usage:
Open and run Project_2.ipynb in Jupyter Notebook or Google Colab.
