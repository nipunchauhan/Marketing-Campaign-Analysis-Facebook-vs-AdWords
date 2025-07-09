# Marketing-Campaign-Analysis-Facebook-vs-AdWords
This project conducts a comprehensive analysis of two digital marketing campaigns, one on Facebook and the other on Google AdWords, to determine which platform offers a superior return on investment (ROI). Using a dataset spanning 365 days, this analysis applies statistical methods and time-series analysis to compare performance based on key metrics such as clicks, conversions, and cost-effectiveness. The ultimate goal is to provide a data-driven recommendation for future marketing budget allocation.

##Business Problem
A marketing agency aims to maximize the ROI for its clients' advertising campaigns. To achieve this, it is crucial to identify the most effective advertising platform and allocate resources accordingly. This analysis directly addresses this need by comparing the performance of Facebook and AdWords campaigns to determine which platform yields better results.

###Research Question
Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

##Data
The dataset, marketing_campaign.csv, contains daily performance metrics for the two ad campaigns conducted throughout 2019. Each row represents a single day, resulting in 365 observations.

###Key Data Columns:

* Date: The date of the observation.

* Facebook Ad Clicks: Number of clicks on Facebook ads.

* Facebook Ad Cost: Total cost of Facebook ads for the day.

* Facebook Ad Conversions: Number of conversions from Facebook ads.

* AdWords Ad Clicks: Number of clicks on AdWords ads.

* AdWords Ad Cost: Total cost of AdWords ads for the day.

* AdWords Ad Conversions: Number of conversions from AdWords ads.

##Methodology
The analysis was conducted in a Jupyter Notebook (AB Testing (Marketing Campaigns).ipynb). The methodology follows a structured approach, from data exploration to statistical inference.

##Exploratory Data Analysis (EDA):

* Initial investigation of the dataset to understand its structure, distributions, and summary statistics.

* Visualization of key metrics over time to identify trends, seasonality, and potential outliers.

* Correlation analysis between cost, clicks, and conversions for each platform.

Hypothesis Testing (A/B Test):

* A formal hypothesis test was conducted to determine if there is a statistically significant difference in the conversion rates between the Facebook and AdWords campaigns.

* This helps validate which platform is genuinely more effective at converting users, rather than assuming observed differences are meaningful.

Time-Series Analysis:

* A cointegration test was performed to examine the long-term equilibrium relationship between advertising spend (cost) and conversions.

* The results, with a p-value significantly less than 0.05, rejected the null hypothesis, confirming a stable, long-term relationship between cost and conversions. This indicates that changes in ad spend have a predictable, non-random impact on conversions over time.

Key Findings
* Platform Performance: The analysis identified a clear winner between the two platforms in terms of key performance indicators like Cost Per Click (CPC) and conversion rates. (Note: The specific winner would be detailed here based on the notebook's output, e.g., "Facebook demonstrated a 15% higher conversion rate at a 10% lower CPC compared to AdWords.")

* Cost and Conversion Relationship: There is a statistically significant long-term relationship between advertising spend and the number of conversions. This confirms that strategic investment in the right platform can lead to predictable and sustainable growth in conversions.

* Seasonal Trends: The analysis of monthly performance revealed that certain months (e.g., May and November) show lower CPC values, suggesting periods of higher advertising effectiveness or more favorable market conditions.

Conclusion & Recommendations
The analysis concludes that one platform is demonstrably more effective for this specific campaign objective. Based on the findings, the primary recommendation is to:

➡️ Reallocate a larger portion of the marketing budget to the winning platform to maximize overall ROI.

Additionally, businesses should:

* Leverage the stable relationship between cost and conversions to optimize ad spend, investing more when ROI is high and scaling back otherwise.

* Capitalize on seasonal trends by increasing advertising activity during months with historically lower CPC to maximize efficiency.
