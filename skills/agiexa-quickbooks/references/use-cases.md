# QuickBooks use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/quickbooks

## Reconcile Shopify Sales With QuickBooks

Compare Shopify orders and sales totals against QuickBooks accounting records to identify missing transactions and unexplained differences.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_QUERY_INVOICES`, `QUICKBOOKS_GET_TRANSACTION_LIST_REPORT`, `QUICKBOOKS_GET_SALES_RECEIPT`, `QUICKBOOKS_QUERY_PAYMENTS`

> Reconcile my Shopify sales with my QuickBooks accounting records for the selected reporting period. Use Shopify orders, refunds, discounts, taxes, shipping charges, and payment information alongside available QuickBooks invoices, sales receipts, payments, and transaction reports. Match transactions using order references, invoice numbers, amounts, dates, and other available identifiers. Identify matched records, possible missing records, duplicate-looking entries, and amount differences. Account for timing differences and distinguish gross sales from recognized accounting revenue. Produce a reconciliation table with supporting evidence and recommended next steps. Do not create or modify accounting records until I approve the exact proposed changes.

## Match Shopify Refunds Against Accounting

Verify that Shopify refunds correspond to appropriate QuickBooks refund receipts, credit memos, and related accounting entries.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_REFUND_RECEIPT`, `QUICKBOOKS_GET_CREDIT_MEMO`, `QUICKBOOKS_GET_TRANSACTION_LIST_REPORT`, `QUICKBOOKS_CREATE_REFUND_RECEIPT`

> Review refunds from my Shopify store for the selected period and compare them with relevant QuickBooks refund receipts, credit memos, payments, and transaction records. Match records using order references, refund amounts, dates, and customer details where available. Identify Shopify refunds with no clear accounting match, accounting refund records that may not correspond to Shopify refunds, and amount discrepancies. Distinguish actual refund transactions from canceled orders or payment reversals. Prepare a report with the Shopify order ID, refund amount, matching QuickBooks record, and recommended action. Do not create refunds, credit memos, or journal entries without my approval.

## Calculate Shopify Product-Level Profitability

Combine Shopify sales data with QuickBooks costs and expenses to estimate product contribution and identify margin improvement opportunities.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_REPORT_ITEM_SALES`, `QUICKBOOKS_GET_VENDOR_EXPENSES_REPORT`, `QUICKBOOKS_GET_PURCHASE`

> Analyze the profitability of products sold through my Shopify store using Shopify order line items, quantities, discounts, refunds, and available QuickBooks item sales, expense, and cost records. Calculate product-level revenue, estimated cost, contribution, and contribution margin wherever the required information is available. Separate confirmed accounting costs from estimated or missing costs. Highlight products with low contribution, frequent refunds, or unusually high discounts. Do not treat revenue as profit or allocate general expenses arbitrarily. Provide recommendations for pricing, discounts, or cost review, but do not change Shopify prices or QuickBooks records automatically.

## Create QuickBooks Invoices From Shopify Orders

Prepare accounting invoices for eligible Shopify orders while preventing duplicate records and incorrect customer balances.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_QUERY_INVOICES`, `QUICKBOOKS_READ_CUSTOMER`, `QUICKBOOKS_CREATE_INVOICE`

> Identify Shopify orders that may need corresponding QuickBooks invoices. Review their order IDs, customer details, line items, quantities, discounts, shipping, taxes, payment status, and total amounts. Search available QuickBooks invoice and transaction records to avoid creating duplicates. Separate paid orders, unpaid orders, partially paid orders, canceled orders, and refunded orders where the available data supports those classifications. Present a proposed invoice for each eligible order and explain any accounting uncertainties. Ask for my approval before creating invoices, and report the actual QuickBooks invoice ID after successful creation. Do not assume every Shopify order should become an invoice; consider the existing bookkeeping workflow.

## Identify Unpaid Shopify Orders And Receivables

Compare Shopify payment status with QuickBooks customer balances to identify collections that require investigation.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_AGED_RECEIVABLES_REPORT`, `QUICKBOOKS_CUSTOMER_BALANCE_REPORT`, `QUICKBOOKS_QUERY_INVOICES`

> Review unpaid and partially paid Shopify orders and compare them with available QuickBooks customer balances, invoices, payments, and aged receivables reports. Identify which orders appear to have outstanding balances, which have corresponding accounting records, and which need further verification. Account for payment timing, partial payments, refunds, and possible differences between Shopify payment status and QuickBooks invoice status. Include Shopify order IDs, customer names, outstanding amounts, invoice references, and due dates where available. Recommend which balances should be followed up first. Do not send collection messages or record payments without approval.

## Compare Shopify Revenue With Financial Reports

Compare Shopify sales trends with QuickBooks Profit and Loss reports to understand accounting revenue and expense movements.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_PROFIT_AND_LOSS_REPORT`, `QUICKBOOKS_GET_PROFIT_AND_LOSS_DETAIL_REPORT`, `QUICKBOOKS_GET_REPORT_CASH_FLOW`

