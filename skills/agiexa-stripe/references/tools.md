# Stripe tools via Agiexa (426)

Preview only - these become available to the agent after Agiexa launches (November 2026) and the merchant connects Stripe and turns the tools on. They cannot be called today.

Interactive explorer: https://agiexa.com/integrations/stripe

| Tool | What it does |
| --- | --- |
| `STRIPE_CREATE_PRODUCT` | Creates a new product in Stripe, encoding the request as `application/x-www-form-urlencoded` by flattening nested structures |
| `STRIPE_CREATE_PRICE` | Creates a new Stripe Price for a product, defining its charges (one-time or recurring) and billing scheme; requires either an existing `product` ID or |
| `STRIPE_CREATE_PREVIEW_INVOICE` | Tool to preview an upcoming invoice without creating it |
| `STRIPE_COLLECT_TERMINAL_READER_PAYMENT_METHOD` | Tool to initiate payment method collection on a Stripe Terminal Reader |
| `STRIPE_CREATE_PLAN` | Tool to create a recurring billing plan with flexible pricing configuration |
| `STRIPE_ACCEPT_QUOTE` | Tool to accept a quote in Stripe |
| `STRIPE_ACTIVATE_BILLING_ALERT` | Reactivates a billing alert, allowing it to trigger again |
| `STRIPE_ADD_INVOICE_LINES` | Tool to add multiple line items to a draft Stripe invoice |
| `STRIPE_ADVANCE_TEST_CLOCK` | Advance a test clock to a future timestamp |
| `STRIPE_APPLY_CUSTOMER_BALANCE` | Manually reconciles remaining amount for a customer_balance PaymentIntent by applying funds from customer's cash balance |
| `STRIPE_ARCHIVE_BILLING_ALERT` | Tool to archive a billing alert in Stripe, removing it from list views and APIs |
| `STRIPE_ATTACH_CUSTOMER_SOURCE` | Attach a payment source (card token or source object) to a customer for future charges |
| `STRIPE_ATTACH_INVOICE_PAYMENT` | Attaches a PaymentIntent or Out of Band Payment to an invoice's payments list |
| `STRIPE_ATTACH_PAYMENT_METHOD` | Attaches a PaymentMethod to a Customer |
| `STRIPE_ATTACH_PRODUCT_FEATURE` | Tool to attach a feature to a product |
| `STRIPE_CANCEL_PAYMENT_INTENT` | Cancels a PaymentIntent when in cancelable state |
| `STRIPE_CANCEL_QUOTE` | Tool to cancel a Stripe quote |
| `STRIPE_CANCEL_SETUP_INTENT` | Cancels a SetupIntent that is no longer needed |
| `STRIPE_CANCEL_SUBSCRIPTION` | Cancels a customer's active Stripe subscription at the end of the current billing period, with options to invoice immediately for metered usage and pr |
| `STRIPE_CANCEL_SUBSCRIPTION_SCHEDULE` | Cancels a subscription schedule and its associated subscription immediately (if active) |
| `STRIPE_CANCEL_TERMINAL_READER_ACTION` | Tool to cancel the current reader action |
| `STRIPE_CAPTURE_CHARGE` | Tool to capture payment on an uncaptured charge |
| `STRIPE_CAPTURE_PAYMENT_INTENT` | Captures the funds of an existing uncaptured PaymentIntent |
| `STRIPE_CLOSE_DISPUTE` | Tool to close a dispute |
| `STRIPE_COLLECT_TERMINAL_READER_INPUTS` | Initiates input collection on a Terminal Reader to display forms and collect customer information |
| `STRIPE_CONFIRM_PAYMENT_INTENT` | Tool to confirm customer intent to pay with current or provided payment method |
| `STRIPE_CONFIRM_SETUP_INTENT` | Confirms a SetupIntent to complete customer payment method setup |
| `STRIPE_CONFIRM_TERMINAL_READER_PAYMENT_INTENT` | Tool to confirm a PaymentIntent on a Terminal reader device |
| `STRIPE_CREATE_ACCOUNTS_CAPABILITIES_CARD_PAYMENTS` | Tool to create or update card payments capability for a Stripe Connect account |
| `STRIPE_CREATE_ACCOUNT_SESSION` | Creates an Account Session for a Stripe Connect account, granting access to embedded components |
| `STRIPE_CREATE_APPLE_PAY_DOMAIN` | Tool to create an Apple Pay domain registration |
| `STRIPE_CREATE_APPS_SECRET` | Tool to create a secret in the Stripe Secret Store |
| `STRIPE_CREATE_BANK_ACCOUNT_TOKEN` | Tool to create a single-use token representing bank account details |
| `STRIPE_CREATE_BILLING_ALERT` | Tool to create a billing alert that monitors usage on a billing meter and triggers notifications when a specified threshold is crossed |
| `STRIPE_CREATE_BILLING_CREDIT_GRANT` | Tool to create a credit grant that allocates billing credits to a customer for use against metered pricing |
| `STRIPE_CREATE_BILLING_METER` | Tool to create a billing meter in Stripe for tracking usage events |
| `STRIPE_CREATE_BILLING_METER_EVENT` | Creates a billing meter event using Stripe API v2 for usage-based billing |
| `STRIPE_CREATE_BILLING_METER_EVENT_ADJUSTMENT` | Creates an adjustment to cancel a billing meter event |
| `STRIPE_CREATE_BILLING_METER_EVENT_SESSION` | Creates authentication session for high-throughput meter event stream |
| `STRIPE_CREATE_BILLING_PORTAL_CONFIGURATION` | Tool to create a Stripe billing portal configuration |
| `STRIPE_CREATE_BILLING_PORTAL_SESSION` | Tool to create a Stripe billing portal session |
| `STRIPE_CREATE_CHARGE_REFUND` | Tool to create a refund for a charge in Stripe |
| `STRIPE_CREATE_CHECKOUT_SESSION` | Tool to create a Stripe Checkout Session |
| `STRIPE_CREATE_COUPON` | Creates a new discount coupon in Stripe with percentage or fixed amount discount |
| `STRIPE_CREATE_CREDIT_NOTE` | Issues a credit note to adjust a finalized invoice's amount |
| `STRIPE_CREATE_CUSTOMER` | Creates a new customer in Stripe, required for creating charges or subscriptions; an email is highly recommended for customer communications |
| `STRIPE_CREATE_CUSTOMER_BALANCE_TRANSACTION` | Tool to create an immutable transaction that updates the customer's credit balance |
| `STRIPE_CREATE_CUSTOMER_BANK_ACCOUNT` | Tool to create a new bank account attached to a customer object |
| `STRIPE_CREATE_CUSTOMER_CARD` | Creates a card or bank account payment source for a Stripe customer |
| `STRIPE_CREATE_CUSTOMER_SESSION` | Tool to create a Stripe Customer Session granting client-side access control over a Customer |
| `STRIPE_CREATE_CUSTOMER_SOURCE` | Attaches a payment source to a customer for later reuse |
| `STRIPE_CREATE_CUSTOMER_SUBSCRIPTION` | Tool to create a subscription for an existing customer |
| `STRIPE_CREATE_CUSTOMER_TAX_ID` | Creates a new tax ID for a customer, used for tax compliance and invoicing across 100+ supported country-specific tax ID formats |
| `STRIPE_CREATE_CVC_UPDATE_TOKEN` | Creates a single-use token representing an updated CVC value for card payments |
| `STRIPE_CREATE_ENTITLEMENT_FEATURE` | Creates a new feature entitlement in Stripe representing a monetizable ability or functionality |
| `STRIPE_CREATE_EPHEMERAL_KEY` | Tool to create a short-lived ephemeral API key for secure mobile SDK access to specific Stripe resources |
| `STRIPE_CREATE_FILE` | Tool to upload a file to Stripe for business purposes such as dispute evidence, identity verification, or business logos |
| `STRIPE_CREATE_FILE_LINK` | Tool to create a file link object that generates a shareable URL for accessing uploaded files |
| `STRIPE_CREATE_FINANCIAL_CONNECTIONS_SESSION` | Tool to create a Financial Connections Session to launch the authorization flow for linking financial accounts |
| `STRIPE_CREATE_FX_QUOTE` | Tool to create an FX quote for currency conversion with optional rate locking |
| `STRIPE_CREATE_INVOICE` | Creates a new draft Stripe invoice for a customer; use to revise an existing invoice, bill for a specific subscription (which must belong to the custo |
| `STRIPE_CREATE_INVOICE_ITEM` | Tool to create an invoice item for draft invoices |
| `STRIPE_CREATE_PAYMENT_INTENT` | Creates a Stripe PaymentIntent to initiate and process a customer's payment; using `application_fee_amount` for a connected account requires the `Stri |
| `STRIPE_CREATE_PAYMENT_LINK` | Tool to create a Stripe Payment Link |
| `STRIPE_CREATE_PAYMENT_METHOD` | Creates a PaymentMethod object representing a customer's payment instrument (card, bank account, etc.) |
| `STRIPE_CREATE_PAYMENT_METHOD_CONFIGURATION` | Creates a payment method configuration to control which payment methods are displayed during checkout |
| `STRIPE_CREATE_PAYMENT_METHOD_DOMAIN` | Tool to create a payment method domain object to control where payment methods are shown |
| `STRIPE_CREATE_PII_TOKEN` | Tool to create a single-use token representing PII (personally identifiable information) |
| `STRIPE_CREATE_PROMOTION_CODE` | Tool to create a promotion code linked to an underlying coupon |
| `STRIPE_CREATE_QUOTE` | Tool to create a Stripe quote modeling prices and services for a customer |
| `STRIPE_CREATE_REFUND` | Creates a full or partial refund in Stripe, targeting either a specific charge ID or a payment intent ID |
| `STRIPE_CREATE_REPORT_RUN` | Creates a new report run object and begins executing the report asynchronously |
| `STRIPE_CREATE_REVERSAL_TAX_TRANSACTION` | Creates a reversal of an existing tax transaction |
| `STRIPE_CREATE_SETUP_INTENT` | Creates a SetupIntent object to collect payment method permissions for future payments |
| `STRIPE_CREATE_SHIPPING_RATE` | Creates a new shipping rate object that appears on Checkout Sessions for customer display |
| `STRIPE_CREATE_SOURCE` | Tool to create a Stripe source object for accepting payment methods |
| `STRIPE_CREATE_SUBSCRIPTION` | Creates a new, highly configurable subscription for an existing Stripe customer, supporting multiple items, trials, discounts, and various billing/pay |
| `STRIPE_CREATE_SUBSCRIPTION_ITEM` | Tool to add a new item to an existing subscription without changing existing items |
| `STRIPE_CREATE_SUBSCRIPTION_SCHEDULE` | Tool to create a new subscription schedule for managing subscription changes over time |
| `STRIPE_CREATE_TAX_CALCULATION` | Creates a Tax Calculation to compute taxes for customer purchases |
| `STRIPE_CREATE_TAX_ID` | Creates a new tax ID for an account or customer |
| `STRIPE_CREATE_TAX_RATE` | Tool to create a new tax rate in Stripe |
| `STRIPE_CREATE_TAX_REGISTRATION` | Creates a new Tax Registration object to enable tax collection in specified jurisdictions |
| `STRIPE_CREATE_TAX_TRANSACTION_FROM_CALCULATION` | Tool to create a Tax Transaction from a calculation before 90-day expiration |
| `STRIPE_CREATE_TERMINAL_CONFIGURATION` | Creates a new Configuration object for Stripe payment terminals with customizable settings |
| `STRIPE_CREATE_TERMINAL_CONNECTION_TOKEN` | Creates a short-lived connection token for Stripe Terminal SDK to connect to readers |
| `STRIPE_CREATE_TERMINAL_LOCATION` | Creates a new Terminal Location for managing Stripe Terminal readers |
| `STRIPE_CREATE_TERMINAL_ONBOARDING_LINK` | Creates an onboarding link for Tap to Pay on iPhone |
| `STRIPE_CREATE_TERMINAL_READER` | Creates and registers a new Terminal Reader to a Stripe account at a specified location |
| `STRIPE_CREATE_TEST_CLOCK` | Tool to create a test clock for testing time-based scenarios in Stripe |
| `STRIPE_DELETE_TERMINAL_CONFIGURATION` | Permanently deletes a Terminal Configuration object from your Stripe account |
| `STRIPE_DELETE_TERMINAL_LOCATION` | Tool to permanently delete a Terminal Location object from your Stripe account |
| `STRIPE_CREATE_TEST_CONFIRMATION_TOKEN` | Creates a test mode Confirmation Token for server-side payment integration testing |
| `STRIPE_CREATE_TOKEN` | Tool to create a single-use CVC update token for card re-collection |
| `STRIPE_CREATE_TRANSFER` | Creates a transfer to move funds between Stripe accounts as part of Connect |
| `STRIPE_CREATE_USAGE_RECORD` | Creates a usage record for a specified subscription item and timestamp |
| `STRIPE_DEACTIVATE_BILLING_ALERT` | Tool to deactivate a billing alert, preventing it from triggering |
| `STRIPE_DEACTIVATE_BILLING_METER` | Deactivates a billing meter |
| `STRIPE_DELETE_APPLE_PAY_DOMAIN` | Tool to delete an Apple Pay domain from a Stripe account |
| `STRIPE_DELETE_APPS_SECRET` | Tool to delete a secret from the Stripe Secret Store by name and scope |
| `STRIPE_DELETE_COUPON` | Tool to delete a coupon from Stripe |
| `STRIPE_DELETE_CUSTOMER_BANK_ACCOUNT` | Deletes a bank account payment source from a customer |
| `STRIPE_DELETE_CUSTOMER_DISCOUNT` | Removes the currently applied discount on a customer |
| `STRIPE_DELETE_CUSTOMERS_CUSTOMER` | Permanently deletes a customer and cancels active subscriptions |
| `STRIPE_DELETE_CUSTOMER_SUBSCRIPTION` | Cancels a customer's subscription immediately |
| `STRIPE_DELETE_CUSTOMER_SUBSCRIPTION_DISCOUNT` | Removes currently applied discount from a customer's subscription |
| `STRIPE_DELETE_CUSTOMER_TAX_ID` | Deletes a customer's tax ID object |
| `STRIPE_DELETE_EPHEMERAL_KEY` | Immediately invalidate an ephemeral key |
| `STRIPE_DELETE_INVOICE` | Permanently deletes a draft invoice |
| `STRIPE_DELETE_INVOICEITEM` | Tool to delete an invoice item from Stripe |
| `STRIPE_DELETE_PLAN` | Tool to delete a plan from Stripe |
| `STRIPE_DELETE_PRODUCT` | Delete a product |
| `STRIPE_DELETE_PRODUCT_FEATURE` | Removes a feature from a product |
| `STRIPE_DELETE_SUBSCRIPTION_DISCOUNT` | Removes the currently applied discount on a subscription |
| `STRIPE_DELETE_SUBSCRIPTION_ITEM` | Deletes a subscription item without canceling the subscription |
| `STRIPE_DELETE_TAX_ID` | Deletes an existing tax ID object |
| `STRIPE_DELETE_TERMINAL_READER` | Permanently deletes a Terminal Reader object from your Stripe account |
| `STRIPE_DELETE_TEST_CLOCK` | Permanently deletes a test clock from Stripe's test environment |
| `STRIPE_DELETE_V1_INVOICES_VOID_AN_INVOICE` | Tool to void a finalized Stripe invoice |
| `STRIPE_DELETEV1_SUBSCRIPTIONS_LIST_SUBSCRIPTIONS` | Tool to cancel a Stripe subscription immediately |
| `STRIPE_DETACH_PAYMENT_FROM_INVOICE` | Tool to detach a payment from an invoice |
| `STRIPE_DETACH_PAYMENT_METHOD` | Detaches a PaymentMethod object from a Customer account |
| `STRIPE_DISABLE_EVENT_DESTINATION` | Disables a v2 Event Destination, preventing it from receiving events |
| `STRIPE_DOWNLOAD_QUOTE_PDF` | Tool to download the PDF for a finalized quote from Stripe |
| `STRIPE_EXPIRE_BILLING_CREDIT_GRANT` | Expires a billing credit grant immediately |
| `STRIPE_EXPIRE_CHECKOUT_SESSION` | Tool to expire an active Stripe Checkout Session |
| `STRIPE_FINALIZE_INVOICE` | Finalize a draft invoice so it becomes open/collectable (and immutable where required) |
| `STRIPE_FINALIZE_QUOTE` | Tool to finalize a quote in Stripe |
| `STRIPE_FIND_APPS_SECRET` | Tool to find a secret by name and scope in the Stripe Apps secret store |
| `STRIPE_FIND_TAX_ASSOCIATION` | Tool to find a tax association by PaymentIntent ID |
| `STRIPE_FUND_TEST_CASH_BALANCE` | Tool to fund a test mode cash balance for a customer |
| `STRIPE_GET_ACCOUNT` | Retrieves detailed information for the authenticated Stripe account |
| `STRIPE_GET_ACCOUNT_CAPABILITIES` | Retrieves a list of all capabilities for a connected Stripe account |
| `STRIPE_GET_ACCOUNT_CAPABILITY` | Retrieves information about a specific capability for a Stripe account |
| `STRIPE_GET_ACCOUNT_PERSON` | Retrieves an existing person associated with a Stripe account |
| `STRIPE_GET_ACCOUNT_PERSONS` | Retrieves a list of people associated with the account's legal entity |
| `STRIPE_GET_ACCOUNTS_ACCOUNT` | Retrieves the details of a Stripe account |
| `STRIPE_GET_ACCOUNT_TOKEN` | Tool to retrieve a v2 Account Token by its ID |
| `STRIPE_GET_ACTIVE_ENTITLEMENT` | Tool to retrieve an active entitlement describing customer access to a feature |
| `STRIPE_GET_APPLE_PAY_DOMAIN` | Retrieves details about a previously registered Apple Pay domain |
| `STRIPE_GET_BALANCE_SETTINGS` | Tool to retrieve balance settings for a Stripe account |
| `STRIPE_GET_BALANCE_TRANSACTION` | Retrieves the balance transaction with the given ID |
| `STRIPE_GET_BILLING_ALERT` | Retrieves a billing alert by its unique identifier |
| `STRIPE_GET_BILLING_CREDIT_BALANCE_SUMMARY` | Retrieves the credit balance summary for a customer in Stripe Billing |
| `STRIPE_GET_BILLING_CREDIT_BALANCE_TRANSACTIONS_ID` | Retrieves a credit balance transaction by its unique identifier |
| `STRIPE_GET_BILLING_CREDIT_GRANTS` | Tool to retrieve a paginated list of billing credit grants |
| `STRIPE_GET_BILLING_CREDIT_GRANTS_ID` | Retrieves a billing credit grant by its unique identifier |
| `STRIPE_GET_BILLING_METERS` | Tool to retrieve a list of billing meters from Stripe |
| `STRIPE_GET_BILLING_METERS_ID` | Retrieves a billing meter by its unique identifier |
| `STRIPE_GET_BILLING_PORTAL_CONFIGURATIONS` | Tool to list billing portal configurations |
| `STRIPE_GET_BILLING_PORTAL_CONFIGURATIONS_CONFIGURATION` | Tool to retrieve a billing portal configuration from Stripe |
| `STRIPE_GET_CHARGES_CHARGE_DISPUTE` | Tool to retrieve a dispute for a specified charge |
| `STRIPE_GET_CHARGES_CHARGE_REFUNDS_REFUND` | Tool to retrieve the details of an existing refund within a specific charge |
| `STRIPE_GET_CHECKOUT_SESSIONS_SESSION_LINE_ITEMS` | Tool to retrieve line items for a Checkout Session |
| `STRIPE_GET_CLIMATE_PRODUCTS_PRODUCT` | Tool to retrieve details of a specific Stripe Climate product |
| `STRIPE_GET_CLIMATE_SUPPLIERS_SUPPLIER` | Retrieves detailed information about a specific Stripe Climate carbon removal supplier |
| `STRIPE_GET_CONFIRMATION_TOKENS_CONFIRMATION_TOKEN` | Tool to retrieve an existing ConfirmationToken object by its ID |
| `STRIPE_GET_COUNTRY_SPECS_COUNTRY` | Retrieves configuration details for a specific country, including supported payment methods, required verification fields, and supported currencies |
| `STRIPE_GET_COUPON` | Retrieves full details for an existing Stripe coupon using its unique ID |
| `STRIPE_GET_CREDIT_NOTES_CREDIT_NOTE_LINES` | Retrieves the paginated list of line items for a specific credit note |
| `STRIPE_GET_CREDIT_NOTES_ID` | Retrieves a credit note by its unique identifier |
| `STRIPE_GET_CREDIT_NOTES_PREVIEW` | Tool to preview a credit note without creating it in Stripe |
| `STRIPE_GET_CREDIT_NOTES_PREVIEW_LINES` | Tool to retrieve a credit note preview's line items from Stripe |
| `STRIPE_GET_CUSTOMERS_CASH_BALANCE_TRANSACTIONS` | Tool to retrieve a specific cash balance transaction that updated a customer's cash balance |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_BALANCE_TRANSACTIONS` | Tool to list customer balance transactions that updated a customer's balance |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_BALANCE_TXNS_TXN` | Retrieves a specific customer balance transaction that updated the customer's balances |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_BANK_ACCOUNTS` | Tool to fetch all bank accounts linked to a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_BANK_ACCOUNTS_ID` | Retrieves details about a specific bank account stored on a Stripe customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_CARDS` | Tool to list all cards for a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_CARDS_ID` | Retrieves details about a specific card for a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_CASH_BALANCE` | Tool to retrieve a customer's cash balance |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_CASH_BALANCE_TRANSACTIONS` | Tool to retrieve a list of cash balance transactions for a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_DISCOUNT` | Tool to retrieve the discount currently active on a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_PAYMENT_METHODS` | Retrieves a list of payment methods for a given customer, supporting type filtering and pagination |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_PAYMENT_METHODS_PAYMENT_METHOD` | Tool to retrieve a specific PaymentMethod object for a given Customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_SOURCES` | Tool to list sources for a specified customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_SUBS_SUB_EXPOSED_ID` | Tool to retrieve a specific subscription for a customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_SUBS_SUB_EXPOSED_ID_DISCOUNT` | Tool to retrieve the discount currently applied to a customer's subscription |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_TAX_IDS` | Tool to retrieve all tax IDs for a specific Stripe customer |
| `STRIPE_GET_CUSTOMERS_CUSTOMER_TAX_IDS_ID` | Tool to retrieve a specific tax ID for a customer |
| `STRIPE_GET_ENTITLEMENTS_ACTIVE_ENTITLEMENTS` | Tool to retrieve active entitlements for a customer |
| `STRIPE_GET_ENTITLEMENTS_FEATURES_ID` | Tool to retrieve a feature by ID from Stripe |
| `STRIPE_GET_EVENTS` | Retrieves a list of Stripe events from the past 30 days with filtering and pagination |
| `STRIPE_GET_EVENTS_ID` | Retrieves event details for events created within the last 30 days |
| `STRIPE_GET_FILE_LINKS_LINK` | Retrieves the details of an existing file link |
| `STRIPE_GET_FILES_FILE` | Tool to retrieve details of an existing file object by its unique identifier |
| `STRIPE_GET_FINANCIAL_CONNECTIONS_SESSIONS_SESSION` | Retrieves the details of a Financial Connections Session |
| `STRIPE_GET_FX_QUOTE` | Retrieve a specific FX (foreign exchange) Quote by its ID |
| `STRIPE_GET_INVOICEITEMS_INVOICEITEM` | Tool to retrieve the details of an invoice item using its unique identifier |
| `STRIPE_GET_INVOICE_PAYMENTS_ID` | Tool to retrieve details of a specific Stripe invoice payment by ID |
| `STRIPE_GET_INVOICES_INVOICE` | Tool to retrieve a specific invoice by ID |
| `STRIPE_GET_INVOICES_INVOICE_LINES` | Tool to retrieve a paginated list of line items for a specific invoice |
| `STRIPE_GET_LINKED_ACCOUNT` | Retrieves the details of a Linked Account object by its unique identifier |
| `STRIPE_GET_MANDATE` | Tool to retrieve a Stripe mandate by ID |
| `STRIPE_GET_PAYMENT_ATTEMPT_RECORDS_ID` | Tool to retrieve a specific Payment Attempt Record by ID |
| `STRIPE_GET_PAYMENT_INTENT_AMOUNT_DETAILS_LINE_ITEMS` | Tool to retrieve paginated line items for a PaymentIntent |
| `STRIPE_GET_PAYMENT_LINK` | Tool to retrieve details of an existing Stripe payment link by ID |
| `STRIPE_GET_PAYMENT_LINKS_PAYMENT_LINK_LINE_ITEMS` | Tool to retrieve paginated line items for a payment link |
| `STRIPE_GET_PAYMENT_METHOD` | Retrieves the details of a PaymentMethod object by its unique identifier |
| `STRIPE_GET_PAYMENT_METHOD_CONFIGURATION` | Tool to retrieve a specific payment method configuration by its unique identifier |
| `STRIPE_GET_PAYMENT_METHOD_DOMAIN` | Retrieves details of an existing payment method domain |
| `STRIPE_GET_PAYMENT_RECORD` | Tool to retrieve a Payment Record from Stripe |
| `STRIPE_GET_PAYOUT` | Tool to retrieve details of an existing Stripe payout |
| `STRIPE_GET_PLAN` | Tool to retrieve a specific Stripe plan by its unique identifier |
| `STRIPE_GET_PRICES_PRICE` | Retrieves detailed information for a specific Stripe price using its unique ID |
| `STRIPE_GET_PRODUCTS_ID` | Retrieves detailed information for an existing Stripe product using its unique product ID |
| `STRIPE_GET_PRODUCTS_PRODUCT_FEATURES_ID` | Retrieves a specific product feature by its ID |
| `STRIPE_GET_PROMOTION_CODES` | Retrieves a list of promotion codes from a Stripe account with optional filters for active status, code value, coupon association, and customer restri |
| `STRIPE_GET_QUOTES_QUOTE` | Tool to retrieve a quote by ID |
| `STRIPE_GET_QUOTES_QUOTE_COMPUTED_UPFRONT_LINE_ITEMS` | Tool to retrieve computed upfront line items for a quote |
| `STRIPE_GET_QUOTES_QUOTE_LINE_ITEMS` | Tool to retrieve a paginated list of line items for a quote |
| `STRIPE_GET_RADAR_VALUE_LIST` | Retrieves a specific Stripe Radar value list by its identifier |
| `STRIPE_GET_RADAR_VALUE_LIST_ITEMS` | Tool to list all value list items from a Stripe Radar value list |
| `STRIPE_GET_REFUNDS_REFUND` | Tool to retrieve details of a specific Stripe refund by ID |
| `STRIPE_GET_REPORTING_REPORT_RUNS_REPORT_RUN` | Retrieves details of an existing Report Run object |
| `STRIPE_GET_REPORTING_REPORT_TYPE` | Tool to retrieve details of a specific Stripe report type by ID |
| `STRIPE_GET_SETUP_ATTEMPTS` | Tool to list SetupAttempts associated with a SetupIntent |
| `STRIPE_GET_SETUP_INTENT` | Retrieves details of a SetupIntent by its ID; `client_secret` is required if a publishable API key is used |
| `STRIPE_GET_SHIPPING_RATE` | Tool to retrieve details of a specific Stripe shipping rate by its unique ID |
| `STRIPE_GET_SUBSCRIPTION` | Retrieves detailed information for an existing Stripe subscription using its unique ID |
| `STRIPE_GET_SUBSCRIPTION_ITEM` | Retrieves detailed information for a specific subscription item using its unique ID |
| `STRIPE_GET_SUBSCRIPTION_SCHEDULES_SCHEDULE` | Retrieve a subscription schedule using its unique identifier |
| `STRIPE_GET_TAX_CALCULATION` | Retrieves a Tax Calculation object by its unique ID |
| `STRIPE_GET_TAX_CALCULATIONS_CALCULATION_LINE_ITEMS` | Retrieves line items of a tax calculation as a paginated collection |
| `STRIPE_GET_TAX_CODE` | Retrieves the details of an existing tax code |
| `STRIPE_GET_TAX_ID` | Retrieves an account or customer tax ID object |
| `STRIPE_GET_TAX_RATE` | Tool to retrieve the details of an existing tax rate |
| `STRIPE_GET_TAX_REGISTRATION` | Tool to retrieve a specific tax registration configured for your Stripe account |
| `STRIPE_GET_TAX_SETTINGS` | Retrieves Tax Settings for a merchant |
| `STRIPE_GET_TAX_TRANSACTION` | Retrieves a Tax Transaction object by ID |
| `STRIPE_GET_TAX_TRANSACTIONS_TRANSACTION_LINE_ITEMS` | Retrieves the line items of a committed standalone tax transaction |
| `STRIPE_GET_TERMINAL_CONFIGURATION` | Tool to retrieve a specific Terminal Configuration object from Stripe |
| `STRIPE_GET_TERMINAL_LOCATION` | Tool to retrieve a Terminal Location object by ID |
| `STRIPE_GET_TERMINAL_READER` | Tool to retrieve a Terminal Reader object by ID |
| `STRIPE_GET_TEST_CLOCK` | Tool to retrieve a test clock by ID |
| `STRIPE_GET_TOKEN` | Retrieves the token with the given ID |
| `STRIPE_GET_TRANSFER_REVERSAL` | Retrieves a transfer reversal by its ID and the associated transfer ID |
| `STRIPE_GET_UPCOMING_INVOICE_LINE_ITEMS` | Tool to retrieve a paginated list of line items for an upcoming invoice preview |
| `STRIPE_GET_V1_CUSTOMERS_SEARCH_CUSTOMERS` | Tool to search for Stripe customers using Stripe's Search Query Language |
| `STRIPE_GET_V1_DISPUTES_DISPUTES` | Retrieves detailed information for an existing Stripe dispute by ID |
| `STRIPE_GET_V1_INVOICE_PAYMENTS_OVERVIEW2` | Tool to list invoice payments in Stripe with pagination and filtering options |
| `STRIPE_GET_V1_PAYMENT_METHOD_CONFIGS_LIST_PAYMENT_METHOD2` | Tool to list all payment method configurations in a Stripe account |
| `STRIPE_GET_V1_PAYMENT_METHOD_DOMAINS` | Tool to retrieve list of payment method domains registered with Stripe account |
| `STRIPE_GET_V1_PAYMENT_METHODS_PAYMENT_METHODS2` | Tool to retrieve a list of PaymentMethods with filtering and pagination support |
| `STRIPE_GET_V1_RADAR_EARLY_FRAUD_WARNINGS_OVERVIEW` | Returns a list of early fraud warnings |
| `STRIPE_GET_V1_RADAR_VALUE_LISTS_OVERVIEW_RADAR_VALUE_LISTS` | Tool to retrieve an overview of Radar value lists |
| `STRIPE_GET_V1_REPORTING_REPORT_TYPES_OVERVIEW_REPORTING` | Tool to list all available Stripe report types |
| `STRIPE_GET_V1_SHIPPING_RATES_OVERVIEW2` | Tool to retrieve an overview of shipping rates from Stripe |
| `STRIPE_GET_V1_SUBSCRIPTION_SCHEDULES_OVERVIEW2` | Retrieves a list of subscription schedules with optional filtering and pagination capabilities |
| `STRIPE_GET_V1_TAX_CODES_TAX_CODE2` | Tool to retrieve all tax codes available to add to Products for specific tax calculations |
| `STRIPE_GET_V1_TAX_IDS_OVERVIEW2` | Tool to retrieve a list of tax IDs with pagination support |
| `STRIPE_GET_V1_TAX_RATES_TAX_RATE2` | Tool to retrieve all tax rates with pagination support |
| `STRIPE_GET_V2_CORE_EVENTS_RETRIEVE_AN_EVENT` | Retrieves detailed information about a specific event from Stripe V2 Core Events API |
| `STRIPE_LIST_ALL_SUBSCRIPTION_ITEM_PERIOD_SUMMARIES` | Tool to list all subscription item period summaries |
| `STRIPE_LIST_APPLE_PAY_DOMAINS` | Retrieves a list of Apple Pay domains registered with Stripe |
| `STRIPE_LIST_APPLICATION_FEES` | Returns a list of application fees you've previously collected, sorted by creation date descending (newest first) |
| `STRIPE_LIST_APPS_SECRETS` | Tool to list all secrets stored on the given scope |
| `STRIPE_LIST_BALANCE_TRANSACTIONS` | Lists all balance transactions for the connected Stripe account |
| `STRIPE_LIST_BILLING_ALERTS` | Tool to retrieve a paginated list of billing alerts |
| `STRIPE_LIST_BILLING_CREDIT_BALANCE_TRANSACTIONS` | Tool to retrieve a paginated list of credit balance transactions with optional filtering |
| `STRIPE_LIST_CHARGE_REFUNDS` | Lists all refunds for a specific charge in Stripe |
| `STRIPE_LIST_CHARGES` | Retrieves a list of Stripe charges with filtering and pagination; use valid cursor IDs from previous responses for pagination, and note that charges a |
| `STRIPE_LIST_CHECKOUT_SESSIONS` | Tool to retrieve a list of Stripe Checkout Sessions with pagination support |
| `STRIPE_LIST_CLIMATE_ORDERS` | Tool to list all Climate order objects |
| `STRIPE_LIST_CLIMATE_PRODUCTS` | Tool to retrieve a list of available Stripe Climate products |
| `STRIPE_LIST_CLIMATE_SUPPLIERS` | Tool to retrieve a list of available Stripe Climate supplier objects for carbon removal |
| `STRIPE_LIST_COUNTRY_SPECS` | Retrieves a list of country specifications available in the Stripe API |
| `STRIPE_LIST_COUPONS` | Retrieves a list of discount coupons from a Stripe account, supporting pagination via `limit`, `starting_after`, and `ending_before` |
| `STRIPE_LIST_CREDIT_NOTES` | Lists Stripe credit notes with optional filtering by customer, invoice, or customer account, and pagination support |
| `STRIPE_LIST_CUSTOMERS` | Retrieves a list of Stripe customers, with options to filter by email, creation date, or test clock, and support for pagination |
| `STRIPE_LIST_CUSTOMER_SUBSCRIPTIONS` | Tool to list all active subscriptions for a customer in Stripe |
| `STRIPE_LIST_DISPUTES` | Tool to list all disputes from a Stripe account |
| `STRIPE_LIST_ENTITLEMENTS_FEATURES` | Retrieves a paginated list of entitlements features from Stripe |
| `STRIPE_LIST_FILE_LINKS` | Tool to retrieve a list of Stripe file links |
| `STRIPE_LIST_FILES` | Tool to retrieve a list of files that your account has access to |
| `STRIPE_LIST_FINANCIAL_CONNECTIONS_ACCOUNTS` | Tool to list Financial Connections Account objects representing external financial accounts |
| `STRIPE_LIST_FORWARDING_REQUESTS` | Lists ForwardingRequest objects from Stripe's Vault and Forward API |
| `STRIPE_LIST_FX_QUOTES` | Retrieves a list of FX quotes that have been issued, with the most recent appearing first |
| `STRIPE_LIST_INVOICEITEMS` | Retrieves a paginated list of Stripe invoice items |
| `STRIPE_LIST_INVOICE_PAYMENTS` | Tool to list all payments for invoices in Stripe |
| `STRIPE_LIST_INVOICE_RENDERING_TEMPLATES` | Tool to list all invoice rendering templates ordered by creation date |
| `STRIPE_LIST_INVOICES` | Retrieves a list of Stripe invoices, filterable by various criteria and paginatable using invoice ID cursors obtained from previous responses |
| `STRIPE_LIST_METER_EVENT_SUMMARIES` | Tool to retrieve billing meter event summaries for a customer within a time range |
| `STRIPE_LIST_PAYMENT_ATTEMPT_RECORDS` | Tool to list payment attempt records for a specified payment record |
| `STRIPE_LIST_PAYMENT_INTENTS` | Tool to list PaymentIntents from Stripe |
| `STRIPE_LIST_PAYMENT_LINKS` | Retrieves a list of payment links from Stripe, sorted by creation date in descending order by default |
| `STRIPE_LIST_PAYOUTS` | Lists Stripe payouts sent to external accounts or received from Stripe, sorted by creation date descending (newest first), with optional filtering by |
| `STRIPE_LIST_PLANS` | Tool to list all billing plans from Stripe account |
| `STRIPE_LIST_PRICES` | Tool to list Stripe prices |
| `STRIPE_LIST_PRODUCTS` | Retrieves a list of Stripe products, with optional filtering and pagination; `starting_after`/`ending_before` cursors must be valid product IDs from a |
| `STRIPE_LIST_PRODUCTS_PRODUCT_FEATURES` | Retrieves a list of features attached to a product |
| `STRIPE_LIST_PROMOTION_CODES` | Tool to retrieve a list of promotion codes from Stripe |
| `STRIPE_LIST_QUOTES` | Retrieves a list of Stripe quotes with pagination support |
| `STRIPE_LIST_RADAR_EARLY_FRAUD_WARNINGS` | Tool to list all early fraud warnings from Stripe Radar |
| `STRIPE_LIST_RADAR_REVIEWS` | Returns a list of Radar Review objects that have open set to true, sorted in descending order by creation date |
| `STRIPE_LIST_REFUNDS` | Lists Stripe refunds, sorted by creation date descending (newest first), with optional filtering by charge or payment_intent and pagination support |
| `STRIPE_LIST_REPORTING_REPORT_RUNS` | Lists Stripe Report Runs, sorted by creation date descending (newest first) |
| `STRIPE_LIST_REVIEWS` | Retrieves a list of open Stripe reviews with pagination support |
| `STRIPE_LIST_SETUP_ATTEMPTS` | Tool to list SetupAttempts associated with a SetupIntent |
| `STRIPE_LIST_SETUP_INTENTS` | Tool to list SetupIntents from Stripe |
| `STRIPE_LIST_SIGMA_SCHEDULED_QUERY_RUNS` | Tool to list all Sigma scheduled query runs |
| `STRIPE_LIST_SUBSCRIPTION_ITEMS` | List all subscription items for a given subscription |
| `STRIPE_LIST_SUBSCRIPTIONS` | Retrieves a list of Stripe subscriptions, optionally filtered by various criteria such as customer, price, status, collection method, and date ranges, |
| `STRIPE_LIST_TAX_CODES` | Retrieves a paginated list of globally available, predefined Stripe tax codes used for classifying products and services in Stripe Tax |
| `STRIPE_LIST_TAX_RATES` | Retrieves a list of tax rates, which are returned sorted by creation date in descending order |
| `STRIPE_LIST_TAX_REGISTRATIONS` | Retrieves a paginated list of tax registrations |
| `STRIPE_LIST_TERMINAL_CONFIGURATIONS` | Tool to retrieve a list of Terminal Configuration objects from Stripe |
| `STRIPE_LIST_TERMINAL_LOCATIONS` | Retrieves a list of Stripe terminal locations with pagination support |
| `STRIPE_LIST_TERMINAL_READERS` | Tool to list all Stripe Terminal Readers with optional filtering |
| `STRIPE_LIST_TEST_CLOCKS` | Retrieves a paginated list of test clocks |
| `STRIPE_LIST_TOPUPS` | Tool to retrieve a list of existing top-ups from Stripe |
| `STRIPE_LIST_TRANSFERS` | List all transfers sent to connected accounts |
| `STRIPE_LIST_V2_CORE_EVENT_DESTINATIONS` | Retrieves a list of event destinations from Stripe V2 Core Events API |
| `STRIPE_LIST_V2_CORE_EVENTS` | Tool to list v2 core events from Stripe |
| `STRIPE_MARK_INVOICE_UNCOLLECTIBLE` | Tool to mark a Stripe invoice as uncollectible for bad debt accounting purposes |
| `STRIPE_MIGRATE_SUBSCRIPTION` | Migrate a subscription from classic to flexible billing mode |
| `STRIPE_PAY_INVOICE` | Tool to pay an invoice manually outside the normal collection schedule |
| `STRIPE_POST_BILLING_CREDIT_GRANTS_VOID_CREDIT_GRANT` | Voids a billing credit grant, preventing it from being applied to future invoices |
| `STRIPE_POST_CHARGES_CHARGE` | Updates a Stripe charge with the specified parameters; unspecified fields remain unchanged |
| `STRIPE_POST_CUSTOMERS_CUSTOMER_SUBS_SUB_EXPOSED_ID` | Tool to update a customer's subscription |
| `STRIPE_POST_CUSTOMERS_SOURCES_VERIFY_THE_BANK_ACCOUNT` | Verifies a bank account for a customer using microdeposit amounts |
| `STRIPE_POST_FILE_LINKS_LINK` | Tool to update an existing file link in Stripe |
| `STRIPE_POST_INVOICES_INVOICE_VOID` | Voids a finalized invoice and maintains a papertrail |
| `STRIPE_POST_PAYMENT_RECORDS_REPORT_PAYMENT` | Tool to report a payment record in terminal state or for initialization |
| `STRIPE_POST_SETUP_INTENTS_INTENT` | Updates a SetupIntent object to modify configuration parameters and metadata |
| `STRIPE_POST_SUBSCRIPTION_ITEMS_ITEM` | Tool to update a subscription item's plan, quantity, billing thresholds, discounts, or metadata |
| `STRIPE_POST_SUBSCRIPTIONS_SUBSCRIPTION_EXPOSED_ID` | Tool to update an existing Stripe subscription with specified parameters |
| `STRIPE_POST_TERMINAL_CONFIGURATIONS_CONFIGURATION` | Tool to update a Stripe Terminal Configuration |
| `STRIPE_POST_TERMINAL_READERS_READER_PROCESS_PAYMENT_INTENT` | Initiates a payment flow on a Stripe Terminal Reader to process a PaymentIntent |
| `STRIPE_POST_TERMINAL_READERS_READER_SET_READER_DISPLAY` | Configures a Stripe terminal reader to display cart information on screen |
| `STRIPE_POST_TERMINAL_READERS_SET_READER_DISPLAY` | Tool to configure a terminal reader's display to show cart details |
| `STRIPE_SEARCH_PRODUCTS` | Tool to search for products using Stripe's Search Query Language |
| `STRIPE_POST_V1_ACCOUNTS_CAPABILITIES_CAPABILITIES` | Updates an existing account capability for a Stripe connected account |
| `STRIPE_POST_V1_BALANCE_SETTINGS_OVERVIEW` | Tool to update balance settings for a Stripe account |
| `STRIPE_POST_V1_BILLING_PORTAL_CONFIGS_OVERVIEW_BILLING` | Tool to update an existing billing portal configuration in Stripe |
| `STRIPE_POST_V1_CHECKOUT_SESSIONS_RETRIEVE_A_CHECKOUT` | Tool to update and retrieve a Checkout Session object from Stripe |
| `STRIPE_POST_V1_CREDIT_NOTES_CREDIT_NOTE2` | Tool to update an existing credit note in Stripe by modifying its memo or metadata |
| `STRIPE_POST_V1_CUSTOMERS_FUNDING_INSTRUCTIONS_FUND_A_TEST` | Creates or retrieves funding instructions for a customer cash balance via bank transfer |
| `STRIPE_POST_V1_CUSTOMERS_SEARCH_CUSTOMERS` | Tool to search for Stripe customers using a search query |
| `STRIPE_POST_V1_INVOICES_FINALIZE_VOID_AN_INVOICE` | Voids a finalized invoice and maintains a papertrail |
| `STRIPE_POST_V1_INVOICES_LINES_OVERVIEW` | Updates an invoice's line item before finalization |
| `STRIPE_POST_V1_INVOICES_REMOVE_LINES_OVERVIEW` | Tool to remove multiple line items from a draft Stripe invoice |
| `STRIPE_POST_V1_INVOICES_SEND_VOID_AN_INVOICE` | Tool to void a finalized Stripe invoice |
| `STRIPE_POST_V1_INVOICES_VOID_AN_INVOICE` | Tool to permanently void a finalized Stripe invoice |
| `STRIPE_POST_V1_PAYMENT_METHOD_CONFIGS_LIST_PAYMENT_METHOD2` | Updates a payment method configuration to control which payment methods are displayed at checkout |
| `STRIPE_POST_V1_PAYMENT_METHOD_DOMAINS_PAYMENT_METHOD` | Updates an existing payment method domain to enable or disable it |
| `STRIPE_POST_V1_PAYMENT_RECORDS_REPORT_ATTEMPT` | Tool to report a payment attempt on a Stripe Payment Record |
| `STRIPE_POST_V1_PAYMENT_RECORDS_REPORT_CANCELED` | Tool to report that the most recent payment attempt was canceled |
| `STRIPE_POST_V1_PAYMENT_RECORDS_REPORT_GUARANTEED` | Reports that a payment attempt was guaranteed for a specific Payment Record |
| `STRIPE_POST_V1_PAYMENT_RECORDS_REPORT_INFO` | Tool to report additional payment attempt information for a payment record |
| `STRIPE_POST_V1_PAYMENT_RECORDS_REPORT_REFUND_OVERVIEW` | Reports that the most recent payment attempt on a Payment Record was refunded |
| `STRIPE_POST_V1_PAYOUTS_RETRIEVE_A_PAYOUT` | Updates a payout's metadata and returns the updated payout object |
| `STRIPE_POST_V1_PLANS_OVERVIEW` | Tool to update a Stripe plan by setting passed parameter values |
| `STRIPE_POST_V1_PROMOTION_CODES_PROMOTION_CODE` | Updates an existing promotion code |
| `STRIPE_POST_V1_SHIPPING_RATES_OVERVIEW2` | Tool to update an existing Stripe shipping rate |
| `STRIPE_POST_V1_SUBSCRIPTION_SCHEDULES_OVERVIEW2` | Tool to update an existing subscription schedule with new phases, settings, metadata, and end behavior |
| `STRIPE_POST_V1_SUBSCRIPTION_SCHEDULES_RELEASE_OVERVIEW` | Tool to release a subscription schedule |
| `STRIPE_POST_V1_SUBSCRIPTIONS_LIST_SUBSCRIPTIONS` | Updates an existing Stripe subscription's properties including metadata, description, payment method, billing settings, trial periods, and cancellatio |
| `STRIPE_POST_V1_TAX_RATES_TAX_RATE2` | Tool to update an existing Stripe tax rate |
| `STRIPE_POST_V2_BILLING_METER_EVENT_ADJUSTMENTS_METER_EVENT` | Creates a billing meter event adjustment to cancel a previously sent meter event |
| `STRIPE_PRESENT_PAYMENT_METHOD` | Tool to present a payment method on a simulated terminal reader for testing purposes |
| `STRIPE_PROCESS_SETUP_INTENT` | Initiates a SetupIntent flow on a Stripe Terminal Reader to save payment details |
| `STRIPE_REACTIVATE_BILLING_METER` | Reactivates a deactivated billing meter |
| `STRIPE_REPORT_PAYMENT_ATTEMPT_FAILED` | Reports that a recent payment attempt on a Payment Record has failed |
| `STRIPE_RESUME_SUBSCRIPTION` | Resumes a paused Stripe subscription with billing cycle and proration options |
| `STRIPE_RETRIEVE_BALANCE` | Retrieves the complete current balance details for the connected Stripe account |
| `STRIPE_RETRIEVE_CHARGE` | Retrieves full details for an existing Stripe charge using its unique ID |
| `STRIPE_RETRIEVE_CHECKOUT_SESSION` | Tool to retrieve a Checkout Session object from Stripe |
| `STRIPE_RETRIEVE_CUSTOMER` | Retrieves detailed information for an existing Stripe customer using their unique customer ID |
| `STRIPE_RETRIEVE_PAYMENT_INTENT` | Retrieves a PaymentIntent by its ID; `client_secret` is required if a publishable API key is used |
| `STRIPE_RETRIEVE_PROMOTION_CODE` | Tool to retrieve a Stripe promotion code by its ID |
| `STRIPE_RETRIEVE_UPCOMING_INVOICE` | Tool to preview the upcoming invoice for a customer, showing all pending charges including subscription renewals and invoice items |
| `STRIPE_SEARCH_CHARGES` | Search charges using Stripe's Search Query Language |
| `STRIPE_SEARCH_CUSTOMERS` | Retrieves a list of Stripe customers matching a search query that adheres to Stripe's Search Query Language |
| `STRIPE_SEARCH_INVOICES` | Searches for invoices using Stripe's Search Query Language |
| `STRIPE_SEARCH_PAYMENT_INTENTS` | Searches for PaymentIntents using Stripe's Search Query Language |
| `STRIPE_SEARCH_PRICES` | Search for prices using Stripe's Search Query Language |
| `STRIPE_UPDATE_CUSTOMER_SOURCE` | Update a specified source for a given customer |
| `STRIPE_SEARCH_SUBSCRIPTIONS` | Searches for subscriptions using Stripe's Search Query Language |
| `STRIPE_SEND_INVOICE` | Tool to manually send a finalized Stripe invoice to the customer outside the automatic billing schedule |
| `STRIPE_SET_READER_DISPLAY` | Configures a Stripe Terminal reader to display cart information on its screen |
| `STRIPE_SET_TERMINAL_READER_DISPLAY` | Tool to set the display on a Stripe Terminal reader to show cart details |
| `STRIPE_SUCCEED_TEST_TERMINAL_READER_INPUT_COLLECTION` | Simulates successful completion of an ongoing input collection on a Terminal reader |
| `STRIPE_TIMEOUT_TEST_TERMINAL_READER_INPUT_COLLECTION` | Simulate an input collection timeout on a Stripe Terminal reader |
| `STRIPE_UPDATE_APPLICATION_FEE_REFUND` | Updates an application fee refund by its fee ID and refund ID |
| `STRIPE_UPDATE_BILLING_CREDIT_GRANT` | Updates an existing billing credit grant |
| `STRIPE_UPDATE_BILLING_METER` | Tool to update a billing meter's display name |
| `STRIPE_UPDATE_BILLING_PORTAL_CONFIGURATION` | Update a billing portal configuration |
| `STRIPE_UPDATE_CASH_BALANCE` | Tool to update a customer's cash balance settings in Stripe |
| `STRIPE_UPDATE_CHARGE` | Tool to update a Stripe charge object with provided parameters |
| `STRIPE_UPDATE_CHARGE_DISPUTE` | Tool to update metadata on a charge's dispute |
| `STRIPE_UPDATE_CHARGE_REFUND` | Tool to update a specified refund within a charge |
| `STRIPE_UPDATE_CHECKOUT_SESSION` | Tool to update a Stripe Checkout Session dynamically |
| `STRIPE_UPDATE_COUPON` | Updates a Stripe coupon's metadata, name, or currency options |
| `STRIPE_UPDATE_CUSTOMER` | Updates an existing Stripe customer, identified by customer_id, with only the provided details; unspecified fields remain unchanged |
| `STRIPE_UPDATE_CUSTOMER_BALANCE_TXN` | Updates an existing customer balance transaction's description and metadata |
| `STRIPE_UPDATE_CUSTOMER_BANK_ACCOUNT` | Updates a specified bank account for a given customer |
| `STRIPE_UPDATE_CUSTOMER_BANK_ACCOUNT_SOURCE` | Updates a bank account source attached to a customer |
| `STRIPE_UPDATE_CUSTOMER_CARD` | Tool to update a card for a specified customer |
| `STRIPE_UPDATE_CUSTOMER_SUBSCRIPTION` | Tool to update a subscription on a customer in Stripe |
| `STRIPE_UPDATE_DISPUTE` | Tool to update a Stripe dispute by submitting evidence or updating metadata |
| `STRIPE_UPDATE_ENTITLEMENT_FEATURE` | Tool to update a feature's properties or deactivate it |
| `STRIPE_UPDATE_EVENT_DESTINATION` | Updates a v2 Event Destination with new values for specified parameters |
| `STRIPE_UPDATE_EXTERNAL_ACCOUNT` | Updates the metadata, account holder name, account holder type of an external bank account or card belonging to a connected account and optionally set |
| `STRIPE_UPDATE_INVOICE` | Updates a draft Stripe invoice |
| `STRIPE_UPDATE_INVOICEITEM` | Updates an invoice item on a draft invoice |
| `STRIPE_UPDATE_INVOICE_LINES` | Tool to bulk update multiple line items on a draft invoice |
| `STRIPE_UPDATE_PAYMENT_INTENT` | Updates a Stripe PaymentIntent with new values for specified parameters; note that if `currency` is updated, `amount` might also be required, and cert |
| `STRIPE_UPDATE_PAYMENT_LINK` | Updates an existing payment link with new configuration details |
| `STRIPE_UPDATE_PAYMENT_METHOD` | Updates an existing PaymentMethod object in Stripe |
| `STRIPE_UPDATE_PRICE` | Updates a Stripe price by setting passed parameter values; unspecified parameters remain unchanged |
| `STRIPE_UPDATE_PRODUCT` | Tool to update an existing product in Stripe |
| `STRIPE_UPDATE_PROMOTION_CODE` | Updates an existing Stripe promotion code by setting the values of the parameters passed |
| `STRIPE_UPDATE_QUOTE` | Tool to update an existing Stripe quote with new values |
| `STRIPE_UPDATE_SUBSCRIPTION` | Updates an existing, non-canceled Stripe subscription by its ID, ensuring all referenced entity IDs (e.g., prices, coupons) are valid and automatic ta |
| `STRIPE_UPDATE_SUBSCRIPTION_SCHEDULE` | Tool to update an existing subscription schedule in Stripe |
| `STRIPE_UPDATE_TAX_REGISTRATION` | Tool to update an existing tax registration in Stripe |
| `STRIPE_UPDATE_TAX_SETTINGS` | Updates Stripe Tax Settings parameters used in tax calculations |
| `STRIPE_UPDATE_TERMINAL_LOCATION` | Updates a Terminal Location by modifying specified parameters |
| `STRIPE_UPDATE_TERMINAL_READER` | Tool to update a Terminal Reader object by setting parameter values |
| `STRIPE_VALIDATE_PAYMENT_METHOD_DOMAIN` | Tool to validate an existing payment method domain in Stripe to activate payment methods |
| `STRIPE_VERIFY_MICRODEPOSITS` | Verifies microdeposits on a SetupIntent object to confirm bank account ownership |
| `STRIPE_VERIFY_MICRODEPOSITS_PAYMENT_INTENT` | Verifies microdeposits on a PaymentIntent object by matching deposit amounts or descriptor code |
| `STRIPE_VOID_CREDIT_NOTE` | Marks a credit note as void |
| `STRIPE_VOID_INVOICE` | Tool to void a finalized Stripe invoice |
| `STRIPE_WHO_AM_I` | Return the connected Stripe account (account id, dashboard name) |
