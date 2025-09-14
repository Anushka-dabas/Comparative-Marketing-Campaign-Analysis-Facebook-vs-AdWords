

# Comparative Marketing Campaign Analysis – Facebook vs AdWords

##  Project Overview  
In today’s competitive marketing landscape, optimising ad spend for maximum returns is critical for agencies and their clients. This project performs an in-depth comparative analysis of two major advertising platforms – **Facebook Ads** and **Google AdWords** – by evaluating performance metrics such as clicks, conversions, cost per result, and Return on Ad Spend (ROAS). The objective is to identify which platform delivers superior results in terms of cost-efficiency and conversion effectiveness.

By leveraging statistical tests, time-series analysis, and visualisations, this analysis informs strategic decisions, enabling data-driven recommendations for allocating advertising budgets, optimising campaigns, and enhancing ROI.

##  Business Problem  
As a marketing agency, our goal is to maximise the return on investment (ROI) for our clients' advertising efforts. To guide future strategy, we conducted a comparative analysis between two distinct campaigns – one on Facebook and another on AdWords. The focus is to determine which platform delivered better results across key performance metrics.

Key objectives include:
- Identify which platform drives more clicks and conversions.
- Evaluate cost-effectiveness and campaign efficiency.
- Provide recommendations based on statistically significant findings.
- Inform strategic allocation of ad budgets for future campaigns.


##  Tech Stack  
 **Python** – Data processing, statistical analysis, and visualization.  
 **Jupyter Notebook** – Interactive environment for data exploration.  
 **Pandas** – For data cleaning, transformation, and aggregation.  
 **Matplotlib** – For plotting time-series visualizations such as ROAS comparisons.  
 **SciPy (Stats)** – For hypothesis testing on campaign effectiveness.  
 **CSV Files** – Structured campaign data from Facebook and AdWords reports.


 ## Data Source  
The datasets were provided by Facebook Ads Manager and Google AdWords, containing campaign metrics such as:  
- Clicks  
- Conversions  
- Cost per Ad  
- Click-Through Rate (CTR)  
- Conversion Rate  
- Return on Ad Spend (ROAS)

The data spans multiple months and includes time-series records for both platforms. The datasets are provided in `.csv` format and include revenue assumptions to calculate ROAS.


##  Key Metrics Analyzed  
### 1. Clicks and Conversions  
Analyzing how many users interacted with ads and completed conversions, revealing platform-specific strengths in driving engagement.

### 2. Cost Efficiency  
Examining cost per ad and overall spend to understand how each platform's budget allocation influences results.

### 3. ROAS (Return on Ad Spend)  
Calculating how much revenue was generated per dollar spent, using a standardized assumption of $100 revenue per conversion.

### 4. Time-Series Trends  
Tracking monthly trends for ROAS and conversions, helping identify peak-performing months and platform sustainability.

### 5. Statistical Significance  
Applying hypothesis tests to determine whether the observed differences between Facebook and AdWords are meaningful and reliable.


##  Outputs and Insights  
###  Facebook Outperforms AdWords  
- Average conversions: **Facebook (11.74)** vs **AdWords (5.98)**  
- Facebook campaign achieves significantly higher conversions.

###  Facebook is More Cost-Efficient  
- ROAS for Facebook is substantially higher at **1528.27%** compared to AdWords at **475.67%**.

###  Statistically Significant Results  
The hypothesis test for ROAS yielded:  
- **T-statistic:** 26.037  
- **P-value:** 3.68e-89  
Result: The difference in ROAS between the two platforms is statistically significant.

###  Long-Term Stability  
A cointegration test revealed that Facebook advertising spend and conversions share a stable, long-term relationship, indicating that sustained investments will yield predictable returns.



##  Visualizations  
- **Monthly ROAS Comparison:** A line chart comparing Facebook and AdWords ROAS trends over the months, highlighting Facebook's superior performance in key periods.  
- **Conversion Analysis:** Data-driven insights into the number of clicks and conversions across platforms.  
- **Cost Efficiency Plots:** Helping visualise which platform delivers the best results per dollar spent.



##  Conclusion and Strategic Recommendations  
###  Facebook’s Advantage  
The Facebook campaign outperforms AdWords in driving clicks, conversions, and overall cost efficiency. Investing more in Facebook ads will likely yield higher ROI.

###  Actionable Steps  
1. **Reallocate Ad Budget:** Increase spending on Facebook campaigns to leverage its cost-effectiveness and higher conversion rates.  
2. **Investigate AdWords Performance:** Perform deeper audits or A/B tests to refine AdWords campaigns and optimize targeting.  
3. **Monitor Metrics Regularly:** Track conversion rates, cost per click, and ROAS monthly, allowing for adjustments based on seasonal trends or performance changes.

