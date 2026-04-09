# Medical Insurance Marketing Campaign Insights

## Background
Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, the company launched a series of marketing campaigns spanning topics like wellness tips, plan affordability, and preventative care. The insurance plans differ in premiums and claim coverage rates. There are four different plans available for customers: Bronze, Silver, Gold, and Platinum 

Over a four-year period, Row Health has acquired over 16,000 new signups and processed approximately 50,000 claims

Recently, Row Health hired a new data team to help with marketing budget decisions for the upcoming year. The company would like to better understand the effectiveness of the existing campaign categories and how they relate to signups and subsequent member claims

## Project Aim
The project aims to analyse the performance of the 57 historical marketing campaigns from 2019-2023 to enable data-driven budget allocation Additionally, it provides the marketing team with self-service dashboards for automated, high-cadence insight reporting

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information

<img width="612" alt="image" src="https://github.com/christinejiang11/rowhealth/assets/56368090/c51a152c-796c-4e64-82b4-db3141a88e0c">

## Insights Summary
### Key Performance Metrics
To evaluate campaign performance, we focused on the following key performance metrics:
- **Signup Rate**: The percentage of website visitors who see a campaign and subsequently sign up for a Row Health plan
- **Cost per Signup (CPS)**: The average dollars spent to acquire a user signup from each campaign
- **Click through Rate (CTR)**: The percentage of website visitors who see a campaign and click on the associated link

#### Signup Rate
- Across campaign categories, "Health for All" is the best-performing campaign with a signup rate of 15x the overage signup rate (2.94% vs 0.19%) and the second-highest number of signups (3.5K), yet the invested amount is relatively low  ($20K)
- This high signup rate is attributed to the "Health Awareness" campaign type, which had by far the highest signup rate across all campaign types (3.72%)
- Interestingly, the category "#HealthyLiving" has the highest user signups but a comparably lower signup rate of 0.3%

#### Click-through Rate (CTR)
- Across categories, "Health for All" and "Benefit Updates" performed nearly 3-4x better than the average CTR at 36% and 22%, respectively
- Within the two high-CTR categories, product promotion-based campaigns had relatively low CTR (0% and 7%)
- Despite having a high impressions, "Family Coverage Plan" had no clicks, possibly due to missing data or issues with the campaign - the underlying reason needs to be further investigated with the marketing teams

#### Cost per Signup (CPS)
- Across campaign categories, "Golden Years Security" is by far the worst-performing, with the highest cost per signup ($124) and the lowest number of signups (23), compared to an average of $2.2
- Within the two campaign categories with the highest CPS, info-based campaign types (i.e., offers and policy info) are the major cost drivers
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K

## Recommendations
- **Redirect funding to "Health for All" campaign category**: Prioritise the high-performing campaigns by reallocating budget from campaigns with high CPS, such as Golden Years Security
- **Focus on "Health Awareness" campaign type**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had a lower signup rate and CTR
- **Reduce investment in "HealthyLiving" campaign category**: The highest-spending campaign ($46K) has mediocre signup rates compared to "Health for All" campaigns
- **Investigate the "COVID Awareness" Campaign type**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns across campaign categories, which had 2 signups that cost over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/views/RowHealth_4Apr_JW/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

 <img width="2398" height="2398" alt="Dashboard" src="https://github.com/user-attachments/assets/c339f414-2e5e-4c74-a7ba-49005930f19e" />

