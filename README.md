![MN POLITICAL banner](https://github.com/dsad8000/mnpolitical/assets/98616377/a7ad78c2-fe6e-4354-be9f-12a0f59fd14c)
# MN Political Political Ad Analysis
## Descriptive analysis of Google political ads for election ad recommendations to a fictitious Political Action Committee

## **Objective:**
#### The MN Political Board of Directors has contracted me to analyze data from the Google political ads from election years 2018, 2020, and 2022 to make recommendations about budget expenditures for their current and future internet ad campaigns.
Questions guiding the analysis are:
* Which weeks of the year and days of the week are best to run ads?
* How much should be spent on ads?
* How many days should ads run?
* What type of ad (text, image, or video) performs best?
* How does ad performance differ among demographic groups?

## Context
The project was a self-designed capstone project to complete the Coursera Google Data Analytics Certificate. SQL queries in BigQuery were used to clean, filter, and analyze the data, and the data was exported for visualization in Google Sheets.

## **Datasets**
[bigquery-public-data.google_political_ads](https://console.cloud.google.com/bigquery?_ga=2.2789936.1651045075.1687355687-572369547.1687355687&_gac=1.215615205.1687355689.CjwKCAjwv8qkBhAnEiwAkY-ahgGIt8TucK1x6-L3ePvmhdMDs3TFFhemhcc6rB5A_YmQe0z_D0LsNxoCbe0QAvD_BwE&pli=1&project=capstone-advertising-dataset&ws=!1m4!1m3!3m2!1sbigquery-public-data!2sgoogle_political_ads)

## Analysis and Results
[Sample SQL Queries](https://github.com/dsad8000/mnpolitical/tree/main/sql_queries)

<kbd>![image](https://github.com/dsad8000/mnpolitical/assets/98616377/083a80e2-7d6f-40d8-a661-f254cc515b21)<kbd>

<kbd>![image](https://github.com/dsad8000/mnpolitical/assets/98616377/b6730322-d8e0-4b97-a634-f60b96327040)<kbd>

<kbd>![image](https://github.com/dsad8000/mnpolitical/assets/98616377/1deb336f-0335-4aa5-af15-a47b38e18269)<kbd>

<kbd>![image](https://github.com/dsad8000/mnpolitical/assets/98616377/f3375f0f-008b-472e-b355-d66f0d17b77c)<kbd>

<kbd>![image](https://github.com/dsad8000/mnpolitical/assets/98616377/3328d94f-fa72-4fb2-ab9b-cb6df4ae12e8)<kbd>

## Recommendations
[Full report on Medium](https://danielle-sadler.medium.com/mn-political-election-ad-analysis-8175f31b8393)
#### Based on the previous election years' data analyzed here, my recommendations are:
* Ads that start on and after April 25, 2022, and April 22, 2024 will receive more impressions than those before. Ads starting on Wednesdays and Saturdays receive more impressions than those starting on other days of the week.
* The data was inconclusive about amount to spend on ads, but data showed that spending more per week didn't correspond to receiving more average weekly impressions on ads.
* There was also not a correlation to receiving more weekly impressions based on number of days an ad was run.
* Text ads are vastly out-performing image and video ads in average weekly impressions in 2022. Text ads should make up the bulk of MN Political's ads for the remainder of 2022 and into 2024, when ad types can be re-evaluated based on large differences in performance of ad types in past years.
* Average weekly impressions increase with both age- and gender-targeting.
