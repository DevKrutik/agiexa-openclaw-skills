# Stripe triggers via Agiexa (40)

Preview only - events that will be able to start an agent run after Agiexa launches (November 2026).

| Trigger | When it fires |
| --- | --- |
| `STRIPE_CUSTOMER_SUBSCRIPTION_TRIAL_WILL_END` | Occurs three days before a subscription's trial period is scheduled to end, or immediately when a trial is ended early (for example, with `trial_end=n |
| `STRIPE_CUSTOMER_SUBSCRIPTION_UPDATED` | Occurs whenever a subscription changes (e.g., switching from one plan to another, or changing the status from trial to active) |
| `STRIPE_CUSTOMER_UPDATED` | Occurs whenever any property of a customer changes |
| `STRIPE_INVOICE_CREATED` | Occurs whenever a new invoice is created |
| `STRIPE_INVOICE_FINALIZED` | Occurs whenever a draft invoice is finalized and updated to be an open invoice |
| `STRIPE_INVOICEITEM_CREATED` | Occurs whenever an invoice item is created |
| `STRIPE_INVOICE_PAID` | Occurs whenever an invoice payment attempt succeeds or an invoice is marked as paid out-of-band |
| `STRIPE_INVOICE_PAYMENT_FAILED` | Occurs whenever an invoice payment attempt fails, due to either a declined payment, including soft decline, or to the lack of a stored payment method |
| `STRIPE_INVOICE_PAYMENT_SUCCEEDED` | Occurs whenever an invoice payment attempt succeeds |
| `STRIPE_CHARGE_SUCCEEDED` | Occurs whenever a charge is successful |
| `STRIPE_CHECKOUT_SESSION_ASYNC_PAYMENT_FAILED` | Occurs when a payment intent using a delayed payment method fails |
| `STRIPE_CHECKOUT_SESSION_ASYNC_PAYMENT_SUCCEEDED` | Occurs when a payment intent using a delayed payment method finally succeeds |
| `STRIPE_CHECKOUT_SESSION_COMPLETED` | Occurs when a Checkout Session has been successfully completed |
| `STRIPE_CHECKOUT_SESSION_EXPIRED` | Occurs when a Checkout Session is expired |
| `STRIPE_CUSTOMER_CREATED` | Occurs whenever a new customer is created |
| `STRIPE_CUSTOMER_DELETED` | Occurs whenever a customer is deleted |
| `STRIPE_CUSTOMER_SUBSCRIPTION_CREATED` | Occurs whenever a customer is signed up for a new plan |
| `STRIPE_CUSTOMER_SUBSCRIPTION_DELETED` | Occurs whenever a customer's subscription ends |
| `STRIPE_CHARGE_CAPTURED` | Occurs whenever a previously uncaptured charge is captured |
| `STRIPE_CHARGE_DISPUTE_CLOSED` | Occurs when a dispute is closed and the dispute status changes to `lost`, `warning_closed`, or `won` |
| `STRIPE_CHARGE_DISPUTE_CREATED` | Occurs whenever a customer disputes a charge with their bank |
| `STRIPE_CHARGE_DISPUTE_UPDATED` | Occurs when the dispute is updated (usually with evidence) |
| `STRIPE_CHARGE_FAILED` | Occurs whenever a failed charge attempt occurs |
| `STRIPE_CHARGE_REFUNDED` | Occurs whenever a charge is refunded, including partial refunds |
| `STRIPE_CHARGE_REFUND_UPDATED` | Occurs whenever a refund is updated on selected payment methods |
| `STRIPE_INVOICE_UPCOMING` | Occurs X number of days before a subscription is scheduled to create an invoice that is automatically charged-where X is determined by your subscripti |
| `STRIPE_INVOICE_VOIDED` | Occurs whenever an invoice is voided |
| `STRIPE_PAYMENT_INTENT_CANCELED` | Occurs when a PaymentIntent is canceled |
| `STRIPE_PAYMENT_INTENT_CREATED` | Occurs when a new PaymentIntent is created |
| `STRIPE_PAYMENT_INTENT_PAYMENT_FAILED` | Occurs when a PaymentIntent has failed the attempt to create a payment method or a payment |
| `STRIPE_PAYMENT_INTENT_REQUIRES_ACTION` | Occurs when a PaymentIntent transitions to requires_action state |
| `STRIPE_PAYMENT_INTENT_SUCCEEDED` | Occurs when a PaymentIntent has successfully completed payment |
| `STRIPE_PAYMENT_LINK_CREATED` | Occurs when a payment link is created |
| `STRIPE_PAYOUT_FAILED` | Occurs whenever a payout attempt fails |
| `STRIPE_PAYOUT_PAID` | Occurs whenever a payout is *expected* to be available in the destination account |
| `STRIPE_PRICE_CREATED` | Occurs whenever a price is created |
| `STRIPE_PRICE_UPDATED` | Occurs whenever a price is updated |
| `STRIPE_PRODUCT_CREATED` | Occurs whenever a product is created |
| `STRIPE_PRODUCT_UPDATED` | Occurs whenever a product is updated |
| `STRIPE_REFUND_CREATED` | Occurs whenever a refund is created |
