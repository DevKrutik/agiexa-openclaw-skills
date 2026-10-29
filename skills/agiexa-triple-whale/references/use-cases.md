# Triple Whale use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/triple-whale

## Identify Your Best Marketing Channels

Discover which first-click sources contribute the most Shopify orders and attributed revenue.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`, `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`

> Analyze my Shopify store performance alongside Triple Whale's first-click attribution data for the last 30 days. Summarize attributed orders and revenue by channel, rank the strongest sources, and calculate attributed revenue per order where possible. Compare the results with Shopify's overall order and revenue figures if available. Explain how first-click attribution affects the conclusions and identify which channels deserve further investigation.

## Trace Revenue Back to Campaigns

Connect attributed orders to their sources and campaigns to see which introduce customers.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`, `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`

> Retrieve the available attributed orders for my Shopify store over the last 30 days. Group the results by first-click source, campaign, ad set, and ad wherever those fields are available. Identify campaigns associated with the most orders and attributed revenue. Match the orders to Shopify records where possible, and clearly flag missing campaign information or unmatched orders. Do not claim that first-click attribution proves a campaign caused the purchase.

## Compare Shopify and Triple Whale

Investigate differences between store sales and performance reporting before deciding.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`, `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`

> Compare my Shopify order and revenue totals with the performance summary and attribution reports available through Triple Whale for the same date range. Identify differences in revenue, order counts, and attributed-order coverage. Explain potential reasons such as reporting definitions, attribution coverage, date boundaries, and refunds if the relevant data is available. Do not assume that different metrics should match exactly. Present the discrepancies and the additional information needed to reconcile them.

## Find High-Value Acquisition Channels

Rank channels by attributed revenue per order with available financial context.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`, `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`

> Analyze first-click attributed orders and revenue for my Shopify store across all available marketing channels. Calculate attributed revenue per order, compare order volume, and identify channels that appear promising for customer acquisition. If advertising spend, product costs, refunds, or contribution margins are available from connected sources, incorporate them into the analysis. Distinguish revenue efficiency from profitability and recommend which channels deserve additional testing.

## Investigate Underperforming Campaigns

Find campaigns with weak order volume or low attributed revenue worth a closer look.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`, `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`

> Review my Triple Whale performance summary and attributed Shopify orders for the last 14 days. Rank available sources and campaigns by attributed order count and revenue. Identify campaigns with low results relative to their available performance context, and compare them with the previous 14 days if the required data is available. Explain the evidence, identify data limitations, and recommend what I should investigate next. Do not label a campaign unprofitable unless spend and relevant cost data support that conclusion.

## Understand Customer Acquisition Paths

See which channels introduce customers and how their orders contribute to revenue.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`, `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`

> Analyze the first-click sources associated with my Shopify orders. Summarize which channels introduce the most recorded orders, their attributed revenue, and their average attributed order value. If Shopify customer history is accessible, compare first-time and repeat-customer patterns without exposing unnecessary personal information. Explain what this attribution model can and cannot tell us about the full customer journey, and recommend additional analyses that could improve acquisition decisions.

## Find Revenue Opportunities by Product

Match attributed orders to Shopify products to spot items deserving more marketing.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`, `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`

> Analyze my Shopify sales and Triple Whale attributed orders to identify products that could be promising candidates for marketing campaigns. Match attributed orders to Shopify product line items where the necessary order details are available. Summarize product revenue, order volume, and associated first-click sources. Identify products with strong sales and products that appear underrepresented in attributed orders. Clearly state when product-level attribution cannot be established from the available data, and do not infer product-level campaign performance without evidence.

## Measure Marketing Performance Changes

Compare attribution and performance across periods to see whether outcomes are improving.

- Apps: Triple Whale, Shopify
- Tools: `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`, `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`

> Compare my Shopify store and Triple Whale marketing performance over the last seven days with the previous seven days. Analyze available store revenue, order counts, attributed orders, channel revenue, and revenue per attributed order. Highlight meaningful increases or decreases and identify which sources contribute most to the changes. Check whether the date ranges and metric definitions are consistent. Separate observed changes from possible explanations, and recommend three actions based on the available evidence.

## Prepare Cross-Channel Budget Recommendations

A data-backed channel allocation plan using attribution plus available spend and margin data.

- Apps: Triple Whale, Shopify, Meta Ads, Google Ads
- Tools: `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`, `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`, `TRIPLEWHALE_GET_ATTRIBUTION_ORDERS`

> Review my Shopify sales, Triple Whale performance summary, and first-click channel attribution. Prepare a proposed marketing budget allocation across the channels with sufficient supporting data. Incorporate campaign spend, revenue efficiency, contribution margins, inventory availability, and refund information when accessible. Show the evidence and risks behind each proposed increase or decrease. If cost or margin data is missing, state what is needed before estimating profitability. Do not change any advertising budgets; provide a recommendation for my review.

## Generate a Daily Store Briefing

A concise daily view of Shopify sales and first-click marketing results.

- Apps: Triple Whale, Shopify, Slack
- Tools: `TRIPLEWHALE_GET_PERFORMANCE_SUMMARY`, `TRIPLEWHALE_CHANNEL_ATTRIBUTION_SUMMARY`

> Prepare a daily briefing using the latest available Shopify sales data and Triple Whale performance summary. Include overall store performance, attributed order volume, revenue by first-click channel, notable campaign patterns, and changes compared with the previous period when available. Highlight the three most important findings and recommend practical next steps. Clearly distinguish store revenue from attributed revenue, note any missing data, and avoid unsupported claims about profitability or marketing causation.
