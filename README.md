# Project -  Real Time Twitter Analytics Dashboard - Power BI

**1. Project Overview** - This project focuses on analyzing social media tweet performance using Microsoft Power BI. The dashboard examines content categories, engagement rates, media interactions, audience behaviour, monthly trends, and top-performing tweets. It uses calculated columns, DAX measures, filters, and interactive visualizations to identify useful patterns in social media engagement.

**2. Objectives** - 
    Analyze click performance across different tweet content categories.
    Compare engagement rates for tweets that generated app opens and those that did not.
    Identify the best days of the week for media interactions.
    Compare replies, retweets, and likes from June to August 2020.
    Track monthly engagement trends for media and non-media tweets.
    Identify the top 10 weekday tweets based on total engagements.

**3. Tools and Technologies**
    Microsoft Power BI
    Power Query for data preparation
    DAX for calculated columns and measures
    Data visualization and conditional formatting
    Interactive filters, tooltips, and classification-based colours

**4. Project Tasks and Methodology**

**Task 1: Tweet Interaction Breakdown by Content Category**
Tweets were classified into Media, Link, Hashtag, Mixed Content, and Plain Text. Tweets containing multiple content elements were assigned to Mixed Content to prevent double counting. A clustered bar chart compares URL Clicks, User Profile Clicks, and Hashtag Clicks across categories. Total Clicks and Click-Through Rate were calculated using impressions. Categories were classified as Traffic Driven, Profile Interest, Discovery Driven, or Mixed Interaction, with an additional Low Click Efficiency flag for categories below the overall median click-through rate.

**Task 2: Engagement Rate Comparison**
Tweet engagement performance was compared between tweets that generated app opens and tweets that did not. The analysis considered weekdays during business hours, from 9:00 AM to 5:00 PM. Average Engagement Rate, total Impressions, total Engagements, and average App Opens were used to compare the groups. Tweets were classified into High App Impact, App Interest–Low Engagement, High Organic Reach, or Low Performance. Conditional colours and tooltips support detailed analysis.

**Task 3: Media Interaction by Day of the Week**
Media Views and Media Engagement Rate were analyzed for the latest complete quarter available in the dataset. A dual-axis chart displays Media Views as columns and Media Engagement Rate as a line, with weekdays sorted chronologically. Days were classified as Strong Media Day, High Reach–Low Interaction, Niche High-Quality Day, or Weak Media Day. Interaction Spike flags identify days when Media Engagements are at least 20% above the weekday average.

**Task 4: Replies, Retweets and Likes Comparison**
Replies, Retweets, and Likes were compared by month for June, July, and August 2020. Tweets with no interactions were excluded. Tweets were classified according to their dominant interaction type as Conversation Driven, Virality Driven, Popularity Driven, or Balanced Interaction. Low Interaction flags identify tweets below the dataset median. A supporting visual presents the number and percentage of tweets in each classification.

**Task 5: Monthly Engagement Rate Trend**
A monthly line-chart analysis compares the average Engagement Rate of media tweets with non-media tweets. A Date table supports chronological month sorting and filtering by year and content type. Monthly classifications include Media Dominant, Non-Media Dominant, and Balanced. An Engagement Decline Alert is used when the overall Engagement Rate decreases for two consecutive months. Tooltips provide tweet counts, impressions, engagement rates, and month-over-month changes.

**Task 6: Top 10 Tweets by Engagement**
A ranked bar chart identifies the top 10 weekday tweets based on Total Engagements, calculated as Likes plus Retweets plus Replies. Tweet labels, Impressions, and Engagement Rate support performance comparison. Tweets are classified as Highly Shareable, Highly Popular, Conversation Driven, or High Volume–Low Efficiency. Classification-based colours and an explanation of the three highest-ranked tweets help interpret the results.

**5. Key Analytical Outcomes** - The dashboard provides a structured way to compare content performance, click behaviour, app-related engagement, media interactions, monthly trends, and high-performing tweets. Its classifications help distinguish traffic generation, profile interest, content sharing, audience conversation, and engagement efficiency. The findings can support decisions about content selection, posting schedules, app conversion improvement, and strategies for increasing audience interaction. Specific recommendations should be based on the values and patterns observed in the completed dashboard.

**6. Conclusion** - This project demonstrates the application of Power BI, data preparation, DAX calculations, and interactive visualizations to social media analytics. By combining multiple analytical views and classification rules, the dashboard supports a clearer understanding of tweet performance and provides a foundation for data-driven social media decisions.
