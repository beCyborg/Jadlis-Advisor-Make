# Launch Playbooks

Procedural reference for launching products on every major platform. Specific tactics, timing, formatting, and anti-patterns for each channel.

---

## Core Principle

"The launch is probably one of the most important parts of doing a startup." And: "Everyone underestimates its importance and difficulty." A great product with a bad launch fails. An average product with a great launch gets traction, feedback, and a chance to iterate into something great.

"It can make an average product or break a great product."

The goal of every launch: get the product in front of real users as fast as possible, collect feedback, learn, and improve. Launch is not a celebration — it is the beginning of the feedback loop.

---

## Pre-Launch Checklist

Complete every item before launching on any platform.

### 1. Verify MVP Actually Works

- Go through the entire new user flow multiple times yourself
- Act as different user types (new visitor, returning user, mobile user, slow connection)
- Test all automated communications (welcome emails, confirmation messages, notifications)
- Get 3-5 other people to go through the flow and report friction points
- Fix anything that blocks the core action. Ignore cosmetic issues.

### 2. Email Capture (Contextual)

Do NOT use "Subscribe to our newsletter." This has zero perceived value to the visitor.

Instead, use contextual propositions that offer specific value:
- Job board on a PHP page: "Get new PHP jobs in your inbox weekly"
- Food delivery service: "We'll text you 30 minutes before delivery"
- Price comparison tool: "Get alerted when price drops below your target"

**Why this is critical:** Most sites see a giant drop of traffic after the launch ends. The launch sends a spike of visitors, then they leave and never return. Email capture during the spike lets you re-engage those visitors later with product updates, new features, and content.

Contextual email capture converts 3-10x better than generic "subscribe to newsletter" because the visitor understands exactly what value they will receive.

### 3. Feedback Box

Add a feedback widget to the bottom-left or bottom-right corner of every page.

**Tools:** Olark, Intercom, or any lightweight chat widget.

**How to use it:**
- You do NOT need to be on-call responding in real-time
- Just have it collecting messages
- Check messages a few times per day
- Users will report bugs within 10 minutes of a broken deploy

"It's like a super power to your app's development." Users encounter edge cases you never imagined. They test on devices you do not own. They use workflows you did not anticipate. "Let your users be your 24/7 continuous testing army."

### 4. Analytics

**Minimum setup:** Google Analytics with the real-time tab bookmarked for launch day.

**What to track:**
- Visitors (total and concurrent)
- Referrer sources (which launch platform sends the most traffic)
- User flow (where do people drop off)
- Conversion events (signups, purchases, key actions)

**Advanced (add later):**
- MixPanel or Amplitude for event-level tracking (button clicks, feature usage)
- HotJar for session recording (watch real users navigate your product)

On launch day, the real-time tab in Google Analytics is your dashboard. Watch traffic spike, see where it comes from, identify problems in real-time.

### 5. Push Notifications

If your product supports push notifications, be extremely modest with them.

- Only send notifications about content directly relevant to the user
- Prefer grouped notifications: "5 new PHP jobs this week" instead of 5 separate notifications
- Never send marketing pushes or "we miss you" messages
- Users will revoke notification permissions permanently after one irrelevant push

---

## Product Hunt Playbook

### Metrics
- Typical traffic: ~10,000 visitors
- Peak concurrent: ~300 simultaneous users
- Conversion: lower than search traffic (visitors are browsing, not searching for solutions)
- Hidden value: Product Hunt is packed with tech journalists who browse daily looking for stories

**The real prize:** Press coverage that follows within hours or days of a successful PH launch, generating 50,000+ additional visitors over the following weeks.

### Timing (CRITICAL)

Product Hunt ranking resets at **midnight Pacific Standard Time (PST)** — San Francisco time.

- Submit at **00:00:01 PST** (one second after midnight)
- This gives you the full 24-hour window to accumulate upvotes
- Submitting at 9:00 PM PST means you only have 3 hours before the leaderboard resets

