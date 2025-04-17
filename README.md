# netflix-content-analysis
Content trend analysis and recommendation insights using clustering and association mining techniques on Netflix data in R.

Netflix Content Analysis & Recommendation Insights Using R

This project explores Netflix’s content trends using data mining techniques including exploratory data analysis (EDA), clustering, association rule mining, and classification. The analysis aims to uncover key viewer preferences and inform recommendation strategies, content acquisition, and platform growth.

##  Objectives
- Explore content types, ratings, durations, and genre trends
- Identify top directors, release year patterns, and user preferences
- Cluster content by `release_year` and `duration` to discover hidden groupings
- Apply association mining to uncover relationships between content attributes
- Support recommendation system design with high-lift itemsets

##  Techniques Used
- **EDA**: Bar plots, histograms, genre frequency, and top directors
- **Clustering**: K-means, Hierarchical clustering with Elbow, Silhouette, and Gap Statistic
- **Association Rule Mining**: Apriori and Eclat algorithms (support, lift, confidence analysis)
- **Classification**: Linear Discriminant Analysis (LDA)
- **Regression**: Relationship between content rating and release year

##  Tools & Libraries
- R, Tidyverse, ggplot2, dplyr, lubridate
- `factoextra`, `NbClust`, `arules`, `arulesViz`, `caret`, `MASS`

##  Files Included
- `Netflix_Content_Analysis.R`: R script with full analysis and visualizations
- `Netflix_Content_Analysis_Report.docx`: Final written report summarizing business findings

## Key Insights
- Most content on Netflix is movies, with `TV-MA` and `TV-14` as dominant ratings
- Viewer preferences lean toward adult content with recent release years
- Association mining showed high-lift rules for content with specific ratings and countries
- Clustering identified meaningful groups based on runtime and release trends


---

**Outcome:**  
This project informs how Netflix and other streaming platforms can personalize content offerings, improve user retention, and optimize content strategy through data mining.
