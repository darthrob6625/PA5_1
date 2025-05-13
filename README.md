# Robert Meza
## Module 5: Practical Application 1

Link: [prompt.ipynb](prompt.ipynb)

### Problem Statement 
The purpose of this module is to analyze the survey responses, which include over 12,000 entries, and identify the characteristics associated with a higher likelihood of accepting a coupon. Without applying any filters, more than 7,000 individuals accepted a coupon, representing approximately 56% of the total respondents. The dataset includes over 20 variables that can be used to further refine the analysis criteria.

### Data Cleaning
Upon initial inspection, the car specification column contained predominantly missing values, so I chose to drop it entirely. Additionally, five other columns each had approximately 200 missing entries, which is less than 1 percent of the total dataset, so I elected not to drop or modify those values.

In hindsight, I should have converted many of the string encoded variables, for example, age categories, into integer or numeric formats. Doing so would have made the numerical analysis and visualization more straightforward. If time allows, I plan to revisit this assignment and reformat the data before proceeding with the analysis.

### Findings
- Of the 7,210 individuals who accepted the coupon, the largest age group was those aged 21–31, accounting for 4,226 individuals, or 59%.
- Of those who accepted the coupon, 1,992 individuals, representing 28%, were either students or unemployed. These were two of the largest occupation categories among recipients, both considered not currently working.
- The coffee house category was the largest group of individuals who were offered a coupon.
- In regards to temperature, the warmer the temperature, the greater the chance of being offered and accepting a coupon. 
- All income groups accepted the coupon, with the highest redemption values observed among groups earning $50K and under.

*See assignment for specifics and visual representations*
