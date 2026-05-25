# 📺 StreamWave Viewer Analytics: Trends, Engagement & Retention Patterns

**An Excel-powered analytics project for optimizing content investment strategy at StreamWave Entertainment**

![Dashboard Preview]()

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Tools and Features Used](#tools-and-features-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [KPIs](#kpis-key-performance-indicators)
- [Insights](#insights)
- [Business Impacts](#business-impacts)
- [Data Snapshots](#data-snapshots)
- [Conclusion](#conclusion)

---

## 🌐 Project Overview

**StreamWave Entertainment** is a leading global streaming platform with over **150 million subscribers**, having successfully transitioned from DVD rentals to a digital-first streaming experience. Despite its growth, the platform faces mounting pressure from increasing competition and rising content production costs.

This project analyzes viewer activity data to identify top-performing content genres that drive **user engagement, retention, and subscriber growth**. Using Excel-based analytics and an interactive dashboard, it delivers a strategic, data-driven framework to guide resource allocation across StreamWave's vast content library.

| Field | Details |
|---|---|
| **Platform** | StreamWave Entertainment |
| **Subscribers** | 150M+ globally |
| **Dataset Size** | 999 users, 9 genres, 60 content items per user |
| **Tools Used** | Microsoft Excel (PivotTables, Charts, Slicers, KPI Cards) |
| **Deliverable** | Interactive analytics dashboard |

---

## ❗ Problem Statement

With increasing competition in the entertainment industry and escalating content production costs, StreamWave faces a critical challenge:

> *How do we allocate resources effectively across a vast content library to maximize subscriber engagement and reduce churn?*

Specifically, the project addresses:

- **Lack of genre-level performance visibility** — no clear view of which genres retain subscribers vs. drive cancellations.
- **Inefficient budget allocation** — production, marketing, and licensing spend not grounded in engagement data.
- **Churn risk** — inability to proactively identify at-risk user segments before cancellation.
- **Suboptimal content recommendations** — personalization limited by insufficient insight into viewing behavior patterns.

---

## 🛠️ Tools and Features Used

### Microsoft Excel
The entire analysis pipeline was built in Excel, leveraging the following features:

| Feature | Purpose |
|---|---|
| **PivotTables** | Aggregating genre popularity, concurrent views, and subscriber trends |
| **PivotCharts** | Visualizing genre performance, monthly subscription/cancellation trends |
| **Slicers** | Interactive genre filtering (Action, Biography, Comedy, Documentary, Drama, Horror, Kids, Musical, Romance, Sci-Fi) |

---

## 🧹 Data Cleaning and Preparation

Before building the dashboard, raw viewer data underwent a structured cleaning and transformation process:

**1. Duplicate Removal**
Identified and removed duplicate viewer records to ensure each user entry was unique and accurate.

**2. Handling Missing Values**
Null or blank values in key fields (genre preferences, subscription tier, engagement scores) were reviewed and either imputed using median values or flagged for exclusion.

**3. Data Type Standardization**
Ensured consistent formatting for dates (monthly subscription/cancellation data), numeric fields (engagement scores, views), and categorical fields (genre labels, user tiers).

**4. Outlier Detection**
Reviewed engagement and completion rate data for anomalous values (e.g., impossible completion rates >100%) and corrected or removed them.

**5. Genre Normalization**
Standardized genre labels across records to eliminate inconsistencies (e.g., "Sci-Fi" vs. "SciFi" vs. "Science Fiction").

**6. Derived Columns**
Created calculated fields including:
- **Engagement-to-Churn Ratio** — active engagement score relative to cancellation likelihood.
- **Completion Rate per Genre** — percentage of content watched to completion per genre category.
- **Repeat View Index** — average repeat views normalized per content item.

**7. Pivot-Ready Structuring**
Reorganized raw data into a flat, tabular format optimized for PivotTable summarization and dynamic chart binding.

---

## 📊 KPIs (Key Performance Indicators)

The dashboard tracks the following core KPIs:

| KPI | Value | Description |
|---|---|---|
| **Active Users** | 86% | Percentage of the user base actively engaging with content |
| **Total Users** | 999 | Total number of users in the dataset |
| **Average User Age** | 34 | Mean age across all subscribers |
| **Average Subscription Duration** | 25 | Average number of months users remain subscribed |
| **Genres Available** | 9 | Total content categories on the platform |
| **Content per User** | 60 | Average number of content items consumed per user |
| **Completion Rate** | 100% | Percentage of started content watched to full completion |
| **Repeat Views per Content** | 3 | Average number of times a single content item is rewatched |
| **Engagement-to-Churn Ratio** | 1 | Balance between active engagement and cancellation rate |
| **Genre Preferences (Satisfaction)** | 96% | User satisfaction score with available genre offerings |

---

## 💡 Insights

### 1. Genre Popularity
Drama and Comedy are the platform's most-watched genres, accounting for **22.13%** and **21.40%** of total views respectively. Documentary (17.20%) and Sci-Fi (14.51%) form a strong secondary tier. Horror (0.51%), Musical (0.10%), and Biography (0.08%) represent niche audiences with low overall viewership.

### 2. Concurrent Views
Drama and Comedy lead concurrent viewership with a score of **4 each**, followed by Sci-Fi, Documentary, and Action at **2 each** — confirming their role as peak-demand categories.

### 3. Gender Distribution
The platform skews slightly **female (52%)** vs. male (48%), suggesting opportunities for targeted content investment in genres with higher female audience affinity.

### 4. User Tier Breakdown
Subscribers are distributed across **Basic, Premium, and Standard** tiers. The tier distribution informs pricing strategy and the bundling of premium genre content for upsell opportunities.

### 5. Monthly Subscriber Trends
New subscriber acquisition peaked at **116 in July**, reflecting strong mid-year growth momentum. Acquisition drops notably toward year-end, with December recording **60 new subscribers** — signalling a seasonal engagement dip.

### 6. Monthly Cancellation Trends
Cancellations peaked in **February and March** (17–18 per month), coinciding with post-holiday content fatigue. A second mini-peak occurs in **June** (13 cancellations), suggesting mid-year churn risk.

### 7. Genre Rank by Engagement
Drama ranks highest with an engagement score of **9/9 stars**, followed closely by Comedy (**8**) and Sci-Fi (**7**). Biography scores the lowest at **1**, confirming it as a low-priority investment category.

### 8. Completion Rate & Repeat Views
A **100% completion rate** signals strong content quality and viewer satisfaction. An average of **3 repeat views per content** item indicates high rewatch value, particularly in top-tier genres.

---

## 📈 Business Impacts

| Impact Area | Recommendation | Expected Outcome |
|---|---|---|
| **Content Investment** | Prioritize Drama, Comedy, and Sci-Fi in production and licensing budgets | Higher engagement ROI on content spend |
| **Churn Reduction** | Launch retention campaigns in Feb–Mar targeting at-risk subscribers with genre-personalized promotions | Reduce peak cancellation months by 15–25% |
| **Subscriber Acquisition** | Capitalize on the July growth spike with targeted marketing campaigns and new content drops | Extend high-acquisition periods beyond a single month |
| **Niche Genre Strategy** | Reposition Horror, Musical, and Biography as niche subscription add-ons or bundled features rather than core investments | Reduce waste on underperforming genre production |
| **Personalization Engine** | Feed genre preference and engagement data into the recommendation algorithm | Improve content discovery and time-on-platform |
| **Tier Upselling** | Promote premium Drama and Sci-Fi exclusives to Basic-tier users | Increase premium tier conversion rates |
| **User Retention Programs** | Leverage the 1:1 Engagement-to-Churn Ratio as an early-warning metric | Enable proactive interventions before cancellation |

---

## 🖼️ Data Snapshots

### Dashboard Overview
The interactive Excel dashboard provides a comprehensive single-view summary of all key metrics and genre performance indicators.

![Full Dashboard](https://github.com/Ola-ykay/StreamWave-Entertainment-Analysis/blob/main/Streamwave-Dashboard.png)
![Full Dashboard](https://github.com/Ola-ykay/StreamWave-Entertainment-Analysis/blob/main/Streamwave-Dashboard.png)

> *Dashboard built in Microsoft Excel featuring KPI cards, donut charts, bar charts, line charts, and star-rating engagement visuals with interactive genre slicers.*

### Key Visual Highlights

**Genre Popularity (Horizontal Bar Chart)**
Displays the percentage share of total views per genre, confirming Drama (22.13%) and Comedy (21.40%) as the platform's dominant content categories.

**New Subscribers vs. Cancellations (Line Charts)**
Side-by-side monthly trend lines revealing the July acquisition peak and the February–March cancellation spike, enabling targeted seasonal planning.

**Genre Rank by Engagement (Star Ratings)**
A visual 9-point star-rating scale ranking all genres by audience engagement depth, from Drama (9 stars) to Biography (1 star).

**Gender & Tier Distribution (Donut Charts)**
Dual donut charts providing a snapshot of audience demographics and subscription tier mix.

---

## ✅ Conclusion

This project delivers a **data-driven content strategy framework** for StreamWave Entertainment, grounded in Excel analytics across 999 users, 9 genres, and 12 months of behavioral data.

Key takeaways:

- **Drama and Comedy are StreamWave's most valuable content categories** by both popularity and engagement — they should anchor the platform's production and licensing priorities.
- **Churn is predictable and seasonal**, with identifiable peaks in February–March and June, enabling proactive retention interventions.
- **Subscriber acquisition has strong mid-year momentum** that can be amplified with strategic content releases and campaigns.
- **Niche genres (Horror, Musical, Biography)** serve small but loyal audiences and should be monetized differently rather than deprioritized entirely.
- **High completion rates and repeat views** confirm that content quality on the platform is strong — investment should focus on scaling what already works.

By acting on these insights, StreamWave can optimize budget allocation, improve subscriber satisfaction, reduce churn, and strengthen its competitive position in the global streaming market.

