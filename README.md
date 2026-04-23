# BrightTV_Viewership_Analysis

BrightTV: Viewership Analytics & Growth Strategy 
Dashboard SQL

1. Project Overview
BrightTV (fictional streaming platform) aims to grow its subscriber base within the current financial year. This analysis focuses on user profiles and viewing behaviour to support the CVM team with actionable insights.

Objective: Identify key audience patterns, peak viewing periods, and content drivers to improve retention and acquisition.

2. Data Engineering & Analytics Workflow

Time Standardisation: Converted UTC timestamps to SAST for accurate local analysis
Feature Creation: Built time segments (Morning, Afternoon, Prime Time), age groups, and weekday/weekend flags using SQL CASE logic
Data Cleaning: Resolved null and inconsistent values using COALESCE and NULLIF
Data Integration: Joined viewership data (10K+ records) with user profiles (5K+ users) to link behaviour with demographics

3. Key Business Insights 

3.1 Usage Trends

Afternoon Engagement: Highest total watch time (36%), indicating longer viewing sessions
Monday Decline: Lowest engagement at 8% of weekly activity
Regional Focus: Majority of usage concentrated in Gauteng, Western Cape, and KZN

3.2 Content & Audience Drivers

Sports Dominance: Accounts for nearly half of total watch time
Core Audience: Primarily users aged 20–35, with a strong male skew
Content Behaviour: Music drives frequent views, but shorter sessions compared to sports

4. Strategic Recommendations
Focus	Action	Outcome
Engagement	Introduce Monday content campaigns	Improve low-performing day
Monetisation	Target ads during afternoon peak	Increase revenue efficiency
Acquisition	Expand content diversity	Broaden audience reach
Expansion	Grow presence in underrepresented areas	Reduce regional concentration
Retention	Strengthen system performance on weekends	Improve user experience
