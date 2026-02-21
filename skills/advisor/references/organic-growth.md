# Organic Growth

Procedural reference for Claude. Covers growth strategies for indie products: organic-first philosophy, launch tactics, shareability engineering, and feedback loops.

---

## Core: Organic First, Always

Growth must be organic before anything else. This is non-negotiable for indie makers.

**Why organic:**
- Free, requires no ad spend
- Provides direct, unfiltered feedback on whether the product is good enough
- If a product grows organically, it has genuine product-market fit

**Why paid traffic is dangerous early:**
- Paid traffic masks bad products: usage grows while paying, falls when you stop
- Funded startups pay 100%+ of revenue in ads. Funding runs out. Collapse follows.
- Creates an illusion of traction that evaporates the moment spending stops

**Decision rule:** If it doesn't get traction organically, there's a good chance it's simply not good enough. Fix the product first, not the distribution.

Common anti-pattern: people start with paid traffic first, end when money runs out, product fails. The correct sequence is reversed.

---

## The 100K MAU Threshold

This is a concrete decision boundary for when paid traffic becomes acceptable:

- **Under 100,000 MAU:** Organic growth ONLY. The product is not yet proven. Any paid traffic is premature and wastes money.
- **After 100,000 MAU:** Product is proven by organic demand. Now paid traffic can amplify what already works.

You can combine organic and paid after the threshold. But always organic first. Paid traffic is a multiplier, not a substitute. Multiplying zero still equals zero.

---

## Growth = Multiplier for Great Product

The best growth hack ever: make a really useful and great product.

This is not platitude. It is procedural truth. If the product is bad, no amount of growth hacking produces sustainable growth. Growth tactics applied to a great product compound. Growth tactics applied to a mediocre product waste effort.

**Sequence:**
1. Make the product genuinely great and useful
2. Then apply growth tactics to amplify organic word-of-mouth
3. Never reverse this order

---

## Anti-pattern: Growth Hackers

Do not hire growth hackers. 99.99% of them are useless. They try to sell a mystical art they often did not even succeed at themselves.

**What they typically do:**
- Dark blackhat spammy techniques
- Short-term results that trigger long-term punishment from platforms
- Burn money on tactics that don't compound

**The correct approach:** Growth should be intrinsic to the product from the start. The product itself must be inherently viral or useful enough that people share it naturally. If you need a growth hacker to make people use your product, the product has a fundamental problem.

---

## Anti-pattern: Fake Users

Buying followers, engagement, likes is the fastest way to failure.

**Why it fails:**
- People don't really care about follower/like counts anymore
- Few followers can actually create underdog appeal, and people support underdogs
- Fake engagement does not convert to real usage or revenue

**Case study:** Levels tried Instagram bots for NomadList. Result: zero organic traction from the effort. Pure waste.

**Reality:** If people like your product they will use it. No shortcuts exist. It can take years. Accept this timeline.

---

## Two Types of Growth

All growth activity falls into exactly two categories:

**1. New users (acquisition)**
- Reach people who don't know your product exists
- Requires active outreach: launches, content, social sharing
- Harder, more expensive in effort

**2. Returning users (retention)**
- Get existing users to come back
- Easier than acquiring new users
- Methods: engagement features, notifications, email, making the product genuinely great
- A great product naturally brings users back

Both matter. But retention on a great product is the foundation. Acquisition without retention is a leaky bucket.

---

## Strategy: Keep Launching

First launch creates a spike for approximately one week, then traffic drops. Most makers treat this as the only launch opportunity. This is wrong.

**Procedure:**
1. First launch: get initial spike and users
2. Collect feature requests and build improvements over months
3. Every few months: bundle new features into a version (Product 2.0, 3.0, etc.)
4. Relaunch the new version as if it were a new product
5. Repeat indefinitely

**Why this works:**
- Each relaunch gets a full spike of attention
- Shows the product is evolving and getting better
- Nobody ever said you cannot keep launching
- The launch is perpetual

**Cadence:** Every few months, whenever enough meaningful features accumulate to justify a version bump.

---

## Strategy: Spinning Off Features

When a feature within your product becomes strong enough, extract it into a separate standalone product.

**Procedure:**
1. Identify a feature that is powerful and self-contained
2. Extract it into its own product with its own name, domain, and identity
3. Launch the spin-off as an entirely new product
4. Get a full launch cycle of attention for the spin-off
5. Cross-link back to the main product

**Case study:** NomadList had a coworking space feature. Levels extracted it into PlacesToWork, a separate app with GPS functionality. This gave an entirely new launch opportunity with entirely new press coverage.

**Requirement:** The feature must be strong enough to stand alone as a product. Weak features spun off will fail their independent launch.

---

## Strategy: Build in Public

One of the most effective strategies to get promotion for free.

**What it means:**
- Blog, vlog, or communicate the entire story of building your product
- Be completely transparent, including about failures and mistakes
- Share revenue numbers, user counts, technical decisions, struggles

**Examples of execution:**
- Buffer shared every step on Buffer Open blog from inception
- Dan from RoxCodes livestreams building products, including mundane activities like sleeping, waking up, and making coffee
- The MAKE book itself was written publicly in Google Docs with Twitch livestreams