**Procedure:**
1. Calculate your local time equivalent of midnight PST
2. Set an alarm
3. Have everything pre-written and ready to submit
4. Submit at exactly 00:00:01 PST
5. Stay awake for the first hour to write the introduction comment and respond to early questions

### Submission Elements

**Name:** Your app's name for a first launch. For relaunches, add version: "ProductName 2.0" or "ProductName 3.0." Check with Product Hunt community managers about repost policies.

**Tagline:** Must be understandable by someone who has never heard of your product. Add emojis for visual distinction.
- BAD: "An algorithmic application for machine learning applied to photos"
- GOOD: "The first machine learning photo editor"

The bad example uses jargon and says nothing about what the user gets. The good example is clear and specific.

**Thumbnail:** Use an animated GIF, not a static image. Video plays automatically on Product Hunt — an animated thumbnail draws more attention than a static logo.
- Convert a short screen recording to GIF
- Keep file size to a few MB
- Use GIPHY Capture or similar tools
- Show the product in action, not just the logo

**Screenshots:** Upload 8-16 high-resolution screenshots.
- Zoom your browser to 125-150% before capturing for extra crispness
- Show core features and key user flows
- Each screenshot should be self-explanatory with a visible feature or benefit

**Video:** Auto-plays muted on desktop. Keep it under 30 seconds. The video must communicate what the app does FAST — viewers will scroll past within 5 seconds if they do not understand the product.

### Post-Submission Protocol

**Immediately after submission:**
1. Share on Twitter, Facebook, Instagram — but do NOT ask for upvotes. Share the product naturally. "I just launched X on Product Hunt — check it out" is fine. "Please upvote my product" is not.
2. Write an introduction comment on your Product Hunt listing: Who you are. Why you made this. What your plans are. Be genuine, not salesy.
3. Stay in the comments for the first several hours. Answer every question. Thank every commenter. Gather feedback actively.

**Attitude:** "Be polite and humble. Don't pose, brag, or market. You're there to take people in as guests." Product Hunt's community is generally supportive and positive. Respect that energy.

**Character of PH feedback:** Generally supportive. Comments tend to be encouraging and constructive. Less brutally honest than Hacker News. Take positive feedback with a grain of salt — it may be politeness, not validation.

---

## Hacker News Playbook

### Metrics
- Typical traffic: 50,000-100,000 visitors
- Peak concurrent: ~1,000 simultaneous users
- This is 5-10x the traffic of Product Hunt
- HN is the highest-volume launch channel for tech products

### Character
Hardcore tech audience. Radically honest. "Can destroy your entire company verbally." If your product has a flaw, HN will find it and discuss it publicly. This is brutal but valuable — the feedback is real.

### Title Formula

The title determines 90% of whether your post gets traction.

- BAD: "Petsy.com - The best food delivery for pets"
- BETTER: "I made a site that lets you subscribe to food delivery for your pet"
- BEST: "Show HN: I made a site that lets you subscribe to pet food delivery"

**Rules:**
- Use "Show HN:" prefix for product launches
- Write in first person: "I made..." or "I built..."
- Be specific about what the product does
- No marketing language. No superlatives. No "the best." No "revolutionary."
- Friendly, personal, authentic tone
- Do not include the domain name in the title

### The 5-Upvotes-Per-Hour Threshold

Understanding this mechanic is critical for a successful HN launch.

1. When you submit, your post appears on the /new page
2. It stays visible on /new for approximately 1 hour
3. If you accumulate roughly **5 upvotes spread across that first hour**, the post typically reaches the front page
4. The upvotes must be gradual and organic — too many upvotes too quickly triggers spam detection
5. Once on the front page, step back completely. Let organic reach take over. Do not try to influence voting from this point.

**How to get those initial 5 upvotes:**
- Share on your personal Twitter/social media (naturally, not begging)
- The post title must be compelling enough to generate organic upvotes from /new browsers
- That is it. There is no hack.

### Spam Protections

HN has aggressive anti-gaming mechanisms:

