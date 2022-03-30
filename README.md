# group10_project

![image](https://user-images.githubusercontent.com/90135381/158727737-2db68a11-9ee9-40e7-986e-71c8bb8369c7.png)





***IMAGE*** obtained from: https://lovepik.com/image-401202582/real-estate-investment.html

________________


 **General Topic: Real Estate in Canada**
 ________________________________

***OVERVIEW:***

The motivation for this project is to ultimately integrate all of the knowledge obtained and pertain it to real life situations utilizing statistics, data (pre)processing and Machine Learning (ML) procedures to create relevent and predictive models regarding this topic. The final model will be presented utilizing vizualizations for ease of conveying the aforementioned. A collaborative effort is being initiated to consider the topic of housing price indices, income, availability, and immigration across Canada, as this is a pertinent and essential topic among people in this day and age! 2011-2019

https://www.nbc.ca/content/dam/bnc/en/rates-and-analysis/economic-analysis/housing-affordability.pdf

## **Questions with data:**

- does immigration or population have a greater impact on housing prices provincially, in Canada?-2x linear regression

- Which province is the best province to purchase a house in for investment/personal purposes?-tableau

- How does household income determine housing selection and location?-linear reg/TBD

- How does immigration effect the residential property price index across Canada?TBD

## **Additional Questions:**

- How does crime rates effect provincial population/housing prices?

- How does secondary school availability effect population/house prices?

- How does provincial greenhouse gas effect population/house prices?

## **We chose this question because:**

- affordability concerns for first-time buyers/younger adults

- population alterations and migration trends across Canada

- municipal/national housing: trending if housing supply meets demands


## **UPDATED ERD**
This updated ERD depicts the relational ties between the nine tables cleaned and  created in a Database in preparation for analysis. With the common denominators being year and province, etc it will be determined how crime rate, greenhouse emmisions, number of post secondary educational institutions, household income, immigration income and population, as well as educational institution tuition help to shape the choice of where to live and the effects on housing prices per province. The nine tables are as follows:

1. avg_house_prices
2. crime_rate
3. educational_institutions
4. greenhouse
5. household_income
6. immigration_median_income
7. immigration_population
8. tuition

<img width="1440" alt="Updated ERD" src="https://user-images.githubusercontent.com/90135381/160885882-59ffcdde-f6e9-4f93-884b-3c9ca2f7120d.png">






## **Data Sources**

- Residential property price index, quarterly 
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810016901

- Components of population change by census metropolitan area and census agglomeration, 2016 boundaries https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1710013601

- Total family income and characteristics of residential property owners by family type
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=4610005101

- Analytical house prices indicators （country)
https://stats.oecd.org/Index.aspx?DataSetCode=HOUSE_PRICES#

- Income of Immigrant tax-filers, by immigrant admission category and tax year, for Canada and provinces, 2019 constant dollars
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=4310002601

- Average house prices in Canada from 2014 to 2020 with a forecast up to 2022 with, by province https://www.statista.com/statistics/587661/average-house-prices-canada-by-province/

- National Price Map
https://www.crea.ca/housing-market-stats/national-price-map/

- Incident-based crime statistics, by detailed violations, Canada, provinces, territories and Census Metropolitan Areas https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510017701&pickMembers%5B0%5D=1.2&pickMembers%5B1%5D=2.1&cubeTimeFrame.startYear=2015&cubeTimeFrame.endYear=2019&referencePeriods=20150101%2C20190101

- Number of Provincial Educational Institutions
https://www.cicic.ca/869/RepertoireEtablissements.aspx?sortcode=2.25.26.26.27.28&p=1%2c2%2c3%2c4%2c5%2c6%2c7%2c13%2c8%2c9%2c10%2c11%2c12&t=1%2c2

- Physical flow account for greenhouse gas emissions, Frequency: Annual, Table: 38-10-0097-01 (formerly CANSIM 153-0114) Release date: 2021-12-13, Geography: Canada, Province or territory: 	https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3810009701		
________
***RESULTS:***

***DELIVERABLE 1***

The results for Deliverable 1 encompass team collaboration via slack and with the Teaching Staff, in order to accomplish the goals. GitHub establishment requirements will be met including: initialization of an appropriate repository, addition of all branches and a README. Additionally, cleaning and pre-processing the data will be considered. A 'mockup' database will be included, as well as a potential 'mockup' ML model. Lastly, an example ERD will be included for this submission to meet all requirements. A SCRUM method of approach will be contemplated in order to attain all goals with optimal results.

