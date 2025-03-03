# PowerBI_Dashboard
Strategic Insights for Lio-Jotstar Merger: Subscriber Behavior & OTT Performance Analysis.

Lio, a leading telecommunications provider in India, is planning a strategic merger with 
Jotstar, one of the country’s most prominent streaming platforms. This potential partnership 
aims to combine LioCinema’s expansive subscriber base and Jotstar’s diverse content library 
to revolutionize digital streaming in India. 
As part of the merger preparation, the management team at Lio wants to analyse the 
performance and user behavior of both platforms—LioCinema and Jotstar—over the past 
one year (January to November 2024). The goal is to gain insights into individual platform 
performance, content consumption patterns, subscriber growth, Inactivity behavior, upgrade 
and downgrade trends. The insights derived from this study will help the management make 
informed decisions and optimize content strategies post-merger, with the ultimate goal of 
establishing Lio-Jotstar as the leading OTT platform in India. I analysed the data and provided insights.

Technology Stack Used: Used MySQL, SQL, Python Pandas and Numpy for exploratory data analysis and fetching the relevant data.

Key Insights analysed are 
  1) Total Users & Growth Trends
  2)  Content Library Comparison
  3)  User Demographics
  4)  Active vs. Inactive Users
  5)  Watch Time Analysis
  6)  Inactivity Correlation
  7)  Downgrade Trends
  8)  Upgrade Patterns
  9)  Paid Users Distribution
  10)  Revenue Analysis

-> Implemented the DAX measure scripts to connect the bridges between different metrics to best represent them accordingly.

Conclusion:
  -> It is been observed that there is sharp rise in the Jotstart degraded count in the month of May, 2024 and Upgrade count is high in January 2024.
  -> It is also observed that there rise in the LioCinema degraded count from May to November 2024 steadily. There is sharp spike in the month of July 2024 and almost a steady increase from April 2024.
  -> Majot contribution of Total run time for Jotstar is Movies and Series content.
  -> Major contribution of Total run time for LioCinema is Movie.
  Subscription Plan Optimization
    -> As a part of strategic merger, to improve the Upgradation and minimize the degradation count as much as possible, we can bring the new initiative from the May as we see there is a steady rise in the degradation count from May to November. 
    -> As most of the users total watch time is very high in Movie Category, we can bring a new plan that has access only to movies from the month of may till the end of the year which reduces the degradation and improves the plan change and therby generate more revenue.
    -> There are high number of Free category user in LioCinema without any plan. The best way to convert them into one of the plan after merging is to put a plan which is more cheaper after mergeing from 100-130 and giving access to limited content according to total          watch time.
  -> User Engagement & Inactivity Reduction
    -> Identify inactive users and their watch behavior patterns (e.g., last watched content, watch duration, subscription plan). Using personalized recommendations accordingly.
    -> Introduce gamification features (rewards for watch streaks, milestone badges).


