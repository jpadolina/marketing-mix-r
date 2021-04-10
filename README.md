# marketing-mix-r
This repository contains an R project that practices variable and model selection for a marketing mix model. This was an assignment for a Marketing Analytics course.

## Goal
The purpose of this assignment was to analyze the effects of various advertising channels on sales. The analysis and modeling were subsequently followed by a best model and recommended actions for the advertising company in question. Using multiple regression and rudimentary variable selection, I experimented with various transformations and selected variables based on the lowest AIC. Most of the modeling decisions were dictated by the homework instructions. I had control over which variables to add or drop, however.

## Model Selection
AIC and BIC were used as the information criteria by which to evaluate models.

## Data Source
The dataset used contains advertising activity from 10 different channels, plus columns aggregating online and offline channels. This small dataset captures 42 months of activity, representing one row per month. Though the data comes from a real cosmetics company, that company's identity was redacted for the purposes of the assignment.

## Files
"HW2_MultimediaHW" contains the dataset used to model the marketing activities' relationship with sales.
"Modeling R code" is self-explanatory.
"BAX 401 HW2" is the report written by my group summarizing our analysis, modelling, and recommendations.

## Division of work
This was a group assignment. My role in this project was the initial modeler in R, but the whole group had a say in the final modeling decisions, and the report was also written as a group.

## Data Dictionary
ADV_Total -	Total Advertising Spend in the month, comprises ADV_Offline and ADV_Online

ADV_Offline -	Total Offline Advertising Spend, comprises Catalogs_ExistCust, Catalogs_Winback, Catalogs_NewCust in the month

Catalogs_ExistCust -	Amount spent on Shopping Catalogs sent to existing Customers in the month

Catalogs_Winback -	Amount spent on Shopping Catalogs sent to Customers (who have not bought for at least 6 months) in the month

Catalogs_NewCust -	Amount spent on Shopping Catalogs sent to New Customers in the month

Mailings -	Amount spent on Mailings (excluding Catalogs) sent to Customers. Mailing include flyers, postcards and letters in the month

ADV_online -	Total Online Advertising Spend, comprises Banner, Search, SocialMedia, Newsletter, Retargeting and Portals in the month

Banner -	Amount spent on Banner ads in the month

Search -	Amount spent on Search ads in the month

SocialMedia -	Amount spent on Social Media ads in the month

Newsletter - 	Amount spent on Newsletter ads in the month

Retargeting -	Amount spent on Retargeting ads in the month (https://retargeter.com/what-is-retargeting-and-how-does-it-work/)

Portals -	Amount spent on ad portal advertising in the month (https://www.marketingterms.com/dictionary/portal/)
