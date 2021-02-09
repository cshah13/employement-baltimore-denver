# Comparing Workforce Opportunities in Baltimore, Maryland and Denver, Colorado with Opportunity Atlas Data
Analysis of workforce opportunities in Baltimore, Maryland and Denver, Colorado to understand the vast lifestyle differences in the two cities

## Background Information
This project aims to analyze workforce opportunities in Baltimore and Denver to better understand the difference in lifestyles. I am interested in identifying the root causes of poverty to identify ways to increase opportunities for success in communities. I chose these specific cities because Denver is my hometown and Baltimore is my collegetown.

When analyzing [a news article from the Baltimore Sun about Baltimore's unemployement problem](https://www.baltimoresun.com/opinion/op-ed/bs-ed-op-0115-baltimore-unemployment-20200115-urcqmi467vcqnlw4usgtonzwja-story.html), it is clear that many individuals in Baltimore do not have the same opportunities that many people across the country have. The article highlights that six years after graduating high school, the class of 2009 had a median income of $15,000, which makes it extremely difficult to pay for basic neccesities. [Baltimore City Schools](https://www.baltimorecityschools.org/district-overview) provide free/reduced lunch to all students, as financial need is typically underreported in the city. When comparing this to [Denver Public Schools](https://www.dpsk12.org/about/facts-figures/#meals), 61.73% of students qualify for free/reduced lunch. An [article published by The Denver Channel](https://www.thedenverchannel.com/news/local-news/denver-ranked-no-2-on-u-s-news-worlds-report-list-of-best-places-to-live), states that Denver was ranked the second best place to live in the United States according to a US News & World Report. The city ranked 8.8/10 for desirability and 7/10 for quality of life. The livelihood in Baltimore seems to vary greatly from Denver, as Denver has a thriving tech industry that is continuing to grow. The city expects a drastic increase in tech jobs in the coming years. Since preliminary research shows a difference in income and lifestyle in Baltimore and Denver, this project aims to analyze data from [The Opportunity Atlas](https://opportunityatlas.org) to understand the differences in workforce opportunities that could be associated with the livelihood differences in these two major cities.

## Business Question
What differences in workforce opportunities are leading to livelihood differences in Baltimore and Denver?

## Open Data 
This analysis uses data from [The Opportunity Atlas](https://opportunityatlas.org) which provides social mobility data from 20 million anonymous individuals. The following data sets were analyzed for both Denver and Baltimore. All original data sets can be found on the Excel sheet [here](https://github.com/cshah13/employement-baltimore-denver/blob/main/Original%20Data%20Baltimore%20Denver.xlsx).
- Household Income (average household income from 2014-2015)
- Employement Rate (fraction who have positive earnings in 2015)
- Density of Jobs in 2013 (number of jobs per square mile in 2013)
- College Graduation Rate (fraction who hold a four year college degree)

## Data Analysis Questions
We will use Microsoft Excel to answer the following questions:
1. How does the average household income differ in Baltimore and Denver?
1. How do the employement rates rates differ in Baltimore and Denver?
1. What does the availability of jobs look like in Baltimore and Denver?
1. What percentage of the people in each city earned a college degree?

## Data Answers

### How does the average household income differ in Baltimore and Denver?
When looking at different factors surrounding employement, we can begin by comparing the average household income in the two cities. [The pivot table, graphs, and formulas](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Household%20Income%20Analysis.xlsx) used for this comparison show that the average household income in Denver is higher than the average income in Baltimore. The median household income in Baltimore is $30,586.5 compared to $37,660.75 in Denver. Although the differences do not seem vast, the range of income in Denver is only $41,723 compared to a much higher range of $54,646 in Baltimore. This confirms the background research that there is a clear income gap that could impact livelihood differences.

### How do the employement rates rates differ in Baltimore and Denver?
When analyzing the employement rates in the two cities, the numbers are quite similar. An average of 76% of the population in Denver is employed compared to 73% in Baltimore. This data shows that the number of people who are employed is not a large contributing factor to livelihood differences. [A data analysis with a pivot table, graph, and formula](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Employement%20Analysis%20.xlsx) was used for this question.
### What does the availability of jobs look like in Baltimore and Denver?
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Denver%20Job%20Density.png)
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Baltimore%20Job%20Density.png)
Job density varies greatly in the two cities. Both graphs are skewed to the left and have a small number of jobs available in a majority of neighborhoods within the city. Please note that although the cities are arranged in ascending order on the graphs, the data would not be skewed if the data was arranged differently. The important point to note is that there are a few neighborhoods in each city that have much higher job density than a majority of the areas in the city. Since the data is skewed, the median was calcuated instead of the mean. The median jobs available per square mile in Baltimore is 1275.5 compared to 2361 in Denver. This is a large difference, as Denver has almost double job density than Baltimore. Although the previous question shows employement rates to be similar, the lack of jobs in Baltimore could be a factor contributing to low household incomes, as there are less well paid opportunities to seek. The complete data analysis can be found [here](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Job%20Density%20Analysis.xlsx).

### What percentage of the people in each city earned a college degree?
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/College%20Degree%20Rates.png)


After [rearranging the data and creating a pivot table](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/College%20Degree%20Rates%20Analysis.xlsx) to view college degree information, we can see that Denver has a 10% higher amount of people with a college degree. This could be a contributing factor to the ability for people in Denver to obtain higher salaries, thus higher household incomes.
## Business Answer
The numerical findings show that _there are greater workforce opportunities in Denver that could be contributing to the different lifestyles in each city_. Denver has more people with college degrees, greater job density, slightly higher employement rates, and higher household incomes. The larger proportion of people with college degrees could be associated to the higher household incomes. Since employement rates are only different by 3% but Denver has almost double the job density compared to Baltimore, there could be others factors such as commuters that aren't being analyzed. Further analysis is needed to understand if there is a correlation between these factors. Further data outling the types of jobs available in each city will be helpful to better understand the income gap. To build on these findings, additional data such as government assistance and investement in education can be analyzed to identify the underlying causes behind the differences in workforce opportunities. These findings show that there is work that needs to be done to provide more opportunities for residents in Baltimore. This could include government programs focusing on career preperation skills. This information is important to me, as I aspire to work in public sector to help create systemic changes. It is important to understand the underlying causes behind the problems to establish programs that could make a difference.
## Step by Step Instructions
Below are the steps that were taken to complete this data analysis:
1. Downloaded Maryland/Colorado Employement data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a bar graph for each city, used the AVERAGE formula to find mean employement rates in each city
1. Downloaded Maryland/Colorado Household Income data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a line graph for each city, used the MEDIAN formula to find median household income rates in each city, used the (=MAX(data)-MIN(data) formula to identify the range for each city
1. Downloaded Maryland/Colorado Job Density data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a line graph for each city, used the MEDIAN formula to find median employement rates in each city since the graphs were skewed
1. Downloaded Maryland/Colorado College Graduation data, reorganized the neccesary information into one data set, created a pivot table, altered the design to be visually appealing

