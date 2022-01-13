# University of Notre Dame-Probability and Statistics Case Study
Probability and Statistics Case Study as part of University of Notre Dame M.S in Data Science

Problem Introduction
Data = 

Barter Jacks recently opened a location in South Bend, Indiana, close to Notre Dame’s campus.  They ask patrons to sign up for their frequent shopper card to learn more about their customer’s shopping patterns.  Since opening 3 months ago, they have had 191 patrons sign up for their frequent shopper card.  They have recruited you to make sense of some of the data that they have collected so far.

The dataset can be found in the Git Repository, and contains the following variables:

Gender – Whether the patron identifies as male or female
Age – The patron’s current age, calculated by the birthdate they provided (not in the data set)
Zip Code – The zip code for the address that the patron provided
Purchases – The number of times the frequent shopper card has been scanned for a purchase
AvgPurchase – The average amount that the patron has spent on purchases while using their frequent shopper card.
WinePurchase – An indicator variable as to whether the patron has purchased a bottle of wine in any of the transactions where their frequent shopper card has been scanned.
 

Define the Problem = 

When the manager gave you the data, she told you “My hope for this project is to gain some insight into my customers, improve sales and bring more people into the store.” 

The following questions are intended to get you started on exploring the data and provide you with information that you could share with the manager.  These are the minimum elements for this case study.  If you feel you need to do more exploration and testing in order to adequately meet the needs of the manager, then you should.

What to Complete
1. Defining the Population of Interest
   - What is the population that this sample represents? That is, to whom can we make generalizations using this data?
 
2. Exploratory Data Analysis
   - For each of the variables: Gender, Age, Zip Code, Purchases, Average Purchase and Wine Purchases, determine if the variable is quantitative or qualitative.
   - Create a histogram and describe the distribution (shape, center and spread) for each of your quantitative variables. Provide at least 3 insights that these graphs have    
     provided you.
   - Create a bar chart for each of your categorical variables. Provide at least 3 insights that these graphs have provided you.
   - Create a scatterplot with Purchases as the independent variable and Average Purchase as the dependent variable. Describe the relationship (Pattern, Direction and Strength)      between these two variables.  Provide the correlation.
   - Create side by side box plots for Average Purchase, based on whether or not the patron has had a wine purchase.  Comment on the relationship that you observe.
 

3. Modeling
   - The number of purchases is a count of how many purchases the patron has made and scanned their frequent shopper card. Propose a distribution for this data (including values       for the parameter(s)).  Show that your proposed distribution fits the given data.
   - If you divide the ages by the maximum age (78) you will get values between 0 and 1. Determine the values for  and  in the Beta distribution that provide a good model for        these scaled ages.  Show that your proposed distribution fits the given data.
 

4. Inferential Statistics
For parts A through C:
   - State the appropriate statistical test for the stated problem,
   - Check conditions for inference for that test,
   - Conduct the appropriate hypothesis test, and
   - Interpret the results of the test.
   
  (a). In glancing at the graphs you provided the manger earlier, from your exploratory data analysis, she noticed that many of her customers come from the zip code 46628. She  
       would like to know if the population of people from this zip code have an average total spending more than $350.  Hint: you will have to calculate total spending for 
       patrons in order to do this problem.
  (b). The store manager knows that the store is located on the border of zip codes 46556 (Notre Dame) and 46617 (a part of South Bend). Because of the convenience she knows 
       that people are more likely to stop in regularly from these locations.  She would like to know if the proportion of patrons that have at least 10 purchases is more for 
       patrons from zip code 46556 than from zip code 46617.
  (c). Patrons from zip code 46556 tend to be college students, whereas patrons from 46617 could be college students or local residents. Because of the difference in 
       demographics, she would also like to know if there is a difference in the average amount spent between these two zip codes.
  (d). Barter Jacks is known for their inexpensive wines, which despite their price, make the store a lot of money. When students go home for the summer, wine sales normally 
       drop.  The manager would like to determine a marketing scheme for wine sales.  In particular, she wants to know if she should target one gender or both with the 
       marketing.
    - Determine the sample odds ratio for females that have purchased wine, versus males that have purchased wine. Interpret this value.
    - Create the confidence interval for the population odds ratio for females that have purchased wine versus males that have purchased wine. Interpret the results of this 
      confidence interval.
    - Conduct the Chi-square test for independence between gender and having purchased wine and interpret your results
 

5. Summary
Write a one to two page report to the manager describing insights from the data and suggestions from your tests that could help her with her goals.  You may assume that the manager understands the basics of a hypothesis test, but cares more about answers than calculations.  Make sure to address any concerns with data collection and how that could impact the results.  Provide at least 2 suggestions for collecting better data for future analysis.