***DELIVERABLE 2***

For this Deliverable, there will be augmentations for 5 requirements:

1) PRESENTATION: with project outline, topic and why we chose the questions, data source, description of data exploration and analysis, google slides

- Link to presentation: https://docs.google.com/presentation/d/1u-Dq1I57YpX5nCJLc6dQAZWPwopah6UY30V5wysAfAc/edit?usp=sharing
Links to scribblemaps:

- Interactive Map of Ranked Provincial Populations (2015-2019)

https://www.scribblemaps.com/create/?gclid=CjwKCAjwuYWSBhByEiwAKd_n_mWpBTjhfwRO0qDbu9-bN8FImiDovtxHWmCMPVT0wdCKbbPEdYf9tBoCOXUQAvD_BwE#/id=lErWy8Ic1v&lat=56.70160853&lng=-98.30477881&z=4&t=custom_style

<img width="1440" alt="Interactive Provincial map with Populations (2015-2019)" src="https://user-images.githubusercontent.com/90135381/160724888-714fc065-a9e4-4c3c-8bc7-ab0301ed2039.png">


- Interactive Map of Provincial House Prices (2015-2019)


https://www.scribblemaps.com/create/?gclid=CjwKCAjwuYWSBhByEiwAKd_n_mWpBTjhfwRO0qDbu9-bN8FImiDovtxHWmCMPVT0wdCKbbPEdYf9tBoCOXUQAvD_BwE#/id=JCrtVfTC3R&lat=53.797534&lng=-94.67929053&z=4&t=custom_style


<img width="1440" alt="Screen Shot 2022-03-28 at 3 25 18 PM" src="https://user-images.githubusercontent.com/90135381/160724911-23a5784b-bb89-487e-8f81-6e1c6a9dcc80.png">



2) GitHub: working code for exploratory and ML updated README, communication protocols, project outline, branches/person with 4 commits per person

3) ML model: preliminary preprocessing, feature engineering and feature description with decision-making process, train and test data description, model choice with limitations and benefits

4) DB: fully integrated DB connecting to the model, 1+ joins, one connection string, updated ERD

5) DASHBOARD: blueprint, storyboard on GoogleSlides, tools and interactive slides description

## **ML Model**

 - Description of preliminary data preprocessing
   - Data cleaning: Remove the irrelevant observations from collect data, including the null value and duplicate data.  Check the outlier? (Box and whisker plot)
   - Data intergration: combime independent variable and dependent variable each year as one table (2015-2019)
     -	Independent variable: provincial population, crime rate, household income,   greenhouse emission, number of colleges
     -	Dependent variable: house price 
   - Data reduction: reduce dimensionality (reshape/scale)
   - Data type transfer: change string to float type

- Description of preliminary feature engineering and preliminary feature selection, including their decision-making process 
   - Take each line as a group, for a total of 50 groups. In 2015, 5 selected characteristics were analyzed to derive each characteristic's impact (correlation) on house prices. and list the corresponding graphs (heatmaps, scatterplots, histograms)

- Description of how data was split into training and testing sets
   - Two years of data are used as the training set, and the remaining three years are used as the test set. Check whether the impact of each year's characteristics on housing prices has changed significantly or remains at a stable level.
   
- Explanation of model choice, including limitations and benefits 
  - Model: multi-variable regression
  - Description: the outcome of the analysis is continuous by each year to figure out the different variables that affect the house price. Therefore, we use the supervised learning method. In addition, our team discovered ten provinces. Each province has 5 of the same factors that affect house prices each year, so multi-variable linear regression can help us analyze the results.
  -	Limitation
    -	The model can only show the effects of selected features and cannot analyze factors that were not selected.
    -	It is challenging to model nonlinear data or polynomial regression with the correlation between data features.
  -	Benefits
    -	Visually show the impact of each element on house prices
    -	Verify if these factors affect house prices to the same extent each year

## **Database**
Postgres and SQL

## **Vizualizations** 
Tableau, Scribblemaps, Google Slides, Python/Vsc, Pandas



________________
________________



## **Participant Names and roles**

- David Baek - Database

- Siddhant Arora - Machine learning model

- Zhiyi Chen - Machine learning model

- Dylan Ruff - Database 

- Tanya Czeban - Github maintain, dashboard, google slides

webpage?
