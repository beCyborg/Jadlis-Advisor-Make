# Monetization Models

Procedural reference for Claude. Covers all monetization strategies for indie products: business models, pricing psychology, payment platforms, validation techniques, and refund strategy.

---

## Core Principle: Charge Early, Do Not Be Afraid

If you never charge, it will never become a real business. It will remain a side project forever.

**Conversion math:**
- Expect approximately 5% of free users to convert to paid
- 1,000 free users produce roughly 50 paying customers
- Need approximately 20,000 potential free users in the funnel to get 1,000 paying
- Not every project is monetizable. If monetization fails after genuine effort, shut it down and try again with something new.

**Constraint breeds creativity:** Musicians make their best songs when they are poor. Financial pressure forces creative solutions.

---

## Internet Hate When Charging

When you start charging, expect hostile reactions: "HOW DARE HE CHARGE" posts on Reddit and forums.

**Procedure for handling this:**
1. Recognize these people will NEVER pay. They are not your customers.
2. Do not lower your prices in response.
3. Do not make the product free in response.
4. There are enough sane people who have money and would love to spend it on your app.
5. Paying customers do not whine on forums. They just pay and use the product.

Do not let vocal non-customers dictate your pricing strategy.

---

## Monetization as Validation: Fake Checkout Technique

This is a concrete validation method that is stronger than a landing page.

**Procedure:**
1. Add a Buy button to your MVP or landing page
2. When user clicks, show a REAL credit card modal (use Stripe Checkout)
3. User enters card details and clicks Pay
4. Show an alert: "Sorry, we didn't charge your card but thanks for your interest. Our product isn't done yet."
5. Log how many people complete this full process
6. Calculate: X completions per day multiplied by price equals estimated monthly revenue
7. If estimated revenue justifies the development cost, build the product fully

**Why this is better than a landing page alone:**
- Landing page with 10,000 visitors tells you nothing about purchase intent
- A person who entered their credit card number has demonstrated a strong buying signal
- This gives real data on willingness to pay, not just willingness to click

---

## Business Model 1: Freemium (Limit Features to Paid)

**Procedure:**
1. Launch with all features available to everyone
2. Use analytics and user feedback to identify the most valued features
3. Gate those valuable features behind payment: "To use this feature, please upgrade [UPGRADE]"
4. The emotional flow for users: "I want that!" then "Pay?!" then "$5, whatever, it solves my problem!"

**Critical implementation detail:** The conversion must be fast and smooth. After payment, immediately enable the feature. No waiting, no manual activation, no email confirmations.

---

## Business Model 2: Pay-Per-Feature (Microtransactions)

Each feature is a single standalone payment. Examples: $5 for sharing capability, $10 for a world map view.

This model has significant untapped potential on the web. It is common in mobile games but surprisingly underexplored for web applications.

**Pricing options:**
- Popular features priced higher (demand-based)
- OR: niche advanced features priced at premium (value-based)

---

## Business Model 3: Native Ads (Not AdSense)

### Why NOT Google AdSense
- Pays approximately $1 per 1,000 views
- 500,000 views per month yields only about $500/month
- Ads are ugly, spammy, irrelevant to your audience, and easily blocked

### Native Ads Instead

**What they are:** Custom-designed advertisements that match your site's look and feel, relevant to your specific audience. You sell placement directly to companies.

**Revenue:** $2,500-$10,000 per month. That is 5x-20x more than AdSense for the same traffic.

**Procedure:**
1. Design ad placements that match your site's visual style
2. Identify companies whose products are relevant to your audience
3. Reach out and sell placements directly
4. Only advertise products you would genuinely use yourself (Joe Rogan model)
5. Always label as "Sponsored" or "Ad" (this is a legal requirement)
6. Implement as custom HTML/CSS, not through ad networks

**Advantages:** Happier users (relevant, non-intrusive ads), happier advertisers (higher conversion), more money for you, and hard for ad blockers to block because the implementation is custom.

