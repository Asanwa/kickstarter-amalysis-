# kickstarter-amalysis-
performing analysis on kickstarter data to identify trends 
PROJECT OVERVIEW 
The analysis of the Kickstarter dataset is essential because it provides playmakers and producers with references to the success of other producers and playmakers in achieving their fundraising goals on many different projects in different categories. It also provides a rough estimate of the time it takes to achieve fundraising goals of various amounts for varying projects across countries. 

Analysis and challenges 
In performing my analysis, I made pivot tables from the existing data set to summarize available data on campaign launch dates and outcomes. For my pivot table in the outcomes based on launch dates sheet, I set the date created conversion as my rows, outcomes for my columns, count of outcomes as my values, using year and parent categories as filters. In the outcomes by goals worksheet, I used conditional statements to obtain statistical information to establish a relationship between various goal ranges and the percentage of success, failure, or cancelation. 

In performing my analysis, the only major issue I encountered was trying to use the countif() function in populating the columns for the number of successful, the number of failed and the number of canceled because I was using [=COUNTIFS(Kickstarter!F:F,"successful",Kickstarter!D:D,"<24999",Kickstarter!D:D,">=20000")] as my formula. After a few tries and a break, I made a google search on “how to count if in excel using filters” I realized that I had been counting without specifying my criteria for the items I wanted to count. So, I adjusted my formula to [=COUNTIFS(Kickstarter!F:F,"successful",Kickstarter!D:D,"<24999",Kickstarter!D:D,">=20000"] and I continued adjusting my formula throughout the cells.


Results  

After analyzing the data provided, we notice that theater fundraising campaigns launched at the start of the summer are most successful in achieving their goals, indicating that May and June are the best months for Louise to lunch the fundraising campaign for her play. We also find that fundraising campaigns launched in December have an equal chance of achieving set fund goals and not achieving their goals. This conclusion is clear because of the 75 campaigns launched in this period 37 where successful, 35 where unsuccessful and 3 were canceled. addition to, the data shows that regardless of what time of the year, more project fundraising campaigns succeed in achieving their fundraising goals than those who do not. The line graph presented  visualizes this trend:


 

Analysis of the data also indicated that campaign goals are negatively correlated with the percentage of success. As set theater fundraising goals become higher, the chances of success become slim. We can decipher this by looking at the percentages of successful campaigns by goal ranges enclosed in the table included. Theater campaigns with goals less than $1000 recorded the highest success rates, while campaigns with goals of $50,000 or more recorded the highest failure rates. 



A graph or table I believe would be helpful in this analysis is one that tracks the amount of time each campaign took to achieve the set goal.
