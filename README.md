<h1 style="text-align: center;">iFood CRM Data Analyst Case</h1>

**AUTHOR:** Thibatsane I. Mahlelebe

## Introduction
This is an open project aimed at getting data analysts to provide insights and value to the company using customers' meta-information and iFood's campaign interactions with those customers. The challenge is to understand the data, find business opportunities & insights and to propose data-driven actions to optimize campaign results and generate value to the company.

## Problem Definition
iFood's revenue projections for the next 3 years shows declining growth. In order to invert this situation, the company has - amongst many other strategic initiatives - sought to improve performance of marketing activities with a special focus on marketing campaigns.
Next month, the company will be rolling out its 6th marketing campaign where it'll be selling a new gadget, so a data-driven strategy is required to make this coming campaign a success.

# Insights From Exploratory Analysis

## Response Analysis
The results have been fairly consistent; all campaigns have been reporting success rates around 10-15%, with the highest success rate in the most-recent campaign.
![Alt Text](https://github.com/IvanMahlelebe/ifood-marketing/blob/master/overall_perfomance.png)

This information thus, begs the question of whether or not these responsive customers were the same set throughout. We thus learn from the following 2 graphs that this is not the case. There's no meaningful positive correlation between acceptance of campaigns, meaning, accepting one campaign didn't say much about whether or not they will accept another campaign in the future.
![Alt Text](https://github.com/IvanMahlelebe/ifood-marketing/blob/master/cmp_correlations.png)

Furthermore, the majority of customers that reacted positively to the campaigns had only accepted one campaign, meaning the majority of wins - per campaign - typically came from customers that hadn't accepted a campaign before.
![Alt Text](https://github.com/IvanMahlelebe/ifood-marketing/blob/master/positive_responses.png)

We can investigate this further, by showing the exact set of campaigns that each customer accepted:
![Alt Text](https://github.com/IvanMahlelebe/ifood-marketing/blob/master/cmp_combos.png)

This shows us that the majority of customers chose only Campaing 3, Campaign 4 and Campaign 3 and 5.

It is worth noting that, the white colour from the correlation map suggest a strong negative/inverse relationship between customers that accepted Campaigns 3 and 4. This is to say, if a customer accepted one of these campaigns, then they're less likely to accept the other. Without any further information on these, it's difficult to tell what this means: an easier explanation is that perhaps, these are loyal customers that are different in their own ways e.g. their preferences, hence one group was catered for more on one campaign and not the other and vice-versa.
It is thus important that further analysis are carried out on these two campaigns as they may shed light on the kind of users we have. Not leaving the fact that campaign 3 was relatively the most successful as it appears on the top 3 twice.
