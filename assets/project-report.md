# Data Analytics Project Report

## Introduction

This project looked at the data on global defense companies to see if it could uncover insights into world complicts, geopolitical alliances, economic and military groupings, and market trends. The project looked at three datasets on global defense manufacturers that covers revenue rankings, historic stock data, and segregation by country, regional, economical and political blocs.

## Project Goals

The goals of the project are:

- Enhance my understanding of data analytics and how to apply it to real-world problems
- Gain some practical experience into chosing the right tools and libraries for a given problem
- some insights into the correlationships between global defense manufacturers, geopolitical alliances, regional groupings and conflicts around the world

## Target Audience

Any one interested in learning or applying data analytics to gain insights into their specific problem or interested in gaining insights into the correlation between global defense manufacturers, geopolitical alliances, economic groupings and conflicts around the world.

## Project Methodology

The methodology used for the project was to source data from Kaggle, then break down the project tasks into items that could be managed through GitHub Projects.

A brainstorming session was conducted to work out the flow of the tasks, how and when they should be completed.  The Kanban flow board allows easy management and monitoring of items in an agile manner, helping to identify bootlenecks and how to deal with them.

The project will be fully documented with contents in README.md and project-documment.md files.  These documents will be continuously updated from the start to the end of the project.

## Data Sourcing

The datasets for the project was sourced at Kaggle. The dataset is based on the SIPRI Top 100 Arms-Producing and Military Services Companies (2023) and was kindly provided by Shreyansh Dangi at the following link [Top 100 Defense Companies Historical Data](https://www.kaggle.com/datasets/shreyanshdangi/worlds-top-100-defense-companies-historical-data?select=All+Listed+Companies+Combined+Historical++Data.csv)

## Data Loading and Exploration

Three complementary datasets were collected from Kaggle, uploaded unto a Juperter Notebook to enable the initial data exploration to begin.

The datasets include:

1. All Listed Companies Combined Historical Data (defense-company-industry-data.csv) - this contains historical stock data and dates.
2. SIPRI Top 100 Defense Companies Official List (defense-company-sipri-data.csv) - this contains revenue and rankings.
3. Listed Companies CountryWise Segregation (defense-company-country-data.csv) = this contains categorical data.

## Data Cleaning and Preprocessing

The data was cleaned and preprocessed to prepare it for data visualisation and predictive analytics tasks ahead. Luckly the datasets are fairly clean and complete. Only the date needs changing to datetime data type.  We also looked for missing values and droped them when we came to predictive analytics.

## Data Visualisation

The datasets were explored using a number of data visualisation techniques.  We start with the basic ones and end with the more interesting ones to see if we can gain insights from the distributions, relationships, correlationships and differences that may exist among some of the features of the dataset to see if we can infer their effects on complicts around the world. The datasets are not complete enough to make accurate inference but if they can be combined with datasets from the World Bank on complicts around the world we could get a better angle on how to mitigate if not end many of these uneccessary conflicts.

## Predictive Analytics

A simple predictive analytics model was built to predict the volume of trade using features such as the the Open, Close, Low and High of the stock price.  A linear regression model was used for the prediction and the model's performance was evaluated using the RMSE and the R² score. There was very little correlation between the selected features and the volume of trade that was used as the target as such it was no surprise that the R² score was very low and the RMSE value very high.

## Project Management and Documentation

The project planning and management was conducted via GitHub Project.  The project was broken down into items using a Kaban flow system with items moving from backlog through ready, in progress to done.  The taken to complete each item can be tracked and the number of commits made during each items can be noted.  The flow of items through the system can be tracked and actions can be taken to deal with bottlenecks or items taken too long than planned.

The project was documented with contents in README.md and project-documment.md files.
These documents were continually updated from the start to the end of the project.

## Conclusion

The project provided me with the opportunity to explore real-world datasets and apply some of the knowledge I gained with the Code Institute to attempt to draw some insights into how defense manufacturers, geopolitical alliances, and regional and economic groupings could impact conflicts around the world.
