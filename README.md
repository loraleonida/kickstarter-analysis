# Kickstarting with Excel: An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose
The purpose of this analysis was to familiarize, organize, and sort through the kickstarter data in order to better understand the information and ultimately find trends and draw conclusions about what made a successful kickstarter campaign. The trends drawn from this data set can then be used as a guideline to help produce another successful kickstarter campaign.

## Analysis and Challenges
Analysis for this project was performed using many different tools including the application of filters, conditional formatting, formulas, generating and interpreting pivot tables, calculating summary statistics, and creating and then interpreting visualizations. All of these tools helped to narrow down the data and interpret the information in order to find trends in the data. Below are screenshot examples of the analysis tools used.


This image shows the formula used for the Date Created Conversion to convert the Unix timestamps into more easily understandable dates.
<img width="1500" alt="Unix Time Stamp Conversion" src="https://user-images.githubusercontent.com/101693004/161404156-ac30a717-f2cb-49ce-a333-5582734fb152.png">



This image shows how I used conditional formatting to label the successful campaigns green, the canceled campaigns yellow, the failed campaigns red, and the live campaigns as blue.
<img width="1505" alt="Conditional Formatting" src="https://user-images.githubusercontent.com/101693004/161404149-9944822d-fb41-4d9f-9345-c77748a6dadc.png">



This image shows the summary statistics calculated of Successful US Kickstarts and an example of the formula used to calculate the Upper Quartile Range of the amount pledged.
<img width="1504" alt="Descriptive Statistics" src="https://user-images.githubusercontent.com/101693004/161404144-19d39eec-e019-4942-ad8a-a14640f8e273.png">



This image shows an example of the pivot tables used for analysis and the corresponding bar graph visualization.
<img width="1502" alt="Pivot Table and Bar Graph" src="https://user-images.githubusercontent.com/101693004/161404173-bc23acdd-403e-4dd6-a623-67d0f55e17fe.png">


### Analysis of Outcomes Based on Launch Date
The line graph visualization of outcomes based on launch date shows the trend that the best time to launch a theatre campaign during the year is in the month of May. May has the highest number of successful theatre campaigns at 111, followed by the months June and July with 100 and 87 successful campaigns respectively.

### Analysis of Outcomes Based on Goals
The line graph visualization of outcomes based on goals shows the trend that the most successful theatre campaigns with the subcategory of plays are those with fundraising goals of less than $4,999. Campaigns with a goal of less than $1,000 have a 76% chance of reaching their fundraising goal, and campaigns with goals of $1,000 to $4,999 have a 73% chance of reaching their fundraising goal. As the fundraising goal increases over $5,000 the chances for success decreases.

### Challenges and Difficulties Encountered
I encountered multiple challenges when analyzing the data. I ran into difficulties trying to filter multiple columns at one time, and learned in order to do this I needed to select the entire first row and apply the filter. This applied filters to all of the columns and allowed me to filter multiple columns as needed. Also, when using the '=COUNTIFS' formula to analyze outcomes based on goals, I encountered the challenge of having to type the range and criteria for each statement into each individual cell. I quickly learned that by using the $ sign before and after the column range, I could drag the formula into the adjacent cell, and it would still reference the original column range. From there I just had to change the goal criteria instead of retyping the whole thing.

## Results

- What are two conclusions you can draw about the Theater Outcomes by Launch Date?
Two conclusions you can draw about the Outcomes based on Launch Date is that May is the most successful month of the year to launch a theatre kickstarter campaign, and December is least successful month of the year.

- What can you conclude about the Outcomes based on Goals?
You can conclude about the Outcomes based on Goals that the campaigns that had the highest rate of success in reaching their goals are those with a goal of less than $1,000. The campaigns with the second highest rate of success at reaching their goals are those with goal amounts of $1,000 to $4,999.

- What are some limitations of this dataset?
Some limitations of this dataset would be sample size of kickstarter campaigns when it comes to parent categories other than theatre. For example, there were only 23 kickstarter campaigns for journalism in the data set, compared to 912 campaigns for theatre. If you wanted to analyze trends in journalism campaigns, that would not be large enough sample size to determine trends accurately. Another limitation of the data set is the demographic of where these kickstarter campaigns took place. Of the 4,115 kickstarter campaigns, 3,038 of them took place in the US. If you were wanting to analyze the success rates of kickstarter campaigns in other countries, this particular data set would not have enough information to make it an accurate analysis.

- What are some other possible tables and/or graphs that we could create?
Other possible tables and/or graphs that we could create would be a table with the addition of another subcategory to the kickstarter data of theatre genre. You could filter the theatre play and musical campaigns based on whether they were a comedy, drama, etc. and determine if there was a trend among those genres of being more or less successful at launching or reaching their fundraising goals.