**Why it works:**
- People enjoy being part of success and failure stories
- Sharing about the product usually makes the product itself do better
- Current advantage: most companies are NOT transparent yet, so transparency is differentiating

**Critical clause:** This only works if your audience overlaps with potential users. Building in public to an audience that will never use your product generates attention but not growth.

---

## Transparency in Mistakes

When something goes wrong, do not hide. Show your mistakes publicly and fix them.

**Case study:** Arq Backup discovered their backup software version actually DELETED backups instead of saving them. The maker wrote a personal post describing exactly what happened and apologizing. Users were angry, but the anger was significantly reduced by seeing a real human handling the crisis honestly.

**Procedure when things break:**
1. Acknowledge the mistake publicly and specifically
2. Explain what happened in plain language
3. Apologize genuinely
4. Describe what you are doing to fix it
5. Follow through on the fix

**Principle:** Behind every company is an imperfect human. Showing that humanity during failures builds more trust than pretending to be perfect.

---

## Strategy: Dynamic Share Images

Social sharing with rich images dramatically increases click-through rates. A shared link with a picture gets significantly more clicks than one without.

### Open Graph and Twitter Cards

Every page on your site must have:
- Facebook Open Graph meta tags, especially `og:image` (unique picture per page)
- Twitter Card meta tags for rich previews
- These must be filled out for EVERY page, not just the homepage
- Social networks can drive up to 30% of total traffic

### Dynamic Screenshot Technique

**Procedure:**
1. Create an HTML page that visually displays key information about each content page
   - Example for marathon app: map with route drawn in thick lines, "25 km / 15 mi" text overlay
   - Example for city page: city photo with data statistics overlaid
2. Auto-screenshot this HTML page using URL2PNG or Headless Chrome
3. Set the screenshot as the `og:image` for the original content page
4. Every page now gets a unique, visually compelling share image automatically

**Case studies:**
- NomadList: city thumbnails with data (internet speed, cost, temperature) printed directly on photos
- Gyroscope: fitness data visualizations that users share to friends, driving viral growth
- Product Hunt: uses URL2PNG for page preview thumbnails

**Result:** Significant increase in traffic from social media after implementing dynamic share images.

---

## Strategy: Human-Readable URLs

URLs are shareable content. Every interactive state of your app must be reflected in the URL.

**URL quality spectrum:**
- BAD: `http://compare.com/razorblades`
- BETTER: `http://compare.com/razorblades?size=large&blades=4&color=blue`
- BEST: `http://compare.com/razorblades/large/4-blade-razors-in-blue`

### Dynamic Sentences in URLs

**Advanced technique:** Convert filter states into natural language URL paths.

**Case study:** NomadList filters generate URLs like:
`https://nomads.com/cities-with-fast-internet-safe-for-women-to-travel-alone-near-a-beach`

This took significant effort to code but is critical for both shareability and SEO.

### Programmatic Share Sentences

Generate human-language descriptions of the current application state that users naturally want to share.

**Example:** "The Gillette 4-blade razor is 6x more powerful than Dollar Shave Club 2-blade"

**Procedure:**
1. Identify all interactive states in your app
2. Write templates that describe each state in natural language
3. Generate these descriptions dynamically
4. Display them prominently so users copy and share them
5. Encode them into URLs where possible

---

## Strategy: Feedback Box

A small chat popup (bottom-left or bottom-right corner) is essential, even for startups running for years.

**What it provides:**
- Bug reports: users report breaks within 10 minutes of deployment
- Feature requests: users tell you exactly what they want
- Lengthy suggestions: power users write detailed improvement proposals

**Why it matters:**
- Users love co-creating a startup with the maker
- The people who give ideas through the feedback box are the best users, effectively experts at your product
- This is a direct, unfiltered channel to your most engaged users

**Implementation:** Keep it simple. A chat widget that sends messages to your email or Slack.

---

## Strategy: API Launch

Make data or features accessible to other startups via API.

**Benefits:**
- Brand awareness through developer integrations
- Traffic funnel from API-powered third-party apps

**Risk and mitigation:**
- NomadList shared ALL data via API. Result: 6 clones appeared in 90 days (English, Russian, Chinese versions). API was disabled.
- Mitigation: require registration, issue API keys, limit the scope of data shared, monitor usage, cut off abusers immediately

**Decision:** Think carefully about your goal and how much data you want to make accessible. Share enough to be useful, not enough to be cloned.

---

## Competitor Benchmarking

Use SimilarWeb to compare traffic with competitors. Accuracy is reasonable above approximately 100,000 visits per month.

**Revenue estimation rules of thumb:**
- 1,000,000 visits/month: approximately $1M-$10M/year (if monetized well)
- 100,000 visits/month: approximately $100K-$1M/year
- 1,000 visits/month: approximately $1-$10/year

**Caveats:**
- Traffic is a very limiting metric. A competitor might get more users but generate less revenue.
- Use these comparisons relatively over time (are they growing faster than you?), not as absolute numbers.
- Revenue per visitor varies enormously by monetization model and market.
