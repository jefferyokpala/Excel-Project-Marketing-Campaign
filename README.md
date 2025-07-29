# Excel Project Marketing Campaign

## Overview

Analysis and Visualization of a company’s marketing campaign data on Microsot Excel

## Business Task

To determine the category of people likely to respond favorably to a company's marketing efforts.

## Data Source

I obtained this dataset from Kaggle, and it can be found [here](https://www.kaggle.com/datasets/khanimar/marketing-campaign-analysis-data?select=test.csv)

## Tool

Microsoft Excel

## Process

### Data Cleaning

* 1 opened the dataset on Microsoft Excel for initial exploration. During this process, I noticed the data was a little dirty and proceeded to clean it.

* Firstly, I searched for duplicate values, but there were none. Next, I sought to standardize the data because there were many columns with values that were written in lowercase. I changed them to the proper case using the =PROPER() function.

* Under the campaign results column, there were “success”, “failure”, “unknown”, and “other” values. I changed the ”other” values to “unknown” because the campaign could reasonably only be a success or failure for each respondent. It is possible that “other” can apply because the marketers may have still been in contact with some respondents, hoping to convince them to buy a product when the data was taken. There could have been other situations that made the campaign status unknown. Therefore, I decided to use the Find and Replace command to change “other” to “unknown”.

* In the education column, I merged the entries of “secondaryschool” and “highschool” into one (High School) because they mean the same thing. I changed “unigraduated” to “University Graduates”.

* I changed the blank values in the Day since the last campaign column to Nulls and deleted the Target column because it was full of blank values.

* Next, I added a new sheet to create pivot tables and charts to visualize relevant data. The first pivot showed the marketing campaign results by job title. From the pivot table and stacked bar chart, the company had the most marketing success reaching out to students, retirees, and unemployed people. The data shows that about 40% of people in each of those categories responded favorably.  Meanwhile, entrepreneurs were the least likely to be persuaded by the campaign.

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image7.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image5.png?raw=true)

* I also created a pivot table and line chart that showed the campaign results by contact type. This lets us know the mode of contact that is most effective in attracting customers. From the data, most respondents were contacted by cell phone. The data also shows that the methods of communication that were entered as unknown had the highest success rate. This deserves further investigation to know what those unknown contact types are. But sticking with the known contact types, the success rate of both is similar, although landlines have a higher success rate. Landlines have a success rate of 26.3% while cellphones have a success rate of 23.7%, according to the dataset.

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image3.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image6.png?raw=true)

* Next, I created a pivot table and horizontal bar chart to visualize the campaign results by education level. The marketing campaign was most successful with university graduates, with 41.7% of respondents responding positively. The success rate of the remaining categories was: high school education level respondents at 21.1% and those that were unspecified at 26.9%.

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image2.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image4.png?raw=true)

* To conclude, I created a dashboard on another sheet that shows all the relevant information in the dataset and makes it possible to present the data to business stakeholders. I added slicers to the dashboard to filter the information displayed by gender, marital status, and whether the respondents had active credit or not.

![image alt](https://github.com/jefferyokpala/Excel-Project-Marketing-Campaign/blob/main/images/image1.png?raw=true)