---

## Business Model 4: Sponsorships

Align your product's mission with a company's brand awareness goals.

**Target sponsors:** Companies with VC funding looking for brand exposure in your niche.

**Pricing:** $250-$2,500 per month per sponsor.

**What sponsors get:** Logo on your site, about page, or specific sections.

**Math:** 4 sponsors at $250/month = $1,000/month. This is survival money that keeps the lights on while you build.

---

## Business Model 5: Patronage

Ask users directly for monthly donations. The product stays free.

**Why this works now:** People understand you are a human and need to pay your bills. This would not have worked a decade ago, but the cultural shift toward supporting creators has made it viable.

**Examples:**
- Overcast podcast app: "Do you want to support development?" leads to an in-app purchase that unlocks no additional features
- NomadList early days: Typeform survey asking for support, which bootstrapped the first year of operation
- Platform: Patreon for recurring patronage

**Best for:** Niche products, early-stage products, makers with strong personal brands.

---

## Business Model 6: Subscription (SaaS) — The Holy Grail

Subscription is the most powerful monetization model because of compounding revenue.

### Revenue Comparison: Single Payment vs Subscription

Assuming 1,000 new customers per year at $75/year:

**Without churn:**

| Year | Single Payment | Subscription |
|------|---------------|-------------|
| 1 | $75,000 | $75,000 |
| 2 | $93,750 | $168,750 |
| 3 | $117,187 | $379,687 |
| 4 | $146,484 | $854,296 |
| 5 | $183,105 | $1,922,167 |

**With 25% annual growth + 7% churn:**

| Year | Single Payment | Subscription |
|------|---------------|-------------|
| 1 | $75,000 | $75,000 |
| 2 | $93,750 | $163,500 |
| 3 | $117,187 | $356,430 |
| 4 | $146,484 | $777,017 |
| 5 | $183,105 | $1,693,897 |

Difference after 5 years: $1,510,792 more with subscription model. Even with moderate churn, subscription grows much faster than single payment.

### The Forgotten Subscriptions Elephant

Up to 50% of subscription revenue comes from users who do not even actively use the product. Nobody in the industry discusses this openly. It is their cash cow.

### Lifetime Membership Option

Charge predicted lifetime value upfront as a one-time option alongside subscription.

**Calculation:** Average member stays 2 years. Annual price is $100. Lifetime payment = $200.

This is a good middle ground: offer both subscription AND lifetime options. Some users prefer certainty, and you get the cash upfront.

---

## Business Model 7: Community Model

Free content attracts audience. Paid community monetizes connections.

### The Pricing Ladder (NomadList Case Study)

| Price | Effect |
|-------|--------|
| Free | Spammers flooded in, quality dropped to unusable |
| $1 | Spammers gone, but quality still low |
| $5 | Better quality users |
| $25 | Much better quality |
| $50 | 10 signups/day = $500/day = $15,000/month |

**Key observation:** Every time the price was raised, signups dropped for about a week then recovered to the same level. The higher price filtered for quality without reducing volume long-term.

**Pattern:** Free content + paid community + niche monopoly = high revenue.

**Why communities work:**
- Network effect: more people equals more value, which justifies higher prices
- Operationally lean: forum software plus a moderator is the entire cost structure
- People do not pay for content anymore, but they pay for connections with other people

---

## Business Model 8: Job Boards

Attach a job board to any free niche site. Companies pay substantial amounts per post.

**Pricing tiers:** $49, $99, $199, $299 per job post.

**This is a B2B model:** Few customers at high prices equals profitability fast.

**Case study:** Dribbble is a free design portfolio showcase. Its job board charges $299 per post. At approximately 5 posts per day, that is $45,000 per month, or $540,000 per year.

**Math:** Just 10 job posts at $299 equals approximately $3,000/month. That is only 10 customers needed.

---

