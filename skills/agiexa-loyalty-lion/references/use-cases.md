# LoyaltyLion use cases via Agiexa

Example prompts a merchant will be able to give their agent after Agiexa launches (November 2026). They are illustrations of future use - do not run them today.

More examples and live demos: https://agiexa.com/integrations/loyalty-lion

## Identify Valuable Loyalty Customers

Find members with strong loyalty engagement and recommend ways to encourage their next purchase.

- Apps: LoyaltyLion, Shopify
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_POINTS_HISTORY`, `LOYALTYLION_LIST_AVAILABLE_REWARDS`

> Analyze my available LoyaltyLion member records to identify valuable loyalty customers. Review their approved and pending points, points spent, membership tier, loyalty segment, and points transaction history where available. Identify members with meaningful approved balances, recurring earning activity, or rewards they can currently redeem. Connect the findings with Shopify order history when accessible. Recommend personalized retention or reward-discovery actions based on verified data. Do not assume that a high points balance means a customer is profitable, and do not change balances or redeem rewards without my approval.

## Reengage At-Risk Loyalty Members

Identify at-risk loyalty members and prepare targeted retention campaigns based on their actual loyalty activity.

- Apps: LoyaltyLion, Shopify, Klaviyo
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_POINTS_HISTORY`

> Find LoyaltyLion members categorized as At Risk or Win Back. Review available points balances, tiers, transaction histories, redeemable rewards, and Shopify purchase history where accessible. Prioritize customers using verified evidence such as previous purchases, recent activity, and available reward opportunities. Draft personalized re-engagement messages that encourage customers to return and explore eligible rewards. Do not invent point expirations, discounts, or reward availability. Respect marketing consent and suppression rules, and present the audience criteria and message drafts for approval before sending any campaign.

## Explain Customer Points History

Investigate loyalty balances and explain how customer activities, redemptions, and adjustments affect available points.

- Apps: LoyaltyLion
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_POINTS_HISTORY`

> Look up the specified LoyaltyLion member and retrieve their points transaction history. Summarize earned points, pending points where available, redemptions, manual adjustments, and expired points. Explain the transaction sequence and reconcile the balance only when the returned data supports the calculation. Highlight unexpected adjustments, duplicate-looking entries, or discrepancies that may require investigation. Distinguish approved points from pending points and do not assume that every recorded transaction is eligible for redemption. Do not modify the customer's points balance; provide an evidence-based explanation and recommended next steps.

## Recommend Suitable Loyalty Rewards

Match members with currently redeemable rewards based on their approved points balance and preferences.

- Apps: LoyaltyLion, Shopify
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_LIST_AVAILABLE_REWARDS`, `LOYALTYLION_REDEEM_REWARD`

> Look up the specified LoyaltyLion member and retrieve their current points balance and available rewards. Recommend rewards the customer can currently redeem, showing the required points and the member's remaining balance after redemption where the information supports that calculation. Rank options by affordability and relevance rather than assuming the most expensive reward is best. Verify the reward's current availability and eligibility. If useful, compare the options with relevant Shopify products or purchase preferences available to me. Do not redeem a reward, spend points, or issue a reward until I approve the specific choice.

## Audit Unexpected Loyalty Balances

Investigate points discrepancies and unusual transactions before making any balance corrections.

- Apps: LoyaltyLion, Shopify
- Tools: `LOYALTYLION_POINTS_HISTORY`, `LOYALTYLION_FIND_CUSTOMER`

> Investigate the LoyaltyLion points history for the specified customer or list of customers. Compare the available approved balance, pending points, points spent, and recorded transactions. Identify discrepancies, unexpected manual adjustments, repeated transactions, or possible issues involving expirations and redemptions. Show the supporting transaction details and explain which conclusions are confirmed versus uncertain. If Shopify order information is available, use it to investigate purchase-related earning activity without assuming every order should generate points. Recommend corrective actions but do not add or remove points until I approve each specific adjustment and its rationale.

