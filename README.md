# CROP PRODUCTION DATA ANALYSIS- INDIA 
  Crop production data analysis involves examining agricultural data to gain insights into patterns, trends, and factors affecting crop yields. This process uses historical and current 
data related to farming practices, environmental conditions, and economic factors to inform decision-making. By leveraging statistical and visualization techniques, stakeholders like 
farmers, policymakers, and researchers can identify opportunities for improving productivity, sustainability, and profitability in agriculture.
# Main Aim of Crop Production Data Analysis : 
1. Identifying Trends: Understanding long-term and seasonal production patterns. 
2. Optimizing Resource Use: Assessing the impact of inputs like water, fertilizers, and labor on yield. 
3. Improving Forecasts: Predicting crop yields based on weather, soil, and market conditions. 
4. Supporting Decision-Making: Guiding policy formulation and farm-level strategies to ensure food security. 
5. Addressing Sustainability: Balancing production with environmental conservation and resource sustainability.
# Objective : 
  Ultimate goal would be to predict crop production and find important insights 
highlighting key indicators and metrics that influence the crop production. 
# Benefits : 
1. Gives better insight of Production base.  
2. Easy to find out which key factor affects the production. 
3. Find out the Production contribution State wise, Crop wise, Year wise. 
4. Easy to understand Where we can Improve the Production.
# Data Description : 
1. Dataset file name (crop_production.csv)  
The dataset file which contains all the details in the CSV format. 
2. Number of Columns ( 7 digits), 2,42,361 row 
3. Missing values (3730) 
Which are analyzed from the above inferences using Power BI. 
# Where it contains a brief informatives as follows: 
Column names and Data types :  
1. State Name - Text  
2. District Name – Text 
3. Crop Year - Whole number 
4. Season - Text  
5. Crop - Text  
6. Area - Decimal number  
7. Production - Decimal number
# Data Collection and Data Cleaning : 
# Purpose of Data Collection : 
Data collection involves gathering raw data from various sources to build a comprehensive dataset for analysis. Its main purpose is to ensure the availability of relevant and accurate 
information for making informed decisions. Data Collection - Data set Collected from data.world/agriculture india Website. 
# Purpose of Data Cleaning : 
Data cleaning ensures the quality and reliability of the dataset by addressing errors, inconsistencies, and missing values. It prepares the data for accurate and meaningful analysis. 
Data Cleaning - In this Data set I had to Remove the error rows. 
# Null values in columns – Null values were presented in production column. Otherwise there 
was no null values presented, there was no duplicated values. 
# Export Data from csv as db : 
Export data from csv as db for analyzing the data, and Gather Insights from the data using sql server. 
# Data Transformation : 
we have to change the data type of crop year column text data type into date data type using power query in power bi. 
# Analyzing & Ask the Right Questions: 
Analyzing the data using these questions  
1. what is the area distribution of different crops in different states in a particular year? 
2. what is the year wise production of different states in a particular year? 
3. which crop has the highest production over a span of years in a particular state? 
4. what is the growth trend of one crop in respect to another crop in different states?       
5. in which year the production of any given crop was the highest in a given dataset? 
6. what is the crop production state wise, district wise, crop wise, crop wise##?
# Data Visualization : 
# Purpose of Data Visualization: 
The primary purpose of data visualization is to transform raw data into a visual format that is easy to understand and interpret. It bridges the gap between complex 
datasets and actionable insights, enabling stakeholders to make informed decisions efficiently. Makes complex or large datasets easier to interpret through visuals like 
charts, graphs, and maps. Enables users to quickly grasp insights without requiring indepth statistical knowledge. 
# Insights Gathered from the Crop_production Dataset : 
# CROP WISE : 
1. Coconut production is high as compared to other crops. (Given below we can see the top 3 crops overall contribution by production) 
# TOP 3 CROPS CONTRIBUTION  
  1. Coconut - 92.71%  
  2. Sugarcane - 3.55%  
  3. Rice - 1.08% 
