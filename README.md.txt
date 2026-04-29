# Mobile App Performance Dashboard

I built this project to practice working with a full data stack — from raw data in Excel, through SQL analysis, to a visual dashboard in Power BI.

The dataset simulates a mobile app company's user acquisition, campaign performance, and in-app event data.

---

## Tools Used
- Excel — raw data storage across 3 tables (users, campaigns, events)
- SQL (SQLite via DB Browser) — querying and aggregating the data
- Power BI — building the final interactive dashboard


What I Analyzed

User Acquisition
Broke down total users and average LTV by acquisition channel. TikTok Ads brought in the most users while Facebook Ads users had the highest average LTV.

Campaign Performance
Calculated ROAS (Return on Ad Spend) and CPI (Cost Per Install) for 12 campaigns across Facebook, Google, and TikTok. TikTok campaigns consistently delivered the best ROAS.

In-App Events
Looked at which event types occurred most frequently and compared average session durations. Purchase events had the longest sessions by far.



SQL Queries Used
The analysis was done with 3 SQL queries:
- Users grouped by channel with paying user count and average LTV
- Campaign performance with calculated ROAS and CPI metrics
- Event frequency and average session duration by event type



Key Findings
- TikTok Ads had the best ROAS across all campaigns
- Facebook Ads users generated higher LTV despite fewer total users
- Purchase events had significantly longer session durations than other event types