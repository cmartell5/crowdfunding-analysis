# excel-challenge
Challenge Module 1
MODULE 1 CHALLENGE
Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this week's Challenge, you will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.
Before You Begin
1.	Create a new space for this project called excel-challenge in either Dropbox or Google Drive. Do not add this Challenge to an existing repository.
2.	Store your Excel workbooks here in this new space, and create a sharable link for submission.
Files
Download the following files to help you get started:
Module 1 Challenge files
Instructions
 
Using the Excel workbook in your .zip file, modify and analyze the sample-project data and try to uncover market trends.
•	This dataset was created by Trilogy Education Services, a 2U, Inc. brand.
•	Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
o	Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
•	Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
o	Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.
o	Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
 
o	Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
•	Create a stacked-column pivot chart that can be filtered by country based on the table that you created.
 
•	Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
•	Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.
•	The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formula (Links to an external site.) that can be used to convert these timestamps to a normal date.
o	Create a new column named Date Created Conversion that will use this formula (Links to an external site.) to convert the data contained in launched_at into Excel's date format.
o	Create a new column named Date Ended Conversion that will use this formula (Links to an external site.) to convert the data contained in deadline into Excel's date format.
 
o	Create a new sheet with a pivot table that has a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.
o	Now, create a pivot-chart line graph that visualizes this new table.
•	Create a report in Microsoft Word, and answer the following questions:
o	Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
o	What are some limitations of this dataset?
o	What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
Bonus
•	Create a new sheet with 8 columns:
o	Goal
o	Number Successful
o	Number Failed
o	Number Canceled
o	Total Projects
o	Percentage Successful
o	Percentage Failed
o	Percentage Canceled
•	In the Goal column, create 12 rows with the following headers:
o	Less than 1000
o	1000 to 4999
o	5000 to 9999
o	10000 to 14999
o	15000 to 19999
o	20000 to 24999
o	25000 to 29999
o	30000 to 34999
o	35000 to 39999
o	40000 to 44999
o	45000 to 49999
o	Greater than or equal to 50000
 
•	Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.
•	Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
•	Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.
