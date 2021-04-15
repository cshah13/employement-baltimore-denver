# Comparing Workforce Opportunities in Baltimore, Maryland and Denver, Colorado with Opportunity Atlas Data
Analysis of workforce opportunities in Baltimore, Maryland and Denver, Colorado to understand the vast lifestyle differences in the two cities

## Background Information
This project aims to analyze workforce opportunities in Baltimore and Denver to better understand the difference in lifestyles. I am interested in identifying the root causes of poverty to identify ways to increase opportunities for success in communities. I chose these specific cities because Denver is my hometown and Baltimore is my collegetown.

When analyzing [a news article from the Baltimore Sun about Baltimore's unemployment problem](https://www.baltimoresun.com/opinion/op-ed/bs-ed-op-0115-baltimore-unemployment-20200115-urcqmi467vcqnlw4usgtonzwja-story.html), it is clear that many individuals in Baltimore do not have the same opportunities that many people across the country have. The article highlights that six years after graduating high school, the class of 2009 had a median income of $15,000, which makes it extremely difficult to pay for basic neccesities. [Baltimore City Schools](https://www.baltimorecityschools.org/district-overview) provide free/reduced lunch to all students, as financial need is typically underreported in the city. When comparing this to [Denver Public Schools](https://www.dpsk12.org/about/facts-figures/#meals), 61.73% of students qualify for free/reduced lunch. An [article published by The Denver Channel](https://www.thedenverchannel.com/news/local-news/denver-ranked-no-2-on-u-s-news-worlds-report-list-of-best-places-to-live), states that Denver was ranked the second best place to live in the United States according to a US News & World Report. The city ranked 8.8/10 for desirability and 7/10 for quality of life. The livelihood in Baltimore seems to vary greatly from Denver, as Denver has a thriving tech industry that is continuing to grow. The city expects a drastic increase in tech jobs in the coming years. Since preliminary research shows a difference in income and lifestyle in Baltimore and Denver, this project aims to analyze data from [The Opportunity Atlas](https://opportunityatlas.org) to understand the differences in workforce opportunities that could be associated with the livelihood differences in these two major cities.

## Business Question
What differences in workforce opportunities could be leading to livelihood differences in Baltimore and Denver?

## Open Data 
This analysis uses data from [The Opportunity Atlas](https://opportunityatlas.org) which provides social mobility data from 20 million anonymous individuals. The following data sets were analyzed for both Denver and Baltimore. All original data sets can be found on the Excel sheet [here](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Original%20Data%20Baltimore%20Denver.xlsx).
- Household Income (average household income from 2014-2015)
- Employment Rate (fraction who have positive earnings in 2015)
- Density of Jobs in 2013 (number of jobs per square mile in 2013)
- College Graduation Rate (fraction who hold a four year college degree)

## Data Analysis Questions
We will use Microsoft Excel to answer the following questions:
1. How does the average household income differ in Baltimore and Denver?
1. How do the employment rates rates differ in Baltimore and Denver?
1. What does the number of jobs available per square mile look like in Baltimore and Denver?
1. What percentage of the people in each city earned a college degree?

### PYTHON WAS USED TO RE-ANSWER THE FOLLOWING QUESTIONS
1. What does the number of jobs available per square mile look like in Baltimore and Denver? [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_Job_Analysis.ipynb)
2. What percentage of the people in each city earned a college degree? [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_College_Analysis.ipynb)

## Data Answers

### How does the average household income differ in Baltimore and Denver?
![altext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Income%20Chart.png)

When looking at different factors surrounding employment, we can begin by comparing the average household income in the two cities. [The pivot table, graphs, and formulas](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Household%20Income%20Analysis.xlsx) used for this comparison show that the median household income in Denver is higher than the average income in Baltimore. The median household income in Baltimore is $25,970 compared to $37,660.75 in Denver. This is a difference of almost $12,000. The range of income in Denver is $41,723 compared to a much higher range of $54,646 in Baltimore. This shows that there are clear income gaps and inequalities present in Baltimore that could impact livelihood differences in the two cities.


### How do the employment rates rates differ in Baltimore and Denver?
When analyzing the employment rates in the two cities, the numbers are quite similar. An average of 76% of the population in Denver is employed compared to 71% in Baltimore. This data shows that the proportion of people employed does not greatly differ in the two cities, so it does not seem to be a large contributing factor to livelihood differences. [A data analysis with a pivot table, graph, and formula](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Employment%20Analysis%20.xlsx) can be viewed for further information.

### What does the number of jobs available per square mile look like in Baltimore and Denver?
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Denver%20Jobs%20Available.png)
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Jobs%20Available%20Baltimore.png)
The number of jobs available per square mile varies greatly in the two cities. Please note that although the neighborhoods are arranged least to greatest on the graphs, the data can be arranged differently. The important point to note is that there are a few neighborhoods in both Baltimore and Denver that have a much higher number of jobs available per square mile compared to a majority of other areas within the city. Since the data has potential outliers, the median was calcuated instead of the mean. The median jobs available per square mile in Baltimore is 1459 compared to 2361 in Denver. This is a large difference, as Denver has almost 1000 more jobs avaialable per square mile compared to Baltimore. It is interesting to see that the previous question shows employment rates to be similar, but the job availability varies greatly. The lack of jobs in Baltimore could be a potential factor contributing to lower household incomes, as the city could have less high paid opportunities available. The complete data analysis can be found [here](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Number%20of%20Jobs%20Analysis.xlsx).

