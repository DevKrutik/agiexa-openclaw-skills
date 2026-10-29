# Meta Ads use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/meta-ads

## Analyze Campaign Performance and ROAS

Understand which advertising campaigns generate the strongest attributed revenue, identify underperforming campaigns, and prioritize further investigation.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_GET_INSIGHTS`, `METAADS_LIST_CAMPAIGNS`

> Analyze my Meta Ads performance for the last 30 days. Retrieve available campaign-level insights, including spend, impressions, reach, clicks, CTR, CPC, CPM, purchases, conversion value, and ROAS wherever available. Rank campaigns by relevant performance metrics and identify the strongest and weakest performers. If Shopify data is available, compare attributed purchases and revenue with actual store orders without assuming the two datasets should match exactly. Explain attribution limitations, identify possible tracking inconsistencies, and recommend specific next steps. Separate confirmed metrics from estimates and missing data. Do not change campaign budgets, pause campaigns, or modify settings. Present the findings in a concise table with prioritized recommendations.

## Identify Wasted Advertising Spend

Find campaigns, ad sets, or ads that consume budget without delivering the expected outcomes, then recommend what to investigate.

- Apps: Meta Ads
- Tools: `METAADS_GET_INSIGHTS`, `METAADS_READ_ADSETS`, `METAADS_LIST_ADS`

> Audit my Meta Ads account for the last 30 days and identify campaigns, ad sets, and ads that may be wasting spend. Consider spending, purchase results, cost per purchase, ROAS, CTR, CPC, frequency, delivery, and available conversion data. Account for campaign objectives: an awareness campaign should not be evaluated using purchase ROAS alone. Flag items with meaningful spend and weak results, explain why each deserves attention, and distinguish between insufficient data and genuinely poor performance. Where possible, compare results across comparable campaigns and account for differences in audience, creative, and objective. Recommend whether each item should be monitored, tested, restructured, or considered for pausing. Do not pause ads or alter budgets. Ask for approval before applying any changes.

## Create New Ad Campaigns for Products

Plan product-specific advertising campaigns using Shopify catalog details, product margins, target audiences, and campaign objectives.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_GET_AD_ACCOUNTS`, `METAADS_LIST_CAMPAIGNS`, `METAADS_CREATE_CAMPAIGN`, `METAADS_CREATE_AD_SET`

> Help me plan a Meta Ads campaign for my Shopify products. First, inspect the available ad accounts, campaigns, and relevant Shopify product information. Ask me for any missing details that materially affect the campaign, such as target country, campaign objective, daily budget, target audience, offer, and desired launch date. Recommend a campaign structure with a clear objective, proposed ad sets, audience hypotheses, placements, budget allocation, creative concepts, and measurement criteria. Include suggested primary text, headlines, descriptions, and calls to action for each creative. Clearly label recommendations as proposals. Check for existing campaigns that could conflict with the new plan. Do not create campaigns, ad sets, or ads until I approve the exact configuration.

## Generate Multiple Ad Creative Variations

Develop alternative hooks, headlines, primary text, and creative concepts to test which messages resonate with potential customers.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_LIST_AD_CREATIVES`, `METAADS_GET_AD_CREATIVE`, `METAADS_CREATE_AD_CREATIVE`

> Review my current Meta Ads creatives and relevant Shopify product information. Generate five distinct creative concepts for my selected product or collection. For each concept, provide a target audience hypothesis, opening hook, primary text, headline, description, call to action, recommended visual direction, and the main variable being tested. Include different approaches such as product benefits, demonstrations, customer objections, social proof, and offers where appropriate. Use only product details and claims supported by the available information. Do not invent customer testimonials, discounts, product certifications, delivery promises, or performance guarantees. If useful, inspect existing creatives and explain which messages appear overused or under-tested. Keep the concepts suitable for the intended campaign objective. Prepare drafts only; do not upload, publish, or replace creatives without my approval.

## Build Retargeting Audiences for Shopify

Design audience strategies for website visitors, previous customers, and other eligible groups to support relevant follow-up advertising.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_LIST_CUSTOM_AUDIENCES`, `METAADS_LIST_AD_ACCOUNT_PIXELS`, `METAADS_CREATE_CUSTOM_AUDIENCE`

> Help me design a Meta Ads retargeting strategy for my Shopify store. Review available custom audiences, Pixel or dataset information, campaign performance, and Shopify customer segments where authorized. Recommend distinct audience groups for recent website visitors, product viewers, cart abandoners, existing customers, and lapsed customers where the required data and permissions are available. For each group, explain the purpose, proposed inclusion and exclusion criteria, suggested message, conversion objective, and possible audience overlap. Recommend appropriate retention windows based on the buying cycle rather than assuming one window fits every product. Check privacy, consent, data-use, and platform-policy considerations. Do not upload customer data, create audiences, or change targeting until I approve the audience definitions and data sources.

## Diagnose Pixel and Conversion Tracking

