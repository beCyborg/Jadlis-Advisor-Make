# Automation and Exit

Procedural reference for Claude. Covers two late-stage topics: automating a product to run without the founder, and selling a company (exit strategy, valuation, negotiation, post-sale life).

---

## PART 1: AUTOMATION

### Core: Robots Over Humans

The default should be automation, not hiring. Avoid hiring. Build robots instead.

**Why avoid hiring:**
- Hiring introduces complexity: training, management, liability, health insurance, interpersonal dynamics
- Humans are complex and slow to scale
- Robots are simple and fast to scale

**Scale reference:** Levels runs 700-2,000 robots depending on server load, handling the work that would otherwise require a team.

**AI inflection point:** Since approximately 2022, it is possible to automate almost any process with AI assistance. This creates the opportunity for the first billion-dollar company run by a single founder.

---

### What Robots Actually Do (Real Examples)

These are concrete examples of automated tasks, not abstractions:

- Find popular cities via data sources, find a bar in each city via Foursquare API, auto-organize meetups, auto-promote on social media at 1 month, 14 days, and 1 day before the event
- Collect weather, internet speed, and air quality data from 25 different sources for 1,000 cities every hour
- Auto-update the server operating system and packages, notify by SMS when anything breaks
- Browse 100+ job boards, parse job listings, filter for remote positions, post to Remote OK, share on social media, email subscribers
- Screenshot city pages and generate social share thumbnails automatically
- Check GoFuckingDoIt deadlines, email the user's designated supervisor, charge the credit card if the goal was not met by the deadline
- Log in to telecom provider, download the monthly invoice, email it to the founder, enter line items into bookkeeping software

Each of these would take a human significant recurring time. As scripts, they run continuously without attention.

---

### What Is a Robot?

A robot is any task you previously did manually that has been converted into an automated script running on a schedule.

**Implementation options:**
- Scripts in any language: PHP, JavaScript (Express, Phantom), Python, shell scripts
- No-code: Zapier workflows for simpler automations
- Scheduling: cron jobs on a server

**Monitoring:**
- Cronitor: checks that cron jobs actually run on schedule, alerts if they stop
- UptimeRobot: checks pages every minute, alerts via SMS or DM if anything is down
  - Advanced check example: UptimeRobot visits a page like "safe cities in Europe with good health care" and checks that "Amsterdam" appears in the results. If Amsterdam is missing, something is broken in the data pipeline.

---

### Decision: Automate or Not?

The programmer trope is real: sometimes automating a task takes longer than just doing it manually forever.

**Decision rule:** Automate if:
1. The task takes significant human time on a recurring basis, AND
2. The automation does not take disproportionately long to build

Do not automate everything. Only automate what is worth the investment. Some tasks are faster to do by hand occasionally.

---

### Where Humans Still Fit

Some tasks are too expensive or too complex to automate. For these, use contractors, not employees.

**Tasks that still need humans:**
- Customer support edge cases (self-service should cover most scenarios: signup, cancel, refund, plan changes)
- Developer on standby for server issues that robots cannot diagnose or fix

**Payment models for contractors:**
1. **Monthly lump sum:** $2,500/month for a customer support contractor who handles the inbox
2. **Per-incident:** Developer gets an alert when something breaks, fixes it, invoices hourly at $50+/hour

**Hiring philosophy:** Work with people who are highly autonomous. Do not manage. Find people who can manage themselves, give them clear scope, and let them operate independently.

**Finding contractors:** Ask friends first. If no referrals available, use Upwork.

---

### Autonomous Organization Checklist

Follow this checklist to build an organization that runs without you:

1. Automate all repetitive work with robot scripts
2. Hire a devops/sysadmin on contract (hire 2 for backup redundancy, so one being unavailable does not create a crisis)
3. Set up monitoring alerts (UptimeRobot) so developers get notified automatically when things break
4. Hire a part-time contractor with PayPal/bank access who can manage and pay the developers
5. Find 1-2 trusted people as informal "board" to check that the executive contractor runs things as you would wish
6. Prepay hosting company and domain registrar for several years (deposit thousands of dollars so nothing expires unexpectedly)

---

### The Bus Test

If you are hit by a bus, will the organization suffer greatly?

- If yes: you fail the bus test. The organization is too dependent on you.
- If no: you pass the bus test. The organization can survive without you.

A mix of robots and autonomous humans creates an organization that passes the bus test. You must pass this test before considering any exit.

---

### Compressed Income (Not Passive)

Passive income is a myth. What exists is compressed income.

