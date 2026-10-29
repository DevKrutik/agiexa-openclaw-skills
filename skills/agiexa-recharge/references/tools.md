# Recharge tools via Agiexa (11)

Preview only - these become available to the agent after Agiexa launches (November 2026) and the merchant connects Recharge and turns the tools on. They cannot be called today.

Interactive explorer: https://agiexa.com/integrations/recharge

| Tool | What it does |
| --- | --- |
| `RECHARGE_FIND_CUSTOMER` | Find a Recharge customer by email, with subscription counts, payment status and (optionally) their upcoming delivery schedule |
| `RECHARGE_LIST_SUBSCRIPTIONS` | List Recharge subscriptions filtered by customer, status (active, cancelled, expired), Shopify variant, or creation/update dates |
| `RECHARGE_GET_SUBSCRIPTION` | Get one Recharge subscription (product, quantity, price, frequency, next charge date, cancellation info) |
| `RECHARGE_LIST_UPCOMING_CHARGES` | List charges by status (default queued = upcoming renewals; also error for failed payments, skipped...) scheduled in a date range, optionally for one |
| `RECHARGE_SKIP_CHARGE` | Skip an upcoming (queued) charge for the given subscriptions in it, so the customer isn't billed or shipped that time |
| `RECHARGE_UNSKIP_CHARGE` | Undo a skip for the given subscriptions in a charge |
| `RECHARGE_SET_NEXT_CHARGE_DATE` | Move a subscription's next charge date (YYYY-MM-DD) |
| `RECHARGE_UPDATE_SUBSCRIPTION` | Change a subscription's quantity, swap it to another Shopify variant (price taken from the variant), or change its frequency |
| `RECHARGE_CANCEL_SUBSCRIPTION` | Cancel an active subscription with a reason |
| `RECHARGE_ACTIVATE_SUBSCRIPTION` | Reactivate a cancelled subscription |
| `RECHARGE_CANCELLATION_REASONS` | Why customers cancel: counts cancellation reasons (and top cancelled products) over subscriptions cancelled recently (default last 30 days; computed b |
