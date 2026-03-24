# Football-player-market-value-and-recruitment-analysis
 Project Overview
This project focuses on data-driven recruitment and squad management within professional football. Using a dataset of over 19,000 professional players, I performed comprehensive data cleaning, feature engineering, and strategic analysis to identify market opportunities and optimize roster construction.
By developing custom metrics like Value-for-Money (VfM) and Cost per Rating Point, this project transforms raw player statistics into actionable financial insights, allowing recruitment departments to identify undervalued talent and manage player lifecycles effectively.

Skills & Tools

Technical Stack: Excel (Advanced Formulas, Data Cleaning), Power BI (DAX, Interactive Dashboards)
Data Techniques: ETL (Extract, Transform, Load), Feature Engineering, Categorical Segmentation, Data Integrity Auditing.
Domain Knowledge: Football Recruitment, Market Value Assessment, Squad Planning, Scouting Analytics.

 Key Metrics & Features Created
 
To provide deeper insights than standard ratings, I engineered several advanced fields:
Market Status Classification: A logic-based system that categorizes players into High Priority Buy, Invest (High Growth), Stable, or Sell/Release.
Golden Age Segmentation: Segments players by career stage: Wonderkids (<21), Developing (21-23), Golden Age (24-29), Veterans, and Legends.
Value-for-Money (VfM) Score: A proprietary calculation weighing a player’s performance (Overall Rating) against their market valuation and wage demands.
National Strength & Elite Talent Count: A macro-level analysis of which countries produce the highest concentration of high-potential players.
Distance from Peak: A metric calculating the growth gap between a player's current ability and their maximum potential.

The Analysis Pipeline

1. Data Cleaning & Integrity
Standardized inconsistent date formats (e.g., converting "04-Jun-2012" to numeric date formats).
Corrected currency and wage notations to ensure uniform financial analysis.
Filtered out players with unverifiable data to maintain the integrity of the scouting reports.
2. Strategic Scouting Analysis
Targeting Wonderkids: Filtered the database for "World Class Prospects" under the age of 21 with a high growth delta.
Financial Efficiency: Calculated "Cost per Rating Point" to pinpoint which leagues or teams offer the highest quality of player for the lowest transfer fee.
Squad Role Mapping: Categorized the dataset into roles ranging from World Class Star to Reserve/Prospect to assist in balanced squad building.

 Key Insights & Outcomes
 
Undervalued Markets: Identified specific player profiles in the "Developing" stage whose market value is significantly lower than their projected potential growth.
Retention vs. Sale: Created a dashboard view that flags "Veterans" with declining value, suggesting optimal windows for player sales to maximize ROI.
Resource Allocation: Provided a clear roadmap for recruitment by highlighting "High Priority Buys" who fit specific squad roles (e.g., First Team Starter vs. Rotation).

Strategic Recommendations & Actionable Insights

Based on the data analysis of the 19,000+ player dataset, the following strategic recruitment actions are recommended:

1. High-ROI "Wonderkid" Acquisition

The analysis identified a high concentration of players in the "1. Wonderkid (<21)" category with a Potential Growth delta of +10 or higher.

Action: Prioritize scouting in regions with high National Strength but lower average player wages to secure "World Class Prospects" before their market value peaks.

Top Target Profile: Players with a high Value-for-Money Score and a Distance from Peak of -5 or more.

2. Squad Optimization & Wage Management
By cross-referencing SQUAD ROLE with Weekly Wage Euro, several "Salary Outliers" were identified.

Action: Review players categorized as "Rotation / Bench" who are currently in the top 10% of the wage bracket.

Strategy: Transition these players to the "SELL / RELEASE" Market Status to reallocate budget toward "First Team Starters" with higher efficiency ratings.

3. Market Entry Timing
The "Distance from Peak" metric revealed that players typically experience their sharpest value increase between ages 21 and 23 (Developing stage).

Action: Implement a "Buy Low, Sell High" policy by acquiring talent in the Developing phase and evaluating for sale or contract extension once they enter the "Golden Age (24-29)" bracket.

4. Risk Mitigation in Recruitment
Using the Cost per Rating Point metric, the portfolio highlights "Overvalued" markets where clubs pay a premium for name recognition rather than statistical output.

Action: Shift recruitment focus toward players with "Elite Talent" status in mid-tier leagues, where the Cost per Rating Point is 30% lower than in top-5 European leagues.