## Reward Repeat Purchases Through Loyalty

Identify opportunities to encourage a second or subsequent purchase using relevant loyalty benefits.

- Apps: LoyaltyLion, Shopify
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_LIST_AVAILABLE_REWARDS`

> Analyze available LoyaltyLion member data alongside Shopify order history to identify customers who may be encouraged to make another purchase. Consider membership tier, approved points, available rewards, purchase history, and loyalty segment. Recommend suitable actions for first-time buyers, repeat customers, and inactive members based on verified data. Where appropriate, suggest reward discovery, relevant product recommendations, or a retention message. Do not assume that points automatically expire or that a customer qualifies for a specific discount. Provide the audience criteria and proposed campaign for approval before modifying points or contacting customers.

## Manage Manual Loyalty Adjustments

Prepare controlled bonus-point or deduction operations with clear eligibility rules and an audit-friendly approval process.

- Apps: LoyaltyLion
- Tools: `LOYALTYLION_ADD_POINTS`, `LOYALTYLION_REMOVE_POINTS`, `LOYALTYLION_FIND_CUSTOMER`

> Help me plan a LoyaltyLion points adjustment for the customers and reason I specify. Identify the intended members, verify their current points balances, and calculate the total points to add or remove. Check for duplicate customers, invalid identifiers, and members who do not meet the stated eligibility criteria. Present a table with each affected customer, current balance, proposed adjustment, resulting balance, and reason. Explain any missing information or unusual cases. Do not execute adjustments until I approve the exact customer list, adjustment amount, and purpose. Never change balances simply to manipulate loyalty statistics.

## Review Loyalty Tier Engagement

Use membership tiers and available loyalty information to recommend ways to improve customer engagement.

- Apps: LoyaltyLion
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_POINTS_HISTORY`

> Analyze available LoyaltyLion membership tiers and member records. Identify how customer segments and points balances relate to tier membership where the available data supports the comparison. Recommend personalized engagement strategies for different tiers, such as reward discovery, relevant product education, or repeat-purchase campaigns. Use actual tier rules if available, and do not invent tier thresholds or benefits. If program-wide tier statistics cannot be retrieved directly, explain the limitation and work with the member records available. Present recommendations that respect the existing loyalty program rules and require approval before customer-facing changes.

## Promote Customer Referral Opportunities

Identify members with available referral links and propose ways to encourage appropriate referral participation.

- Apps: LoyaltyLion, Shopify, Klaviyo
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_LIST_AVAILABLE_REWARDS`

> Review available LoyaltyLion member records for customers with referral links. Identify opportunities to encourage eligible members to share their referral links through an appropriate customer communication campaign. Verify the referral link, applicable referral rules, and any supported reward conditions before using them. Draft personalized messages that explain how customers can participate without promising benefits that are not confirmed. If Shopify order data is available, recommend ways to evaluate referral-related purchases without claiming attribution that cannot be verified. Respect marketing consent, protect customer information, and obtain approval before sending messages or changing any loyalty balances.

## Prepare a Loyalty Performance Report

Combine member-level loyalty information and points activity into a practical report with prioritized retention actions.

- Apps: LoyaltyLion, Shopify
- Tools: `LOYALTYLION_FIND_CUSTOMER`, `LOYALTYLION_POINTS_HISTORY`, `LOYALTYLION_LIST_AVAILABLE_REWARDS`

> Prepare a LoyaltyLion program report using the available customer lookup results, points histories, redeemable rewards, tiers, and loyalty segments. Summarize the customers analyzed, approved and pending points where available, common transaction patterns, reward opportunities, and members who may need retention attention. Include a clear distinction between individual-member findings and account-wide statistics. Do not extrapolate account totals from a small sample or claim program-wide trends without complete supporting data. Where Shopify order information is available, connect loyalty activity to purchase behavior carefully. End with three prioritized actions, explain the evidence for each, and do not modify points or redeem rewards without my approval.