- **Controversy filter:** If a post receives more comments than upvotes, it gets auto-flagged and may drop off the front page. Controversial posts that spark arguments get penalized.
- **Voting ring detection:** If the same group of accounts consistently upvotes each other's posts, their votes get discounted.
- **Manual moderation:** HN moderators (dang and others) can manually discount votes or remove posts. If a mod decides a post does not belong, it drops off regardless of upvotes.
- **Aggressive moderating:** "If the mod doesn't like the post, it drops off." This is subjective and there is no appeal process.

### Re-submissions

Re-submitting is allowed on HN. If your first submission does not gain traction:
- Try a different day of the week
- Try a different time of day
- Try a different title angle
- "Usually if it doesn't work the first time, it's not for HN." But sometimes timing and title make all the difference.

### Zeitgeist Alignment

HN's audience has strong collective values that shift over time. Posts that align with the current cultural moment perform better.

Current tendencies that tend to resonate:
- Anti-Big-Tech sentiment
- Pro-privacy
- Pro-indie / bootstrapped
- Open source appreciation
- Technical depth and craftsmanship

### Server Requirements

**Your server MUST handle 1,000 simultaneous users.** If your site crashes during an HN front page spike, you lose the entire opportunity. The traffic window is short (4-8 hours of peak). If your server is down for 30 minutes of that window, you lost a significant percentage of potential users.

Test your server under load before launching on HN. Use a load testing tool to simulate 1,000 concurrent connections.

---

## Reddit Playbook

### Metrics
- Front page traffic: 50,000-500,000 visitors
- Peak concurrent: 5,000-25,000 simultaneous users
- This is the highest potential traffic of any launch channel
- Also the most unpredictable

### Character
Mainstream hivemind. Reddit communities either love something collectively or destroy it collectively. There is little middle ground. The hivemind decides within the first hour.

### CRITICAL: Static Pages Preparation

Most websites crash before reaching the Reddit front page. The traffic volume is extreme. The solution:

**Step 1:** Convert dynamic pages to static HTML files.
```
php index.php > index.html
```
Set this up as a cron job that regenerates the static file periodically (every 5-15 minutes).

**Step 2:** Keep dynamic elements as lightweight AJAX API calls.
- Initial page load serves a static HTML file (fast, cacheable, nearly unbreakable)
- Interactive elements load via small API calls after the page renders
- "Dramatically reduces load — not a program operation but a file read operation"

**Step 3:** Revert to fully dynamic pages when traffic normalizes.

**Key insight:** Only about 20% of Reddit visitors actually interact with your product beyond the landing page. The other 80% look at the page, read it, and leave. Optimizing that initial page load for 80% of visitors who just need to read something is the priority.

### Subreddit Selection

**Step 1 — Niche subreddit first:**
Post to the most specific relevant subreddit. For a pet food delivery service: r/pets, r/dogs, r/cats, r/petcare. Niche subreddits have engaged users who care about the topic.

**Step 2 — General tech subreddits:**
If the niche post gains traction, post to broader subreddits:
- r/startups
- r/internetisbeautiful
- r/SideProject

**Step 3 — Data-oriented subreddits (if applicable):**
If your product involves interesting data:
- r/dataisbeautiful
- r/MapPorn

**Title format:** Personal and friendly. "Hi /r/pets! I made a site that lets you subscribe to pet food delivery." Use the subreddit name in the greeting. First person. Conversational tone.

### Front Page Mechanics

How a post reaches the Reddit front page:

1. Post gains traction in a subreddit → reaches top of that subreddit
2. Top of subreddit → enters the top 100 of all of Reddit → approximately page 4
3. From page 4, the post must climb to page 1. This requires surviving the traffic AND maintaining hivemind approval (upvote ratio stays high)
4. The climb from page 4 to page 1 takes hours
5. It probably will not happen. But if it does, the traffic is massive.
6. At the top-100 scale, you cannot affect the outcome anymore. The organic hivemind decides.

**The takeaway:** Optimize for the niche subreddit. Front page is a bonus, not a strategy.

---

## BetaList

### Metrics
- Traffic: 500-1,000 visitors
- Audience: targeted tech early adopters
- Cost: ~$129 to skip the 2-month waiting list

