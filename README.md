# MSDS_Casestudy2
MSDS 6306: Doing Data Science Case study 2
Prepared by Anand R and Shantanu G
#Due: Sunday, December 9 11:59pm. 
 
### Background
We are from DDSAnalytics a talent management company specializing in talent management solutions. We do solutions for workforce planning, employee training programs, identifying high-potential employees and reducing/preventing voluntary employee turnover (attrition).


### About our client

Our client Anheuser-Busch is one of the top beer producers in the world with the following vitals to boast. Head quartered in St. Louis MO, the company brews more than 100 brands of beers with flagship brands Budweiser and Bud Light.
Budweiser has an issue with employee attrition and improving employee morale to gain competitive edge in its industry. We are conducting an analysis using the existing employee data.

### Pitfalls of High attrition
1. Losing talented employee with the company's business knowledge
2. Replacing with new employee costs
3. Replaced employee needs to be trained in business
4. Recruiting costs

### Analysis
The goal is to ascertain the HR problem of employee attrition and how we can predict the rate through Machine Learning model.
We were supplied with data set of 1170 rows of data with 34 columns, which we will use to
do the exploratory data analysis and predic the top 3 attributes that would affect the attrition.

  The following steps will be done in that order.

1. Conduct exploratory data analysis
2. Create training and test data sets
3. Build knn classification model to train the training data provided.
4. Minimise the top 10 columns that comprise the model to predict with accuracy
5. Run it thru again to check if they can give top 3 variables that affect attrition
6. Evaluation of the model - we will do several iterations to come up with changing k values
7. Conclusion - draw inferences from the model

===
R version 3.5.1 (2018-07-02)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows >= 8 x64 (build 9200)

Matrix products: default

