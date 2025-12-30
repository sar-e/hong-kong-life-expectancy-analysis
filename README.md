# Hong Kong Life Expectancy Analysis (1960-2023)
Analysis of Hong Kong life expectancy trends (1960-2023) - Data Science portfolio project
**Author:** [Sarah Waseem]


## TL;DR
- **Analyzed 64 years** of Hong Kong life expectancy data from World Bank
- **Found 19.6-year improvement** (1960-2023) → **0.31 years/year average**
- **Current: 85.25 years** (2023) vs **65.70 years** (1960)
- **Skills shown:** Data cleaning, time-series analysis, visualization, statistical modeling
- **Relevance:** Directly applicable to actuarial risk assessment and insurance pricing


## PROJECT OVERVIEW
As a first-year Data Science student exploring actuarial career paths, I analyzed Hong Kong's life expectancy trends using World Bank data. This project demonstrates my ability to transform raw data into actionable insights relevant to insurance risk modeling.


## KEY FINDINGS
### **Statistical Summary**
| **Total Improvement (1960-2023)** | 19.6 years |
| **Average Annual Increase** | 0.31 years |
| **Highest Annual Increase** | 1.59 years (2023) |
| **Lowest Annual Change** | -1.87 years (2022) |
| **Current Life Expectancy** | 85.25 years (2023) |
| **Starting Point** | 65.70 years (1960) |
| **Probability of Annual Improvement** | 92% |

### **Trend Insights**
- **Rapid Growth Periods:** 1975-1985, 1995-2000, 2010-2021
- **Recent Volatility:** 2022 showed unusual decline (-1.87 years), followed by recovery in 2023
- **Steady Improvement:** Only 5 years showed decline in 64-year period


## METHODOLOGY
### **1. Data Acquisition & Cleaning**
- **Source:** World Bank API (SP.DYN.LE00.IN indicator)
- **Initial dataset:** 266 countries × 70 columns (1960-2024)
- **Extraction:** Filtered for "Hong Kong SAR, China"
- **Transformation:** Pivoted from wide to time-series format
- **Cleaning:** Removed null values, standardized date format
- **Validation:** Checked for data consistency and completeness

### **2. Analysis Performed**
# Key calculations in the notebook:
1. Annual change = Life_Expectancy(t) - Life_Expectancy(t-1)
2. 5-year moving average
3. Statistical summaries (mean, min, max)
4. Trend line fitting (linear regression)
5. Future projections (2024-2033)

![Hong Kong Life Expectancy Trends](https://raw.githubusercontent.com/sar-e/hong-kong-life-expectancy-analysis/main/actuarial_life_expectancy_analysis.png)

_Created as part of my data science learning journey._
