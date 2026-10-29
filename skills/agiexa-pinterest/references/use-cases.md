# Pinterest use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/pinterest

## Discover Trending Keywords For Products

Find growing Pinterest search terms relevant to your products and turn them into actionable content ideas.

- Apps: Pinterest
- Tools: `PINTEREST_GET_KEYWORD_TRENDS`, `PINTEREST_GET_PRODUCT_TRENDS`

> Research Pinterest search keyword trends for my product category and target market. Identify the most relevant growing, monthly, yearly, and seasonal keywords available for the selected region. Where supported, narrow the results using relevant audience filters or seed search terms. Group the findings by product relevance, search intent, and potential content theme. Recommend keywords for Pin titles, descriptions, and board organization. Clearly distinguish actual trend data from your own recommendations, and do not invent search volumes or growth percentages when they are unavailable.

## Identify High-Performing Pins Across Boards

Analyze existing Pins and identify the content that generates the strongest engagement, saves, and outbound traffic.

- Apps: Pinterest, Shopify
- Tools: `PINTEREST_GET_TOP_PINS`, `PINTEREST_GET_ACCOUNT_ANALYTICS`, `PINTEREST_GET_PIN_ANALYTICS`

> Analyze my Pinterest account's top-performing Pins over the last 30 days. Retrieve available account analytics and identify the best-performing regular and video Pins using relevant metrics such as impressions, engagements, saves, and outbound clicks. Include Pin titles or IDs where available and explain why each result matters. Group the findings by content theme where possible. Check that the reporting period and metric definitions are consistent, and avoid claiming that a Pin drives Shopify purchases unless that information is available from a suitable source.

## Generate Pinterest Content From Trends

Convert current Pinterest inspiration and keyword trends into relevant, searchable content ideas for your business.

- Apps: Pinterest
- Tools: `PINTEREST_GET_INSPIRATION_TRENDS`, `PINTEREST_GET_KEYWORD_TRENDS`, `PINTEREST_GET_PRODUCT_TRENDS`

> Research Pinterest editorial inspiration, trending search keywords, and relevant product category trends for my business. Generate 15 Pin ideas that align with these findings and my products. For each idea, provide a 5-6-word title, a short description, suggested keywords, a visual concept, and an appropriate destination page type. Prioritize ideas that are relevant to my target audience and season. Label trend-derived recommendations separately from creative suggestions, and do not publish any Pins without my explicit approval.

## Organize Boards For Better Discovery

Review board structure and recommend a clearer organization strategy that helps users discover relevant products and ideas.

- Apps: Pinterest
- Tools: `PINTEREST_LIST_BOARDS`, `PINTEREST_LIST_BOARD_SECTIONS`, `PINTEREST_UPDATE_BOARD`, `PINTEREST_UPDATE_BOARD_SECTION`

> Review my Pinterest boards, their descriptions, sections, and existing Pins. Identify boards that have unclear names, overlapping themes, or content that would be easier to discover with better organization. Propose a revised structure using clear, searchable board names and relevant sections. For each recommendation, include the current board or section ID where available, the proposed name, the reason for the change, and which existing Pins could belong there. Preserve existing content and do not delete boards, sections, or Pins. Ask for my approval before making any changes.

## Create Search-Optimized Pinterest Pins

Prepare keyword-focused Pin titles and descriptions that match search intent and direct visitors to relevant products.

- Apps: Pinterest, Shopify
- Tools: `PINTEREST_GET_KEYWORD_TRENDS`, `PINTEREST_GET_TOP_PINS`, `PINTEREST_CREATE_PIN`

> Create 10 Pinterest Pin drafts for my products or Shopify collections. Use relevant Pinterest keyword trends and my existing high-performing content as inspiration. For each draft, provide a clear title, a natural description, suggested keywords, a visual concept, a recommended board, and a destination URL placeholder or verified URL. Avoid keyword stuffing, misleading claims, and unsupported product benefits. Make each Pin distinct rather than repeating the same description with minor changes. Do not publish anything until I approve the final copy, media, board, and destination.

