# Pinterest Ads use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/pinterest-ads

## Analyze Advertising Performance Across Campaigns

Summarize campaign performance across a selected period, compare spend and conversions, and identify which campaigns deserve closer investigation.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_AD_ACCOUNTS`, `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_GET_METRICS_READY_STATE`, `PINTEREST_ADS_LIST_CAMPAIGNS`

> Analyze my Pinterest Ads performance for the last 30 days. List my accessible advertiser accounts and identify the relevant campaigns. Retrieve available analytics for the reporting period and check whether the metrics are finalized before relying on them. Compare spend, impressions, clicks, conversions, cost per conversion, and ROAS wherever those metrics are available. Rank campaigns by business performance, highlight strong and weak results, and explain any limitations in the data. Do not modify campaigns or assume that attributed revenue equals profit.

## Identify Campaigns Wasting Advertising Spend

Find campaigns with high costs and weak conversion outcomes, then recommend which ones need investigation or possible pausing.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_GET_METRICS_READY_STATE`, `PINTEREST_ADS_LIST_CAMPAIGNS`, `PINTEREST_ADS_UPDATE_CAMPAIGNS`

> Review my Pinterest Ads campaigns for the last 30 days and identify campaigns that may be wasting advertising spend. Compare spend, conversions, cost per conversion, and ROAS where available. Check reporting completeness before treating low conversion counts as reliable. Separate campaigns with genuinely weak results from campaigns that may need more data. For each concern, provide the campaign name and ID, supporting metrics, possible causes, and a recommended next step. Do not pause anything automatically. If pausing appears justified, prepare a proposed action list and request my approval first.

## Compare Individual Ads Within Campaigns

Evaluate individual ads to discover which creatives are associated with stronger results and which may need replacement or further testing.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_ADS`, `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_LIST_CAMPAIGNS`

> Analyze the performance of individual Pinterest ads within my selected campaigns over the last 30 days. Retrieve the relevant ad and campaign details, then compare available impressions, clicks, spend, conversions, and cost-efficiency metrics. Identify the ads with the strongest and weakest results while accounting for differences in delivery volume and reporting completeness. Explain which ads merit further testing, investigation, or possible pausing. Include ad IDs and parent campaign names. Do not claim that a creative caused a performance difference unless the data supports that conclusion. Do not change ad statuses without my explicit approval.

## Detect Underperforming Ad Groups Early

Compare ad groups within campaigns to uncover inefficient targeting or delivery patterns before making status changes.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_AD_GROUPS`, `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_UPDATE_AD_GROUPS`

> Review my Pinterest ad groups for the last 30 days, grouped by parent campaign. Compare available spend, clicks, impressions, conversions, and cost per conversion. Identify ad groups that are materially weaker than comparable groups, and explain the evidence for each finding. Check whether the reporting period is finalized and flag groups with insufficient data. Recommend whether each group should remain active, be investigated, or be considered for pausing. Include the parent campaign and ad group IDs. Do not make any status changes until I approve the exact list.

## Validate Reporting Before Making Decisions

Check whether Pinterest reporting data is finalized so campaign decisions aren't based on incomplete conversion metrics.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_GET_METRICS_READY_STATE`, `PINTEREST_ADS_GET_ANALYTICS`

> Before analyzing my Pinterest Ads performance for the latest completed reporting dates, check whether conversion and non-conversion metrics are finalized for each relevant UTC report date. Clearly separate finalized dates from dates with metrics that may still change. Retrieve analytics for the relevant period and explain how incomplete reporting could affect campaign rankings, conversion rates, cost per purchase, and ROAS. If data is not ready, identify which conclusions should be postponed. Do not treat missing or delayed conversions as proof that a campaign is failing, and do not modify any campaigns.

## Discover Valid Audience Targeting Options

