# Seal Subscriptions use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/seal-subscriptions

## Monitor Upcoming Subscription Billings

Combine Seal billing schedules with Shopify product information to prepare a daily or weekly renewal review.

- Apps: Seal Subscriptions, Shopify
- Tools: `SEAL_LIST_UPCOMING_BILLINGS`, `SEAL_GET_SUBSCRIPTION`, `SEAL_LIST_SUBSCRIPTIONS`

> Review my Seal subscriptions with billing attempts scheduled over the next seven days. List the relevant subscriptions, upcoming billing dates, subscription items, quantities, and statuses where available. Group the results by billing date and identify records that need further investigation. Use associated Shopify product details where available to make the report easier to understand. Distinguish scheduled billing attempts from completed or failed attempts. Prepare a prioritized renewal report, but do not skip, reschedule, or otherwise modify any billing attempt without my approval.

## Investigate Subscription Billing Problems

Inspect subscription billing history and identify records that require payment or billing-schedule investigation.

- Apps: Seal Subscriptions
- Tools: `SEAL_GET_SUBSCRIPTION`, `SEAL_LIST_UPCOMING_BILLINGS`, `SEAL_LIST_SUBSCRIPTIONS`

> Review my Seal subscriptions and inspect upcoming and recent billing attempts for records that may require attention. Retrieve the full subscription details, including current status, subscription items, next billing date, and available billing history. Identify unusual or unsuccessful attempts only when the returned data supports that conclusion. Include subscription IDs, relevant dates, quantities, and recommended next steps. Do not invent payment failure reasons or claim that a payment has been recovered. Prepare an investigation report without changing billing attempts or subscription statuses.

## Manage Customer Subscription Changes

Review Shopify subscription requests and prepare approved quantity, pause, resume, or cancellation changes.

- Apps: Seal Subscriptions
- Tools: `SEAL_GET_SUBSCRIPTION`, `SEAL_CHANGE_SUBSCRIPTION_STATUS`, `SEAL_UPDATE_ITEM_QUANTITY`

> Help me process the subscription change requests I provide. Find the relevant Seal subscription and retrieve its current status, items, item identifiers, quantities, and next billing date. Compare the customer's requested change with the existing configuration. Prepare the exact proposed action, including whether it involves pausing, resuming, cancelling, reactivating, or changing an item quantity. Explain the likely implications for future billing where the available information supports them. Ask for explicit approval before applying the change, and report the actual result afterward. Do not assume a customer wants to cancel or resume a subscription without clear instructions.

## Reduce Churn Through Flexible Billing

Identify opportunities to adjust billing schedules or quantities instead of unnecessarily losing subscribers.

- Apps: Seal Subscriptions, Shopify
- Tools: `SEAL_LIST_SUBSCRIPTIONS`, `SEAL_LIST_UPCOMING_BILLINGS`, `SEAL_UPDATE_BILLING_ATTEMPT`, `SEAL_CHANGE_SUBSCRIPTION_STATUS`

> Review my Seal subscription records and upcoming billing attempts to identify potential opportunities for more flexible subscription management. Look for upcoming billings and existing subscription details that could support customer-requested date adjustments, quantity changes, or temporary pauses. Use Shopify product information where available to explain the affected items. Do not assume that a customer is dissatisfied based only on subscription status or billing history. Prepare a recommendation list with subscription IDs, current settings, proposed changes, and reasons. Ask for approval before skipping, rescheduling, pausing, or changing any subscription.

## Reactivate Cancelled Shopify Subscribers

Identify cancelled subscriptions suitable for review and prepare a controlled reactivation workflow.

- Apps: Seal Subscriptions, Shopify
- Tools: `SEAL_LIST_SUBSCRIPTIONS`, `SEAL_GET_SUBSCRIPTION`, `SEAL_CHANGE_SUBSCRIPTION_STATUS`

> Review cancelled Seal subscriptions and retrieve their available details, including subscription items, quantities, billing information, and status. Identify records that may be suitable for a reactivation campaign based on the information available. Group candidates by product and any relevant historical details returned by the integration. Do not assume why a customer cancelled or that they want to restart. Prepare a shortlist and recommend obtaining customer consent before reactivation. Ask for explicit approval for each subscription ID before changing its status, and report the actual result of any approved operation.

