Movie Studio Strategy Analysis ,
Project Overview
This project conducts a comprehensive analysis of the movie industry to uncover actionable insights for stakeholders looking to enter the market. By leveraging data from multiple sources including Box Office Mojo, IMDB, and movie_gross, we explore trends in financial performance, audience reception, and market dynamics. The goal is to guide a new movie studio in deciding what types of films to create by identifying which genres and strategies are currently most successful.

Project Team Members:
Akonon Bagat, 
Alvin Mwenda, 
Augustine Magani ,
Isabella Siele,
Nicole Otieno,
Stephen kimani,

Problem Statement.

The company needs to pinpoint what types of movies are most successful in the current market to propel the new studio's launch. Specifically, the project aims to:

Identify the genre with the highest profitability (Genres vs ROI, gross, budget)

Analyze the relationship between production scale and profitability (Budget vs ROI, gross)

Evaluate the impact of release timing on movie financial success (Release Quarter vs ROI)

Explore how movie length impacts profitability (Runtime vs ROI)

Data Understanding

This project utilizes box office and movie metadata from publicly available datasets. The primary variables analyzed include:

Movie Title – Name of the film

Genre – Category or categories the movie belongs to

Budget – Production cost of the film

Worldwide Gross – Total global box office earnings

Domestic & International Gross – Regional earnings breakdown

Runtime – Length of the film in minutes

Release Date – Used to derive release quarter and seasonality patterns

Studio – Production or distribution company

Data cleaning steps include handling missing values, removing duplicates, standardizing date formats, and computing derived metrics such as ROI.

Data Visualizations & Insights
1. Budget vs Revenue

The scatterplot indicates a strong positive correlation (r = 0.75) between production budget and total revenue. Higher-budget films typically earn more, although the spread in the data shows that simply spending more does not ensure blockbuster results.

Insight: Budget strongly influences revenue potential, but studios must still manage risk carefully.

2. Genre vs ROI, Gross, and Budget

This visualization compares genres across three dimensions: production budget, worldwide gross, and ROI.

Key Insights:

Horror stands out with extremely high ROI and low budgets, making it a top performer in terms of profitability.

Family and Fantasy films achieve very high worldwide gross but require large budgets.

Animation and Adventure deliver strong global performance with moderate ROI.

Western and Music genres underperform in both ROI and gross.

Conclusion: Profitability does not always correlate with production scale—low-cost genres can outperform expensive ones. High-budget genres generate substantial revenue but carry higher financial risk.