**How it works:**
- Work intensely for 3 years building and automating a product
- Product generates money without daily work for perhaps 3 more years
- Total: 3 years of work produces 6 years of income
- That is compressed income, not passive income

**Reality check:** There will always be at least monthly situations where you need to step in personally. The product is nearly passive but never fully passive. Accept this.

---

## PART 2: EXIT

### First Contact

Eventually, you will receive messages saying "interested in acquiring your product/company."

**First reaction:** Excitement and naive optimism.

**Reality:** Approximately 1 in 100 acquisition inquiries actually goes through to a completed deal. Most are noise.

**Procedure:** Keep your email public and DMs open. Serious buyers will find you. Do not chase buyers. Let them come to you.

---

### The 5 Types of Buyers

#### Type 1: Deadbeat Non-Serious (90-99% of inquiries)

These offer 100x to 1000x less than market value. Example: Someone DM'd to buy NomadList (generating $300K+/year in revenue) for "a few thousand dollars."

**Action:** Ignore completely. Do not engage, do not counter-offer, do not respond.

#### Type 2: Competitive Snooper

These use the acquisition process to extract competitive intelligence. They lead you through the process, request private business details during "due diligence," then back off. They have learned your business details for free.

Fake acquisitions for competitive intelligence is used far more often than people realize.

**Defense:** Set a BREAKUP FEE before sharing any proprietary data. If they are not willing to put money at risk, they are not serious.

#### Type 3: String-You-Alonger

These schedule calls, then reschedule, then reschedule again, and the call never happens. They are not serious buyers. They are middle managers filling their schedules.

**Defense:** Decline calls. Require text-only communication. By text their entire theatre show falls apart, because text is concrete and cannot be endlessly rescheduled.

#### Type 4: Serious but Formal

These are big traditional enterprise companies. Expect NDAs, legal agreements, extensive contracts. Worth engaging if they are genuinely serious, but the process involves high costs in time and lawyer fees. The formality implies a lack of mutual trust.

#### Type 5: Serious and Informal (BEST)

These communicate in a friendly, concise manner and are genuinely willing to buy. The purchase process is simple and usually structured in your favor. Even BigTech companies like Google can operate this way.

This is a tiny percentage of inquiries. Wait for this type.

**Statistical reality:** 95-99% of acquisition inquiries are useless. You need 20-100 inquiries before finding 1 serious buyer.

---

### The Breakup Fee

A breakup fee is a penalty paid if the acquiring party backs out of a deal after the process has begun.

**Reference:** AT&T paid $4 billion on a $39 billion deal, approximately 10%.

**Standard range:** 1-3% is common. But for indie makers, request 10%, consistent with what large companies negotiate.

**Why it works:**
- Stops non-serious bidders immediately. They will not agree to risk real money.
- Compensates you for the competitive intelligence you share during due diligence.
- If a party is serious, they will agree to 10%.

---

### Negotiation Strategy

#### Bargaining Power

- **Best position:** You do NOT want to sell. Set an extremely high price. If it happens, great. If not, no worries. This gives you maximum negotiating power.
- **Worst position:** You want or need to sell. You will accept a lower price because the buyer knows you are motivated.

The best time to sell is when you do not want to sell (Justin Kan).

#### First Move

**Option A:** Do not open with a price. Let the buyer bid first. This filters non-serious buyers immediately, because they will either lowball (revealing themselves as Type 1) or offer something reasonable.

**Option B:** Open with an aggressively high anchor price (example: 10x annual revenue).

**Research finding (Harvard, 2004):** Most negotiators make first offers that are not aggressive enough. More aggressive first offers lead to better outcomes for the person who made the offer. Err on the side of too high, not too low.

---

### Valuation Methods

#### Method 1: Revenue Times Growth Multiples

| Annual Growth Rate | Approximate Multiple |
|---|---|
| ~10% | ~3x annual revenue |
| ~25% | ~5x annual revenue |
| ~33% | ~7x annual revenue |
| ~50% | ~10x annual revenue |
| ~100%+ | ~15x+ annual revenue |

**Example:** $100K/year revenue with 33% year-over-year growth. Multiple: 7x. Valuation: $700,000.

#### Sell vs Hold Calculation

Selling for $700K now versus holding 5 years at 33% growth:

- Revenue over years 1-5: $100K + $133K + $177K + $235K + $313K = $958K total earned
- Company worth after 5 years: $313K annual revenue times 7x = $2.19M
- Total value from holding: approximately $3.1M versus $700K from selling now

