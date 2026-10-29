# Slack use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/slack

## Monitor Shopify Orders Through Slack

Give your operations team a single place to review unfulfilled orders, delayed shipments, and order issues.

- Apps: Slack, Shopify
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_FETCH_CONVERSATION_HISTORY`, `SLACK_RETRIEVE_MESSAGE_PERMALINK_URL`

> Review my Shopify orders that are currently unfulfilled, overdue according to their expected fulfillment dates, or otherwise flagged for attention. Search my accessible Slack messages for discussions mentioning the relevant order numbers, products, fulfillment issues, or customers. Match records only when there is sufficient evidence. Separate confirmed Shopify facts from possible matches found in Slack. Prepare an operations report containing the order number and status, order value and product details, the relevant Slack discussion and permalink if available, the potential reason, and a recommended next action and responsible team if identifiable. Do not assume a Slack discussion proves the cause of an order delay. Do not change orders or send messages without my approval.

## Detect Inventory Risks Before Campaigns

Combine Shopify inventory levels with Slack marketing plans to identify products that may sell out before a promotion launches.

- Apps: Slack, Shopify
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_FIND_CHANNELS`, `SLACK_SEND_MESSAGE`

> Analyze my Shopify inventory and search Slack for discussions about upcoming promotions, product launches, influencer campaigns, and seasonal sales. Identify products mentioned in upcoming marketing activities that also have low inventory or limited available stock in Shopify. For each potential risk, report the product name and variant, available inventory when accessible, the relevant campaign discussion and planned timing, why the stock may be insufficient, and a suggested inventory or campaign adjustment. Do not invent demand forecasts or assume campaign dates that are not stated. Clearly label estimated risks and missing information. Prepare a Slack alert for the relevant team, but ask for my approval before posting it.

## Investigate Customer Complaints Across Apps

Combine Shopify order and customer details with Slack support discussions and connected shipping or subscription data.

- Apps: Slack, Shopify, Shippo, Recharge
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_FETCH_MESSAGE_THREAD_FROM_A_CONVERSATION`, `SLACK_LIST_CONVERSATIONS`

> Investigate unresolved customer complaints using Shopify order and customer records, relevant Slack conversations, and any connected shipping or subscription integrations available to me. Match information using order numbers, tracking references, customer identifiers, or other reliable evidence. Avoid exposing unnecessary personal information in Slack. For each complaint, summarize the customer issue and relevant order, current fulfillment or subscription status, relevant tracking or billing information when available, what support has already discussed in Slack, and a suggested resolution with any missing information. Do not issue refunds, cancel subscriptions, modify orders, or contact customers without explicit approval. If the sources disagree, report the discrepancy rather than choosing an unsupported answer.

## Alert Teams About Failed Payments

Combine Shopify order and payment information with Slack discussions and connected accounting data to investigate discrepancies.

- Apps: Slack, Shopify, QuickBooks
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_FIND_CHANNELS`, `SLACK_SEND_MESSAGE`

> Review Shopify orders and their available payment statuses. If a connected accounting integration is available, compare the relevant transactions with its records. Search Slack for discussions about payment failures, payment-provider issues, reconciliation problems, and customer reports. Produce a report showing the order reference and payment status, the corresponding accounting transaction if confidently matched, relevant Slack discussions, the potential discrepancy or unresolved question, and recommended investigation steps. Do not treat an order as paid merely because a Slack message says payment succeeded. Do not retry charges, issue refunds, or modify accounting records without explicit approval. Prepare a concise alert for the finance channel and show me the message before posting it.

## Coordinate Shipping Problems Automatically

Combine Shopify order data, a connected shipping integration, and Slack conversations to coordinate delivery follow-ups.

- Apps: Slack, Shopify, Shippo, ShipEngine
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_FETCH_CONVERSATION_HISTORY`, `SLACK_SEND_MESSAGE`

> Review Shopify orders that have shipping or delivery issues. Use connected shipping integrations, if available, to check tracking events, shipment status, and relevant label or carrier information. Search Slack for discussions about the same orders, tracking references, carriers, or warehouse problems. Identify orders with tracking exceptions or stalled shipments, orders marked fulfilled but showing concerning tracking, Slack discussions that may explain the issue, cases requiring support or warehouse attention, and suggested next steps with evidence. Distinguish carrier-confirmed events from internal Slack comments. Do not promise delivery dates or claim a package is lost without sufficient evidence. Draft a prioritized report for #shipping-operations. Ask for approval before sending messages or initiating shipment changes.

## Summarize Customer Feedback Into Product Actions

Combine Shopify product and order information with Slack feedback discussions and connected review data.

- Apps: Slack, Shopify, Judge.me
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_SEARCH_ALL`, `SLACK_FETCH_MESSAGE_THREAD_FROM_A_CONVERSATION`

