In this project my task was to organize and analyze a database of four thousand past projects in order to uncover any hidden trends for the website KickStarter..

I was provided an Excel table to modify and analyze the data of four thousand past Kickstarter projects, to uncover some of the market trends. I used conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live".

I created a new column at column O called percent funded that uses a formula to uncover how much money a campaign made towards reaching its initial goal.

I used conditional formatting to fill each cell in the percent funded column using a three-color scale. The scale starts at 0 and is a dark shade of red, transitioning to green at 100, and then moving towards blue at 200.

I created a new column at column P called average donation that uses a formula to uncover how much each backer for the project paid on average. I also created two new columns, one called category at Q and another called sub-category at R, which used formulas to split the Category and Sub-Category column into two parts.


I created pivot table that analyzed my initial worksheet to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per category. I also made a stacked column pivot chart that can be filtered by country based on the table you have created.

Created a new sheet with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled


In the goal column, created twelve rows with the following headers...
Less Than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
Greater than or equal to 50000

I used a COUNTIFS() formula, to count how many successful, failed, and canceled projects were created with goals within those ranges listed above. Populated the Number Successful, Number Failed, and Number Canceled columns with this data.

Added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, I used a mathematic formula, to find the percentage of projects which were successful, failed, or were canceled per goal range.

Then I created a line chart which graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
