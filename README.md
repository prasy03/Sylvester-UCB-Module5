## Project Readme 
#### Prepared by: Sylvester Prasanna
### Project Summary: 

The `"coupons"` dataset was analyzed using pandas and other standard packages. 
This analysis extracted meaningful information, providing a better understanding of the data and aiding in the prediction of future customer behaviors based on observed patterns.

### Steps used to extract and visualize (reference to CRISP-DM) 

#### Business Understanding: 
* Project Scope: The project involves importing and analyzing data provided in CSV format.

#### Data Understanding: 
* The coupons.csv file was imported as a CSV.
* A sub-dataframe containing specific columns was created for particular use cases.

#### Data Preparation: 
* The dataframe was thoroughly checked for null values, incomplete strings, missing data, and incorrect data types. No deviations or misalignments were found.
* The .index was incorporated to improve the accuracy of the .count() function. 
* Wherever needed, the following functions were used to validate incomplete data `.isnull` 
* Some columns were dropped as they were not relevant for this specific use case. 
* Utilizing standard libraries for data extraction and visualization. 
* 'pandas', 'numpy', 'Matplotlib', 'seaborn', and 'plotly.express' were used.

#### Hypothesis:  
* An initial assessment was conducted using a subset of coupon usage data specifically for 'Bar' locations, revealing the following inferences:

#### Key Observations on Bar Coupon Usage:

1. `Gender Neutrality:` Coupon usage for bars is equally distributed between males and females.
2. `Offer Rate:` Bar coupons represent approximately 9% of all coupon categories offered.
3. `Low Redemption:` Despite being offered, bar coupons are the least frequently used category.
4. `Temperature Influence:` As temperatures rise, the redemption of bar coupons increases.
5. `Loyalty Paradox:` Frequent bar visitors (more than four times) tend to utilize fewer coupons.
6. `Demographic Contribution:` Unemployed individuals, students, and sales professionals collectively account for about 35% of all bar coupon redemptions.
7. `Marital and Age Demographics:` Divorced individuals and unmarried partners in the 31 to 46 age group show a higher propensity to use bar coupons. 

### Visualization: 

1. Name: Bar coupon usage by gender
  - Library Used: matplotlib
  - Inference: Both genders equally use coupons at bar. 

2. Name: Coupons by distribution of restaurants / bar 
  - Library Used: matplotlib
  - Inference: Coffee House and Cheap restaurants (Less than $20) occupy more than 50% of usage. 

3. Name: Bar usage more than once a month with a passenger. 
  - Library Used: Seaborn
  - Inference: Patrons visiting the bar more than 4 times tend to use less coupons. 

4. Name: Bar coupon usage across temperature variations 
  - Library Used: Seaborn and Matplotlib 
  - Inference: higher temperatures causes more visits and coupon usages at the bar. 

5. Name: Bar coupon usage by age
  - Library Used: Matplotlib and Seaborn 
  - Inference: Ages 31 to 41 used more coupons. 


6. Name: Bar coupon usage across number of visits 
 - Library Used: Seaborn
 - Inference: Frequent visitors use less coupons 


7. Name: Bar coupon usage across number of visits & varying conditions specified in Question#6 
  - Library Used: Matplotlib

8. Name: Bar coupon usage across Age and Marital status 
  - Library Used: Seaborn
  - Inference:  Divorced individuals and unmarried partners in the 31 to 46 age group show a higher propensity to use bar coupons. 


### Findings:
1. Problem Statement: Coupon Usage in the Bar Category
 - Frequent visitors (more than four visits) exhibit lower coupon redemption rates, suggesting potential issues with coupon insufficiency, expiration/validity, or proximity.

2. Visualizations: Differences in Coupon Acceptance and Rejection
 - Bar coupons constitute approximately 9% of all coupon categories offered.
 - Unemployed individuals, students, and sales professionals collectively account for about 35% of all bar coupon redemptions.

3. **Next Steps and Recommendations** 
Increase the number of coupons available in the Bar category.
Consider extending the validity period of bar coupons.


## Additional use case : Coffee House. 


- The high distribution of coffee house coupons (more than 50% of usage) suggests that this category is a significant driver of customer engagement. This widespread usage indicates a strong general interest in coffee house offerings, likely due to their accessibility and common consumption habits.

- Unemployed individuals and students collectively account for more than 56% of total coffee consumption.


nemployed individuals and students represent a portion (over 56%) of total coffee consumption, indicating that these categories are key targets for coffee house promotions. Tailoring coupon strategies to appeal to these groups could significantly boost redemption rates and overall engagement in the coffee house category.