## Business Model 9: Conditional Payments

Users pay for failure, not for the service itself.

**Case study:** GoFuckingDoIt. Users set a goal, a deadline, and enter their credit card. If they fail to meet the deadline, they are charged. The maker keeps the money.

**Variants:** Fitness app that uses GPS to detect if you skip the gym, then charges your card.

**Core concept:** Money as a disciplinary tool. The service is free as long as users follow through on their commitments.

---

## Business Model 10: Agency to SaaS Productization

Build custom solutions for clients, notice patterns in what clients need, then productize the common solution.

**Case studies:**
- Typeform: originated as a client project building a lead generation form for a toilet company exhibition. The maker needed something more inspiring than a plain vanilla form. The result became Typeform.
- Basecamp (37signals): started as a web agency in 1999. Built internal project management tools for client work. Noticed every client needed similar tools. Productized into Basecamp. Revenue estimated at $168 million.

**Critical requirement:** Own the rights to the work you create for clients. If the client owns the IP, you cannot productize it.

---

## Competing on Price

Two viable strategies exist:
- **Premium:** Higher price, better product. Apple model: 20% of market share, more total profit.
- **Low-cost:** Lower price, undercut competitors. Android model: 80% of market share, less profit per unit.

There is room for both strategies in most markets. Choose based on your strengths and target audience.

---

## Keep Experimenting with Monetization

Monetization is never finished. It requires perpetual experimentation.

**Procedure:**
1. Put Buy buttons everywhere throughout your product
2. Observe what people click and what they ignore
3. Test prices continuously: raise them, lower them, observe the effect
4. Keep putting buttons everywhere to discover what people are willing to pay for
5. Never assume your current monetization is optimal

---

## Refund Strategy

The worst thing you can do is refuse to give a refund. An angry customer generates internet hate that costs you many more future customers than the refund amount.

**Refund procedure:**
1. Say sorry and mean it genuinely
2. Immediately refund the money. No delays, no conditions.
3. Ask why the product did not meet their expectations
4. Use this as a critical feedback moment. You learn more from angry customers than from happy ones.

**Chargeback prevention:** Always refund BEFORE the customer contacts their bank.
- If customer initiates a chargeback: you lose the full payment amount PLUS a $35 fine PLUS damage to your reputation with Stripe
- If you refund proactively: you lose only the payment amount, nothing more

Quick refunds are both ethically correct and financially optimal.

---

## Payment Platform Decision

### Options

**Stripe:**
- Best choice for developers
- Simple, well-documented API
- Handles subscription billing automatically
- Not available in all countries

**Braintree:**
- Available in more countries than Stripe
- Owned by PayPal
- Good alternative where Stripe is unavailable

**PayPal:**
- Highest conversion rate (no credit card entry needed, supports national payment systems worldwide)
- BUT: archaic technology and real risk of account freezes

**Combination strategy:** Stripe + PayPal together increased conversion by approximately 40%. Revenue went from $10,000/month to $14,000/month by adding PayPal as an option alongside Stripe.

### Quick Setup Without Code

Typeform + Stripe = instant monetization. You can start charging before building any payment infrastructure.

### For Non-Stripe Countries

Stripe Atlas: allows you to set up a US company with a US bank account, enabling Stripe access from anywhere.

---

## When Are You Done Monetizing?

You are never done, but here are signals that more work is needed:

**Lifestyle math:** $2,000/month sounds good but after taxes and insurance you may have only $1,200/month. Calculate net, not gross.

**Competitor comparison:** If competitors with similar traffic earn more revenue, you have room to improve monetization.

**Market expansion:** Widen the market your product serves. NomadList expanded from digital nomads to expats and general travelers, a market approximately 1,000x bigger. Sometimes the path to more revenue is not better monetization but a larger addressable market.

**Principle:** Grow the pie. Make the entire market bigger, the way Airbnb expanded the vacation rental market beyond what existed before.
