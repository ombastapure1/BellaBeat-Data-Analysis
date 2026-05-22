# 🌿 Bellabeat Wellness Tech — Data Analytics

> Analyzing FitBit smart device data to uncover wellness trends and drive Bellabeat's marketing strategy.

**Author:** Om Santosh Bastapure  
**Dataset:** [FitBit Fitness Tracker Data — Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)

---

## 🎯 Business Task

Bellabeat is a high-tech wellness company that manufactures smart health products for women. The goal of this analysis is to:

> **Identify trends in smart device usage from third-party FitBit data and apply those insights to Bellabeat's marketing strategy.**

**Key Questions:**
1. What are the trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could they influence Bellabeat's marketing strategy?

---

## 🔬 Six-Phase Analysis (Ask → Act)

### 1. 🙋 Ask
Defined the business task and key stakeholder questions. Identified the need to understand how consumers use non-Bellabeat smart devices and translate that into marketing opportunities.

### 2. 📥 Prepare
Downloaded FitBit dataset from Kaggle. Assessed data credibility using the **ROCCC framework** — noted limitations around sample size, age of data, and absence of demographic information.

### 3. 🔧 Process
- Parsed and standardized date/time columns
- Removed duplicate rows
- Filtered out zero-step days (non-wear days)
- Extracted day-of-week and hour features
- Classified users into activity tiers (Sedentary / Lightly Active / Fairly Active / Very Active) based on CDC daily step guidelines
- Merged daily activity with sleep data for joined analysis

### 4. 📊 Analyze
- Computed descriptive statistics across all key metrics
- Identified activity patterns by day of week and hour of day
- Analyzed sleep duration and efficiency
- Examined device usage frequency
- Explored correlation between steps and calories burned

### 5. 📈 Share
Generated 7 visualizations covering user types, step patterns, hourly trends, calorie relationships, activity breakdowns, sleep patterns, and device usage. See [Visualizations](#-visualizations) below.

### 6. 🚀 Act
Produced 5 actionable marketing recommendations for Bellabeat. See [Recommendations](#-recommendations-for-bellabeat) below.

---
