# Assignment-1---Kickstarter-
##Assignment 1 - Boot camp, Kickstarter

# Kickstarting with Excel
By: Jeremy Pimentel
## Overview of Project
 This assignment seeks to build on skills related to Excel, and Github. Various Power Excel functions were used for this project such as Vlookups, Countifs, and other data formatting tools. 
## Purpose
The purpose of this assignment was to use a large sample of data related to kickstarter campaigns of various plays, and to use Excel formulas and functions to organize, analyze and discover new insights that be used to be better understand the makeup of successful, failed or canceled campaigns. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
- This data was analyzed using pivot tables and graphs (see below), and was done to understand how various factors can influence the success or failures of plays. 

![Pivot table](https://user-images.githubusercontent.com/107723677/177398706-eaca7623-8359-4516-acd1-4d6706b01ce6.PNG)
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107723677/176959554-a6eb73f2-47ee-478b-b477-dbeb00e9e9d3.png) 

- From analyzing Theater outcomes based on launch date, we can recognize a few characteristics. The number of successes ranges from ~38 to 110 depending on what month the play was launched. May had the highest number of successes and one of the highest number of failures, however, it also saw the most number of plays launched in total. The large gap between the success and failures for the month of May shows that May had the highest percentage of success, while Decemeber saw the lowest percentage of success as there is almost no gap between succeess and failure. 

- There doesnt seem to be any relation between a play being canceled and when it was launched. 
### Analysis of Outcomes Based on Goals
- The outcomes based on goal appears to have an inverse relationship. As in, the plays with the smallest goal, have the highest sucess rate and the lowest failure rate, while playes with more than 50,000 as their goal, have the opposite. 
- The first inflection point, where plays have a higher percent chance of failing, occurs when the goal amount is between 15,000 and 19,999. There is then a brief shift at the range, 35,000 to 39,999 which changes back to failures being more likely at, 40,000 to 44,999. 
- ![Outcomes vs Goals](https://user-images.githubusercontent.com/107723677/177051621-70b284b4-e346-4590-a78c-69731dff2a39.png)
### Challenges and Difficulties Encountered
- Some challenging parts to working with this dataset was that the dates for the projects was tricky to understand and I had some difficulties with the date conversion function. 
- Also, working with some of the pivot tables was a little tricky at times, with how to organize each variable into it's repsective section of the table.



# Results
-What are two conclusions you can draw about the Outcomes based on Launch Date?
 1) Plays launched in the month of December have the highest probnability of failure at nearly 50%. 

2) Plays launched in the month of May have the highest probability of success at nearly 70%. 


-What can you conclude about the Outcomes based on Goals? 

- Success and failures are inversly related to the goal amount. The percent of successes is greatest whenthe goal amount in less than 1000 and it is smallest when the goal amount is greater than 50,000.

-What are some limitations of this dataset?

- It's difficult to get a full picture of how well a play may do based on the factors given in this dataset. 
- We can only really compare how well plays do based on a limited number of variables such as: 
1) Goal amount,
2) Launch date.

-What are some other possible tables and/or graphs that we could create?

- We could create tables to look at number of backers, or play descriptions and whether they were receieved positively or negatively for example. 
- We could also create map charts for country launched in data.
- We could also look at how backers count is related to category or subcategory. 







