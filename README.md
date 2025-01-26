# **Exploring Visitor Trends in Portugal: A Data-Driven Perspective**
**Data Science for Marketing** |
Outomn Semester - 2024/2025



Student Number  | Student Name
-------------------|------------------
20240108| Catarina Sousa
20240125|Maria Rita Correia
20211619       | Mariana Takimura
20241482 | Tomás Gomes

# 1. Business Understanding

## Background

**Problem**

The Portuguese NTBO (National Tourism Board Organization) is interested in assessing the impact of the COVID-19 pandemic on tourism. During the pandemic, visits to tourist attractions declined, and the goal is to analyze whether and how tourism is recovering. Compared to its main European competitors, Portugal wants to understand visitation patterns and visitor perceptions at its top attractions.

**Tourism in Portugal Over the Last Year (2016-2023)**

**Pre-pandemic Growth (2016-2019)**

Portugal's tourism sector experienced a period of robust growth between 2016 and 2019, supported by the global rise in trave demand and Portugal's increasing appeal as a destination.
- **Economic Contribution**: During this time, the CTTE increased by 40%, elevating its share in the GDP by 2.7 percentage points. Similarly, the VAGBT grew by 35.7%, adding 1.2 percentage points to the GVA.</p>
- **Visitor Arrivals**: by 2019, Portugal welcomed approximatel 24.6 million international visitors, marking a peak in tourism influx. These figures underscored Portugal's growing reputation as a preferred destination for leisure, culture, and gastronomy.
**Main effects of the COVID-19 pandemic on tourism in 2020**
The COVID-19 pandemic caused a severe and unprecedented disruption in global travel, with Portugal being no exception.
- **Decline in Tourism Activity:** in 2020, international visitor arrivals dropped drastically, from 24.6 million in 2019 to just 7.0 million. This decline continued into 2021, with only 6.35 million visitors recorded.
- **Economic Downturn:** These sharp declines had far-reaching economic repercurssions. Tourism's contribution to Portugal's GDP and employment contracted significantly, disrupting local businessess and leading to widespread uncertainty in the sector.

**Recovery and Resurgence (2022-2023)**

Despite the unprecedented disruptions caused by the pandemic, Portugal's tourism sector demonstrated remarkable resilience during its recovery phase.
- **Rebound in Visitor Numbers:** the easing of travel restrictions and successful vaccionation campaigns facilitated a rapid recovery. By 2023, Portugal recorded over 30 million visitors, surprassing pre-pandemic levels.
- **Economic Impact:** The resurgence of tourism translated into substantial economic gains, with revenues reaching approximately €25 billion in 2023. The sector's contribution to GDP not only rebounded but exceeded pre-pandemic levels, emphasizing its vital role in the national economy.

**Visualization of Tourism Trends (2016-2023)**

To better understand the trajectory of international visitor arrivals in Portugal from 2016 to 2023, the following Python code visualizes the data


## 1.1 Determine Business Objectives

**PRIMARY OBJECTIVE**

Identify and describe changes in visitor patterns and satisfaction levels in Portugal, comparing them with other European destinations.

**Related Questions**
- How have visitor volumes and satisfaction ratings for Portuguese attractions evolved during and after the pandemic’s peak periods compared to competitor destinations?
- What differences exist between local and international tourist behaviors, preferences, and satisfaction levels when visiting Portuguese attractions?
- Which holidays or specific timeframes (e.g., summer, Christmas) show the fastest tourism recovery in Portugal compared to competitors?
- What types of tourists (personas) are most likely to visit Portugal, and how do their preferences and behaviors differ from tourists visiting competing destinations?
- What is the relationship between tourist personas visiting Portugal and those choosing its primary European competitors?
- How do seasonal patterns, holiday periods, and post-pandemic sentiment influence tourism recovery in Portugal versus competing countries?

**BUSINESS SUCCESS CRITERIA**

The success of this project will be determined by both business outcomes and technical achievements. On the business side, the project aims to deliver actionable insights into visitor demographics, preferences, patterns, and satisfaction levels, enabling strategic decision-making for Portugal's tourism industry. Success will be measured by the comprehensiveness and usability of the insights provided.

