## About Me

Welcome to my website! I'm originally from Westchester, New York, and I'm currently a senior at Lehigh University where I study Financial Engineering in the Integrated Business and Engineering (IBE) honors program. Following my graduation from Lehigh, I will be working for Greenhill & Co. in New York City as an investment banking analyst. 

---

## Portfolio

_**[Quantifying 10-K Sentiment and Stock Price Impact](midterm_summary.md)**_

In this project, I modeled how sentiment in 2022 S&P 500 10-K filings affected stock returns one to four trading days after release, focusing on divestitures, lawsuits, and new product launches. I found that aggregate positive and negative sentiment scores had virtually no predictive power, whereas contextual sentiment around divestitures and lawsuits produced modest but meaningful slopes and mentions of new products consistently forecasted a negative price reaction. My regression’s R² was respectable, indicating the model captured enough variation to validate these event-specific signals despite low overall explanatory power. Overall, these results suggest that granular, event-driven sentiment measures offer more insight into market responses than aggregate sentiment alone.

---

<a href="https://lehigh-asset-pricing.streamlit.app/" target="_blank">
  <b>Lehigh Asset Pricing Dashboard</b>
</a>

Myself alongside my team developed a Lehigh Asset Pricing model where we fit regressors and neural networks to predict stock returns and construct a zero-cost long-short portfolio. We ingested WRDS CRSP, OpenAP, and Fama–French factor data, selected the top 5,000 firms by net operating assets, and trained Lasso, Ridge, HistGradientBoosting, and three MLP architectures using an expanding window approach. Predictions were binned into portfolios to compute Sharpe ratios where HistGradientBoosting achieved the best, and the 3 fold Nueral Network achieved the best of the networks, while the overal best was the stacked regessor we developed.

Click on the link above to see our dashboard!


<img src="images/Market.png?raw=true"/>

---

_**[Industrial and Systems Engineering Optimization Project](pdf/McDowell_Ryan_De Cerbo_Jamesley_Mock Final Project Report.pdf)**_

Our team built an Arena simulation of SM Paints’ production facility to evaluate how various upgrades—additional shifts, tanks, and fill lines—would impact the goal of shipping 98% of orders within three working days. By running 30 replications per scenario and measuring both on-time fulfillment and upgrade cost, we found that only the addition of a quart fill line pushed the on-time rate above target, achieving 99.74% while lowering quart‐line utilization by 15.39%. A one-way ANOVA and Tukey pairwise comparisons confirmed that this upgrade was statistically superior to all others. Finally, sensitivity analyses across different order arrival rates demonstrated that the quart line recommendation remains cost-effective and robust under varying demand.

---
## Personal Interests and Hobbies
 - Reading about new IPO's, stock predictions, company financial analysis
 - Looking into space advancements with NASA, SpaceX, Blue Origin, and all the other amazing new initiatives
 - Watching sports, specifically the Giants (NFL), Rangers (NHL), Knicks (NBA), and Mets (MLB)
 - Strong passion towards fitness
 - Playing strategic games with friends

<!-- Remove above link if you don't want to attibute -->
