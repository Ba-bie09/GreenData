## GreenData
#Data Cleaning Challenge

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Explanatory Data Analysis](#explanatory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Inference](#inference)

[Limitations](#limitations)

[Recommendations](#recommendations)

## Project Overview
---
The aim of this project is to analyze and clean messy data related to patients' health records. The goal is to help enhance critical thinking, attention to details, and problem-solving skills in data cleaning. 

## Data Source
---
The main source is the GreenData Dirty Healthcare Data csv

## Tool used
- Microsoft Excel [Download here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis

## Data Cleaning and Preparation
---
At the beginning of Data Cleaning and Preparation, the following steps were taken.
 1. Data was downloaded and inspected
 2. The Data used was dirty and consisted of errors, missing variables and inconsistencies.
 3. Cleaning and Preparing the Data for further analysis.

## Explanatory Data Analysis 
---
This includes exploring of data to identify cities or demographics with higher healthcare needs based on health conditions and admission dates.

## Data Analysis
---
CONCAT
FIND AND REPLACE

## Data Visualization
---

![Final GreenData 1](https://github.com/user-attachments/assets/66274b2a-6fe8-4431-b497-723b6f111fb8)

![Final GreenData 3](https://github.com/user-attachments/assets/f6d08d7e-63d1-4241-9ae7-fe009525b7af)

![Final Pivot](https://github.com/user-attachments/assets/eadd0e6d-b8d7-4a3a-924f-d8b48dbe6d34)


## Inference
The city of Atlanta has the highest healthcare needs with 973 (59%) counts of admissions of the total entries, followed by Albuquerque with 378 counts (29%) and Baltimore with 305 counts (18%).

## Limitations
1. There was no entry of health conditions, therefore the variable could not be used to identify cities or demographics with higher healthcare needs.
2. Due to a large number of missing entries, errors and inconsistencies, there is restriction in insightful and important analysis that could be carried out.

## Recommendations
1. There should be a revisit of the Data entries to find the missing variables especially in Gender.
2. A lot of inconsistencies should be looked into and corrected, for example, a year old who is already an undergraduate and many others.

# Report

REPORT ON GREENDATA CLEANING
1.	The data was checked for duplicates and three duplicates were found and removed.
2.	Names are being changed to “Proper” format.
3.	There are blank cells in the age column and there are some ages that are questionable, especially ages 0-20, where we have ID number 30 who is a year old, is an undergraduate student already. In view of these, the blank cells and age range 0-20 are in Lilac colour, because it is not ethical to assign random ages to patients medically; some illnesses are age-related.
4.	Gender column was removed totally because only 1.8% of the entries were made.
5.	The cities are narrowed down to three, and it was noticed that abbreviations made the cities six initially. They are changed to proper format too. 
6.	The repitions in the Education were removed and the blank spaces filled with Null, because educational level cannot be fabricated to maintain reliability.
7.	An additional column is created for Employment to separate the type e.g. Employed (Gig-work) are being separated into two columns by using “Find and Replace” and so on, to remove ambiguity, and to make it error free when using other tools like SQL, Python.
8.	The Salary column is also having an additional column to separate the specifics e.g.  with “N/A” and “Missing” values being changed to “$0”.
9.	In credit score, N/A are being replaced with “0” to have the same data type. Also 380 (Typo) are changed to “0” (Red).
10.	Date of Admissions are changed to integers to have consistency in the data type. 
11.	The dataset is changed to Table format.



Thank you.














