# Shippo use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/shippo

## Track Shopify Orders And Deliveries

Connect Shopify order references with Shippo tracking information to monitor deliveries and prepare accurate customer updates.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_SHIPMENTS`, `SHIPPO_GET_TRACK`, `SHIPPO_GET_SHIPMENT`

> Review Shippo shipments associated with my recent Shopify orders. Retrieve available order references, shipment IDs, carrier details, tracking numbers, tracking links, and latest tracking statuses. Identify shipments with delivery exceptions, apparent delivery, or tracking activity that may require investigation. Distinguish confirmed carrier events from assumptions and do not label a shipment as lost solely because tracking has not updated. Prepare a prioritized report and draft customer-friendly updates using verified information only. Do not send messages or change shipments automatically.

## Compare Carrier Rates Before Label Purchase

Compare available carrier services for Shopify orders to reduce shipping costs while respecting delivery expectations.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_SHIPMENT_RATES`, `SHIPPO_GET_SHIPMENT`, `SHIPPO_CREATE_TRANSACTION`

> Find Shopify-related shipments that may benefit from a shipping rate comparison. Retrieve the relevant Shippo shipment details and available carrier rates. Compare prices, service levels, and estimated delivery times where available. Calculate potential savings against the current rate only when the amounts are comparable. Recommend the best option based on shipping cost and the delivery promise for each Shopify order. Identify missing parcel or address details that prevent a reliable comparison. Do not purchase labels or select a carrier automatically. Ask for approval before purchasing a label at a specific rate.

## Validate Shopify Customer Addresses

Identify incomplete or potentially invalid shipping addresses before fulfillment to reduce delivery failures and returned parcels.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_VALIDATE_ADDRESS`, `SHIPPO_GET_SHIPMENT`, `SHIPPO_CREATE_ADDRESS`

> Review shipping addresses for the Shopify orders I specify. Use Shippo's address validation capability to identify missing address components, formatting concerns, and validation warnings. Present the original address, validation result, normalized address where available, and associated Shopify order reference. Distinguish confirmed validation findings from suggestions that need customer verification. Do not assume a suggested correction is accurate or overwrite a Shopify customer address automatically. Prepare proposed corrections and request my approval before changing any shipment or address record.

## Investigate Shipping Label Problems

Inspect Shippo label transactions and related shipment details to identify orders that may be blocked from fulfillment.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_GET_TRANSACTION`, `SHIPPO_GET_SHIPMENT`, `SHIPPO_CREATE_TRANSACTION`

> Review Shippo label transactions for the Shopify orders I select. Retrieve the relevant transaction and shipment details, including available status information, carrier, rate, and label references. Identify records that appear unsuccessful, incomplete, or otherwise require investigation based on returned data. Match each record to its Shopify order where possible and explain the evidence for each concern. Do not assume that every unsuccessful transaction can be retried safely. Prepare a recovery plan and ask for approval before creating another label or changing the shipment.

## Prepare Bulk Shipping Batches Safely

Organize eligible Shopify shipments into batches and review their rates and costs before purchasing labels in bulk.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_CREATE_BATCH`, `SHIPPO_GET_MERCHANT_BATCH`, `SHIPPO_PURCHASE_MERCHANT_BATCH`, `SHIPPO_VALIDATE_ADDRESS`

> Help me prepare a bulk shipping workflow for selected Shopify orders. Identify the relevant Shippo shipments, verify their required address and parcel information, and organize approved shipments into a batch where supported. Show the shipment IDs, selected rates, estimated costs, and unresolved issues before purchasing labels. If the batch already exists, retrieve its details and inspect any available processing information. Ask for explicit approval before purchasing a batch. After processing, report the actual result and any returned errors. Do not claim that labels were purchased unless the operation confirms success.

## Monitor International Shipping Requirements

Review international Shopify shipments and identify customs information that may need preparation or verification.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_CUSTOMS_DECLARATIONS`, `SHIPPO_LIST_CUSTOMS_ITEMS`, `SHIPPO_GET_CUSTOMS_DECLARATION`, `SHIPPO_CREATE_CUSTOMS_ITEM`