Explore available Pinterest targeting values to plan campaigns around relevant audiences, locations, interests, and keywords.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_GET_TARGETING_OPTIONS`, `PINTEREST_ADS_LIST_AD_ACCOUNTS`, `PINTEREST_ADS_LIST_AD_GROUPS`

> Help me plan a Pinterest Ads targeting strategy for my products. First, identify my accessible advertiser accounts and review the existing campaigns and ad groups for context. Retrieve valid targeting options for relevant targeting types, including locations, languages, age groups, genders, interests, and keywords where supported. Recommend a small number of audience and keyword hypotheses that fit the products and target market I describe. Distinguish actual valid targeting values from strategic suggestions. Do not assume the integration can create or edit targeting settings; prepare a targeting plan for review instead.

## Recommend Which Campaigns To Pause

Produce an evidence-based pause shortlist while protecting promising campaigns and accounting for incomplete reporting.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_CAMPAIGNS`, `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_GET_METRICS_READY_STATE`, `PINTEREST_ADS_UPDATE_CAMPAIGNS`

> Review all my active Pinterest campaigns and recommend which ones, if any, should be considered for pausing. Use the last 30 days of available analytics, verify reporting completeness, and compare spend, conversions, cost per conversion, and ROAS where available. Consider the campaign's business objective and whether its performance is supported by enough data. Produce a shortlist with campaign name, campaign ID, current status, supporting evidence, risk of pausing, and recommendation. Clearly distinguish a firm recommendation from a low-confidence hypothesis. Do not pause anything until I approve each specific campaign ID.

## Audit Campaign Statuses Across Accounts

Review campaign, ad group, and ad statuses to identify paused campaigns, inactive ads, and inconsistencies requiring attention.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_CAMPAIGNS`, `PINTEREST_ADS_LIST_AD_GROUPS`, `PINTEREST_ADS_LIST_ADS`, `PINTEREST_ADS_GET_ANALYTICS`

> Audit the status of my accessible Pinterest Ads accounts. List campaigns, ad groups, and ads with their IDs, names, parent relationships, and available status information. Identify paused or inactive items, as well as active items that may deserve a performance review. Where analytics are available, compare status with recent delivery and conversion performance. Do not assume that a paused item is a mistake or that every active item should remain active. Provide a concise audit report and propose only justified status changes. Do not rename, pause, or resume any item without my approval.

## Improve Campaign Naming And Organization

Identify confusing campaign and ad group names, then propose a consistent naming convention that makes reporting easier.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_LIST_CAMPAIGNS`, `PINTEREST_ADS_LIST_AD_GROUPS`, `PINTEREST_ADS_LIST_ADS`, `PINTEREST_ADS_UPDATE_CAMPAIGNS`

> Review my Pinterest campaign, ad group, and ad names. Identify inconsistent naming patterns, duplicate-looking names, unclear product references, and names that make performance reporting difficult. Propose a consistent naming convention based on the campaign objective, product category, audience or targeting theme, and campaign period where appropriate. Provide a table with the current name, item type, ID, proposed name, and reason for the change. Preserve the original names in your proposal and avoid renaming anything automatically. Ask for approval before applying any approved changes, and ensure that each proposed rename maps to the correct item ID.

## Create A Recurring Campaign Review Workflow

Establish a repeatable performance review that highlights meaningful changes and prepares an approval-ready optimization plan.

- Apps: Pinterest Ads
- Tools: `PINTEREST_ADS_GET_ANALYTICS`, `PINTEREST_ADS_GET_METRICS_READY_STATE`, `PINTEREST_ADS_LIST_CAMPAIGNS`, `PINTEREST_ADS_UPDATE_CAMPAIGNS`

> Prepare a Pinterest Ads performance review for the latest completed reporting period using a consistent structure. Check whether the relevant metrics are finalized before drawing conclusions. Summarize account-level performance, rank campaigns by available business metrics, identify underperforming ad groups and ads, and flag unusual spend or conversion patterns. Compare results with a previous period only when equivalent data is available. End with prioritized recommendations, the evidence supporting each recommendation, the expected benefit, and the risk of acting. Include exact item IDs for any proposed status or naming changes. Do not make changes automatically. Clearly state when data is incomplete or a requested action is not supported by the available integration.
