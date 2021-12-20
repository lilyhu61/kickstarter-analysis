# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
Written analysis for the Kikerstarter_Challenge project.


# Overview of Project

Due to Louise’s play “Fever” came close to its fundraising goal in a short amount of time, so she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

The purpose of this project is to help Louise by providing unbiased view of the data tables and graphic visualizations to predict future trends of her campaign. Based on those she will be able to make decisions about her campaign with confidence.

## Analysis and Challenges

### For the Deliverable 1: Outcomes Based on Lunch Date Chart. I did the following steps:
1, Created a "Years" column based on the "Date Created Conversion" column in the Kickstarter spreadsheet.
2, Created a pivot table that filters on "Parent Category" and "Years" in a new worksheet labeled "Theater Outcomes by Launch Date".
3, In the PivotTable Fields, drag the outcomes to the Columns, drag the Date Created Conversion to the Rows, drag the Outcomes to the values, and drag the Parent Category to the Filters.
4, Filtered the "Parent Category" on "theater".
5, Changed the row labels to display the months of the year, and the campaign outcomes are sorted in descending order.
6, Created a line chart showing the number of successful, failed, or canceled projects by month, it has a title, and it is saved as Theater_Outcomes_vs_Launch.png.

### For the Deliverable 2: Outcomes Based on Goals Chart. I did the following steps:
1, Created a new sheet with eight columns and twelve rows, according to the instructions.
2, Used the COUNTIFS() function to populate the "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome," the "goal" amount using the goal ranges that be created before , and the Subcategory "plays" .
3, Used the SUM() function is used on each row to add the "Number Successful," "Number Failed," and "Number Canceled" columns to populate the "Total Projects" column.
4, Calculated the percentages of successful, failed, and canceled projects based on the data from the "Total Projects," "Number Successful," "Number Failed," and "Number Canceled" columns.
5, Created a line chart and saved as Outcomes_vs_Goals.png with the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis, and an appropriate title.
One of the most difficult problems that I encountered is the COUNTIFS() function, at first I didn’t put “plays” as the criteria, I expended a lot of time to verify the data. I should read instructions more carefully in the future.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on pivot table and chart from Outcomes based on Launch Date, we can determine the launch date during the month of May and Jun is the most successful. Lunch date for failed is not main reason.

- What can you conclude about the Outcomes based on Goals?

From the Outcomes Based on Goals chart, goal amount range between 1000 to 4999 is the most successful, I saw the success rate of plays decline when the goal amount increases.  And I noticed none of the plays were canceled.

- What are some limitations of this dataset?
 The dataset didn't account for the exchange reate amongst different currencies.

- What are some other possible tables and/or graphs that we could create?
   We can create Outcomes Based on Deadline.


![image](https://user-images.githubusercontent.com/95242493/146726444-b230ab93-ebf7-4c8e-9061-64911ddf702d.png)
