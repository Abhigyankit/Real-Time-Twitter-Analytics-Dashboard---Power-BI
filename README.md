# 📊 Real-Time Twitter Analytics Dashboard | Power BI

**Transforming Twitter engagement data into actionable social media insights using Power BI, DAX, and interactive visualizations.**

## 📌 Project Overview

The **Twitter Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI to evaluate tweet performance, audience engagement, content effectiveness, and social media interaction patterns.

The dashboard transforms raw tweet-level data into meaningful insights through data preparation, DAX calculations, performance classifications, and interactive visualizations. It helps identify high-performing content, understand audience behaviour, compare media engagement, and evaluate the relationship between impressions, clicks, and interactions.

The project demonstrates practical skills in **data analytics, business intelligence, data modeling, KPI development, and dashboard design**.

## 🎯 Project Objectives

- Analyze click performance across different tweet content categories.
- Compare engagement rates between tweets with and without app opens.
- Identify the best-performing weekdays for media interactions.
- Compare replies, retweets, and likes across June, July, and August 2020.
- Track monthly engagement rate trends for media and non-media tweets.
- Identify the top 10 weekday tweets based on total engagements.
- Develop classification-based insights to support data-driven social media decisions.

## 🛠️ Tech Stack

| Technology | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development and data visualization |
| Power Query | Data cleaning, transformation, and preparation |
| DAX | Calculated columns, measures, KPIs, and classification logic |
| Data Modeling | Date table, chronological sorting, and analytical relationships |
| Conditional Formatting | Performance-based colours and visual indicators |
| Interactive Reporting | Filters, tooltips, drill-down analysis, and rankings |

## 📈 Dashboard Modules

### 1. Tweet Interaction Breakdown by Content Category

**Objective:** Understand how different content types drive clicks and audience interest.

- Categorized tweets as Media, Link, Hashtag, Mixed Content, or Plain Text.
- Compared URL Clicks, User Profile Clicks, and Hashtag Clicks using a clustered bar chart.
- Calculated Total Clicks and Click-Through Rate (CTR) using impressions.
- Classified categories as Traffic Driven, Profile Interest, Discovery Driven, or Mixed Interaction.
- Flagged categories with below-median CTR for further investigation.

**Business value:** Helps identify content formats that generate traffic, encourage profile visits, and improve content discovery.

### 2. Engagement Rate Comparison

**Objective:** Evaluate engagement performance for tweets associated with app opens.

- Compared tweets with app opens against tweets without app opens.
- Focused on weekdays during business hours (9:00 AM–5:00 PM).
- Analyzed Average Engagement Rate, Total Impressions, Total Engagements, and Average App Opens.
- Classified performance as High App Impact, App Interest–Low Engagement, High Organic Reach, or Low Performance.
- Used conditional formatting and tooltips to improve interpretability.

**Business value:** Supports evaluation of app-related engagement patterns and helps identify opportunities to improve audience conversion.

### 3. Media Interaction by Day of the Week

**Objective:** Identify weekdays associated with stronger media reach and interaction.

- Analyzed Media Views and Media Engagement Rate for the latest complete quarter available in the dataset.
- Built a dual-axis visualization combining media views and engagement rate.
- Sorted weekdays chronologically for meaningful comparison.
- Classified days as Strong Media Day, High Reach–Low Interaction, Niche High-Quality Day, or Weak Media Day.
- Flagged interaction spikes when media engagements were at least 20% above the weekday average.

**Business value:** Helps identify promising posting days and distinguish high-reach content from content that generates stronger engagement.

### 4. Replies, Retweets, and Likes Analysis

**Objective:** Compare audience interaction patterns across June, July, and August 2020.

- Compared replies, retweets, and likes by month.
- Excluded tweets with no recorded interactions from the interaction comparison.
- Identified dominant interaction types: Conversation Driven, Virality Driven, Popularity Driven, and Balanced Interaction.
- Flagged tweets below the dataset median for interaction.
- Added a supporting visual showing the count and percentage of tweets in each classification.

**Business value:** Reveals whether audience responses are primarily driven by conversation, sharing, or popularity.

### 5. Monthly Engagement Rate Trends

**Objective:** Monitor changes in engagement performance over time.

- Compared average engagement rates for media and non-media tweets.
- Created a Date table to support chronological sorting and year-based filtering.
- Classified monthly performance as Media Dominant, Non-Media Dominant, or Balanced.
- Introduced an Engagement Decline Alert when overall engagement rate decreased for two consecutive months.
- Included tooltip metrics for tweet counts, impressions, engagement rates, and month-over-month changes.

**Business value:** Helps track engagement trends, identify changes in content effectiveness, and support continuous performance monitoring.

### 6. Top 10 Tweets by Total Engagements

**Objective:** Identify the most engaging weekday tweets.

- Ranked the top 10 tweets using Total Engagements.
- Calculated total engagements as Likes + Retweets + Replies.
- Displayed tweet labels, impressions, and engagement rates for comparison.
- Classified tweets as Highly Shareable, Highly Popular, Conversation Driven, or High Volume–Low Efficiency.
- Used classification-based colours to distinguish engagement patterns and support interpretation of the top three tweets.

**Business value:** Helps identify content characteristics associated with stronger audience interaction and provides direction for future content strategies.


## 💡 Key Analytical Outcomes

The dashboard provides a structured framework for evaluating social media performance across content categories, click behaviour, app-related engagement, media interactions, monthly trends, and individual tweet rankings.

Its classification rules help translate numerical metrics into interpretable performance groups, making it easier to investigate:

- Which content categories generate different types of clicks.
- How engagement patterns differ between tweets with and without app opens.
- Which weekdays show stronger media reach or interaction.
- Whether audience engagement is driven primarily by likes, retweets, or replies.
- How media and non-media engagement rates change over time.
- Which tweets combine high engagement with comparatively efficient reach.

**The practical outcome:** a reusable analytical framework that can support content planning, posting schedules, engagement optimization, and performance reporting. Actual recommendations should be validated against the completed dashboard's measured results.

## 🧠 Skills Demonstrated

- **Data Analytics:** Exploratory analysis, KPI tracking, trend analysis, and comparative analysis.
- **Power BI Development:** Interactive reports, charts, slicers, tooltips, and conditional formatting.
- **DAX:** Calculated columns, measures, ranking logic, threshold-based flags, and classification rules.
- **Data Preparation:** Power Query transformations and content categorization.
- **Data Modeling:** Date tables, chronological sorting, and time-based analysis.
- **Business Intelligence:** Translating social media metrics into interpretable performance indicators.
- **Data Storytelling:** Designing analytical views to support business-oriented decisions.

## 🚀 Future Enhancements

- Integrate a live or scheduled data pipeline to support regularly refreshed Twitter/X analytics.
- Add automated refresh monitoring and data-quality validation.
- Introduce sentiment analysis to evaluate audience responses.
- Compare engagement across additional content types and time periods.
- Develop predictive models to estimate tweet engagement.
- Publish the dashboard through Power BI Service with appropriate access controls.


## 👨‍💻 About This Project

This project demonstrates how business intelligence tools can transform social media data into actionable analytical insights. It combines data preparation, DAX-based calculations, interactive visualization, and performance classification to explore how content type, timing, and interaction patterns relate to tweet performance.


⭐ If you find this project interesting, feel free to explore the repository and share your feedback.
