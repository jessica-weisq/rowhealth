# Row Health Marketing Campaign Insights
## The project aim is to analyse historical campaign performance to enable data-driven budget allocation. Additionally, it provides the marketing team with self-service dashboards for automated, high-cadence insight reporting

**Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates

Recently, Row Health have hired a new data team to help with marketing budget decisions for the year. The company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information

<img width="612" alt="image" src="https://github.com/christinejiang11/rowhealth/assets/56368090/c51a152c-796c-4e64-82b4-db3141a88e0c">

## Insights Summary
#### To evaluate campaign performance, we focused on the following key metrics:
- **Signup Rate**: The percentage of website visitors who see a campaign and subsequently sign up for a Row Health plan
- **Cost per Signup (CPS)**: The average dollars spent to acquire a user signup from each campaign
- **Click through Rate (CTR)**: The percentage of website visitors who see a campaign and click on the associated link

#### Signup Rate
- Across campaign categories, "Health for All" is the best-performing campaign with a signup rate of X15 the overage signup rate (2.94% vs 0.19%) and the second-highest number of signups (3.5K), yet the invested amount is relatively low  ($20K)
- This high signup rate is attributed to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest user signups - #HealthyLiving - had a comparably lower signup rate at 0.3%.

#### Click-through Rate (CTR)
- Across categories, Health for All and Benefit Updates performed nearly 3-4x better than the average CTR at 36% and 22%, respectively
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%)
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign

#### Cost per Signup (CPS)
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($124), as well as the lowest number of signups (23), compared to an average of $2.2
- Within the two campaign categories with the highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K

## Recommendations
- **Reallocate funding to "Health for All"**: Prioritise the high-performing campaigns by reallocating budget from campaigns with high CPS, such as Golden Years Security
- **Focus on "Health Awareness" campaign category**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had a lower signup rate and CTR
- **Investigate COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that cost over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether
- **Reduce investment in HealthyLiving campaign**: The highest-spending campaign ($46K) has mediocre signup rates compared to "Health for All" campaigns

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/views/RowHealth_4Apr_JW/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<div class='tableauPlaceholder' id='viz1775667453790' style='position: relative'><noscript><a href='#'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ro&#47;RowHealth_4Apr_JW&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RowHealth_4Apr_JW&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ro&#47;RowHealth_4Apr_JW&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                

This dashboard enables users to filter by plan, campaign type, and state, with the focus on trends and values for marketing metrics, signup metrics, and claim metrics.





