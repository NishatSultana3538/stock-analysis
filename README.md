# stock-analysis

## Overview of Project
An Analysis of Kickstarter Campaigns by usng Kickstarter data [kickstarter-analysis](https://github.com/NishatSultana3538/kickstarter-analysis/blob/main/Kickstarter_Challenge%20.xlsx) to help Louise with her project campaign.

### Purpose
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset I am trying to  visualize campaign outcomes based on their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created the Year column using date conversion column. Then I created a pivot table in a new worksheet. I filtered the pivot table using the parent catagory and years. Then I filtered the Filter the column labels to show only "successful," "failed," and "canceled." Then I group the "Row Labels" column to show the months of the year. Then I filtered the "Parent Category" to show only the data for "theater" and sort  the campaign outcomes in descending order so "successful"  column comes is first.Then I create a line chart from the pivot table to visualize the relationship between outcomes and launch month.![image_name](https://github.com/NishatSultana3538/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
First I create the formula for all different goal categories for number "successful" , then I copied it to number "failed" and number "canceled" and change the "successful" into "failed" and "canceled". I get 0 output for all canceled column. So i was confused and later cheked and find that there is no canceled outcome for "Plays" catgory. Next I  use "Sum" formula to get total project. Then I use percentage formula with rounding to get percentage successful , failed and canceled. To make the cells out come to % I have to divide by 100 to convert it to decimal and then format cells to use %.Then I insert the line chart and switch row and column.![2017]https://github.com/NishatSultana3538/stock-analysis/blob/main/Resources/VBA-Challenge_2017.png
### Challenges and Difficulties Encountered
I first face challenge to filter the parent catagory into Theater. The parent catagory was only showing "Film & video" as options. ![image-name](https://github.com/NishatSultana3538/kickstarter-analysis/blob/main/image/image%201.png)  So,  find out that my Excel file was corrupted and I started from a new file then it works. 

## Results

* What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The highest successful outcomes happen in the month of May and then it gradually decreases towards fall .
2. Number of successful outcome is always more than failed outcome . 



* What can you conclude about the Outcomes based on Goals?

1. The goal range doesnt clearly related to the successfull outcome.
2. The canceled outcome is 0% through all ranges for Plays catagory.


* What are some limitations of this dataset?

1. Comparing data set that was collected in different years could be misleading as there could be other influences on data based on years e.g. in year 2020/2021 outcomes could be different due to COVID.
2. Datasets are collected in different countries and different currencies so comparing them can be misleading.

* What are some other possible tables and/or graphs that we could create?

1. We can also create outcomes based on launch date by comparing diffenrent year.
2. We can create outcomes based on goals tables and line chart by filtering on other catagories e.g. television.
3. We can create outcomes based on goals by filtering only for US.
4. We can create column graphs by comparing what percentage of goal has been met.
