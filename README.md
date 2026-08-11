# External Food Purchase Analysis

## Objective

This project analyzes patterns in external food purchases across days, weeks, and months to identify changes in purchasing frequency and spending.

## Tools

- Google Sheets
- Data Visualization

## Questions
### 2025 Purchasing Trends
1. Which months saw the most purchases in 2025?
2. Which days of the week showed the highest total spent in 2025?
3. Does spending vary by week of the month?
4. Is there a correlation between the timing of the month (weeks 1 through 4) and increased spending? 
### 2025 to 2026 Comparison
1. Which restaurants had the most purchases over both years?
2. Are there consistent purchasing patterns between both January through July time periods?

## Challenges and Discoveries
### Data Cleaning is King
When analyzing which restaurants had the most purchases, my initial results surprised me. There were restaurants with lower purchase numbers than I knew to be true. When pulling the list of restaurant names, I initially used the =UNIQUE() function. Going back to the data cleaning step, I identified naming inconsistencies. For example, for one restaurant, one was spelled **"Anitas"** and the other spelled **"Anita's."** This created two separate unique entries and split the number of purchases for the same restaurant. I recleaned the data before starting a second analysis. 
### Partial Data
I initially used all the available 2025 and 2026 transaction data in this analysis. I identified an issue after the initial analysis. 2026 only carried partial-year observations. There would be months with two years of complete data (January - July) and others without (August - December). This may skew the results and the analysis. Therefore, I altered my approach by splitting the analysis into two parts: trends over 2025 and comparing the (January - July) timeframe for both years. 

## Key Findings
IN PROGRESS

## Recommendations

IN PROGRESS
