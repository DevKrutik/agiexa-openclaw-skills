# Seal Subscriptions tools via Agiexa (7)

Preview only - these become available to the agent after Agiexa launches (November 2026) and the merchant connects Seal Subscriptions and turns the tools on. They cannot be called today.

Interactive explorer: https://agiexa.com/integrations/seal-subscriptions

| Tool | What it does |
| --- | --- |
| `SEAL_LIST_SUBSCRIPTIONS` | List or search the merchant's Seal subscriptions (50 per page) |
| `SEAL_GET_SUBSCRIPTION` | Get one Seal subscription with its items, next billing date and upcoming/recent billing attempts |
| `SEAL_LIST_UPCOMING_BILLINGS` | List subscriptions with at least one billing attempt scheduled between `from` and `to` (e.g |
| `SEAL_CHANGE_SUBSCRIPTION_STATUS` | Pause, resume, cancel or reactivate a Seal subscription |
| `SEAL_UPDATE_BILLING_ATTEMPT` | Skip, unskip or reschedule one upcoming billing attempt (get attempt IDs from GET_SUBSCRIPTION) |
| `SEAL_UPDATE_ITEM_QUANTITY` | Change the quantity of one item in a Seal subscription (item IDs from GET_SUBSCRIPTION) |
| `SEAL_GET_CUSTOMER_PORTAL_LINK` | Get the magic link that lets a customer manage all their subscriptions (only works if they have one) |
