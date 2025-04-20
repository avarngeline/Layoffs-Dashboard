# Global Tech Layoffs Dashboard
## Executive Summary

This project explores global tech industry layoffs between March 2020 and March 2023, with a focus on the United States. Using a cleaned dataset and an interactive Power BI dashboard, the analysis reveals key patterns in workforce reductions across industries, funding levels, and regions. Key findings show that over 384K layoffs occurred globally, with the U.S. alone accounting for 257K across 1885 companies. Consumer tech was the most affected industry, and even well-funded firms faced significant layoffs—highlighting that financial backing alone could not shield companies from market pressures.

The dashboard enables users to explore data by time, geography, industry, and funding stage. Insights point to common causes like economic uncertainty. The project emphasises the need for more sustainable growth and cautious workforce planning in the tech sector. While the dashboard provides meaningful insights, the dataset is limited to publicly available reports and includes some estimations due to missing data.

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

This dataset offers an in-depth overview of global company layoffs that took place between March 2020 and March 2023, covering 59 countries and 1885 companies. Primarily driven by the impact of the COVID-19 pandemic, the insights were derived from a Power BI dashboard that visualises key data points such as industry sectors, total layoffs, funding categories, and impacted companies.

## 2. Project Objectives
The objective of this project is to enhance the previous analysis of layoff trends—initially conducted through data cleaning and exploratory data analysis (EDA) using MySQL—by introducing advanced data visualisation through Power BI. The upgraded version incorporates an interactive dashboard. A key focus of the analysis is to drill down into the country most affected by layoffs—the United States—offering a closer look at the companies and sectors contributing to the trend.

**Key Objectives for the USA Focus**
- To determine which industries and companies in the United States experienced the highest number of layoffs, helping to uncover patterns in sectors most vulnerable to workforce reductions.
- To evaluate how funding categories influenced the scale of layoffs among US-based companies, offering insight into whether higher funding provided stability.
- To track the timeline of layoffs across the US from March 2020 to March 2023, identifying peak periods and correlating them with major economic events or shifts.

## 3. Dashboard Features

