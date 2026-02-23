# 📊 Digital Marketing KPI Dashboard (Power BI)
Interactive Marketing Campaign Performance Dashboard built in Power BI to analyze campaign effectiveness, customer engagement, and revenue performance across devices.

## 🚀 Project Overview
Comprehensive analysis of marketing campaign performance using key KPIs:

| KPI                | Metric             | Value     |
| ------------------ | ------------------ | --------- |
| 📧 Emails Sent     | Total Campaigns    | 2M        |
| 📬 Open Rate       | Industry Benchmark | 23%       |
| 🖱️ CTR            | Click Performance  | 9.2%      |
| 🔄 Conversion Rate | Goal Achievement   | 11.1%     |
| 💰 CPC             | Cost Efficiency    | Optimized |
| 📈 ROI             | Revenue Multiple   | 2.89x     |

₹100K Cost → ₹289K Revenue (Desktop drives highest conversions)

## 📌 Key Insights

| Insight                   | Impact                    |
| ------------------------- | ------------------------- |
| Desktop > Mobile > Tablet | Revenue Priority          |
| 23% Open Rate             | Industry Competitive      |
| 2.89x ROI                 | Strong Campaign Return    |
| 9.2% CTR                  | Above Average Performance |

## 📊 Dashboard Features

1️⃣ KPI Cards (Top-Level Monitoring)

Email Sent → Delivered → Opens → CTR → Conversions → Revenue → ROI
Real-time single-glance performance tracking

2️⃣ Campaign Conversion Analysis
| Status          | Campaigns | Conversion Rate |
| --------------- | --------- | --------------- |
| Top Performers  | 15        | 15%+            |
| Average         | 25        | 8-12%           |
| Underperformers | 10        | <5%             |

3️⃣ Device Performance Breakdown
| Device  | Conversions | Revenue Contribution |
| ------- | ----------- | -------------------- |
| Desktop | 62%         | 68%                  |
| Tablet  | 18%         | 16%                  |
| Mobile  | 20%         | 16%                  |

4️⃣ Month-over-Month Trends
📈 Open Rate: Consistent 22-25%
📈 CTR: Improving 8% → 9.2%
📈 Conversion Rate: 9.8% → 11.1%

5️⃣ Campaign Performance Table
| Campaign | Ad Group | CTR | Conv. Rate | Action   |
| -------- | -------- | --- | ---------- | -------- |
| Q1 Promo | Display  | 12% | 14%        | Scale    |
| Retarget | Social   | 8%  | 10%        | Monitor  |
| Brand    | Video    | 6%  | 3%         | Optimize |

## 🛠️ Technical Stack
technologies:
  dashboard: Power BI Desktop
  etl: Power Query (Data Cleaning)
  calculations: DAX Measures
  source: Excel Dataset

## 🧮 Key DAX Measures
Total Revenue = SUM(Sales[Revenue])
CTR = DIVIDE(SUM(Clicks), SUM(Impressions)) * 100
Conversion Rate = DIVIDE(SUM(Conversions), SUM(Clicks)) * 100
ROI = DIVIDE([Total Revenue], [Total Cost])

## 📂 Dataset Details
Source: Excel file (Marketing Campaigns)
Transformations: Power Query
Key Assumptions:
├── 95% Email Delivery Rate
├── 23% Industry Open Rate
└── Standard CTR/Conversion Formulas

## 🚀 Quick Setup
1. Clone repo: git clone <your-repo>
2. Open PowerBI file: Marketing_KPI_Dashboard.pbix
3. Refresh data connection
4. Explore interactive features

## 👩‍💻 Author
** Harshita Kanwar **