#### PYTHON ANALYSIS
View Google Colaboratory Here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_Job_Analysis.ipynb)

![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Denver%20Jobs%20Python%20Graph.png)
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Batimore%20Jobs%20Python%20Graph.png)

This same analysis was conducted on Python. The [full data analysis on Google Collab can be found here](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_Job_Analysis.ipynb). Both graphs for  Baltimore and Denver can be seen above. When creating the graphs in Excel, the software automatically formated the x-axis to be organized, hindering all location names to be shown in the axis. Using Python required more steps to format the graph, but more location names are viewable. Furthermore, Python was easier to use, as altering a code immediately provided the desired outcome rather than needing to navigate through various formulas and buttons on Excel. Although it was a timely process to accurately manipulate the code, the graph from Python looks more professional and detailed.

### What percentage of the people in each city earned a college degree?
![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/College%20Degree%20Rates.png)


After [rearranging the data and creating a pivot table](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/College%20Degree%20Rates%20Analysis.xlsx) to view college degree information, we can see that Denver has a 10% higher amount of people with a college degree. This could be a contributing factor to the ability for people in Denver to obtain higher salaries, thus higher household incomes.

#### PYTHON ANALYSIS
View Google Colaboratory Here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_College_Analysis.ipynb)

![alttext](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/College%20Degree%20Graph.png)

The college degree data was further developed through a Python analysis. The [data analysis conducted on Google Collab can be viewed here](https://github.com/cshah13/workforce-opportunities-baltimore-denver/blob/main/Shah_Baltimore_Denver_College_Analysis.ipynb). A bar chart was created to directly visualize and compare the differences in the two cities. We can see the 10% difference clearly on the Python graph. It was easier to create a neat visualization on Python, as the software automatically creates a visually appealing output. In Excel, the output needs to be heavily manipulated to become visually appealing. This graph is  clear and a better visualization for college degree holders in Denver and Baltimore. 

## Business Answer
The numerical findings show that _there are greater workforce opportunities in Denver that could be associated with the different livelihoods in each city_. Denver has more people with college degrees, greater number of jobs available per square mile, slightly higher employment rates, and higher household incomes. The greater proportion of people with college degrees in Denver could be associated with the higher household incomes. Since employment rates are only different by 3% but Denver has a greater number of jobs available per square mile compared to Baltimore, there could be others factors such as commuters that aren't being analyzed. Further analysis is needed to understand if there is a correlation between these factors. Since Baltimore has a higher household income range than Denver, additional data outling the types of jobs available throughout each city will be helpful to better understand the income gap. To build on these findings, additional data such as government assistance and investement in education can be analyzed to identify the underlying causes behind the differences in workforce opportunities. These findings show that there is work that needs to be done to provide additional workforce opportunities for residents in Baltimore and Denver. This could include government programs focusing on career preperation skills. This information is important to me, as I aspire to work in public sector to help create systemic changes. It is important to understand the underlying causes behind the problems to establish programs that could make a longlasting difference in both Denver and Baltimore.

#### PYTHON ADDITIONS 
The Python analysis led to the same findings since the data was the same. Denver has a greater number of jobs available per square mile along with more people with college degrees. This information is useful for governments and nonprofit organizations to further analyze the underlying differences between the two cities to understand why the gaps exist. For example, if higher education is not promoted as much in Baltimore Public Schools, the government can focus more attention on higher education preparation to increase the proportion of the population with college degrees in Baltimore. In the Python analysis, the graphs are more visually appealing compared to the graphs from Excel. I extended the analysis by adding a graph to show the proportion of the population who earned a college degree in Baltimore and Denver. Although the findings are the same, the Python graph allows the audience the better visualize the findings. By using a graph as opposed to a table, we can see the direct differences in the proportion of college degree holders between the two cities. This new graph should be presented to government and non profit organizations to efficiently show the gap in college degree holders between Baltimore and Denver. Although Denver has a higher amount of college degree holders and jobs available compared to Baltimore, there is still work that needs to be done to increase the rates in both cities. To build on these findings, additional data such as government assistance and investment in education can be analyzed to identify the underlying causes behind the differences in workforce opportunities in Baltimore and Denver. Based on the findings, programs can be implemented to increase the availability of jobs and number of people with college degrees in each city.

I noticed that Excel was easier for reorganizing the data, but Python was easier for creating visualizations. In the future I can download and sort data in Excel prior to analyzing the data in Python. In the future, I can also use Python to add onto this analysis by creating a double line graph that shows how each indicator has changed overtime. This will allow the government to see the progress each city is making to better understand the efforts that are still needed.

## Step by Step Instructions
Below are the steps that were taken to complete this data analysis:
1. Downloaded Maryland/Colorado Employment data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a bar graph for each city, used the AVERAGE formula to find mean employment rates in each city
1. Downloaded Maryland/Colorado Household Income data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a line graph for each city, used the MEDIAN formula to find median household income rates in each city, used the (=MAX(data)-MIN(data) formula to identify the range for each city
1. Downloaded Maryland/Colorado Job Density data, created a pivot table for each state, changed the format from sum to average, filtered the data to only view Baltimore/Denver, created a line graph for each city, used the MEDIAN formula to find median employment rates in each city since the graphs were skewed
1. Downloaded Maryland/Colorado College Graduation data, reorganized the neccesary information into one data set, created a pivot table, altered the design to be visually appealing

### PYTHON STEPS
The steps taken to conduct the Python analysis can be seen in the Google Collab link that corresponds to the specific data question.
