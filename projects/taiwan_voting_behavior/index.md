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
*Predictive Models: Logistic Regression, Random Forest, XGBoost
*Interpretability: SHAP feature analysis
*Clustering & Typology: K-Means clustering, PCA
*Visualization: Heatmaps, PCA projections, SHAP analysis
*Programming: Python, scikit-learn, Matplotlib

## Key Results 
* Age, education, and household size are the strongest predictors of voting outcomes
* Two main district clusters identified: Aging Middle-Income & Young High-Income
* SHAP analysis reveals heterogeneous influence of income and stable effect of age structure
* PCA and heatmap visualizations illustrate distinct demographic and socioeconomic profiles

## Figures
![SHAP summary plot](Figures/shap_summary_xgb.png)

SHAP summary plot illustrating feature importance in XGBoost model. Consumption, higher education percentage, age 15-64 percentage, and elderly population share emerge as the most  influential factors in explaining district-level voting behavior.

![Cluster profile heatmap](Figures/cluster_profiles_heatmap.png)

Standardized cluster profiles of Taiwan’s districts based on demographic, socioeconomic, and voting characteristics. Values represent relative deviations from the overall mean. The heatmap highlights two structurally distinct district types with contrasting age, income, education, and voting profiles.

## Reflection
* Learned the importance of combining predictive modeling with interpretable insights for policy relevance

* Small sample size limits predictive accuracy, emphasizing the need for careful contextualization

* Gained experience in interdisciplinary research, integrating political science theory, ML methods, and data visualization

* Recognized how clustering and feature interpretation can inform actionable campaign strategies beyond raw prediction
  
## Code
[GitHub Repository](https://github.com/yyunchieh/Analysis-of-Voting-Behavior-in-Taiwan)











