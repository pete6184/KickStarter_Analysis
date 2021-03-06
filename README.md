# KickStart_My_Chart

## Requirements & Summary
The only program this challenge required was Microsoft Excel. 


## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects to uncover any hidden trends.


Instructions

- Using the Excel table provided, modify, and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

- Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

- Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

- Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

- Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

- Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

- Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

- Create a stacked column pivot chart that can be filtered by country based on the table you have created.

- Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

- Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

- The dates stored within the deadline and launched at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.

- Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched at into Excel's date format.

- Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.

- Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

- Now create a pivot chart line graph that visualizes this new table.


![image1](https://user-images.githubusercontent.com/74940976/118373363-46453180-b56b-11eb-8483-8981b1a44e4c.PNG)

![image2](https://user-images.githubusercontent.com/74940976/118373366-49d8b880-b56b-11eb-8e7b-86f3524daba9.PNG)

![image3](https://user-images.githubusercontent.com/74940976/118373369-4d6c3f80-b56b-11eb-81b1-6162f0bbdbe3.PNG)

![image4](https://user-images.githubusercontent.com/74940976/118373370-4fce9980-b56b-11eb-877f-3749ff683a85.PNG)