![image](https://github.com/user-attachments/assets/794b6349-8b0b-401b-befc-6ac5c5a225b2)

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

![image](https://github.com/user-attachments/assets/52ce1a14-cb9b-46e2-9b45-55f3a1646f7f)

The recent wave of tech layoffs has resulted in over 384K jobs lost across 1885 companies in 59 countries, with affected firms laying off an average of 17% of their workforce. Despite raising significant funding, many companies, including 115 that shut down entirely, have struggled to withstand economic pressures.

**4.1.2. Top Layoff Companies**

![image](https://github.com/user-attachments/assets/c300fa9a-977d-4259-bc7e-dacb9e6c60f7)

Major tech firms, including Amazon, Google, Meta, Salesforce, Microsoft and Philips, have accounted for a significant share of layoffs, with Amazon leading at 18,150 job cuts. These numbers highlight the extensive restructuring and cost-cutting measures within the tech and consumer services sectors.

**4.1.3. Layoffs by Industry**

![image](https://github.com/user-attachments/assets/f5541ea5-b683-4512-99c1-7413514b665b)

Layoffs occurred across various tech industries, with consumer tech being the most affected, losing 45,182 jobs. Other sectors, including retail tech (43,613 layoffs), other tech (36,289), and transportation (33,748), also saw significant job losses. These figures reflect how economic pressures and market shifts have forced tech companies to scale back.

**4.1.4. Layoff Timeline (Mar 2020 – Mar 2023)**

![image](https://github.com/user-attachments/assets/ba449535-de2c-4546-8ef8-fce0842a704e)

The overall layoff timeline from March 2020 to March 2023 shows a progressive rise, with several notable points highlighted below.

- **Initial Spike During Early COVID-19 (Apr–May 2020):** Layoffs surged to around 27K in May 2020, reflecting the immediate economic impact of the pandemic’s first wave.

- **Stability Through 2021:** From mid-2020 through most of 2021, layoff numbers remained relatively low and stable, with only minor fluctuations and periods where layoffs were nearly zero.

- **Rising Layoffs in 2022:** Starting in mid-2022, layoffs began to climb, peaking at approximately 54K in November, indicating growing economic uncertainty and shifts in company strategies.

- **Peak in January 2023:** The most significant spike occurred in January 2023, with over 85K layoffs—marking the highest point in the entire timeline.

- **Decline After Peak:** After January 2023, layoff numbers declined sharply, suggesting a possible stabilisation or completion of major workforce reductions.

**4.1.5. Layoffs by Geography**

![image](https://github.com/user-attachments/assets/f7ddf9d3-e928-4c19-be9a-d74205fd2040)

Tech layoffs were most concentrated in North America and Europe, with the United States experiencing the highest number. Other affected countries include Canada, Germany, India, Brazil, and Australia, highlighting the global impact of macroeconomic challenges on the tech industry.

**4.1.6. Layoff Impact vs. Funding**

![image](https://github.com/user-attachments/assets/812fb710-16ec-470c-b70b-b6424f1bf798)

Layoffs affected companies at all funding stages, from early-stage startups to well-funded firms. Even companies with over $200 million in funding were not immune, while startups with less than $50 million also faced significant layoffs. This indicates that funding alone did not protect companies from the pressures of economic challenges.

**Global Insights Summary:**

The global analysis of tech sector layoffs reveals a significant concentration of workforce reductions in the United States, which has emerged as the epicentre of this trend. Despite widespread impacts across multiple countries, U.S.-based tech companies, both large and small, have experienced substantial layoffs. This underscores the necessity for a more in-depth examination of the specific factors driving layoffs within the U.S. market. The following section will explore the key trends, prominent companies, and regional variations of layoffs within the United States.

### 4.2. USA-Focused Insights

**4.2.1. Overview**

![image](https://github.com/user-attachments/assets/17e2062b-a536-4a5f-a0e4-6826c1a7b0fa)

These cards indicate that even heavily funded firms were not immune to market pressures. As between March 2020 and March 2023, the U.S. tech sector saw 257K layoffs across 1,232 companies, with 72 company shutdowns. The average funding per company stood at $791.31 million, and on average, 17% of each company’s workforce was laid off. 

**4.2.2. The Most Affected Industries and Companies in the US**

![image](https://github.com/user-attachments/assets/30703baa-3ffd-4629-a720-849bf809667d)

Layoffs in the U.S. tech sector were heavily concentrated among a few key players and industries between March 2020 and March 2023. The five most affected companies—Amazon (18,150 layoffs), Google (12,000), Meta (11,000), Salesforce (10,090), and Microsoft (10,000)—collectively accounted for 24% of all U.S. tech layoffs. This highlights significant restructuring efforts by some of the industry’s largest employers in response to shifting market conditions. 

![image](https://github.com/user-attachments/assets/eeac845b-47e2-4852-b14b-fd3e65abde96)

At the industry level, consumer tech still experienced the highest number of layoffs at 38,080, followed by retail tech (33,590), transportation (20,885), other (19,857), and real estate (14,837). The particularly severe impact on consumer tech can be attributed to the post-pandemic normalisation of consumer shopping behaviour, which followed a period of rapid expansion and hiring during the e-commerce boom.

**4.2.3. Startup Vulnerability and Funding Stage Impact**

![image](https://github.com/user-attachments/assets/00726f66-e537-4116-9704-3ac6ed0ffae8)

Startups with under $50M in funding were particularly vulnerable, often experiencing disproportionately high layoffs. However, highly funded firms (> $200M) also saw major reductions, indicating that funding size alone did not guarantee resilience. Companies across all funding categories—early-stage to post-IPO—faced pressures to reduce workforce, suggesting broader structural and economic drivers.

**4.2.4. Temporal Pattern of Layoffs**

![image](https://github.com/user-attachments/assets/663f6d6d-8906-450b-acc0-fce22ef78e3e)

The layoff trend in the United States closely mirrors the global pattern, with several notable highlights outlined below.

**Peak Activity:** Layoffs peaked in January 2023 (~65K), likely due to recession fears, inflationary pressures, and corporate over-hiring in earlier quarters.

**Other Spikes:** Notable layoffs occurred in May 2020 (~20K) during the first COVID-19 wave and in late 2022, hinting at early responses to macroeconomic uncertainty.

**Delayed Market Response** A gradual increase through 2022 followed by a sharp peak in late 2022 indicates a lagged reaction to market conditions.

**4.2.5. Geographic Concentration**

![image](https://github.com/user-attachments/assets/2ac6d80d-94de-4853-a333-2645cb9441d4)

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

![image](https://github.com/user-attachments/assets/6dbd1a81-fbce-4f0a-b87a-7e4316fd539c)

**4.3.2. Top Industries by Layoff Volume**

Consumer leads layoffs both globally and in the U.S., but industry impacts vary. Globally, consumer, retail, and other are heavily affected, while the U.S. sees more layoffs in consumer, retail, and transportation. Overall, global layoffs are higher, showing broader international disruption.

![image](https://github.com/user-attachments/assets/fff0fb0a-c075-4ba4-8671-1c133f1c972f)

**4.3.3. Company-Level Analysis: Notable Layoffs**

While the U.S. dominates global layoff volumes, the top five companies responsible—Amazon, Google, Meta, Salesforce, and Microsoft—highlight how the largest tech firms contributed significantly to workforce reductions globally.

![image](https://github.com/user-attachments/assets/4b5ee534-1a40-44b7-ae9c-945b4bb613d8)

**4.3.4. Temporal Patterns: Layoff Timeline Analysis**

Both datasets show a major synchronised peak in January 2023, reflecting global macroeconomic tightening.

![image](https://github.com/user-attachments/assets/2edbea87-bd04-470a-b4ff-71993f2403ae)

**4.3.5. Layoff Exposure by Funding Level**

The visual comparison shows that in the U.S., layoffs are largely concentrated among companies with lower funding levels, particularly those with less than $50M, as seen by the tight cluster of blue dots on the left side of the U.S. chart. In contrast, the global chart displays a wider spread of layoffs across all funding levels, including a significant number among companies with over $200M in funding. This suggests that while U.S. layoffs are more prevalent in underfunded firms, layoffs globally affect companies across all funding categories, indicating broader structural challenges in the global tech industry.

![image](https://github.com/user-attachments/assets/2463e333-ff3d-4a18-b041-b02921373ae6)

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
