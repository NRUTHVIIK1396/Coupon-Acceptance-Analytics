# Will a Customer Accept the Coupon?
UC Berkeley, PC-MLAI, Practical Application 1

### Overview
This repository hosts the code and analysis for a project titled "On Route Coupon Acceptance While Driving." The primary goal of the project is to predict whether a customer will accept a coupon while driving, based on specific contextual factors.

### Data Source
The dataset originates from the UCI Machine Learning repository and was collected via surveys on Amazon Mechanical Turk. The survey includes various driving scenarios, covering factors like destination, time of day, weather, and passengers. Respondents are asked whether they would accept a coupon while driving. Answers are classified as 'Y = 1' if the respondent would use the coupon immediately or later before expiration, and 'Y = 0' if the coupon is declined. The survey covers five coupon types: inexpensive restaurants (under $20), coffee houses, takeout, bars, and higher-end restaurants ($20 - $50).

### Methodology
The project employs several analytical methods and tools:
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Summaries
- Data Visualizations using Matplotlib, Seaborn, and Plotly

### Findings
Insights from the data analysis reveal the following patterns for coupon acceptance:

- Bar Coupons:
  - More likely to be accepted by:
  - Individuals Aged 25-30
  - Frequent bar-goers, especially those who visit more than three times a month
  - Driving with passengers who aren’t children
  - Working in occupations outside of farming, fishing, or forestry
  - Not widowed
  - Less likely to be accepted by those:
  - Visiting low-cost restaurants over four times a month
  - Earning less than $50K

- Coffee House Coupons:
  - About half of the coffee house coupons are accepted.
  - Drivers who visit coffee houses more than four times a month have higher acceptance rates than those who go less often.
  - Coupon acceptance is generally higher among younger adults (under 30 years old).
  - Among younger adults, acceptance is significantly higher for those visiting more than four times a month.
  - Widowed and divorced individuals have very low coffee house coupon acceptance rates.
  - For single and married drivers, those who visit more than three times a month are more likely to accept the coupon.
       
### Conclusion
The analysis suggests that targeting bar and coffee house coupons to the specific customer segments identified above will likely increase acceptance rates. Particularly younger adults who often visit have higher acceptance rate.

### Future Work
- Implementing a real-time recommendation system that personalizes coupons based on a combination of user preferences, driving behavior, and current contextual factors (e.g., traffic, weather, and time of day).
- Exploring the impact of offering multiple coupons simultaneously, such as bundling coffee house coupons with restaurant discounts or bar coupons, to assess whether bundled offers increase overall acceptance rates.
