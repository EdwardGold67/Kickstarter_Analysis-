# Kickstarter_Analysis

week 1 for Coloumbia's DS bootcamp
---
## Overview of Project
The purpose of the analysis was to determine how successful plays on Kickstarter are at reaching their monetary goals. The parameters for this analysis were based on the month of the year that theater kickstarters – the parent category- were launched and how that impacted a successful, failed or canceled outcome. Following that analysis, we then compared how much money the goals of play kickstarters were set at and how it also impacted a successful, failed or canceled outcome.

---
## Analysis and Challenges
### Theater Outcomes by Launch date 
The first step in my analysis was comparing the launch date for theater kickstarters with the resulting outcomes. Through the use of a pivot table, I filtered out the parent category, Theater, and I created a line chart with the month of year on the X-axis and the number of outcomes on the Y-axis. The outcomes were split up into successful, failed and canceled.
![Theater_Outcomes_vs_Launch.png](https://user-images.githubusercontent.com/48603147/138617957-ca5dc715-8d9d-4f68-b32f-5bdcc37fae3c.png)
### Outcomes Based on Goals
In the second step of the analysis, I narrowed down the focus on plays, a sub category of theater. This time I compared how the outcomes were impacted based on the monetary goals for which the kickstarter’s were set at. To group projects based on their goals, I created dollar-amount ranges so that the data can be read more clearly. Using the Countifs function,…,I calculated the sum of successful, failed and canceled projects based on what range their goals were in. Following that step I summed up the total projects, within their ranges, using the sum function and divided by the number of successful, failed and canceled projects. From this I calculated the percentages of each outcome to make the data easier to understand and manipulate. As you can see from the line graph below, I put the dollar-amount ranges on the x-axis and the outcome percentages on the y-axis. 
![Outcomes_vs_Goals.png](https://user-images.githubusercontent.com/48603147/138618042-3912440b-ffe0-48aa-ac2d-ae55b38eb0f4.png)

### Challenges
One of the challenges I encountered was dealing with unexpected results. I thought that there would be a number of canceled plays present in the second analysis however there were none present in the data and it caught me off guard. I thought I made an error so I went to the raw data and filtered out outcomes by canceled. This helped me confirm that the steps I took in the analysis were correct.

---
## Results
### Theater Outcomes by Launch Date
After analyzing the line chart I created for Theater Outcomes by Launch Date, I concluded that theater Kickstarters were being launched at a higher rate during the spring and beginning of summer time with May having the largest number of projects with successful outcomes. This is probably due to warmer weather and people being more inclined to go out. A second observation I had is that canceled theater projects were not greatly affected by the time of year. This could be because canceling a project could be a result of multiple factors.
### Outcome based on Goals 
I have concluded from the line chart that generally goals with lower dollar amounts have higher success rates. While this was not the case for goals between the ranges of $35000 to $44999, the number of projects in that range was small and not really substantial.

### Dataset limitations
One limitation in the data set I noticed was that there were a number of outliers present with projects that had very unrealistic monetary goals. With some project goals exceeding a million dollars and others asking for one dollar, the data could have been distorted from these questionable projects. I think a new table that be created for futher analysis could be using a Box Plot of successfully funded plays in the US.