> Compare my Shopify sales performance with QuickBooks Profit and Loss reports for the same reporting period. Summarize Shopify gross sales, discounts, refunds, and net sales using the available store data. Compare these with QuickBooks income, expenses, and net profit. Explain differences in reporting scope, taxes, shipping, transaction timing, refunds, and accounting classifications where relevant. Show monthly comparisons when equivalent data is available and identify material differences that need reconciliation. Do not assume Shopify sales totals should exactly equal QuickBooks income, and do not modify accounting records automatically.

## Review Shopify Expenses And Supplier Costs

Analyze QuickBooks vendor expenses alongside Shopify sales to identify rising costs and opportunities to improve margins.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_VENDOR_EXPENSES_REPORT`, `QUICKBOOKS_QUERY_BILLS`, `QUICKBOOKS_GET_PURCHASE`, `QUICKBOOKS_QUERY_VENDORS`

> Analyze my Shopify sales alongside QuickBooks vendor expenses, bills, purchases, and relevant item costs. Identify major suppliers, fulfillment expenses, packaging costs, shipping expenses, and other costs that can be connected to my store operations using the available records. Compare expenses across periods and relate them to sales trends where the data supports the comparison. Highlight rising costs, unusual transactions, and products whose margins may be affected. Distinguish directly attributable product costs from general business expenses. Recommend specific investigations or cost-saving opportunities without assuming that every vendor expense belongs to Shopify or changing any accounting records.

## Track Shopify Payouts Against Bank Records

Investigate differences between Shopify payment activity, recorded payouts, and QuickBooks accounting transactions.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_DEPOSIT`, `QUICKBOOKS_GET_TRANSFER`, `QUICKBOOKS_QUERY_PAYMENTS`, `QUICKBOOKS_GET_TRANSACTION_LIST_REPORT`

> Help me reconcile Shopify payment activity and payouts with available QuickBooks payment, deposit, transfer, and transaction records. Compare payout amounts, transaction dates, fees, refunds, chargebacks, and other available adjustments. Identify records that appear matched, unmatched, duplicated, or different in amount. Distinguish order revenue from the net cash deposited after fees and adjustments. Do not claim that bank reconciliation is complete unless the necessary bank and payout data is available. Prepare a report of discrepancies and the evidence needed to resolve them. Do not create deposits, transfers, payments, or journal entries without my approval.

## Prepare Tax And Accounting Review Reports

Consolidate Shopify sales, refunds, taxes, and QuickBooks accounting reports for bookkeeping and professional tax review.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_GET_PROFIT_AND_LOSS_REPORT`, `QUICKBOOKS_GET_REPORT_TRIAL_BALANCE`, `QUICKBOOKS_GET_GENERAL_LEDGER_REPORT`, `QUICKBOOKS_GET_BALANCE_SHEET_REPORT`

> Prepare a period-end review using Shopify order and refund data alongside available QuickBooks tax, Profit and Loss, Trial Balance, and transaction reports. Summarize sales, discounts, refunds, recorded taxes, expenses, and outstanding balances where available. Identify transactions with missing tax information, inconsistent totals, or unclear accounting treatment. Separate sales tax collected from revenue and distinguish recorded values from estimates. Provide a checklist of records to verify with my accountant. Do not assume that the integration provides a complete tax filing or compliance assessment, and do not change tax codes or accounting entries without approval.

## Automate Shopify Bookkeeping With Approval

Build an approval-based workflow for turning Shopify sales activity into accurate QuickBooks accounting records.

- Apps: QuickBooks, Shopify
- Tools: `QUICKBOOKS_QUERY_INVOICES`, `QUICKBOOKS_GET_CHANGED_ENTITIES`, `QUICKBOOKS_CREATE_INVOICE`, `QUICKBOOKS_CREATE_JOURNAL_ENTRY`, `QUICKBOOKS_CREATE_PAYMENT`

> Design an approval-based bookkeeping workflow for my Shopify store and QuickBooks account. Review Shopify orders, refunds, payment status, customers, products, and relevant existing QuickBooks invoices, payments, credit memos, and sales receipts. Identify which transactions need accounting records and which are already represented. Prepare proposed invoices, payments, refund receipts, deposits, or journal entries only when supported by the available information and capabilities. Check for duplicates and show the financial impact before each consequential action. Ask for explicit approval before creating or sending any records. After each approved operation, report the actual result and record identifier. Never claim that the Shopify and QuickBooks accounts are fully synchronized unless the available evidence supports that conclusion.
