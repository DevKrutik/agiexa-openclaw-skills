# Loox use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/loox

## Identify Products With Poor Ratings

Rank low-rated products and investigate the customer feedback behind their ratings.

- Apps: Loox, Shopify
- Tools: `LOOX_PRODUCT_RATING_SUMMARY`, `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_GET_RATING_SUMMARY`

> Analyze my Loox product rating summaries and available product reviews. Identify the lowest-rated products, considering both average rating and review count. Retrieve recent reviews for the products that need attention and summarize the main positive and negative themes supported by the review text. Match each product to its Shopify product information where possible. Recommend which products should be investigated first and explain why. Distinguish between low ratings and small review samples, clearly state the number of reviews analyzed, and do not invent complaint themes or claim a product has a defect without evidence.

## Summarize Customer Review Sentiment

Turn product and store reviews into actionable insights about customer satisfaction and recurring feedback.

- Apps: Loox
- Tools: `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_LIST_STORE_REVIEWS`, `LOOX_GET_RATING_SUMMARY`

> Analyze my available Loox product reviews and store-level reviews. Summarize the rating distribution, recurring positive themes, negative feedback, and customer suggestions. Separate product-specific concerns from store-level experiences such as service or delivery. Group similar comments together and include representative examples when useful. Report counts and percentages only when supported by the retrieved data. Clearly state any date filters, review limits, or pagination restrictions. Do not generalize from a small sample or invent feedback that is not present in the actual reviews.

## Draft Responses to Negative Reviews

Prepare empathetic, personalized replies that address customer concerns without making unsupported promises.

- Apps: Loox, Shopify
- Tools: `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_GET_PRODUCT_REVIEW`

> Find low-rated Loox product reviews that may need a response. Retrieve the review details and draft a professional, empathetic reply that addresses the customer's actual concern. Use verified Shopify product information and available store policies where relevant. Avoid blaming customers, exposing private information, promising refunds without authorization, or making claims that have not been verified. Show the original review, star rating, associated product, and proposed reply. Explain whether a public response or a separate support conversation would be more appropriate. Do not publish a response or change review visibility until I approve the specific action.

## Highlight Products With Strong Reviews

Find highly rated products and identify customer-verified strengths that can improve merchandising.

- Apps: Loox, Shopify
- Tools: `LOOX_PRODUCT_RATING_SUMMARY`, `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_GET_PRODUCT_REVIEW`

> Use my available Loox rating summaries to identify highly rated Shopify products. Consider average rating, review count, and the reliability of each sample. Retrieve relevant positive reviews and identify product benefits that customers explicitly mention. Recommend improvements to product descriptions, featured-product selections, and merchandising based on verified feedback. Match each review to the correct product and preserve the customer's original meaning. Do not fabricate testimonials, overstate product benefits, or treat a high rating based on very few reviews as conclusive evidence of broad customer satisfaction.

## Detect Recurring Product Quality Issues

Find repeated complaints in product reviews to help prioritize product improvements and supplier investigations.

- Apps: Loox, Shopify
- Tools: `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_PRODUCT_RATING_SUMMARY`, `LOOX_GET_PRODUCT_REVIEW`

> Analyze available Loox reviews for recurring product issues. Group actual customer feedback into themes such as durability, performance, sizing, packaging, or usability only when those themes are supported by the review text. For each theme, identify affected products, supporting review examples, and the number of matching reviews when reliably countable. Prioritize concerns based on frequency, severity, rating, and potential customer impact. Distinguish reported experiences from confirmed defects. Recommend whether each issue needs supplier investigation, clearer product information, or customer support follow-up. State any review retrieval limits that could affect the findings.

## Compare Ratings Across Products

Compare product ratings and review volumes to identify customer satisfaction differences across the catalog.

- Apps: Loox, Shopify
- Tools: `LOOX_PRODUCT_RATING_SUMMARY`, `LOOX_GET_RATING_SUMMARY`, `LOOX_LIST_PRODUCT_REVIEWS`

> Compare Loox product rating summaries across my Shopify catalog. Identify the highest-rated and lowest-rated products, products with substantial review volume, and products whose ratings may be unreliable because of small samples. Present a table containing product name, average rating, review count, and recommended action. Retrieve review text when needed to explain differences in customer feedback. Ensure products are matched correctly and distinguish published rating summaries from rankings calculated using a limited set of recent reviews. Do not invent ratings or review counts, and disclose any limitations in the available data.

## Investigate Negative Store Reviews

Review store-level feedback to uncover customer experience issues that may affect trust and repeat purchases.

- Apps: Loox
- Tools: `LOOX_LIST_STORE_REVIEWS`, `LOOX_GET_PRODUCT_REVIEW`

> Analyze my available Loox store-level reviews, including star ratings, dates, and review status where available. Identify recurring concerns relating to the overall shopping experience, customer service, delivery, or other issues explicitly mentioned by reviewers. Compare feedback across time periods only when sufficient comparable data exists. Separate store-level complaints from product-specific issues. Provide supporting review examples and prioritize the concerns that deserve investigation. Recommend appropriate customer support or operational improvements, but do not assume a complaint is verified or change review status without my approval.

## Find Products Needing More Reviews

Identify highly rated products with relatively few reviews and suggest ethical ways to strengthen social proof.

- Apps: Loox, Shopify
- Tools: `LOOX_PRODUCT_RATING_SUMMARY`, `LOOX_GET_RATING_SUMMARY`

> Analyze Loox product rating summaries and review counts to identify products that may benefit from more customer feedback. Consider products with low review volume, strong existing ratings, and meaningful commercial relevance using available Shopify data. Rank opportunities by potential usefulness rather than assuming that fewer reviews mean poor performance. Recommend appropriate post-purchase review request improvements using the store's existing review collection process. Do not fabricate reviews, manipulate ratings, selectively suppress criticism, or assume customers have consented to unrelated marketing. Explain which products deserve attention and what evidence supports each recommendation.

## Improve Product Pages With Review Insights

Use authentic customer feedback to recommend product-page improvements and address common purchase objections.

- Apps: Loox, Shopify
- Tools: `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_GET_PRODUCT_REVIEW`

> Analyze Loox reviews for selected Shopify products and identify recurring product benefits, questions, concerns, and unmet expectations. Recommend specific product-page improvements, such as clearer feature explanations, sizing details, instructions, product photography, or shipping information, only when supported by the feedback and available product data. Include the affected product, evidence from reviews, proposed change, and expected customer benefit. Preserve the meaning of customer comments and do not publish altered testimonials as direct quotations. Present the recommendations for review rather than changing product pages automatically.

## Generate a Weekly Review Insights Report

Prepare a concise report highlighting review trends, product satisfaction, recurring issues, and recommended actions.

- Apps: Loox, Shopify
- Tools: `LOOX_LIST_PRODUCT_REVIEWS`, `LOOX_LIST_STORE_REVIEWS`, `LOOX_GET_RATING_SUMMARY`, `LOOX_PRODUCT_RATING_SUMMARY`

> Prepare a weekly customer review report using available Loox product reviews, store reviews, rating summaries, and Shopify product information. Include the number of reviews analyzed, rating distribution, highest- and lowest-rated products, recurring positive themes, negative feedback, and reviews that may need responses. Compare with the previous week only when comparable historical data is available. Clearly distinguish published overall ratings from rankings calculated using a limited number of recent reviews. Include three prioritized actions for product quality, customer support, or merchandising. Disclose missing data and retrieval limits, and do not publish replies or modify review visibility without my approval.