2. In 2011 coconut contribution is 10.90%. 
3. Meghalaya rice crop Contribution is increasing year by year . But 2015- 0% contribution. If we take Further steps for improve the Meghalaya rice crop production , There will be a high chances of rice get a high contribution over other states. 
4. Wheat crop Gradually decreased from 2010 – 2015. 
5. Jowar crop Gradually decreased from 1999 – 2014. 
# PRODUCTION BY YEAR WISE : 
# Top 3 years contribution by production : 
 1. 2011 - 10.90% 
 2. 2013 - 9.13% 
 3. 2006 - 6.14% 
1. In 2011 contribution is very high Because the coconut Production is high in Tamilnadu. 
2. In 2013 contribution also high Because the coconut Production is high in Kerala. 
3. In 2006 contribution also high Because the coconut Production is high in Kerala. 
4. In 2003, (Tamilnadu )coconut contribution is 0%, but In 2003 Tamilnadu sugarcane contribution is high. 
5. In 2015 Odisha Contribution is 98.51%. 
6. 1997 – 2006 the overall production is increasing gradually increase. 
7. But In 2007 the production decreased 2 % compare to previous year decrease. 
# Reason: 
1. Coconut contribution decreased 2% Overall 2015 year contribution- 0.007% , 20142015 decreased 6.12%. 
2. In 2007 TO 2015 Production we can see the ups and downs. 
3. In 2008 to 2009 Production decreased because kerala production is very low. 
4. When ever the coconut contribution is high the kerala contribution is also high and there is no fall in the production. 
5. When ever the coconut contribution is low the kerala contribution is also low and the production is decreased. 
6. So, Coconut and Kerala Interchangebly impact the production.  
7. In 2010 the production loss because the coconut production decreased. 
8. In 2011 the production contribution is very high as compared all other years especially Tamilnadu production is 2% high compare to kerala.  
9. Overall 2015 year contribution- 0.007% , 2014-2015 decreased 6.12%. 
10. Wheat crop Gradually decreased from 2010 – 2015 . 
11. Jowar crop Gradually decreased from 1999 – 2014. 
# State wise : 
# TOP 3 States Contribution by production : 
  1. Kerala - 69.33%  
  2. Andhra Pradesh - 12.27%  
  3. Tamilnadu - 8.55%  
1. In 2015 Odisha Contribution is 98.51%. 
2. In 2015 Rice crop production is 84.98% at same time odisha rice crop contribution is 99.67%. 
3. Chandigar production decreased from 1998 – 2010 gradually, 2011 – 2015 ( 0 % contribution) Here we don’t need to take further action. Because the production decreased year by year. 
# Season wise: 
1. 96.69% coconut contribution in whole year season in Tamil nadu. 
2. Whole year contribution is very high as compared to other seasons. 
3. 44.03% sugarcane crop contribution in kharif uttarpradesh state. 
4. In rabi wheat crop contribution is high in Westbengal 64.53%. 
5. Autumn season highest contribution crop is Rice 80.50% in bihar . 
6. Winter season highest contribution crop is rice 87.81%. 
7. summer season highest contribution crop is rice 74% in west Bengal. 
# Conclusion: 
1. Overall In kerala the coconut crop influence the production, when the kerala coconut 
production is low that year overall production is low . 
2. In 2015 The production was very less as compared to 1997.  
3. In 2015 Odisha and Sikkim contribution only available. There was no other states contribution, and In 2015 the winter season RICE crop contribution is very high. 
4. Area distribution is high in Uttar Pradesh as compared to other states and production wise uttar pradesh gets 4th place. 
5. Area wise kerala gets 17 th place when it comes to production kerala gets 1st place. 
6. Kerala coconut crop production is 75.24% and coconut, wholeyear, kerala influence the production. 
7.  In 2011 production is very high as compared to other states because coconut contribution is 10.90%.