> Review the international Shopify shipments I specify and retrieve their available Shippo shipment, parcel, and customs information. Identify which shipments may require customs declarations or item details based on the destination and available records. Where supported, inspect existing customs declarations and customs items. Prepare a checklist of missing information, such as item descriptions, quantities, values, origin details, and other required fields where applicable. Do not invent customs values or guarantee regulatory compliance. Ask for approval before creating customs records or purchasing shipping labels.

## Analyze Shipping Costs Across Shopify Orders

Aggregate available shipping rate and transaction information to identify expensive destinations, products, and shipping patterns.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_SHIPMENTS`, `SHIPPO_LIST_SHIPMENT_RATES`, `SHIPPO_GET_TRANSACTION`

> Analyze shipping costs for my Shopify orders using available Shippo shipment, rate, and label transaction records. Group the results by destination, carrier, service level, and reporting period where the data supports it. Identify orders with unusually high shipping costs and compare alternative rates where available. Calculate potential savings only when comparable rates and the relevant order details are present. Distinguish purchased label costs from unpurchased rate estimates. Recommend changes to shipping policies or rate selection without assuming that the cheapest service is always suitable. Do not purchase labels or update checkout settings automatically.

## Manage Shipping Accounts And Parcel Templates

Review carrier accounts, parcel templates, and default package settings to identify configuration issues affecting Shopify fulfillment.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_CARRIER_ACCOUNTS`, `SHIPPO_LIST_USER_PARCEL_TEMPLATES`, `SHIPPO_GET_CARRIER_REGISTRATION_STATUS`, `SHIPPO_UPDATE_CARRIER_ACCOUNT`, `SHIPPO_UPDATE_USER_PARCEL_TEMPLATE`

> Audit my Shippo carrier accounts and parcel templates relevant to my Shopify fulfillment workflow. Retrieve available carrier registration statuses, parcel dimensions, weight settings, and default parcel configuration. Identify missing information, inactive or unregistered carrier accounts, and package settings that may not match the products being shipped. Explain how each issue could affect rate availability or label preparation, without assuming causation where data is insufficient. Recommend specific configuration updates and request approval before changing carrier accounts or parcel templates.

## Review Refunds And Shipping Transactions

Investigate shipping-related refunds and transaction records to help reconcile fulfillment costs with Shopify order activity.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_REFUNDS`, `SHIPPO_GET_REFUND`, `SHIPPO_GET_TRANSACTION`, `SHIPPO_CREATE_REFUND`

> Review Shippo refunds, shipping label transactions, and related shipment records for the Shopify orders I specify. Match records using available Shopify order references, transaction IDs, shipment IDs, dates, and amounts. Identify refunds that require verification, transaction records that appear inconsistent, and shipping costs that need reconciliation. Distinguish a refund request or record from a confirmed refund outcome. Prepare an investigation report with supporting evidence and recommended next steps. Do not create refunds or claim that Shopify customer refunds have been completed unless the relevant operation and result confirm that outcome.

## Build A Daily Shopify Shipping Report

Consolidate tracking, shipping costs, address validation, label transactions, and fulfillment exceptions into one operational report.

- Apps: Shippo, Shopify
- Tools: `SHIPPO_LIST_SHIPMENTS`, `SHIPPO_GET_TRACK`, `SHIPPO_LIST_SHIPMENT_RATES`, `SHIPPO_VALIDATE_ADDRESS`

> Prepare a daily shipping operations report for my Shopify store using available Shippo data. Summarize shipments, tracking statuses, purchased label transactions, available shipping rates, address validation concerns, and records requiring investigation. Include Shopify order references wherever available. Highlight potential cost savings only when comparable rates exist, and prioritize issues by customer impact and operational urgency. Separate confirmed facts from estimates and recommendations. Include shipment IDs, transaction IDs, tracking links, and proposed next steps where available. Do not purchase labels, create refunds, or modify shipping records without my explicit approval.
