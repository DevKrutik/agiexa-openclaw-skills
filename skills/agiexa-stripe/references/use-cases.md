# Stripe use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/stripe

## Reconcile Shopify Orders With Stripe

Match Shopify orders and refunds against Stripe charges and refunds to surface discrepancies.

- Apps: Stripe, Shopify
- Tools: `STRIPE_LIST_CHARGES`, `STRIPE_LIST_PAYMENT_INTENTS`, `STRIPE_LIST_REFUNDS`, `STRIPE_SEARCH_CHARGES`

> Reconcile my Shopify orders and refunds against available Stripe payment records for the date range I specify. Match records using reliable identifiers first, followed by customer references, amount, currency, timestamps, and metadata where appropriate. Prepare a report containing the Shopify order number and payment status, matching Stripe charge or PaymentIntent reference, transaction amount and currency, Shopify refund amount and corresponding Stripe refund records when available, potentially unmatched or inconsistent records, and recommended investigation steps. Account for partial refunds, multiple transactions, and processing delays. Do not assume that similar amounts alone prove two records are related. Clearly distinguish confirmed matches from possible matches. Do not create refunds, modify payment records, or mark orders as paid. Ask for approval before taking any corrective action.

## Investigate Failed Shopify Payments

Combine Shopify order details with Stripe failure data to explain failed payments and next steps.

- Apps: Stripe, Shopify
- Tools: `STRIPE_SEARCH_PAYMENT_INTENTS`, `STRIPE_RETRIEVE_PAYMENT_INTENT`, `STRIPE_RETRIEVE_CHARGE`, `STRIPE_LIST_PAYMENT_ATTEMPT_RECORDS`

> Investigate Shopify orders with failed, pending, or otherwise concerning payment statuses. Search available Stripe PaymentIntents, charges, and payment attempt records for matching transactions. For each case, provide the Shopify order number and current payment status, the matching Stripe transaction reference if confirmed, available failure information, whether the payment requires customer action, further investigation, or no action, and a suggested next step for the support or finance team. Do not infer a specific decline reason when Stripe does not provide one. Do not treat a failed attempt as proof that every subsequent attempt failed. Do not retry charges, create new payment requests, or change Shopify order status without explicit approval.

## Monitor Payment Disputes And Chargebacks

Match open Stripe disputes to Shopify orders and assemble evidence checklists with deadlines.

- Apps: Stripe, Shopify, Shippo
- Tools: `STRIPE_LIST_DISPUTES`, `STRIPE_GET_V1_DISPUTES_DISPUTES`, `STRIPE_RETRIEVE_CHARGE`, `STRIPE_UPDATE_DISPUTE`

> Review open Stripe disputes and match them with the relevant Shopify orders wherever reliable references are available. For each dispute, summarize the Stripe dispute reference, amount, currency, and status, the matching Shopify order and purchased products, available fulfillment and delivery evidence from connected integrations, relevant refund history, dispute deadlines and evidence requirements when available, and recommended evidence to gather next. Distinguish retrieved facts from suggested evidence. Do not claim an order was delivered unless the available records support that statement. Prepare an evidence checklist for each case. Do not submit evidence, accept a dispute, close a dispute, or issue a refund without my explicit approval.

## Detect Refund Reconciliation Problems

Compare Shopify refunds with Stripe refunds to catch amount, status, or timing differences early.

- Apps: Stripe, Shopify
- Tools: `STRIPE_LIST_REFUNDS`, `STRIPE_GET_REFUNDS_REFUND`, `STRIPE_LIST_CHARGE_REFUNDS`

> Review Shopify refunds for the specified period and compare them with available Stripe refund records. Identify Shopify refunds with no confidently matched Stripe refund, Stripe refunds without a confidently matched Shopify refund, differences between recorded refund amounts or currencies, partial refunds that need additional reconciliation, and refunds whose current status may require follow-up. Include order references, transaction IDs, timestamps, amounts, and supporting evidence where available. Do not assume that every discrepancy is an error. Consider processing delays, multiple refunds, and differences in record timing. Prepare a prioritized report for finance. Do not create additional refunds or modify existing records without approval.

## Alert Teams About Payment Failures

Use Stripe failure triggers with Shopify matching and Slack alerts for fast team response.

- Apps: Stripe, Shopify, Slack
- Tools: `STRIPE_GET_EVENTS`, `STRIPE_GET_EVENTS_ID`, `STRIPE_RETRIEVE_PAYMENT_INTENT`, `STRIPE_SEARCH_CHARGES`

> Design a workflow for Stripe payment failure events. When a relevant failure event occurs, retrieve the available Stripe payment and failure details. Attempt to match the transaction with a Shopify order using reliable identifiers. Include the order number, amount, currency, payment status, and failure details when available. Search relevant Slack discussions for existing context if Slack is connected. Prepare a concise alert for the designated finance or support channel. Include only information needed to investigate the issue. Avoid sharing full card details or unnecessary customer personal information. Do not automatically retry the payment, create another charge, or mark an order as paid. If the order cannot be confidently matched, label it as unmatched. Ask me to confirm the channel and workflow behavior before enabling notifications.

## Analyze Shopify Sales Against Stripe Payouts

Compare Shopify sales with Stripe transactions, fees, and payouts to explain revenue differences.

