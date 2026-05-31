# COVID-19 Exploratory Data Analysis
### CodeAlpha Data Analytics Internship — Task 2

## What is this?
An exploratory analysis of the COVID-19 pandemic using the Our World in Data dataset. I did this as part of my internship at CodeAlpha — the goal was to dig into the numbers and understand how the pandemic actually played out across countries and continents.

## Dataset
Got it from kaggle  
Downloaded as `owid-covid-data.csv`

## Tools Used
- Python, Pandas, Matplotlib

## What I explored
- How global cases and deaths grew over time
- Which countries were hit hardest (top 10 by cases and deaths)
- Continental breakdown — where did the burden fall?
- Daily new cases with 7-day rolling average to cut through the reporting noise
- Cases vs deaths scatter — is there a clean relationship between the two?

## Key findings
- The US led in both total cases and deaths, though high testing rates play a role in that
- Europe's share of global cases is surprisingly large relative to its population vs Asia
- The Omicron wave (early 2022) shows up as a near-vertical spike in daily cases — nothing like it before or after
- Brazil and Peru rank higher in deaths than in cases, which points to healthcare strain and underreporting
- Raw daily case numbers are very noisy — the 7-day average is much more useful for spotting actual waves

## How to run
```bash
pip install pandas matplotlib
jupyter notebook covid_eda.ipynb
```
Make sure `owid-covid-data.csv` is in the same folder.
