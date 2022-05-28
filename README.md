# Project-2-E-news-Business-Project
An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. Companies often analyze users' responses to two variants of a product to decide which of the two variants is more effective. This experimental technique is known as a/b testing that is used to determine whether a new feature attracts users based on a chosen metric.

The design team of the company has created a new landing page. You have been assigned the task to decide whether the new landing page is more effective to gather new subscribers. Suppose you randomly selected 100 users and divided them equally into two groups. The old landing page is served to the first group (control group) and the new landing page is served to the second group (treatment group). Various data about the customers in both groups are collected in 'abtest.csv'. 

Required to perform the statistical analysis to answer the following questions using the collected data
Explore the dataset and extract insights using Exploratory Data Analysis.
Do the users spend more time on the new landing page than the existing landing page?
Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
Does the converted status depend on the preferred language? [Create a contingency table using the pandas.crosstab() function]
Is the time spent on the new page same for the different language users?
Consider a significance level of 0.05 for all tests.

Tools Used
•	Numpy library: Log return 
•	Hypothesis Testing: Scipy Stats library
•	Tests from Statsmodels library: ztest, pairwise, t-test, proportions_ztest, Chi-square test
•	Inferential Statistics: binom methods, uniform methods, norm methods, t methods

Project Coverage
•	Statistical analysis and extract actionable insights from the data

Tasked Performed

•	Explore the dataset and extract insights using Exploratory Data Analysis (histograms, boxplots, barplot, heat maps).
•	Compare the new landing page to old landing page using boxplot to determine which of them users spend more time on
•	Visual analysis using bar plot to determine if the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page
•	Using visual analysis decide if the converted status depends on the preferred language
•	Determined if the mean time spent on the new page same for the different language use
•	Define the null and alternate hypothesis, select appropriate test, decide significance level anddraw inference

Business Insights

•	The users spend more time on the new page compared to the old page.
•	The conversion rate for the new page is greater than the conversion rate of the old page.
•	The conversion status is independent of the preferred language there is no correlation.
•	Based on the conclusions of the hypothesis tests, the news company should use the new landing page to gather more subscribers.
•	The longer a visitor spends on a site, the more likely he/she is to convert. 
•	The business logic would appear to be too design a page that people spend time in, conversion will follow.

