# WhatsApp use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/whatsapp

## Answer Product Questions Instantly

Help shoppers discover products using Shopify catalog details inside WhatsApp conversations.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_GET_MESSAGE_HISTORY`, `WHATSAPP_SEND_MESSAGE`, `WHATSAPP_SEND_MEDIA`, `WHATSAPP_SEND_INTERACTIVE_BUTTONS`

> Help customers shop through WhatsApp using my Shopify catalog. When a customer asks about a product, identify relevant Shopify products, compare available prices, variants, and product details, and suggest the most suitable options. Ask clarifying questions when necessary. Share product images or links when available. Never invent prices, stock quantities, or product features. If the required Shopify information is unavailable, clearly say so.

## Send Personalized Order Updates

Prepare order notifications from Shopify fulfillment data with approved templates.

- Apps: WhatsApp, Shopify, Shippo
- Tools: `WHATSAPP_GET_MESSAGE_TEMPLATES`, `WHATSAPP_GET_TEMPLATE_STATUS`, `WHATSAPP_SEND_TEMPLATE_MESSAGE`

> Review my Shopify orders and identify orders that qualify for a customer status update. Use the available order, fulfillment, tracking, and customer contact information to prepare accurate WhatsApp messages. Use an approved message template when required by WhatsApp. Before sending messages in bulk, show me the recipient count, eligibility checks, and exact message content for approval. Never expose one customer's order information to another customer or claim delivery before the message status confirms it.

## Build Interactive Shopping Experiences

Collect preferences via WhatsApp Flows and use the answers to guide product discovery.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_CREATE_FLOW`, `WHATSAPP_UPDATE_FLOW_JSON`, `WHATSAPP_PUBLISH_FLOW`, `WHATSAPP_LIST_FLOWS`

> Design a WhatsApp Flow for my Shopify store that helps customers choose products. Ask for their preferred category, budget, and relevant product requirements. Keep the form short and easy to complete on mobile. Provide the proposed Flow structure and field validation rules for review. If approved, create and configure the Flow using the available WhatsApp capabilities, then publish it only after I confirm the final configuration. Explain how submitted answers would need to be connected to Shopify customer or product data.

## Follow Up on Customer Inquiries

Draft relevant follow-ups for customers who asked about products or orders.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_GET_MESSAGE_HISTORY`, `WHATSAPP_SEND_MESSAGE`, `WHATSAPP_GET_MESSAGE_TEMPLATES`

> Review available WhatsApp conversation history and match relevant inquiries to Shopify products or orders when the necessary identifiers are available. Identify conversations that may benefit from a helpful follow-up. Draft a personalized message based on the customer's actual question, avoiding unsupported claims or aggressive sales language. Check applicable contact permissions and WhatsApp messaging requirements. Show me the proposed recipients and messages before sending anything.

## Create Click-to-Chat Campaigns

Generate WhatsApp QR codes that open product or support conversations.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_CREATE_QR_CODE`, `WHATSAPP_LIST_QR_CODES`, `WHATSAPP_GET_PHONE_NUMBERS`

> Help me create a WhatsApp QR code for my Shopify store. Recommend a prefilled message that encourages shoppers to ask about a selected product or promotion. Show me the intended WhatsApp phone number, message text, and proposed use before creating the QR code. If approved, create it using the available capabilities and explain how I can use it on product packaging, store signage, or marketing materials. Do not claim that the QR code has been added to my Shopify storefront unless that action is actually supported and completed.

## Share Product Images and Guides

Send product images and documents to customers through WhatsApp media.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_UPLOAD_MEDIA`, `WHATSAPP_GET_MEDIA_INFO`, `WHATSAPP_SEND_MEDIA_BY_ID`, `WHATSAPP_CREATE_UPLOAD_SESSION`

> Help me answer customer questions by sharing relevant Shopify product images, instruction guides, or other approved media through WhatsApp. Identify the correct product or document from available store information. If media must be uploaded first, prepare the upload and confirm the intended file and recipient. Verify that the media is appropriate for the conversation and that the correct customer is receiving it. Do not send private internal documents or unrelated files.

## Manage WhatsApp Message Templates

Create reusable templates for order updates, support, and approved marketing.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_GET_MESSAGE_TEMPLATES`, `WHATSAPP_GET_TEMPLATE_LIBRARY`, `WHATSAPP_UPSERT_MESSAGE_TEMPLATE`, `WHATSAPP_GET_TEMPLATE_STATUS`

> Review my existing WhatsApp message templates and identify opportunities to improve customer communication for my Shopify store. Propose templates for shipping updates, order assistance, product inquiries, and eligible promotional messages. Include clear variable placeholders and explain the intended use of each template. Check available template status before recommending a template for use. Show me the exact content before creating or updating templates, and do not assume a new template is approved until its actual status confirms approval.

## Improve Customer Support Routing

Use automation settings and interactive messages to route customers to the right help.

- Apps: WhatsApp, Shopify, Gorgias
- Tools: `WHATSAPP_CONFIGURE_CONVERSATIONAL_AUTOMATION`, `WHATSAPP_SEND_INTERACTIVE_LIST`, `WHATSAPP_SEND_INTERACTIVE_BUTTONS`

> Design a WhatsApp support journey for my Shopify store with options for product questions, order status, returns, and speaking with a human. Recommend concise interactive buttons or lists where supported. Explain which steps require Shopify order lookup and which require a human support team. Show me the proposed conversation flow before changing automation settings or sending messages. Do not promise refunds, cancellations, or returns unless the relevant Shopify action and store policy support them.

## Monitor Message Delivery Results

Use message status data to find delivery problems and improve reliability.

- Apps: WhatsApp, Shopify
- Tools: `WHATSAPP_GET_MESSAGE_HISTORY`, `WHATSAPP_GET_ACTIVITIES`, `WHATSAPP_GET_TEMPLATE_STATUS`

> Review available WhatsApp message status information and identify messages that failed, remain pending, or have not reached the expected status. Summarize the results by message status and relevant communication purpose, such as Shopify order updates. Where message identifiers can be matched safely, connect the result to the corresponding notification record. Recommend appropriate next steps, such as checking contact details or template configuration. Do not repeatedly message customers or retry failed communications without checking the cause and confirming that another attempt is appropriate.

## Launch Customer-Friendly Promotions

Plan promotional conversations from Shopify products while respecting messaging rules.

- Apps: WhatsApp, Shopify, Klaviyo
- Tools: `WHATSAPP_CREATE_MESSAGE_TEMPLATE`, `WHATSAPP_SEND_TEMPLATE_MESSAGE`, `WHATSAPP_CREATE_MAX_PRICE_AGREEMENTS`

> Help me plan a WhatsApp promotion for selected Shopify products. Identify relevant products, verify available prices and stock information where accessible, and draft a concise message with a clear offer and call to action. Prepare an approved template if the campaign requires one. Before sending, show me the audience selection criteria, recipient count, message content, and relevant contact-permission checks. Send only after my approval, and do not invent discounts, create unsupported Shopify offers, or contact customers who are not eligible to receive the message.