> Analyze customer feedback using available Shopify product and order information, relevant Slack discussions, and review data from any connected review integration. Group the findings by product and recurring issue, such as quality, sizing, packaging, product descriptions, or delivery expectations. For each finding, include the product name and Shopify reference, a summary of the feedback, the number of distinct supporting records when measurable, relevant Slack discussion or review references, and a suggested product, support, or operations action. Do not treat an internal Slack opinion as a verified customer complaint. Avoid double-counting duplicated feedback. Prepare a product-improvement summary for the team. Do not publish replies to reviews or modify product listings without approval.

## Discover Sales Opportunities From Conversations

Connect Shopify sales performance with Slack marketing and sales discussions to find coordination opportunities.

- Apps: Slack, Shopify, Pinterest Ads
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_LIST_CONVERSATIONS`, `SLACK_SEND_MESSAGE`

> Analyze Shopify sales and product performance for the requested period, then search Slack for discussions about campaigns, product launches, customer requests, and sales opportunities. Identify products that appear in both the Shopify data and relevant team conversations. For each opportunity, report product sales and available inventory when accessible, the relevant performance metrics, the Slack discussion and any stated campaign timeline, the potential opportunity or operational risk, and a recommended next action. Do not claim that a Slack discussion caused a sales increase. Do not invent attribution, margins, or projected revenue. Prepare a short opportunity report for the marketing team and request approval before posting it.

## Turn Slack Requests Into Store Tasks

Use Slack messages as the starting point for Shopify operations, preparing actionable summaries with approval before changes.

- Apps: Slack, Shopify
- Tools: `SLACK_FETCH_CONVERSATION_HISTORY`, `SLACK_SEARCH_MESSAGES`, `SLACK_CREATE_SLACK_LIST`, `SLACK_CREATE_SLACK_LIST_ITEM`

> Review messages in the Slack channels I specify and identify actionable requests related to my Shopify store. For each request, determine whether it concerns an order, product, customer, inventory issue, or another store operation. Retrieve the relevant Shopify information when the necessary integration and permissions are available. Search for related Slack messages to understand the context. Summarize the request, current state, missing information, and recommended next step. Prepare a task list or Slack List, if the required capabilities are available. Do not interpret every message as an instruction to change the store. Ask clarifying questions when the request is ambiguous. Get my explicit approval before modifying Shopify data, inviting people, changing access, or posting externally visible updates.

## Create Daily Cross-Team Operations Briefings

Bring together Shopify order and inventory information with Slack conversations and connected data for one concise briefing.

- Apps: Slack, Shopify, Shippo, QuickBooks, Recharge
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_SEND_MESSAGE`, `SLACK_CREATE_A_REMINDER`, `SLACK_LIST_UNREAD_CHANNEL_MESSAGES`

> Prepare a daily operations briefing using Shopify data, relevant Slack discussions, and any connected shipping, accounting, or subscription integrations that are available. Include orders requiring attention, low-stock products and relevant upcoming promotions, shipping exceptions, payment or accounting discrepancies, subscription issues if applicable, important customer complaints and unresolved team discussions, and prioritized actions for today. Include source references and timestamps where available. Clearly distinguish verified facts, possible matches, and recommendations. Avoid duplicate issues across integrations. Keep the briefing concise and prioritize business impact. Draft it for my designated Slack channel. Do not post it until I approve the destination and message. If I want recurring briefings, ask me to confirm the schedule before setting up a reminder or scheduled workflow.

## Investigate Revenue Drops With Team Context

Combine Shopify sales trends with Slack conversations and connected data to help explain revenue changes.

- Apps: Slack, Shopify, QuickBooks, Meta Ads
- Tools: `SLACK_SEARCH_MESSAGES`, `SLACK_SEARCH_ALL`, `SLACK_SEND_MESSAGE`

> Investigate the change in Shopify revenue for the period I specify compared with the previous comparable period. Analyze available order, product, discount, and refund data. Search Slack for discussions about marketing campaigns, website issues, inventory shortages, pricing changes, or customer complaints. Use connected marketing or accounting integrations when available. Produce revenue and order-count changes, the products or categories contributing most, relevant inventory, discount, refund, or payment observations, related Slack discussions with references, potential explanations ranked by supporting evidence, and recommended investigations and actions. Do not claim causation based solely on timing or Slack discussions. Do not invent advertising spend, profit, conversion rates, or attribution data that is unavailable. Prepare an executive summary and a draft Slack message for the leadership channel. Ask for approval before publishing the report or making changes to campaigns, products, prices, or financial records.