### Use Case
Get early beta users before bigger launches on PH, HN, or Reddit. BetaList users expect rough products and are willing to provide feedback. Use this as a warm-up round.

---

## Strategy: Perpetual Launching

"The launch is perpetual." Do not launch once and then wait for growth. Growth comes from repeated launches.

**The perpetual launch procedure:**
1. Ship features continuously (weekly or biweekly)
2. Every few months, bundle recent features into a version release
3. Launch the new version: "Product 2.0," "Product 3.0"
4. Each version launch gets its own Product Hunt submission, HN post, press outreach
5. Put version numbers visibly on your site to signal active development

**Every major feature is a launch opportunity.** Do not bury new features in a changelog. Give them their own moment.

---

## Strategy: Side Project Marketing

Decouple features from your main product and launch them as standalone products. Each standalone product gets its own full launch cycle.

**Case studies:**

**Buffer** (social media scheduler):
- Extracted image creation into a standalone tool called Pablo
- Extracted customer service tool called Respond
- Each got its own launch, press coverage, and user base
- Users discovered Buffer through these side projects

**Crew** (freelancer marketplace):
- Created Unsplash: a free stock photo site using leftover photos from a photoshoot
- Unsplash became BIGGER than Crew itself (later acquired for significant sum)
- Also created HowMuchToMakeAnApp.com: a simple calculator
- The calculator got massive press coverage and drove traffic back to Crew

**NomadList:**
- Spun off the coworking space directory into PlacesToWork
- Separate brand, separate launch, separate press cycle
- Both products drove traffic to each other

"They could have launched these as features, but specifically chose not to." A feature buried inside an existing product gets no press, no launch spike, no standalone attention. The same feature as its own product gets all of those.

**Procedure:**
1. Look at your product's features
2. Identify any feature that could work as a standalone tool
3. Build a minimal standalone version with its own domain
4. Launch it on PH, HN, Reddit as its own product
5. Include clear links back to your main product
6. Each side project expands your audience and creates backlinks

---

## Handling Hate

Launching publicly means receiving hate. This is unavoidable.

**What to expect:**
- "This already exists" (even when it does not, or your version is different)
- "This is pointless" (from people who are not in your target audience)
- Personal attacks on your skills, design, code quality
- Accusation of copying someone else
- "The world can be a dark place"

**What NOT to do:**
- Do not fight strangers on the internet. "The fastest way to failure." You cannot win an argument with an anonymous commenter. Every response escalates.
- Do not take it personally. The commenter spent 30 seconds forming an opinion. You spent months building the product. Their opinion is uninformed by design.
- Do not let hate stop you from launching again.

**What TO do:**
1. Read through every piece of hate
2. Extract any actual, actionable feedback hidden inside the negativity
3. If the feedback is valid, implement the improvement immediately
4. Respond publicly and politely: "Good point. I just fixed that. Thanks."
5. This response pattern transforms haters into supporters: "Oh wait, there's a real person behind this? With feelings? Oh wow!"

Listening to criticism and acting on it visibly is the most powerful launch-day PR tool available. It converts hostile commenters into loyal users.

---

## Anti-patterns

**1. Asking people to upvote or share.**
"I never did, never will, don't consider them friends anymore." Asking for upvotes is spam. It also masks whether your product is genuinely interesting. If you need to beg for upvotes, the product or the title is not compelling enough.

**2. Buying fake upvotes or followers.**
Masks whether the product is actually good. You get vanity metrics instead of real signal. Platforms detect this and penalize you. Even if you reach the front page through fake votes, the users who arrive will give honest feedback — and if the product is not good, you wasted money to learn that faster.

**3. Not preparing for traffic.**
Server crashes during launch spike = missed opportunity that does not come back. The HN front page window is 4-8 hours. The Reddit front page window is 12-24 hours. If your server is down during that window, those visitors are gone forever.

**4. One-and-done launching.**
Launching once and then waiting for organic growth. Organic growth without repeated launches is extremely slow. The perpetual launch strategy creates repeated traffic spikes that compound over time.
