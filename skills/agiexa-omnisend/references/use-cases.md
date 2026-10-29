# Omnisend use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/omnisend

## Recover Abandoned Carts More Effectively

Identify potentially abandoned carts, prioritize recovery opportunities, and prepare relevant follow-up messages.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_CARTS`, `OMNISEND_GET_CART`, `OMNISEND_LIST_PRODUCTS`

> Review my Omnisend cart and order data to identify potential abandoned-cart recovery opportunities. Examine available cart records, timestamps, product details, cart values, and related order information. Exclude carts that can be confirmed as converted or otherwise no longer eligible for recovery. If the available records do not establish whether a cart is abandoned, label it as requiring verification. Group eligible candidates by cart value, recency, and product category. Recommend a recovery strategy for each group and draft a personalized message using only supported customer and product fields. Do not assume that an abandoned-cart automation already exists or that campaign analytics are available. Do not send messages, create campaigns, or change carts without my explicit approval.

## Segment Customers for Repeat Purchases

Identify customer groups based on available order history and product interests to support relevant retention campaigns.

- Apps: Omnisend, Shopify
- Tools: `OMNISEND_LIST_CONTACTS`, `OMNISEND_GET_CONTACT`, `OMNISEND_LIST_PRODUCTS`

> Analyze the available Omnisend contacts, orders, and product catalog to propose customer segments for increasing repeat purchases. Consider previous purchase activity, order recency, product categories, and available customer attributes. Suggest groups such as recent customers, repeat purchasers, customers who have not purchased recently, and buyers of products that may have relevant complementary items. Explain the criteria for each segment, its business purpose, and the type of message that may be relevant. Clearly distinguish confirmed order history from inferred purchase intent. Do not assume that all contacts have marketing consent or that every proposed segment can be created directly with the available integration. Prepare segment definitions for review and do not modify customer records or send campaigns without approval.

## Prepare Personalized Promotional Campaigns

Draft targeted promotional messages using relevant product information and verified customer attributes.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_CONTACTS`, `OMNISEND_LIST_PRODUCTS`, `OMNISEND_LIST_CAMPAIGNS`

> Help me prepare a personalized promotional campaign using my Omnisend contact and product data. First, ask for the campaign objective, target audience, offer, campaign date, and preferred communication channel if these details are not available. Review the product catalog and customer attributes that are accessible. Create three campaign concepts with a subject line where applicable, message copy, call to action, personalization fields, and the intended audience. Explain why each concept suits its proposed segment. Use only verified product details and approved offers. Do not invent discounts, prices, stock availability, shipping promises, or customer preferences. Do not create or send the campaign until I approve the audience, content, and timing.

## Analyze Campaigns and Marketing Results

Review available campaign records and combine them with order data where possible to identify useful marketing insights.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_CAMPAIGNS`, `OMNISEND_GET_ORDER`

> Review my available Omnisend campaign records and relevant order data for the last 30 days. Summarize the campaigns that can be retrieved, including their names, types, and statuses where available. If campaign performance metrics are accessible through another authorized reporting source, include relevant results such as deliveries, opens, clicks, conversions, revenue, and unsubscribe rates. Compare results only when the metrics and reporting periods are comparable. Explain attribution limitations and distinguish unavailable metrics from actual zero values. Identify the strongest opportunities for improvement and recommend the next tests to run. Do not claim campaign performance based only on campaign metadata, and do not change or send campaigns without approval.

## Improve Customer Data Quality

Detect incomplete or inconsistent contact records and prepare a safe plan for improving customer data.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_CONTACTS`, `OMNISEND_GET_CONTACT`, `OMNISEND_UPDATE_CONTACT`

> Audit my Omnisend contact data for quality issues that could affect segmentation and personalization. Review available contact fields and identify records with missing important attributes, inconsistent formatting, incomplete profile information, or possible duplicates. Use only fields available in the retrieved data and avoid exposing unnecessary personal information in the report. Separate confirmed data issues from possible duplicates or inferred inconsistencies. Recommend corrections and explain which fields should be verified before being changed. Prepare a proposed cleanup list with record identifiers, the issue, suggested correction, and confidence level. Do not merge, delete, unsubscribe, or overwrite contacts automatically. Ask for approval before modifying any customer record.

## Recommend Relevant Products to Customers

