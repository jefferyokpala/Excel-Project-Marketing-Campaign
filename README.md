# Excel Project Marketing Campaign

## Overview

Analysis and Visualization of a company’s marketing campaign data on Microsot Excel

## Business Task

To determine the category of people likely to respond favorably to a company's marketing efforts.

## Data Source

I obtained this dataset from Kaggle, and it can be found here

## Tools

Microsoft Excel

## Process

### Data Cleaning

* 1 opened it on Microsoft Excel for initial exploration. During this process, I noticed the data was a little dirty and proceeded to clean it.

* Firstly, I searched for duplicate values, but there were none. Next, I sought to standardize the data because there were many columns with values that were written in lowercase. I changed them to the proper case using the =PROPER() formula.

* Under the campaign results column, there were “success”, “failure”, “unknown”, and “other” values. I changed the ”other” values to “unknown” because the campaign could reasonably only be a success or failure for each respondent. It is possible that “other” can apply because the marketers may have still been in contact with some respondents, hoping to convince them to buy a product when the data was taken. There could have been other situations that made the campaign status unknown. Therefore, I decided to use the Find and Replace command to change “other” to “unknown”.

* In the education column, I merged the entries of “secondaryschool” and “highschool” into one (High School) because they mean the same thing. I changed “unigraduated” to “University Graduates”.

* I changed the blank values in the Day since the last campaign column to Null values and deleted the Target column because it was full of blank values.

* Next, I added a new sheet to create pivot tables and charts to visualize relevant data. The first pivot showed the marketing campaign results by job title. From the pivot table and stacked bar chart, the company had the most marketing success reaching out to students, retirees, and unemployed people. The data shows that about 40% of people in each of those categories responded favorably.  Meanwhile, entrepreneurs were the least likely to be persuaded by the campaign.

![image alt](

![image alt](

