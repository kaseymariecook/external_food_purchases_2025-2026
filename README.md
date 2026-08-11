# External Food Purchase Analysis

## Objective

This project analyzes patterns in external food purchases across days, weeks, and months to identify changes in purchasing frequency and spending.

## Tools

- Google Sheets
- Data Cleaning
- Pivot Table
- Graph Generation
- Data Visualization

## Data Set
- External food transactions from January 2, 2025 to August 4, 2026
- 2025 includes full year data set (January - December)
- 2026 includes a partial data set (January - July)

## Questions
### 2025 Purchasing Trends
1. Which months saw the most purchases in 2025?
2. Which days of the week showed the highest total spent in 2025?
3. Is there a pattern between the timing of the month (weeks 1 through 4) and increased spending? 
### 2025 to 2026 Comparison
1. Which restaurants had the most purchases over both years?
2. Are there consistent purchasing patterns between both January through July time periods?

## Challenges and Discoveries
### Data Cleaning and Validation
When analyzing which restaurants had the most purchases, my initial results surprised me. There were restaurants with lower purchase numbers than I knew to be true. When pulling the list of restaurant names, I initially used the =UNIQUE() function. Going back to the data cleaning step, I identified naming inconsistencies. For example, for one restaurant, one was spelled **"Anitas"** and the other was spelled **"Anita's."** This created two separate unique entries and split the number of purchases for the same restaurant. I recleaned the data before starting a second analysis. 
### Partial Data
I initially used all the available 2025 and 2026 transaction data in this analysis. I identified an issue after the initial analysis. 2026 only carried partial-year observations. There would be months with two years of complete data (January - July) and others without (August - December). This may skew the results and the analysis. Therefore, I altered my approach by splitting the analysis into two parts: trends over 2025 and a comparison of the (January - July) timeframe for both years.

## Data Visualizations
<img width="350" height="234" alt="chart" src="https://github.com/user-attachments/assets/e47f6323-3e2c-4797-b402-60877aac26b1" />
<img width="350" height="216" alt="Number of Purchases vs  Week Number" src="https://github.com/user-attachments/assets/533b4950-4d49-40a0-905c-a1b2fa3478e9" />
<img width="350" height="216" alt="Number of Purchases vs  Month 2025" src="https://github.com/user-attachments/assets/c0dff8e1-e919-4a2f-8d91-7d9db2e3ebe7" /><img width="350" height="216" alt="Amount Spent Per Day of the Week 2025" src="https://github.com/user-attachments/assets/9edf68fe-80d5-4365-9c50-ad6adfa0c0e5" />
<img width="350" height="234" alt="chart (1)" src="https://github.com/user-attachments/assets/56b48804-90b8-4a1c-8ce5-7caa82371124" />

### 2025
<img width="371" height="659" alt="Top Restaurants in 2025" src="https://github.com/user-attachments/assets/112dc105-828c-4664-ac57-8d35abd18530" />

### 2026
<img width="371" height="659" alt="Top Restaurants in 2026" src="https://github.com/user-attachments/assets/24477952-4843-44f0-a51b-544858349423" />


## Key Findings
### 2025 Purchase Trends
1. **The month of June saw the most purchasing activity in 2025**
2. **Saturdays saw the most purchasing activity across days of the week**
3. **Spending was highest during the fourth week of the month, while Week 2 showed the lowest activity.** One possible explanation is that spending patterns may be influenced by the timing of the monthly food budget, although this analysis does not establish causation.
### 2025 to 2026 Comparison
1. **Taco Bell was the restaurant frequented the most in 2025. Panera was the restaurant frequented the most in 2026.** For context, this coincides with joining Panera's Sip Club membership to receive free beverages and eating there more as a result. We also were gifted a Costco membership and moved our lower food tier spending from Taco Bell to the Costco Food Court.
2. For both 2025 and 2026, spending consistently increased from January into March and then from April to June. Spending in 2026 is higher than spending in the same time period in 2025. 

## Recommendations
- Monitor spending during the last week of the month and on weekends since these periods produced the highest external food spending.  
- Continue to use standardized restaurant names for efficient analysis moving forward.
- Collect data for the rest of 2026 and recompare annual spending against 2025 for further conclusions. 
