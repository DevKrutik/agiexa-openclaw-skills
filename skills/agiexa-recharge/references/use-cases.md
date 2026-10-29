# Recharge use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/recharge

## Analyze Recurring Revenue And Subscription Health

Combine Shopify product information with Recharge subscription data to understand recurring revenue opportunities and operational risks.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_LIST_UPCOMING_CHARGES`, `RECHARGE_CANCELLATION_REASONS`, `RECHARGE_FIND_CUSTOMER`

> Analyze my Shopify subscription business using Recharge customer, subscription, upcoming charge, and cancellation data. Summarize active, cancelled, and expired subscriptions where available, and group subscriptions by Shopify product variant. Identify upcoming renewals, charges in error status, and products associated with frequent cancellations where the data supports these comparisons. Explain which findings represent confirmed facts and which are possible risks. Do not estimate recurring revenue unless the necessary subscription pricing and billing frequency data is available. Prepare prioritized recommendations without changing subscriptions or charges.

## Identify Customers With Failed Payments

Find subscription charges in error status and connect them with relevant customer and Shopify product information.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_UPCOMING_CHARGES`, `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_FIND_CUSTOMER`

> Review Recharge charges with error status over the selected period. Identify the associated customers and subscriptions where the available data supports the match. Retrieve subscription details, including product variant, quantity, price, billing frequency, next charge date, and current status. Group cases by urgency and identify which records need payment investigation or customer follow-up. Do not assume the exact reason for a failed payment unless the returned data confirms it. Prepare customer support notes and recommended next steps, but do not modify subscriptions or claim that payments have been recovered.

## Prepare Upcoming Subscription Renewal Reports

Combine upcoming Recharge charges with Shopify product details to identify renewals requiring operational attention.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_UPCOMING_CHARGES`, `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_LIST_SUBSCRIPTIONS`

> Review upcoming Recharge charges for the next seven days. List the scheduled charge dates, associated subscriptions, customer information where available, products, quantities, and charge statuses. Retrieve individual subscription details for records that need further investigation. Group the results by renewal date and flag error-status charges or unusual scheduling situations. Distinguish queued charges from failed or skipped charges. Prepare a daily renewal report with recommended follow-up actions. Do not skip, unskip, or reschedule charges automatically.

## Reduce Churn Through Flexible Renewals

Identify customers who may benefit from adjusted billing frequency or renewal dates instead of cancelling.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_CANCELLATION_REASONS`, `RECHARGE_UPDATE_SUBSCRIPTION`, `RECHARGE_SET_NEXT_CHARGE_DATE`, `RECHARGE_SKIP_CHARGE`

> Analyze my Recharge subscriptions and recent cancellation reasons to identify potential opportunities for reducing churn. Look for available evidence that customers may need more flexible delivery intervals or renewal timing. Group recommendations by product variant and cancellation reason where supported. For active subscriptions that could benefit from a frequency or next-charge-date adjustment, prepare a proposed change with the current and requested values. Do not infer customer preferences without evidence. Ask for approval before updating subscription frequency, moving a charge date, or skipping a charge.

## Understand Why Shopify Subscribers Cancel

Analyze Recharge cancellation reasons and associated Shopify products to identify recurring retention problems.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_CANCELLATION_REASONS`, `RECHARGE_LIST_SUBSCRIPTIONS`

> Review cancellation reasons from Recharge for the last 30 days, or another period I specify. Summarize cancellation counts and identify the most common reasons and products associated with cancelled subscriptions where available. Compare cancellation patterns across Shopify product variants if the returned data supports it. Explain which findings are directly reported and which are hypotheses. Recommend specific retention experiments, such as flexible billing frequency, improved product education, or clearer subscription value communication. Do not reactivate cancelled subscriptions or contact customers automatically.

## Reactivate Eligible Cancelled Subscribers

Identify cancelled subscribers who may be suitable for a retention campaign and prepare a controlled reactivation plan.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_ACTIVATE_SUBSCRIPTION`, `RECHARGE_CANCELLATION_REASONS`

> Review cancelled Recharge subscriptions and the available cancellation reasons. Identify customers or product groups that may be appropriate for a reactivation campaign, using only available evidence. Retrieve subscription details to verify current status, product variant, quantity, price, billing frequency, and cancellation information where available. Prepare a shortlist with the reason for consideration and any details that require confirmation. Do not reactivate subscriptions merely because they were cancelled recently. Request explicit approval for each subscription before reactivation and clearly state that the available integration does not provide customer messaging capabilities.

## Offer Subscription Quantity And Product Changes

Evaluate subscription quantity and product-variant changes to accommodate customer preferences and improve retention.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_UPDATE_SUBSCRIPTION`

> Review the Recharge subscriptions I specify and retrieve their current products, Shopify variant references, quantities, prices, billing frequencies, and next charge dates. Based on the customer request I provide, prepare a proposed quantity change or product-variant swap. Verify that the requested Shopify variant is valid using the available information and explain that the subscription price may change according to the selected variant. Show the current and proposed configuration, including any known price impact. Do not update any subscription until I approve the exact subscription ID and proposed changes.

## Manage Subscription Skips And Rescheduling

Handle customer-requested renewal skips and date changes while minimizing billing and fulfillment surprises.

- Apps: Recharge
- Tools: `RECHARGE_LIST_UPCOMING_CHARGES`, `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_SKIP_CHARGE`, `RECHARGE_UNSKIP_CHARGE`, `RECHARGE_SET_NEXT_CHARGE_DATE`

> Review the Recharge subscriptions and upcoming charges relevant to the customer request I provide. Verify the current charge status, subscription IDs associated with the charge, next charge dates, and available product details. If a customer requests a one-time skip, prepare the proposed skip action and explain the likely billing and delivery implications based on available information. If the customer requests a different renewal date, prepare the proposed date change. Confirm whether the requested operation is supported and ask for approval before skipping, unskipping, or changing any date. Report the actual result after execution.

## Compare Subscription Products And Billing Frequency

Analyze Shopify product variants and Recharge subscription settings to identify product-level retention and subscription configuration opportunities.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_GET_SUBSCRIPTION`, `RECHARGE_CANCELLATION_REASONS`

> Analyze Recharge subscriptions grouped by Shopify product variant and billing frequency. Retrieve available subscription counts, quantities, prices, next charge dates, and statuses. Compare active and cancelled subscription patterns across products and intervals where the data supports it. Identify products that may benefit from alternative billing frequencies or a closer review of their subscription offering. Avoid assuming that a product is unprofitable or has high churn without sufficient evidence. Provide a prioritized set of experiments and clearly separate measured results from recommendations. Do not change subscription configurations without approval.

## Build A Daily Subscription Operations Review

Consolidate subscription status, renewal schedules, payment issues, and cancellation insights into one actionable report.

- Apps: Recharge, Shopify
- Tools: `RECHARGE_LIST_SUBSCRIPTIONS`, `RECHARGE_LIST_UPCOMING_CHARGES`, `RECHARGE_CANCELLATION_REASONS`, `RECHARGE_GET_SUBSCRIPTION`

> Prepare a daily Recharge operations report for my Shopify subscription business. Summarize active, cancelled, and expired subscriptions where available, upcoming charges, charges in error status, and subscriptions requiring renewal-date or frequency review. Include relevant customer and subscription identifiers, product variants, quantities, prices, and next charge dates when available. Add recent cancellation insights and prioritize cases by customer impact and urgency. Clearly identify missing data and distinguish confirmed issues from possible risks. Do not skip charges, modify subscriptions, cancel subscriptions, or reactivate customers without my explicit approval.