## Track Individual Pin Performance Over Time

Examine individual Pin analytics to understand performance trends and identify content worth refreshing or expanding.

- Apps: Pinterest
- Tools: `PINTEREST_GET_PIN_ANALYTICS`, `PINTEREST_GET_PIN`, `PINTEREST_LIST_PINS`

> Review the daily, summary, and lifetime analytics available for my selected Pinterest Pins. Compare impressions, engagements, saves, outbound clicks, and other available metrics over the requested date range. Identify Pins with sustained performance, recent improvement, or declining engagement. Explain whether changes may reflect reporting windows, content age, or insufficient data. Recommend which topics to reuse, refresh, or investigate further. Include Pin IDs and supporting metrics, and do not modify existing Pins automatically.

## Plan Seasonal Content Around Shopping Trends

Use seasonal keyword and shopping category trends to plan timely Pinterest content for relevant products.

- Apps: Pinterest, Shopify
- Tools: `PINTEREST_GET_KEYWORD_TRENDS`, `PINTEREST_GET_PRODUCT_TRENDS`, `PINTEREST_GET_INSPIRATION_TRENDS`

> Research Pinterest's available seasonal keyword trends, editorial inspiration, and growing shopping categories for my target region. Recommend a content plan for the next four weeks based on my products and the seasonal themes supported by the available data. For each week, provide content themes, suggested Pin titles, relevant keywords, a visual concept, and a suitable Shopify destination page type. Separate verified trend information from predictions and creative recommendations. Do not invent exact trend dates or demand figures, and do not publish or schedule content without my approval.

## Refresh Existing Pins With Better Copy

Improve outdated Pin titles and descriptions while preserving accurate product information and relevant destinations.

- Apps: Pinterest
- Tools: `PINTEREST_LIST_PINS`, `PINTEREST_GET_PIN_ANALYTICS`, `PINTEREST_GET_KEYWORD_TRENDS`, `PINTEREST_UPDATE_PIN`

> Review my existing Pinterest Pins and identify those that may benefit from clearer titles, improved descriptions, or more relevant keywords. Use available Pin analytics and current keyword trends to prioritize candidates. For each Pin, show its ID, current title and description where available, proposed copy, suggested keywords, and the evidence supporting the update. Preserve accurate product details and the original destination unless I approve a change. Do not update Pins automatically. Present the complete proposed changes for review first.

## Publish Approved Pins To Relevant Boards

Create approved image, carousel, or video Pins with appropriate descriptions and destinations on selected boards.

- Apps: Pinterest
- Tools: `PINTEREST_LIST_BOARDS`, `PINTEREST_REGISTER_MEDIA`, `PINTEREST_GET_MEDIA`, `PINTEREST_CREATE_PIN`

> Help me publish a batch of Pinterest Pins using the content and media I provide. First, verify the target boards and review the final title, description, media, and destination URL for each Pin. Confirm that the selected media format is supported and that any video upload or processing requirements are satisfied before attempting to create a video Pin. Present a final publication checklist with the target board, content, and destination for each item. Ask for my explicit approval before publishing. After each creation attempt, report the actual result and any returned Pin identifiers. Never claim a Pin was published unless the operation succeeded.

## Audit Pinterest Profile And Website Verification

Review profile resources and website verification status to identify account setup gaps that could affect business presence.

- Apps: Pinterest
- Tools: `PINTEREST_GET_PROFILE`, `PINTEREST_LIST_PROFILE_RESOURCES`, `PINTEREST_GET_WEBSITE_VERIFICATION`, `PINTEREST_LIST_BOARDS`

> Audit my connected Pinterest profile and available business resources. Review profile details, boards, linked businesses, claimed websites, and website verification information. Identify which relevant resources are available and whether website verification appears complete based on the returned status. If verification is incomplete, explain the available verification methods and the material Pinterest provides, without assuming that a domain is verified. Prepare an action checklist for any missing setup steps. Do not change board privacy, delete content, or make account changes without my explicit approval.
