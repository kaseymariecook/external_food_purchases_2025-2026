# External Food Purchase Analysis

## Objective

This project analyzes patterns in external food purchases across days, weeks, and months to identify changes in purchasing frequency and spending.

## Tools

- Google Sheets
- Data Visualization

## Data Set
- External food transactions from January 2, 2025 to August 4, 2026

## Questions
### 2025 Purchasing Trends
1. Which months saw the most purchases in 2025?
2. Which days of the week showed the highest total spent in 2025?
3. Is there a pattern between the timing of the month (weeks 1 through 4) and increased spending? 
### 2025 to 2026 Comparison
1. Which restaurants had the most purchases over both years?
2. Are there consistent purchasing patterns between both January through July time periods?

## Challenges and Discoveries
### Data Cleaning is King
When analyzing which restaurants had the most purchases, my initial results surprised me. There were restaurants with lower purchase numbers than I knew to be true. When pulling the list of restaurant names, I initially used the =UNIQUE() function. Going back to the data cleaning step, I identified naming inconsistencies. For example, for one restaurant, one was spelled **"Anitas"** and the other was spelled **"Anita's."** This created two separate unique entries and split the number of purchases for the same restaurant. I recleaned the data before starting a second analysis. 
### Partial Data
I initially used all the available 2025 and 2026 transaction data in this analysis. I identified an issue after the initial analysis. 2026 only carried partial-year observations. There would be months with two years of complete data (January - July) and others without (August - December). This may skew the results and the analysis. Therefore, I altered my approach by splitting the analysis into two parts: trends over 2025 and a comparison of the (January - July) timeframe for both years.

## Key Findings
### 2025 Purchase Trends
1. The month of June saw the most purchasing activity in 2025
2. Saturdays saw the most purchasing activity across days of the week
3. Spending does vary by week order in the month, with purchases being highest in the 4th week (end of the month). This is likely due to upcoming budget rollover to the next month and wanting to spend what's left of the category. Week 2 consistently shows the lowest activity. I believe this is due to falling excitement after going out to eat when the budget first rolls over to a new month.
### 2025 to 2026 Comparison
1. Taco Bell was the restaurant frequented the most in 2025. Panera was the restaurant frequented the most in 2026. This is likely due to us joining Panera's Sip Club membership to receive free beverages and eating there more as a result. We also were gifted a Costco membership and moved our lower food tier spending from Taco Bell to the Costco Food Court.
2.  

## Recommendations

IN PROGRESS
