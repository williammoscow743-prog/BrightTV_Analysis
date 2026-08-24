# BrightTV Viewership Analytics

## Audience Behaviour, Content Consumption & Customer Growth Opportunities

A Data Analytics case study analysing BrightTV viewing behaviour to identify audience trends, content consumption patterns, low-consumption opportunities and potential customer growth initiatives.

---

## 1. Project Overview

BrightTV wants to grow its subscription base and improve customer value management through a better understanding of viewer behaviour.

This project analyses viewing-session data to identify:

- Who is watching BrightTV
- What content users are watching
- When users are watching
- Where users are located
- Patterns associated with higher and lower consumption
- Opportunities to increase viewing on low-consumption days
- Potential initiatives to grow the BrightTV user base

The analysis was completed using Databricks and SQL, supported by data visualisation and an interactive dashboard.

---

## 2. Business Questions

The analysis was designed to answer four key questions:

1. What are the main user and usage trends?
2. What factors influence consumption?
3. What content should be recommended to increase consumption on low-consumption days?
4. What initiatives could further grow the BrightTV user base?

---

## 3. Project Objectives

The main objectives were to:

- Analyse user demographics and viewing behaviour.
- Identify the strongest audience segments.
- Analyse viewing patterns by day and time.
- Identify high-performing channels and content.
- Investigate demographic and channel relationships.
- Identify the lowest-consumption day.
- Recommend content strategies for low-consumption periods.
- Identify potential customer acquisition and engagement opportunities.
- Present the findings through an interactive dashboard.

---

## 4. Dataset

The project uses BrightTV viewing-session data containing information relating to users, viewing sessions, channels, dates/times and demographic attributes.

The analysis includes variables relating to:

- User ID
- Age
- Gender
- Province
- Channel
- Viewing date/time
- Session information

Each viewing session is represented as one record.

### Data Preparation

The data was processed in Databricks and included:

- Data inspection
- Data cleaning
- Missing/unknown value handling
- Age-group creation
- Day-of-week analysis
- Hourly viewing analysis
- UTC to South African Standard Time (SAST) conversion
- User and session aggregation
- Channel analysis

---

## 5. Tools & Technologies

The project used:

- **Databricks** – data processing and analysis
- **SQL** – querying, aggregation and analytical calculations
- **Python** – data analysis where applicable
- **Excel** – supporting analysis
- **Lovable** – interactive dashboard development
- **Power BI** – dashboard development
- **Data Studio** – dashboard/visualisation work
- **GitHub** – project version control and portfolio repository

---

## 6. Key Results

### Overall Usage

| Metric | Result |
|---|---:|
| Unique Users | 4,386 |
| Total Sessions | 9,995 |
| Sessions per User | 2.28 |

### Audience

The largest age group was **25–34**, representing **40.56%** of unique users.

The 25–44 age groups combined represented:

**67.53% of unique users**

Male users represented **84.88%** of unique users, while female users represented **11.13%**.

Unknown gender records represented **3.99%**.

### Geography

**Gauteng** had the largest observed audience:

- 1,607 unique users
- 3,652 sessions

This represents the largest observed audience in the available dataset. It should not be interpreted as market penetration because population/subscriber denominator data was not available.

### Viewing Days

| Day | Sessions |
|---|---:|
| Friday | 1,673 |
| Saturday | 1,633 |
| Wednesday | 1,553 |
| Thursday | 1,440 |
| Sunday | 1,418 |
| Tuesday | 1,322 |
| Monday | 956 |

**Friday** was the highest-consumption day.

**Monday** was the lowest-consumption day.

### Peak Viewing Hour

The highest number of sessions occurred at:

**17:00 – 648 sessions**

Other strong viewing periods included the afternoon and evening.

### Channel Performance

The strongest channels in the verified analysis included:

| Channel | Sessions |
|---|---:|
| Supersport Live Events | 1,637 |
| ICC Cricket World Cup 2011 | 1,465 |
| Channel O | 1,048 |
| Trace TV | 952 |
| SuperSport Blitz | 896 |
| Africa Magic | 857 |
| Cartoon Network | 793 |
| Boomerang | 714 |
| CNN | 505 |
| E! Entertainment | 367 |

Supersport Live Events was the strongest channel in the verified channel analysis.

---

## 7. Consumption Analysis

The analysis considered several factors associated with viewing consumption:

- Age
- Gender
- Province
- Channel
- Day of week
- Hour of day
- Age and gender
- Channel and gender

The analysis identifies **observed patterns and associations**. It does not establish causal relationships.

For example, strong viewing of sports and event-based content indicates an association with high viewing activity in the dataset, but does not prove that the content itself caused the higher consumption.

---

## 8. Low-Consumption Day Analysis

Monday was identified as the lowest-consumption day with:

**956 total sessions**

The strongest Monday channels included:

- Channel O – 136 sessions
- Trace TV – 115 sessions
- Supersport Live Events – 98 sessions
- Cartoon Network – 94 sessions
- Africa Magic – 92 sessions
- Boomerang – 84 sessions
- CNN – 73 sessions
- SuperSport Blitz – 71 sessions
- ICC Cricket World Cup 2011 – 69 sessions

The analysis indicates an opportunity to test targeted programming and engagement strategies on Mondays.

