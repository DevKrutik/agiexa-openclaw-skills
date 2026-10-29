# Mailchimp use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/mailchimp

## Analyze Email Campaign Performance

Review campaign reports and subscriber engagement to identify opportunities to improve email marketing results.

- Apps: Mailchimp
- Tools: `MAILCHIMP_LIST_CAMPAIGN_REPORTS`, `MAILCHIMP_GET_CAMPAIGN_REPORT`, `MAILCHIMP_LIST_CAMPAIGNS`

> Analyze my recent Mailchimp campaign reports for the requested reporting period. Review available delivery, open, click, unsubscribe, bounce, and e-commerce conversion metrics. Compare campaigns across equivalent periods and relevant audience segments where possible. Identify the strongest and weakest campaigns, explain the evidence behind their performance, and recommend five experiments involving subject lines, content, CTAs, or audience selection. Use actual reports and distinguish measured results from hypotheses. Do not assume opens guarantee engagement or that campaign-attributed revenue represents all incremental sales. Do not modify, schedule, or send campaigns without my approval.

## Create Valuable Customer Segments

Organize subscribers and customers into useful groups based on verified purchase history and engagement.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_SEGMENTS`, `MAILCHIMP_LIST_MEMBERS_INFO`, `MAILCHIMP_ADD_SEGMENT`

> Analyze available Mailchimp audiences, saved segments, subscriber activity, e-commerce customers, and order information. Recommend useful customer segments for new subscribers, first-time buyers, repeat customers, inactive subscribers, and shoppers with abandoned carts where the data supports those groups. For each segment, define the purpose, eligibility conditions, relevant time window, exclusions, and recommended campaign. Check for overlap with existing segments and automations. Respect unsubscribe status and marketing eligibility. Present the proposed segment definitions for approval before creating or modifying any audience segments.

## Improve Abandoned Cart Recovery

Design a cart-recovery sequence that reminds shoppers about their products and helps address purchase objections.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_CARTS`, `MAILCHIMP_LIST_AUTOMATIONS`, `MAILCHIMP_ADD_AUTOMATION`

> Review available Mailchimp carts, cart line items, customer records, and existing abandoned-cart automations. Determine whether a recovery sequence already exists and identify possible duplication or missing steps. Propose a sequence with appropriate timing, relevant product information, clear CTAs, and an optional final reminder. Use verified Shopify product information where available. Explain how to exclude customers who have completed their purchase and how to measure recovered orders. Do not invent discounts, stock scarcity, or delivery promises. Present the proposed workflow and messages for approval before creating or activating an automation.

## Prepare Personalized Promotional Emails

Draft targeted campaigns using customer interests, purchase history, and verified Shopify product information.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_ADD_CAMPAIGN`, `MAILCHIMP_SET_CAMPAIGN_CONTENT`, `MAILCHIMP_GET_CAMPAIGN_SEND_CHECKLIST`, `MAILCHIMP_SEND_TEST_EMAIL`

> Prepare a Mailchimp promotional email campaign for my Shopify store using the campaign goal and audience I specify. Draft the subject line, preview text, email body, CTA, and relevant product or collection recommendations. Use available subscriber merge fields with safe fallbacks for missing values. Verify product details, prices, discount terms, destination URLs, and campaign dates. Check the audience selection, unsubscribe status, and send checklist. Show the final content, intended audience, and available recipient estimate. Do not send or schedule the campaign until I approve the content, audience, and timing.

## Reengage Inactive Subscribers Effectively

Identify eligible inactive subscribers and prepare a campaign that encourages renewed interest without excessive messaging.

- Apps: Mailchimp
- Tools: `MAILCHIMP_LIST_MEMBERS_INFO`, `MAILCHIMP_LIST_EMAIL_ACTIVITY`, `MAILCHIMP_LIST_SEGMENTS`

> Analyze Mailchimp subscriber activity, campaign engagement, available order history, and saved segments to identify potentially inactive subscribers. Define inactivity using a clear time window and verified activity data. Exclude unsubscribed, bounced, or otherwise ineligible contacts from marketing sends. Recommend a re-engagement campaign with useful content, relevant products, and a clear way to manage preferences or unsubscribe. Check existing automations to avoid duplicate messages. Explain the proposed audience criteria, message content, and success metrics. Do not change subscriber status or send a campaign without my approval.

## Encourage Repeat Customer Purchases

Identify opportunities to encourage a second or subsequent Shopify purchase through relevant email recommendations.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_CUSTOMERS`, `MAILCHIMP_LIST_ORDERS`, `MAILCHIMP_LIST_PRODUCT`