- Apps: Stripe, Shopify, QuickBooks
- Tools: `STRIPE_LIST_BALANCE_TRANSACTIONS`, `STRIPE_LIST_PAYOUTS`, `STRIPE_GET_PAYOUT`, `STRIPE_RETRIEVE_BALANCE`

> Compare Shopify sales and refund records with available Stripe balance transactions, fees where exposed, and payout information for the period I specify. Prepare a reconciliation summary showing Shopify gross sales and recorded refunds, matched Stripe payment transactions, available Stripe fees and adjustments, payout amounts and payout statuses, timing differences and potential unmatched transactions, and remaining unexplained differences. Use consistent currencies and date ranges. Distinguish order revenue from payment volume, Stripe balance movements, and bank payouts. Do not assume that payout totals equal Shopify sales for the same day. Account for processing timing, fees, refunds, and other available adjustments. Identify missing data and recommend next checks. Do not modify financial records or initiate transfers.

## Investigate Suspicious Shopify Transactions

Prioritize orders flagged by Stripe disputes, fraud warnings, and reviews for manual checks.

- Apps: Stripe, Shopify
- Tools: `STRIPE_LIST_RADAR_EARLY_FRAUD_WARNINGS`, `STRIPE_LIST_RADAR_REVIEWS`, `STRIPE_LIST_DISPUTES`, `STRIPE_SEARCH_CHARGES`

> Review Shopify orders alongside available Stripe disputes, early fraud warnings, open reviews, and related payment records. Identify transactions that have explicit risk signals or inconsistencies requiring further investigation. For each case, include the Shopify order reference and available order details, the matching Stripe transaction and its current status, the specific risk signal returned by Stripe, relevant refund, dispute, or review information, and recommended verification steps. Do not invent fraud scores or classify a customer as fraudulent based solely on order value, location, or a failed payment. Clearly distinguish a warning from a confirmed fraudulent transaction. Prepare a review queue. Do not cancel orders, block customers, capture payments, or issue refunds without my approval.

## Manage Stripe Subscriptions For Customers

Combine Shopify customer context with Stripe subscription, invoice, and payment status.

- Apps: Stripe, Shopify, Recharge
- Tools: `STRIPE_LIST_SUBSCRIPTIONS`, `STRIPE_GET_SUBSCRIPTION`, `STRIPE_RETRIEVE_UPCOMING_INVOICE`, `STRIPE_LIST_INVOICES`, `STRIPE_SEARCH_SUBSCRIPTIONS`

> Review the subscription-related customer issues I specify using Shopify customer and order information alongside available Stripe subscription and invoice records. Identify active, trialing, past-due, or canceled Stripe subscriptions, upcoming invoice information where available, failed invoice payment attempts, relevant Shopify orders or customers when confidently matched, and potential customer access or billing issues. Do not assume that every Shopify customer has a Stripe subscription or that every Stripe subscription belongs to a Shopify order. Explain how each match was established. Recommend appropriate follow-up for billing or support. Do not cancel, resume, or modify subscriptions, change discounts, or send payment requests without explicit approval.

## Compare Discounts With Payment Outcomes

Relate Shopify discounts to Stripe payments, refunds, and transaction values where data supports it.

- Apps: Stripe, Shopify
- Tools: `STRIPE_SEARCH_CHARGES`, `STRIPE_LIST_REFUNDS`, `STRIPE_GET_PROMOTION_CODES`, `STRIPE_LIST_COUPONS`

> Analyze Shopify orders and available discount information alongside matched Stripe payment records for the period I specify. Compare performance across discount codes or campaign groups where the data supports reliable attribution. Include order counts and sales totals, discount amounts recorded in Shopify, matched Stripe payment totals and refund activity, payment failure rates if the available data supports the calculation, differences across promotion groups, and data limitations plus recommended experiments. Do not assume a Stripe transaction contains the Shopify discount code unless it is explicitly recorded or reliably linked. Do not infer profit without product costs, payment fees, and other necessary data. Summarize the findings and recommend tests. Do not create promotion codes, change prices, or modify payment settings without approval.

## Build A Daily Payment Operations Briefing

One prioritized daily report from Shopify orders and Stripe payments, refunds, disputes, and payouts.

- Apps: Stripe, Shopify, Slack
- Tools: `STRIPE_LIST_PAYMENT_INTENTS`, `STRIPE_LIST_REFUNDS`, `STRIPE_LIST_DISPUTES`, `STRIPE_LIST_PAYOUTS`, `STRIPE_LIST_INVOICES`

> Prepare a daily payment operations briefing using Shopify order and refund data alongside available Stripe payment records. Include failed or incomplete payment attempts, Shopify orders with potentially inconsistent payment status, refunds requiring reconciliation, new or updated disputes, invoice payment failures if applicable, payout issues and relevant balance movements, unmatched transactions, and recommended investigations. Include transaction references, amounts, currencies, timestamps, and source status where available. Avoid duplicate alerts for the same underlying issue. Prioritize cases by urgency and financial impact, but do not invent a risk score. Clearly separate verified discrepancies from possible ones. If Slack is connected, draft a concise briefing for the finance channel. Ask for approval before posting. If recurring delivery is required, confirm the schedule and destination before configuring it.
