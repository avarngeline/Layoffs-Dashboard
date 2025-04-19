# Global Tech Layoffs Dashboard
## Executive Summary

This project explores global tech industry layoffs between March 2020 and March 2023, with a focus on the United States. Using a cleaned dataset and an interactive Power BI dashboard, the analysis reveals key patterns in workforce reductions across industries, funding levels, and regions. Key findings show that over 203,000 layoffs occurred globally, with the U.S. alone accounting for 138,000 across 535 companies. Retail tech was the most affected industry, and even well-funded firms faced significant layoffs—highlighting that financial backing alone could not shield companies from market pressures.

The dashboard enables users to explore data by time, geography, industry, and funding stage. Insights point to common causes like overhiring, economic uncertainty, and shifting consumer behaviour. The project emphasises the need for more sustainable growth, adaptive business models, and cautious workforce planning in the tech sector. While the dashboard provides meaningful insights, the dataset is limited to publicly available reports and includes some estimations due to missing data.

## Table of Content

[1. Overview](#1-overview)  
[2. Project Objectives](#2-project-objectives)  
[3. Dashboard Features](#3-dashboard-features)  
[4. Key Insights](#4-key-insights)  
[5. Strategic Implications](#5-strategic-implications)  
[6. Limitations](#6-limitations)  
[7. Conclusion](#7-conclusion)  


## 1. Overview
Layoffs, often resulting from financial pressures, strategic pivots, or market volatility, have become increasingly prevalent in recent years—particularly in the United States. The COVID-19 pandemic significantly disrupted global operations, forcing companies to adapt rapidly to changing economic conditions. In the US market, many organisations downsized their workforce to manage declining revenue, operational inefficiencies, overhiring during growth phases, and shifts in consumer demand. This analysis focuses on the US to better understand layoff patterns across industries, company funding levels, and the broader business impact.

This dataset offers an in-depth overview of global company layoffs that took place between March 2020 and March 2023, covering nearly 40 countries and more than 820 companies. Primarily driven by the impact of the COVID-19 pandemic, the insights were derived from a Power BI dashboard that visualises key data points such as industry sectors, total layoffs, funding categories, and impacted companies.

## 2. Project Objectives
The objective of this project is to enhance the previous analysis of layoff trends—initially conducted through data cleaning and exploratory data analysis (EDA) using MySQL—by introducing advanced data visualisation through Power BI. The upgraded version incorporates an interactive dashboard. A key focus of the analysis is to drill down into the country most affected by layoffs—the United States—offering a closer look at the companies and sectors contributing to the trend.

**Key Objectives for the USA Focus**
- To determine which industries and companies in the United States experienced the highest number of layoffs, helping to uncover patterns in sectors most vulnerable to workforce reductions.
- To evaluate how funding categories influenced the scale of layoffs among US-based companies, offering insight into whether higher funding provided stability.
- To track the timeline of layoffs across the US from March 2020 to March 2023, identifying peak periods and correlating them with major economic events or shifts.

## 3. Dashboard Features

![Image](https://github.com/user-attachments/assets/95195dbf-da11-4583-983e-69f8355aa6f5)

**1. Date Range Slider**

Users can adjust the date range to focus on a specific period (e.g., pre- and post-pandemic peaks).This allows exploration of how layoffs evolved over time and whether spikes align with global events or funding cycles.

**2. Dropdown Filters (Country, Industry, Fund Category)**

These filters customise the view based on user needs, allowing to filter by industry, while an investor could focus on funding categories to understand funding vs layoff risk.

**3. KPI Tiles**

When filters are applied, these numbers update instantly which helps users quickly grasp how total layoffs or company shutdowns vary across filters like industry or location.

**4. Time Series Chart**

Hovering or filtering shows how layoffs change month by year/quarter/month. Users can identify layoff surges (e.g., Jan 2023 spike) and drill down to see which companies/industries contributed.

**5. Industry Bar Chart**

This chart can be used to filter the entire dashboard by clicking on a specific industry, helping isolate and compare which sectors had the highest numbers, like Retail or Consumer.

**6. Map Visual (Global Layoffs Overview)**

The clickable regions allow location-specific exploration, helping to nderstand the geographical spread of layoffs.

**7. Scatter Plot (Layoff Impact vs. Funding by Industry)**

Users can spot industries with high funding but also high layoffs—suggesting potential inefficiencies or mismanagement.

## 4. Key Insights
### 4.1. Global Insights


**4.1.1. General Layoff Statistics**

![Image](https://github.com/user-attachments/assets/44f2e362-4373-42e7-8bcc-829886695158)


The recent wave of tech layoffs has resulted in over 203,000 jobs lost across 823 companies in 39 countries, with affected firms laying off an average of 26% of their workforce. Despite raising significant funding, many companies, including 61 that shut down entirely, have struggled to withstand economic pressures.

**4.1.2. Top Layoff Companies**

![Image](https://github.com/user-attachments/assets/ff89edc4-e982-4353-8949-f02234ce7418)

Major tech firms, including Amazon, Google, Ericsson, Dell, and Booking.com, have accounted for a significant share of layoffs, with Amazon leading at 18,150 job cuts. These numbers highlight the extensive restructuring and cost-cutting measures within the tech and consumer services sectors.

**4.1.3. Layoffs by Industry**

![Image](https://github.com/user-attachments/assets/d6a4184d-8f1a-4140-add5-3c23c4a2f5d4)

Layoffs occurred across various tech industries, with retail tech being the most affected, losing 31,370 jobs. Other sectors, including consumer tech (20,883 layoffs), food tech (14,650), and transportation (13,785), also saw significant job losses. These figures reflect how economic pressures and market shifts have forced tech companies to scale back.

**4.1.4. Layoff Timeline (Mar 2020 – Mar 2023)**

![Image](https://github.com/user-attachments/assets/9576c5ce-4f33-448c-accd-1cd5d1ad791c)

The overall layoff timeline from March 2020 to March 2023 shows a progressive rise, with several notable points highlighted below.

- **Initial Spike During Early COVID-19 (Apr–May 2020):** Layoffs surged to around 12,000 in May 2020, reflecting the immediate economic impact of the pandemic’s first wave.

- **Stability Through 2021:** From mid-2020 through most of 2021, layoff numbers remained relatively low and stable, with only minor fluctuations and periods where layoffs were nearly zero.

- **Rising Layoffs in 2022:** Starting in mid-2022, layoffs began to climb, peaking at approximately 10,000 by mid-year, indicating growing economic uncertainty and shifts in company strategies.

- **Peak in January 2023:** The most significant spike occurred in January 2023, with over 41,000 layoffs—marking the highest point in the entire timeline.

- **Decline After Peak:** After January 2023, layoff numbers declined sharply, suggesting a possible stabilisation or completion of major workforce reductions.

**4.1.5. Layoffs by Geography**

![Image](https://github.com/user-attachments/assets/1d723420-ccfd-4ca4-9887-8a8fec6f8c62)

Tech layoffs were most concentrated in North America and Europe, with the United States experiencing the highest number. Other affected countries include Canada, Germany, India, Brazil, and Australia, highlighting the global impact of macroeconomic challenges on the tech industry.

**4.1.6. Layoff Impact vs. Funding**

![image](https://github.com/user-attachments/assets/7d0a486f-4092-4246-a4fb-d842360472b8)

Layoffs affected companies at all funding stages, from early-stage startups to well-funded firms. Even companies with over $200 million in funding were not immune, while startups with less than $50 million also faced significant layoffs. This indicates that funding alone did not protect companies from the pressures of economic challenges.

**Global Insights Summary:**

The global analysis of tech sector layoffs reveals a significant concentration of workforce reductions in the United States, which has emerged as the epicentre of this trend. Despite widespread impacts across multiple countries, U.S.-based tech companies, both large and small, have experienced substantial layoffs. This underscores the necessity for a more in-depth examination of the specific factors driving layoffs within the U.S. market. The following section will explore the key trends, prominent companies, and regional variations of layoffs within the United States.

### 4.2. USA-Focused Insights

**4.2.1. Overview**

![image](https://github.com/user-attachments/assets/8702cb0d-65b8-4dc5-a632-76faee28c732)

These cards indicate that even heavily funded firms were not immune to market pressures. As between March 2020 and March 2023, the U.S. tech sector saw 138,000 layoffs across 535 companies, with 42 company shutdowns. The average funding per company stood at $391.73 million, and on average, 25% of each company’s workforce was laid off. 

**4.2.2. The Most Affected Industries and Companies in the US**

![Image](https://github.com/user-attachments/assets/ba72e295-1f87-4303-8704-4a369693705b)

Layoffs in the U.S. tech sector were heavily concentrated among a few key players and industries between March 2020 and March 2023. The five most affected companies—Amazon (18,150 layoffs), Google (12,000), Dell (6,650), Cisco (4,100), and Carvana (4,000)—collectively accounted for over 32% of all U.S. tech layoffs. This highlights significant restructuring efforts by some of the industry’s largest employers in response to shifting market conditions. 

![Image](https://github.com/user-attachments/assets/1c59ec34-de82-4b27-9b93-2743dc44a72e)

At the industry level, retail tech still experienced the highest number of layoffs at 26,827, followed by consumer tech (16,173), hardware (12,394), food tech (9,567), and finance (9,264). The particularly severe impact on retail tech can be attributed to the post-pandemic normalisation of consumer shopping behaviour, which followed a period of rapid expansion and hiring during the e-commerce boom.

**4.2.3. Startup Vulnerability and Funding Stage Impact**

![image](https://github.com/user-attachments/assets/b3e95fa3-9797-469c-9564-e26ac7d6700e)

Startups with under $50M in funding were particularly vulnerable, often experiencing disproportionately high layoffs. However, highly funded firms (> $200M) also saw major reductions, indicating that funding size alone did not guarantee resilience. Companies across all funding categories—early-stage to post-IPO—faced pressures to reduce workforce, suggesting broader structural and economic drivers.

**4.2.4. Temporal Pattern of Layoffs**

![Image](https://github.com/user-attachments/assets/aea92f57-4f2a-4610-bd42-92053adf6ed1)

The layoff trend in the United States closely mirrors the global pattern, with several notable highlights outlined below.

**Peak Activity:** Layoffs peaked in January 2023 (~36K), likely due to recession fears, inflationary pressures, and corporate over-hiring in earlier quarters.

**Other Spikes:** Notable layoffs occurred in May 2020 (~9K) during the first COVID-19 wave and in late 2022, hinting at early responses to macroeconomic uncertainty.

**Delayed Market Response** A gradual increase through 2022 followed by a sharp peak in early 2023 indicates a lagged reaction to market conditions.

**4.2.5. Geographic Concentration**

![Image](https://github.com/user-attachments/assets/43d16547-6bb9-4785-915b-0d71dd82fa83)

The map highlights a concentration in North America, with tech layoffs centred around key U.S. hubs such as:

- San Francisco Bay Area
- New York City
- Seattle

This distribution aligns with the locations of major tech headquarters, reinforcing the regional dependency of the U.S. tech industry on a few high-density ecosystems.

**USA-Focused Insights Summary**

The U.S. has been at the epicentre of global tech layoffs, with widespread impact across both mature firms and startups. Despite high funding levels, structural overcapacity, market volatility, and evolving consumer behaviour drove significant workforce reductions. The trends call for cautious growth strategies, better capital allocation, and agile workforce planning as the industry stabilises.


### 4.3. Comparative Analysis: U.S. vs Global Tech Layoffs

**4.3.1. Key Highlights Overview**

This table provides a side-by-side comparison of key layoff metrics between the United States and the global landscape.

![Image](https://github.com/user-attachments/assets/ef12e9d3-6680-4318-a7c4-78cfc5cf381c)

**4.3.2. Top Industries by Layoff Volume**

Retail leads layoffs both globally and in the U.S., but industry impacts vary. Globally, consumer, food, and transportation are heavily affected, while the U.S. sees more layoffs in hardware, healthcare, and real estate. Overall, global layoffs are higher, showing broader international disruption.

![Image](https://github.com/user-attachments/assets/42d3b69a-e464-49b6-a08f-40566401290c)


**4.3.3. Company-Level Analysis: Notable Layoffs**

While the U.S. dominates layoff volumes, companies like Ericsson and Booking.com illustrate how multinational firms across Europe were also severely affected.

![Image](https://github.com/user-attachments/assets/7657d398-b1d1-4758-8c00-3e188319edd9)

**4.3.4. Temporal Patterns: Layoff Timeline Analysis**

Both datasets show a major synchronised peak in January 2023, reflecting global macroeconomic tightening.

![Image](https://github.com/user-attachments/assets/45771cd0-20b2-4d64-b2e1-b48ade6a33ac)

**4.3.5. Layoff Exposure by Funding Level**

The comparison shows that globally, layoffs are more widespread across all funding levels, with a major spike in the $50M–$200M category. In the U.S., layoffs are more concentrated among companies with less than $50M in funding. While both globally and in the U.S. even highly funded companies (> $200M) experienced layoffs, the impact appears more severe and varied on a global scale.

![Image](https://github.com/user-attachments/assets/5f6dbb84-e494-4a19-8fd3-bff553513e77)

## 5. Strategic Implications

These findings carry important implications for the tech industry’s strategic planning. First, they call attention to the limitations of over-reliance on funding as a buffer against economic downturns. Second, the geographic concentration of layoffs suggests that regions with dense tech ecosystems may be particularly vulnerable during global downturns. Lastly, the recurrence of layoffs across all stages—from early-stage startups to post-IPO firms—highlights the need for more agile business models, prudent hiring strategies, and sustainable scaling practices.

Overall, while the U.S. serves as the focal point of tech layoffs, the broader global perspective reveals a shared vulnerability across the industry. Future growth in tech will likely depend on balancing innovation with operational resilience and adapting to dynamic global economic environments.

## 6. Limitations

- Some records had missing values, such as unknown funding or unreported layoff percentages. In these cases, values were either filled using the most common entry or estimated using aggregate measures, depending on the context and data availability.
- The dataset may not represent every company impacted by layoffs worldwide, as it is limited to publicly reported cases and available records.
- Certain assumptions were applied during the analysis, such as grouping funding amounts into broad categories for clearer comparison and interpretation.

## 7. Conclusion

This project provided a data-driven view of global and U.S. tech layoffs from March 2020 to March 2023. Using Power BI, it highlighted key trends across industries, funding levels, and time. The U.S. emerged as the most affected, with major layoffs concentrated in retail and consumer tech, regardless of funding size.

The findings show that high funding did not guarantee stability, and layoffs were driven by structural shifts, economic pressures, and overexpansion. While the dashboard offers valuable insights, the analysis is limited by incomplete data and necessary assumptions. Future research could expand with more detailed and current datasets.