**But consider:**
- This assumes 33% growth holds for 5 consecutive years. Most companies do not survive 3 years.
- After selling $700K and investing at 7% in an ETF, you earn $49K/year passively versus $100K+/year from running the business.
- Selling is a transaction: you trade high-risk/high-reward cash flow for low-risk/low-reward cash.

#### Method 2: Seller's Discretionary Earnings (SDE)

What does the new owner actually earn after all costs?

**Example scenario:**
- You: earn $300K/year, do everything yourself, run on a friend's free server
- Buyer needs: programmer + designer + marketer ($300K) + hosting ($5K) = net negative SDE

SDE is not particularly useful for DIY indie maker sellers because it mostly reduces your negotiating power. The value of the business with YOU running it at zero labor cost is very different from the value with paid employees.

#### Method 3: Industry Comps

Look at what similar companies sold for recently. Compare revenue, growth rate, and market position. This provides a reality check on your valuation expectations.

---

### Deal Terms

#### Cash vs Stock
- **Cash:** Simple, best for most sellers. You receive money. Done.
- **Public stock:** Can sell immediately on the market, but you have single-company concentration risk.
- **Private stock:** Impossible or extremely difficult to sell. Essentially illiquid.
- **Best outcome:** Full cash acquisition.

#### Earnouts and Why They Are Problematic

An earnout splits the payment: for example, $500K cash now plus $500K if performance targets are met within 1 year.

**Problems:**
1. You must keep working at a company you no longer own
2. The new owner can sabotage your targets to avoid paying the second installment
3. After the earnout period ends, they stop sabotaging and profit from the work you put in

Earnouts show disrespect from the buyer and are usually never worth accepting.

#### Asset Purchase Agreement

For smaller companies, buyers often purchase assets rather than the legal entity. Assets include: source code, brand, intellectual property, domains, hosting accounts, analytics, and customer lists.

This is legally much simpler than buying an entire company.

#### Non-Compete Agreement

Reasonable example: do not build another remote job board for 2 years.
Too broad example: do not build anything in the HR space for 5 years.

Make sure the non-compete is not too wide. It should be specific to the exact product category, not the entire industry.

#### Using a Broker

**Pros:** Access to buyer network, expert presentation of your business, valuation guidance, legal process knowledge.

**Cons:** 10-15% fee (that is $150K on a $1M sale), buyer also pays approximately 2.5%, brokers have short-term mindset focused on closing deals.

**Main brokers:** FE International, Empire Flippers.

**Decision:** Skip the broker if you are confident in negotiation and have time to manage the process. Use one if you are not.

---

### Post-Sale

#### Celebrate

The ritual of celebration is scientifically beneficial. It demarcates a life event and helps with psychological transition. Do not skip this.

#### Emotional Fallout

This is real and common. Markus Persson (notch) sold Minecraft for $2.5 billion and reported: "Never felt more isolated." The sale changed friendship dynamics and complicated relationships.

**Why this happens:** When your identity is tied to your company, selling the company means losing your identity. "Who am I if not the Nomads.com guy?"

**Procedure:**
1. Build your identity beyond the company BEFORE selling
2. Consult a psychologist. Everyone should, especially during life-changing moments.
3. Expect an adjustment period. It is normal and temporary if handled well.

#### FIRE (Financial Independence, Retire Early)

**The 4% Rule (Trinity Study):**
- Invest sale proceeds in a diversified portfolio (S&P 500 average return 7-10%)
- Withdraw 4% per year
- Money lasts perpetually at this withdrawal rate

| Sale Price | 4% Annual Withdrawal | Monthly Amount |
|---|---|---|
| $500,000 | $20,000 | $1,667 |
| $1,000,000 | $40,000 | $3,333 |
| $5,000,000 | $200,000 | $16,667 |
| $10,000,000 | $400,000 | $33,333 |

**Principle:** Instead of buying a Ferrari and an expensive house, live off 4%. This is the opposite of what most people think when becoming rich. Wealth preservation, not wealth display.

#### Career Options After Exit

**1. Stay at the company:** Typical vesting period of 36-48 months. You help with transition. Can feel soul-sucking, working on something you no longer own or control.

**2. Angel investing or VC:** Gives status and management fees (approximately 2.5%), but generally produces negative ROI compared to simple index funds. Most angel investments return zero.

**3. Start another company:** Repeat founders have approximately 30% success rate versus 18% for first-time founders. Risk: work addiction pulls you back into the grind before you are emotionally ready.

**4. Charity and volunteering:** Platforms like Catchafire or Peace Corps. Get out of your ego and pursue happiness by helping others. Often the most fulfilling option but the least considered.
