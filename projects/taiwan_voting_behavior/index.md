---
layout: default
title: Analysis of Voting Behavior in Taiwan
---

# Analysis of Voting Behavior in Taiwan

## Overview
This project investigates how demographic, economic, and educational characteristics of Taiwan's 20 districts influence voting behavior in the 2024 presidential election. Unlike purely predictive studies, this project emphasizes exploratory analysis, feature interpretation, and district typology, integrating political science insights with data science methods to inform campaign strategy design.

## Motivation
Designing effective campaign strategies is a critical challenge in any election. My background in political science motivated me to explore quantitative relationships between socioeconomic factors and voting patterns, using ML to extract actionable insights. The project demonstrates how data science can complement political analysis, bridging social science understanding and predictive modeling.

## Data Sources
* [Central Election Commission (CEC)](https://db.cec.gov.tw/)
* [Ministry of Interior Statistics](https://www.moi.gov.tw/cp.aspx?n=5590)
* [Directorate General of Budget, Accounting, and Statistics (DGBAS)](https://www.dgbas.gov.tw/)
* [Ministry of Labor](https://statfy.mol.gov.tw/map02.aspx?cid=9&xFunc=68&xKey=1)
  
## Tech Stack & Methods
* Predictive Models: Logistic Regression, Random Forest, XGBoost
* Interpretability: SHAP feature analysis
* Clustering & Typology: K-Means clustering, PCA
* Visualization: Heatmaps, PCA projections, SHAP analysis
* Programming: Python, scikit-learn, Matplotlib

## Key Results 
* Age, education, and household size are the strongest predictors of voting outcomes
* Two main district clusters identified: Aging Middle-Income & Young High-Income
* SHAP analysis reveals heterogeneous influence of income and stable effect of age structure
* PCA and heatmap visualizations illustrate distinct demographic and socioeconomic profiles

## Campaign Strategy Implications
Urban districts are characterized by higher education levels, higher income, and more heterogeneous political preferences. Clustering and SHAP analyses suggest that voting behavior in these districts is less driven by a single socioeconomic factor and more influenced by issue-based considerations.

* Campaign messaging in urban districts may benefit from emphasizing detailed policy proposals, social issues, and innovation-driven narratives.
* Digital platforms and social media appear to be effective channels for engaging these voters, who exhibit higher exposure to diverse information sources.

Rural districts exhibit more competitive voting dynamics and stronger associations with traditional socioeconomic indicators. In these districts, variables such as age structure and household characteristics show more consistent relationships with voting outcomes.

* Messaging that highlights economic stability, local infrastructure, and community-oriented values may resonate more strongly.
* Traditional outreach channels, including local events, radio, and print media, may remain influential in these areas.

Youth mobilization emerges as a key factor in specific district clusters. Districts with a higher proportion of younger residents display distinct voting patterns, suggesting untapped mobilization potential.

* Data-driven targeting through social media campaigns, interactive events, and youth-oriented messaging could enhance engagement.
* Encouraging voter registration and participation among younger demographics may be particularly impactful in these clusters.

## Figures
![SHAP summary plot](Figures/shap_summary_xgb.png)

SHAP summary plot illustrating feature importance in XGBoost model. Consumption, higher education percentage, age 15-64 percentage, and elderly population share emerge as the most  influential factors in explaining district-level voting behavior.

![Cluster profile heatmap](Figures/cluster_profiles_heatmap.png)

Standardized cluster profiles of Taiwan’s districts based on demographic, socioeconomic, and voting characteristics. Values represent relative deviations from the overall mean. The heatmap highlights two structurally distinct district types with contrasting age, income, education, and voting profiles.

## Reflection

This project emphasized the trade-off between predictive performance and interpretability in socially grounded datasets. By using machine learning as an analytical lens rather than optimizing solely for prediction, I gained deeper insight into how data-driven methods can support substantive social analysis.

  
## Code
[GitHub Repository](https://github.com/yyunchieh/Analysis-of-Voting-Behavior-in-Taiwan)