Use product catalog and purchase information to develop relevant cross-sell and complementary-product campaigns.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_PRODUCTS`, `OMNISEND_LIST_PRODUCT_CATEGORIES`, `OMNISEND_GET_PRODUCT`

> Review my Omnisend product catalog and available order history to identify relevant cross-sell and complementary-product opportunities. Group products by available categories and identify combinations supported by actual catalog information or purchase patterns. Explain the reasoning behind each proposed product pairing and identify the customer segment that may find it useful. Draft a campaign concept for the strongest opportunities, including the target audience, product recommendations, message copy, and call to action. Verify product names and available details against the catalog. Do not invent compatibility, product benefits, availability, or purchase behavior. Do not update the catalog or send promotional messages without approval.

## Audit Contacts Before Campaign Sends

Reduce the risk of sending promotional messages to ineligible contacts by reviewing available subscription and profile information.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_CONTACTS`, `OMNISEND_GET_CONTACT`, `OMNISEND_CREATE_OR_UPDATE_CONTACT`

> Review my Omnisend contacts before I launch a promotional campaign. Inspect the available subscription, consent, contact-status, and profile fields. Identify records that appear eligible, records that require verification, and records that should be excluded based on their available status. Do not infer consent from the existence of a contact record, an order, or a previous interaction. Explain any limitations in the available data and recommend the checks needed before sending. Produce a summary of the proposed audience eligibility criteria. Do not subscribe contacts, update consent, suppress or delete records, or send the campaign. Require my approval before any change to contact status.

## Monitor Customer Events and Orders

Review customer events and order records to understand recent activity and identify useful follow-up opportunities.

- Apps: Omnisend
- Tools: `OMNISEND_LIST_EVENTS`, `OMNISEND_GET_ORDER`, `OMNISEND_SEND_EVENT`

> Review the available Omnisend customer events and order records for the last seven days. Summarize the types of events available, recent order activity, and meaningful patterns in customer behavior. Where the data supports it, identify potential follow-up opportunities such as post-purchase communication, product education, or customer retention. Distinguish recorded events from inferred customer intent. Check whether event names, timestamps, and associated customer or order identifiers are available before drawing conclusions. Recommend which follow-up workflows may be useful, but do not assume that Omnisend triggers or automated workflows are configured. Do not submit new events or modify orders without explicit approval.

## Maintain Accurate Product Catalog Data

Identify product catalog inconsistencies that may affect product recommendations and marketing personalization.

- Apps: Omnisend, Shopify
- Tools: `OMNISEND_LIST_PRODUCTS`, `OMNISEND_LIST_PRODUCT_CATEGORIES`, `OMNISEND_REPLACE_PRODUCT`, `OMNISEND_UPDATE_PRODUCT_CATEGORY`

> Audit my Omnisend product catalog and category records. Review available product names, identifiers, categories, and other returned fields. Identify products with missing or inconsistent information, possible duplicate entries, unclear category assignments, and catalog records that need verification. Provide a table containing the product identifier, observed issue, evidence, recommended correction, and confidence level. Do not infer unavailable product attributes or assume the Omnisend catalog exactly matches my current Shopify catalog. Prepare suggested changes for review. Do not create, replace, recategorize, or delete products or categories until I approve the exact changes.

## Create a Weekly Marketing Action Plan

Turn available contact, cart, product, and order information into a prioritized plan for the coming week.

- Apps: Omnisend, Shopify
- Tools: `OMNISEND_LIST_CAMPAIGNS`, `OMNISEND_LIST_CARTS`, `OMNISEND_LIST_CONTACTS`, `OMNISEND_LIST_EVENTS`

> Prepare a weekly ecommerce marketing action plan using the Omnisend data available to me. Review contacts, carts, orders, products, categories, customer events, and campaign records where accessible. Identify the most actionable opportunities for cart recovery, repeat purchases, contact quality, product promotion, and customer retention. For each recommendation, include the supporting evidence, intended audience, proposed activity, expected benefit, required data, priority, and any risks or limitations. Separate confirmed findings from assumptions and do not invent campaign metrics that are unavailable. Organize the plan into daily priorities for the next seven days. Include the campaign drafts or segment definitions that would be useful to prepare first. Do not send messages, create campaigns, submit events, or modify customer, order, cart, or product records without my explicit approval.