## Update Subscription Item Quantities

Adjust subscription quantities in response to customer requests while verifying the exact subscription item.

- Apps: Seal Subscriptions
- Tools: `SEAL_GET_SUBSCRIPTION`, `SEAL_UPDATE_ITEM_QUANTITY`

> Process the quantity change requests I provide for Seal subscriptions. Find each subscription and retrieve its full details to identify the correct item ID, current quantity, product, and next billing date. Compare the requested quantity with the current configuration and prepare a before-and-after summary. Explain that the change may affect future order totals, while avoiding unsupported price calculations. Confirm the subscription and item identifiers before applying any update. Do not change quantities until I approve the exact subscription item and requested value.

## Reschedule Or Skip Upcoming Billings

Handle customer-requested billing changes using verified billing-attempt identifiers and current subscription details.

- Apps: Seal Subscriptions
- Tools: `SEAL_LIST_UPCOMING_BILLINGS`, `SEAL_GET_SUBSCRIPTION`, `SEAL_UPDATE_BILLING_ATTEMPT`

> Review the upcoming Seal billing attempts relevant to the customer requests I provide. Retrieve the associated subscription details and identify the exact billing-attempt IDs where available. For each request, prepare the appropriate action: skip one billing attempt, undo an existing skip, or reschedule a billing attempt. Verify the current billing status and requested date before proposing a change. Explain the expected effect on the next billing schedule based on the available information. Ask for explicit approval before making any change, and report the actual result without claiming that a billing operation succeeded unless confirmed.

## Provide Self-Service Subscription Portal Links

Retrieve eligible customer portal links so Shopify subscribers can manage their own subscriptions.

- Apps: Seal Subscriptions, Shopify
- Tools: `SEAL_LIST_SUBSCRIPTIONS`, `SEAL_GET_SUBSCRIPTION`, `SEAL_GET_CUSTOMER_PORTAL_LINK`

> Help me locate the Seal subscription management portal for the customer I specify. Find the customer's subscription records and verify whether the available portal-link capability applies. Retrieve the customer portal link when supported, and explain that it provides access to manage eligible subscriptions. If the customer cannot be identified or the capability's eligibility requirements are not met, explain what information is missing. Handle portal links carefully because they may grant account access. Do not send a link to anyone or claim that it was delivered unless a supported sending action and confirmed result are available.

## Audit Active And Paused Subscriptions

Review subscription statuses and billing schedules to identify records that need clarification or operational follow-up.

- Apps: Seal Subscriptions
- Tools: `SEAL_LIST_SUBSCRIPTIONS`, `SEAL_GET_SUBSCRIPTION`, `SEAL_LIST_UPCOMING_BILLINGS`

> Audit my Seal subscriptions and group them by active, paused, cancelled, and other returned statuses. Include subscription IDs, items, quantities, next billing dates, and recent or upcoming billing attempts where available. Identify paused subscriptions with upcoming billing information that needs clarification, active subscriptions with unusual scheduling details, and cancelled subscriptions that may warrant a review. Do not assume any status is incorrect simply because it differs from the expected workflow. Prepare an audit report with evidence, recommended next steps, and exact identifiers. Do not change any statuses or billing schedules without my approval.

## Build A Daily Subscription Operations Report

Consolidate billing schedules, subscription statuses, quantity changes, and customer follow-ups into one operational report.

- Apps: Seal Subscriptions, Shopify
- Tools: `SEAL_LIST_SUBSCRIPTIONS`, `SEAL_LIST_UPCOMING_BILLINGS`, `SEAL_GET_SUBSCRIPTION`

> Prepare a daily operations report for my Shopify store's Seal subscriptions. Summarize active, paused, cancelled, and other available subscription statuses; upcoming billing attempts; next billing dates; subscription items and quantities; and recent billing activity where available. Identify records requiring investigation, customer-requested changes, potential rescheduling needs, and subscriptions that may warrant a consent-based reactivation review. Include exact subscription and billing-attempt IDs wherever available. Separate confirmed facts from recommendations and clearly identify missing information. Do not skip billings, change quantities, pause or resume subscriptions, cancel subscriptions, or reactivate subscribers without my explicit approval.