Investigate whether Meta is receiving reliable event data before making decisions based on purchases, conversions, or return on ad spend.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_LIST_AD_ACCOUNT_PIXELS`, `METAADS_GET_PIXEL_EVENT_STATS`, `METAADS_LIST_CUSTOM_CONVERSIONS`

> Audit the available Meta Pixel and dataset configuration for my Shopify store. Review accessible data sources, recent event-processing statistics, custom conversions, and available purchase or conversion insights. Look for potential issues such as missing events, unusually low event volume, inconsistent purchase values, duplicate purchase reporting, or differences between Meta-reported conversions and Shopify orders. Identify which checks can be completed from the available data and which require additional access or a separate diagnostic. Produce a tracking audit with the suspected issue, supporting evidence, business impact, confidence level, and recommended verification steps. Do not claim a problem is confirmed when the available data only suggests it. Do not modify tracking, create custom conversions, or submit server-side conversion events without my explicit approval. Clearly flag any proposed event submission because it may be irreversible.

## Compare Audience and Creative Effectiveness

Compare available ad performance to identify promising audience and creative combinations for controlled experiments.

- Apps: Meta Ads
- Tools: `METAADS_GET_INSIGHTS`, `METAADS_READ_ADSETS`, `METAADS_LIST_AD_CREATIVES`

> Compare the performance of my available Meta Ads audiences, ad sets, and creatives over the last 30 days. Use comparable metrics such as spend, reach, frequency, CTR, CPC, purchases, cost per purchase, conversion value, and ROAS where available. Separate creative performance from audience performance wherever the data permits, and explain when the campaign structure prevents a reliable comparison. Identify potentially strong and weak combinations, flag small sample sizes, and suggest three controlled experiments. Each experiment should state the hypothesis, the variable being changed, the success metric, the minimum evidence needed before a decision, and the potential risk. Do not declare a winner based solely on a few conversions or incomparable campaigns. Do not edit targeting, budgets, or ads. Present the recommended experiments for approval.

## Review Lead Generation Campaign Results

Evaluate lead-generation campaigns, inspect available lead records, and recommend ways to improve lead quality and follow-up.

- Apps: Meta Ads, Shopify, HubSpot
- Tools: `METAADS_GET_INSIGHTS`, `METAADS_LIST_LEADS`, `METAADS_CREATE_LEAD_FORM`

> Analyze my Meta Ads lead-generation campaigns and available lead-form results. Retrieve campaign performance metrics and available lead records for the selected period. Summarize spend, leads generated, cost per lead, campaign delivery, and lead volume by campaign or form where supported. If CRM or Shopify data is available, compare leads with downstream outcomes without assuming every lead should become a customer. Identify potential quality issues, form friction, targeting questions, or follow-up gaps. Recommend improvements to the form questions, offer, creative, and lead-handling process. Minimize exposure of personal information and do not include unnecessary personal data in the report. Do not create forms, contact leads, export their personal information, or change campaigns without explicit approval.

## Monitor Campaign Changes and Account Access

Review accessible account activity and business assets to help identify unexpected changes or configuration issues.

- Apps: Meta Ads
- Tools: `METAADS_LIST_ACTIVITIES`, `METAADS_LIST_CAMPAIGNS`, `METAADS_LIST_ASSIGNED_USERS`

> Review the available Meta Ads account activity for the last seven days and summarize meaningful changes to campaigns, ad sets, creatives, and relevant business assets. Where supported, inspect activity history, campaign status, accessible account and Page assignments, and relevant Pixel or dataset associations. Highlight unexpected changes, inactive campaigns, missing assets, unusual configuration differences, or access arrangements that deserve verification. For each finding, include the affected object, available timestamp or evidence, potential impact, confidence level, and recommended next step. Do not assume an activity is unauthorized merely because it is unfamiliar. Do not remove users, change permissions, delete campaigns, or modify business assets. Ask for approval before any corrective action.

## Prepare a Weekly Advertising Report

Generate a concise weekly report combining advertising performance, Shopify sales context, tracking observations, and next-week priorities.

- Apps: Meta Ads, Shopify
- Tools: `METAADS_GET_INSIGHTS`, `METAADS_LIST_CAMPAIGNS`, `METAADS_GET_PIXEL_EVENT_STATS`

> Prepare a weekly Meta Ads performance report for my Shopify store using the most recent complete seven-day period and compare it with the preceding seven days. Include total spend, impressions, reach, clicks, CTR, CPC, CPM, purchases, cost per purchase, attributed revenue, ROAS, and other relevant metrics available in the account. Include campaign-level breakdowns and highlight significant changes. If Shopify order data is accessible, compare store orders and revenue with Meta-attributed results, clearly explaining that attribution and actual business outcomes can differ. Identify the best-performing campaigns, potential waste, tracking concerns, creative fatigue indicators, and the three most important actions for next week. Use tables and concise explanations. Show percentage changes only when the comparison is meaningful, and distinguish unavailable data from zero values. Do not change campaign settings or send reports externally. Prepare the report for my review.