---

## 9. Recommendations

### 9.1 Monday Engagement

Test Monday-specific programming and engagement strategies based on content that already performs well.

Potential approaches include:

- Music and entertainment programming
- Content similar to strong Monday performers such as Channel O and Trace TV
- Strategic promotion of sports and event content
- Monday notifications and content reminders

These recommendations should be tested rather than treated as guaranteed outcomes.

### 9.2 Audience Targeting

The **25–44 audience represents 67.53%** of unique users.

BrightTV could therefore prioritise this audience for targeted engagement and retention initiatives.

### 9.3 Female Audience Acquisition

Female users represent **11.13%** of unique users in the verified analysis.

BrightTV could test targeted initiatives aimed at improving female audience acquisition and engagement.

### 9.4 Younger Audience Advocacy

Some younger audience segments show relatively high sessions per user.

BrightTV could test referral, advocacy and social-sharing initiatives aimed at highly engaged younger users.

### 9.5 Regional Targeting

Gauteng has the largest observed audience in the available dataset.

Regional campaigns could be explored using observed audience concentration, while avoiding unsupported claims about market penetration.

### 9.6 Sports & Event Content

Sports and event-based content shows strong viewing activity.

BrightTV could strategically promote high-performing events while measuring the effect of those campaigns.

---

## 10. Interactive Dashboard

An interactive BrightTV dashboard was developed to communicate the findings visually.

The dashboard includes:

- Overview
- Audience Analysis
- Viewing Behaviour
- Channel Performance
- Demographic Analysis
- Detailed Analysis
- Key Insights
- Data Methodology

Interactive filters include:

- Gender
- Age Group
- Province
- Channel
- Day of Week
- Hour
https://tvinsight-hub.lovable.app
The dashboard is designed to allow users to explore the data beyond the static report.

## Interactive Dashboards

### Looker Studio

Explore the BrightTV Viewership Analytics dashboard:

**[Open BrightTV Looker Studio Dashboard](https://datastudio.google.com/s/rTCqCmjZDh0)**

The dashboard provides interactive analysis of:

- Audience demographics
- Age and gender
- Province
- Viewing by day
- Viewing by hour
- Channel performance
- User and session behaviour
- Key BrightTV insights

### Lovable Dashboard

**[Open BrightTV Interactive Dashboard](YOUR_LOVABLE_LINK)**

The Lovable dashboard provides an additional interactive presentation of the BrightTV analysis.

---
## 11. Final Presentation

The BrightTV Viewership Analytics findings were presented in a 20-minute data analytics presentation covering the complete analysis and business recommendations.

### Presentation Contents

The presentation covers:

1. **Project Introduction**
2. **Business Problem**
3. **Business Questions & Objectives**
4. **Data & Methodology**
5. **Executive Overview**
6. **Audience Analysis**
7. **Age Group Analysis**
8. **Geographic Analysis**
9. **Viewing by Day of Week**
10. **Viewing by Hour**
11. **Channel Performance**
12. **Factors Associated With Consumption**
13. **Low-Consumption Day Analysis**
14. **Content Recommendations**
15. **Customer Growth Initiatives**
16. **Interactive Dashboard**
17. **Key Findings & Business Recommendations**
18. **Conclusion**

### Presentation File

The final presentation is available in:

`06_Presentation/BrightTV_Viewership_Analytics.pptx`

### Presentation Preview

A PDF version or slide preview can also be included in this repository for easy review.

**Presentation:** [BrightTV Viewership Analytics](./06_Presentation/BrightTV_Viewership_Analytics.pptx)




## 11. Data Quality & Limitations

The analysis identified several data-quality considerations.

### Missing / Unknown Values

Some records contain unknown or missing demographic values.

These are represented as **Unknown** where appropriate.

### Channel Naming Inconsistencies

The dataset contains naming inconsistencies such as:

- `SawSee` vs `Sawsee`
- `Supersport Live Events` vs `SuperSport Live Events`

These inconsistencies were identified and flagged rather than silently removed.

### Analytical Limitations

The analysis:

- Identifies patterns and associations rather than causation.
- Does not provide population denominators for calculating provincial market penetration.
- Contains some unknown demographic records.
- Contains smaller segments where interpretation should be cautious.
- Represents the available analysis period and should not automatically be treated as real-time behaviour.

Recommendations should therefore be validated through controlled testing and performance measurement.

---

## 12. Repository Structure

```text
BrightTV-Viewership-Analytics/
│
├── README.md
│
├── 01_Project_Description/
│   └── BrightTV_Project_Description.pdf
│
├── 02_Project_Planning/
│   ├── Mind_Map.pdf
│   └── Gantt_Chart.pdf
│
├── 03_Raw_Data/
│   └── BrightTV_Raw_Data.xlsx
│
├── 04_Data_Analysis/
│   ├── SQL/
│   ├── Excel/
│   └── Databricks/
│
├── 05_Dashboards/
│   ├── Lovable/
│   ├── PowerBI/
│   └── DataStudio/
│
├── 06_Presentation/
│   └── BrightTV_Viewership_Analytics.pptx
│
└── 07_Final_Report/
    └── BrightTV_Viewership_Analytics_Report.pdf
