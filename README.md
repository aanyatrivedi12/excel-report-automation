# Excel Report Automation Tool

So basically I got tired of the idea of manually making Excel reports 
and thought -> can Python just do this for me? Turns out yes it can.

This is my first automation project. I used the Superstore Sales 
dataset from Kaggle and wrote a script that loads the raw CSV, 
cleans it up, and spits out a formatted Excel file automatically.

## What it does
- loads and cleans 9800 rows of sales data using pandas
- fixes data type issues (dates stored as text, postal codes as floats)
- creates 3 summary sheets -> region wise, category wise, monthly trend
- adds a cover sheet with key numbers like total revenue and top region
- embeds bar, pie and line charts directly into the Excel file

## What I learned
- how groupby works (basically a pivot table but in Python)
- openpyxl for writing and styling Excel files from scratch
- why data cleaning matters before doing any analysis
- datetime handling in pandas
- that column names are case sensitive and will ruin your day

## Tools used
- Python (pandas, openpyxl)
- Google Colab
- Dataset: Superstore Sales -> Kaggle

## Output
A 4 sheet Excel report with formatted tables, colored headers, 
zebra striping, and embedded charts.

## How to run
1. upload train.csv to Google Colab
2. run all cells top to bottom
3. download the Excel file at the end
##yuip
---
This is Project 1 of my ongoing data automation series.
Still learning but building things along the way.