> Analyze available Mailchimp customer records and e-commerce orders alongside Shopify purchase history where accessible. Identify first-time buyers, repeat customers, and customers who may benefit from product education or relevant complementary recommendations. Use actual order and catalog data to determine what products are relevant. Do not assume every product needs replenishment or that a customer is ready to buy again. Recommend appropriate audience segments, email timing, message drafts, and measurable success criteria. Check existing automations before suggesting new ones, and obtain approval before creating workflows or sending marketing emails.

## Manage Promotional Codes Carefully

Plan targeted offers and manage promotional codes while avoiding conflicting discounts and unauthorized terms.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_PROMO_RULES`, `MAILCHIMP_ADD_PROMO_RULE`, `MAILCHIMP_ADD_PROMO_CODE`

> Help me plan a Mailchimp promotional campaign using the available e-commerce store, promotion rules, and promo-code information. Define the intended audience, eligible products, discount structure, validity period, exclusions, and campaign objective using the terms I provide. Check existing promotion rules and codes for potential conflicts. Calculate estimated campaign costs only when the necessary pricing and margin data is available. Do not invent discounts, promise unauthorized offers, or create or modify codes without approval. Present the proposed offer, message draft, eligibility rules, and risks before making changes.

## Audit Subscriber Data Quality

Identify duplicate-looking contacts, inconsistent audience fields, and data issues that could undermine campaign targeting.

- Apps: Mailchimp
- Tools: `MAILCHIMP_LIST_MEMBERS_INFO`, `MAILCHIMP_SEARCH_MEMBERS`, `MAILCHIMP_LIST_MEMBER_TAGS`

> Audit my available Mailchimp audience members, contact profiles, merge fields, tags, and subscriber activity for data-quality issues. Identify possible duplicates, missing fields, inconsistent customer attributes, and unexpected segment membership. Match records using reliable identifiers rather than names alone. Explain the evidence for each proposed correction and its potential impact on segmentation or personalization. Do not assume a contact should be subscribed because they appear in Shopify customer records. Do not archive, permanently delete, merge, subscribe, or unsubscribe contacts without my approval.

## Improve Signup Forms and Landing Pages

Review available forms and landing pages to identify ways to improve subscriber acquisition and campaign relevance.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_SIGNUP_FORMS`, `MAILCHIMP_LIST_LANDING_PAGES`, `MAILCHIMP_GET_LANDING_PAGE_REPORT`

> Review available Mailchimp signup forms, landing pages, form content, and performance reports. Identify opportunities to improve signup messaging, CTA clarity, audience relevance, and the information collected from subscribers. Where Shopify product or collection information is available, suggest relevant signup offers or content themes. Use actual performance metrics when available and distinguish observed problems from hypotheses. Recommend improvements to copy, form structure, and landing-page messaging. Respect applicable consent requirements and do not publish landing pages, modify live forms, or change signup settings without showing me the proposed changes and obtaining approval.

## Generate a Weekly Marketing Report

Combine campaign analytics, audience growth, subscriber activity, and e-commerce data into a concise weekly report.

- Apps: Mailchimp, Shopify
- Tools: `MAILCHIMP_LIST_CAMPAIGN_REPORTS`, `MAILCHIMP_LIST_GROWTH_HISTORY_DATA`, `MAILCHIMP_LIST_RECENT_ACTIVITY`

> Prepare a weekly Mailchimp marketing report using available campaign reports, subscriber activity, audience growth statistics, saved segments, automations, and relevant e-commerce data. Include campaign delivery and engagement metrics, audience growth, unsubscribe and bounce trends, top-performing campaigns, and available attributed revenue. Compare the current period with the previous equivalent period only when comparable data exists. Identify three prioritized improvements for campaigns, audience targeting, or customer retention. Distinguish Mailchimp-attributed revenue from total Shopify revenue, disclose missing data, and do not claim causation without evidence. Do not modify audiences, automations, or campaigns while preparing the report.
