<h1 style="text-align: center;">iFood CRM Data Analyst Case</h1>

**AUTHOR:** Thibatsane I. Mahlelebe

## Introduction
This is an open project aimed at getting data analysts to provide insights and value to the company using customers' meta-information and iFood's campaign interactions with those customers. The challenge is to understand the data, find business opportunities & insights and to propose data-driven actions to optimize campaign results and generate value to the company.

## Problem Definition
iFood's revenue projections for the next 3 years shows declining growth. In order to invert this situation, the company has - amongst many other strategic initiatives - sought to improve performance of marketing activities with a special focus on marketing campaigns.
Next month, the company will be rolling out its 6th marketing campaign where it'll be selling a new gadget. A predictive model is therefore required that will produce the highest profit in this campaign.

As a precursor to this upcoming campaign, a pilot campaign was carried out. The campaign randomly selected 2 240 customers, contacted them by phone and asked them about the acquisition of this new gadget. These were the observations from this pilot:
* The pilot campaign cost \$6.72M (not sure what MU is, I wonder if it's "million USD", and I wonder how reasonable it is)
* Revenue generated from the campaign was \$3.674M i.e. money generated from customers who accepted the offer.
* Profit was therefore \$-3.046M
* With a success rate of 15%. I suppose this the conversion rate

## Expected Key Deliverables
- [ ] **Data Exploration** - The marketing team needs to adopt a more quantitative approach to their decision-making. Therefore you need to help them better understand the characteristic features of the respondents.
- [ ] **Customer Segmentation** -  The CMO is interested in understanding the characteristic feature of customers that are willing to buy this gadget, hence, a segmentation model for customer behaviours will be useful.
- [ ] **A Classification Model** - The goal is to make the next campaign more profitable. Thus, this model should be able to predict customer behaviour as it will be applied to the entire customer base so that the company can cherry pick customers that are most likely to purchase the offer while leaving out non-respondents.
- [ ] **Final Business Presentation** - Compile a presentation for the non-technical marketing team and the CMO, communicating important information for their understanding and decision-making.

# Insights

## Response Analysis
After the business had ran multiple campaigns(6 of them) on the same set of customers over time, we learn that the response rate has been consistent at 15% as we can see from the following graph:
![Alt Text](overall_performance.png)