The project will be deemed successful if it provides the NTBO with actionable insights into visitor behavior and preferences, enabling the board to tailor marketing strategies, optimize resource allocation, and support the recovery of the tourism sector.


## 1.2 Assess Situation

**INVENTORY OF RESOURCES**

**Data**: Tripadvisor reviews and visitation data for attractions in Europe, holiday data, and additional datasets for cross-country comparison.
- **Primary Dataset:** _EuropeTop100Attractions_ sourced from TripAdvisor, this dataset includes reviews for the top 100 tourist attractions across Europe from January 1, 2019 to August 21, 2021. It provides valuable insights such as visitor reviews, user locations, trip types, and the timing of visits
- **Suplementary Dataset:** _Holidays_ contains worldwide public holiday information, essential for analyzing seasonal and peak tourist trends.
- **Aditional Datasets:** potential use of geographic and supplementary datasets to enhance cross-country comparisons and enrich data understanding.

**Personnel**: a team of four analysts will handle the data exploration, modeling, and reporting tasks. External consultation with tourism experts may be sought for contextual understanding.

**Software Tools**: Primary tools include Python (Jupyter notebooks) for data analysis and Excel for additional hangling.

**REQUIREMENTS, ASSUMPTIONS, AND CONSTRAINTS**

**Requirements**:
- Complete the analysis within a specified timeframe (semester)
- Deliver visual reports that are easy for the NTBO to understand

**Assumptions**:
- Review data reflects the actual experience and satisfaction of tourists.
- Observed changes after March 2020 are largely due to the pandemic's impact

**Constraints**:
- Limited access to data beyond Tripadvisor and holiday datasets.
- Constraints on time and resources for detailed text analysis

**RISKS AND CONTINGENCIES**

**Risks**: Inconsistencies or incomplete data; lack of comparable data from other countries; time limitations.

**Contingencies**: Reevaluate project scope if data proves insufficient for cross-country comparisons or certain temporal analyses.

**TERMINOLOGY**

**Business Glossary**: Recovery tourism, seasonality, visitor satisfaction, NTBO (National Tourism Board Organization).
- _Recovery Tourism_: Strategies aimed at revitalizing the tourism sector post-pandemic.
- _Seasonality_: Patterns of visitor behavior based on seasonal factors or holidays.
- _Visitor Satisfaction_: Metrics or feedback indicating how well a destination meets visitor expectations.


**Data Mining Glossary**: Visitor segmentation, time series analysis, RFM (Recency, Frequency, Monetization).
- _Visitor Segmentation_: Grouping visitors based on shared characteristics or behaviors.
- _Time Series Analysis_: Analyzing temporal data to identify trends and forecast future behavior.
- _RFM Analysis_: A technique to classify visitors based on Recency, Frequency, and Monetary (or equivalent engagement-based) values.

**COSTS AND BENEFITS**

**Costs**: Time investment from the analysis team. Resources needed for software licenses or additional tools (e.g., visualization platforms).

**Benefits**: Insights that guide the NTBO on marketing and recovery strategies, along with the competitive advantage of understanding post-pandemic tourism patterns.

## 1.3 Determine Data Mining Goals

**DATA MINING GOALS**
- Conduct a temporal analysis of visits and ratings to identify recovery and seasonality trends.
- Use segmentation (such as RFM) to categorize visitors and identify behavioral profiles.
- Compare Portugal with competitor countries on key metrics like average ratings, visit volume, and seasonal patterns.

**DATA MINING SUCCESS CRITERIA**
- Technical success will be achieved if time-series and segmentation algorithms reveal clear, accurate patterns.
- The segmentation model should produce visitor groups that are useful for marketing recommendations, based on precision and differentiation.

## 1.4 Project Plan

**PROJECT PLAN**
1. Data Understanding
2. Data Preparation
2. Market Basket Analysis
3. RFM Model


**TOOLS AND TECHNIQUES**

Python for data analysis and for visualizations, and clustering methods for segmentation.
