# Crowdfunding Analysis of Trends

## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. I will organize and analyze a database of 1,000 sample Crowdfundig projects to uncover any hidden trends.

## Project Steps: 
 - Use an Excel workbook to modify and analyze the project data to uncover market trends.
 - This dataset was created by Trilogy Education Services, a 2U, Inc. brand.
 - Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
- Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
 - Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
 - Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.
- Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
 
- Create a new sheet with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
 - Create a stacked-column pivot chart that can be filtered by country based on the table that was created.
 
- Create a new sheet with a pivot table that analyzes my initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
- Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that was created.
- The dates in the deadline and launched_at columns use Unix timestamps. 
- Create a new column named Date Created Conversion that will use a formula to convert the data contained in launched_at into Excel's date format.
- Create a new column named Date Ended Conversion that will use a formula to convert the data contained in deadline into Excel's date format.
 
- Create a new sheet with a pivot table that has a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

- Now, create a pivot-chart line graph that visualizes this new table.

## Analysis
- Given the provided data, some conclusions that can be drawn about these crowdfunding campaigns:
   - More crowdfunding campaigns are successful, than not successful.
   - Crowdfunding for theater projects, specifically plays, is the most popular and had the most amount of successful campaigns; however, if you do the ratio of total campaigns and how many failed, it also has the highest percentage of failures.
   - About 43% failed to meet their goal amount for crowdfunding, and about 57% met or exceeded their goal of crowdfunding.
   - Those who had a goal of raising $50,000 or more had the lowest percent of being successful.

- Some limitations on this data include the reason why some crowdfunding campaigns cancelled or failed.	There also could be more specific categories than the sub-categories listed. For instance, food trucks is a sub-category. But what types of food trucks were successful vs. failed? Does this play into the failure to raise money?

- What are some other possible tables and/or graphs that I could create, and what additional value would they provide?
   - Create a pivot table to reflect by category, and did the time they launched to the deadline, play a factor in if crowdfunding was more successful or not? Did projects with a short deadline fail more? 
   - What was the average time from launch to deadline by category? This could be useful for people looking to crowdfund to help manage expectations.
   - What was the average financial goal, per category and sub-category, to give perspective to those thinking about starting a crowdfunding campaign?

 
