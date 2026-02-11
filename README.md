## 📊 Twitter Analysis Dashboard

A complete Twitter data analysis project built using Excel, Power BI, Python, and SQL concepts to analyze engagement metrics, impressions, media views, and user interactions.
This project provides insights into tweet performance across different days and months using interactive visualizations and KPI tracking.

## 🚀 Project Overview: 
This project analyzes Twitter engagement data to answer key business questions:
  1. Which day has the highest engagement?
  2. How do impressions vary across the week?
  3. Which tweets generate the most URL clicks?
  4. What is the overall engagement rate?
  5. How do media views compare with engagement?
The dashboard helps in understanding audience behavior and optimizing content strategy.

## 📌 Dashboard Highlights:

## 1️⃣ Weekly Tweet Analysis:
    - Tweet count by weekday
    - Engagement trends by day
    - Impression distribution by week
## From the dashboard:
    - Highest engagement observed on Tuesday (131)
    - Lowest engagement on Sunday (49)

## 2️⃣ Key Performance Indicators (KPIs):
| Metric                 | Value |
| ---------------------- | ----- |
| 👍 Total Likes         | 6,836 |
| 🔁 Max Retweets        | 165   |
| 👁 Media Views         | 81K   |
| 📊 Impression Count    | 710   |
| 📈 Avg Engagement Rate | 3.75% |
| 🔗 User Profile Clicks | 2,383 |

## 3️⃣ Engagement Insights:
 
 - Tuesday and Thursday show strong engagement consistency.
 - Weekend engagement drops significantly.
 - Friday has the highest combined likes and replies (as shown in engagement summary panel).
 - Media engagement closely follows media views pattern.

## 4️⃣ URL Click Analysis:

Top performing tweets (by URL clicks):
  - Tweet 1 – 240 clicks
  - Tweet 2 – 217 clicks
  - Tweet 3 – 199 clicks
  - Tweet 4 – 170 clicks
  - Tweet 5 – 93 clicks
This helps identify high-performing content.

## 🛠 Tools & Technologies Used:
  - Python (Data Cleaning & Preprocessing)
  - Pandas (Data Analysis)
  - Power BI (Dashboard & Visualization)
  - Excel (Initial Cleaning & Formatting)
  - DAX (Calculated Columns & Measures)

## Example DAX used:
  - Weekday Number = WEEKDAY('SocialMedia'[Date], 2)
  - Weekday Name = FORMAT('SocialMedia'[Clean Date], "dddd")

## Example Power Query transformation:
  - = Date.FromText(Text.Start([time], 10))

## 📂 Project Structure:

  ├── SocialMedia.csv        # Dataset
  ├── socialmedia.ipynb      # Data preprocessing notebook
  ├── Dashboard.pdf          # Final dashboard export
  ├── README.md              # Project documentation

## 📊 Business Insights Derived:
  - Mid-week content performs better than weekend posts.
  - Engagement rate of 3.75% indicates moderate audience interaction.
  - URL click-through rate shows strong performance on specific tweets.
  - Media content significantly boosts interaction.

🎯 Use Cases:
 - Social Media Performance Tracking
 - Marketing Analytics
 - Engagement Optimization
 - Content Strategy Planning
 - KPI Monitoring Dashboard

## 🔮 Future Improvements:
 - Sentiment Analysis using NLP
 - Hashtag performance prediction

Time-based engagement forecasting

Automated data refresh pipeline
