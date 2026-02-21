# Build Fast

Procedural reference for building products quickly as a solo maker. Every technique prioritizes shipping speed over theoretical correctness.

---

## MVP Definition: Minimum GOOD Product

An MVP must actually function. The core user flow must work end-to-end.

**What qualifies as an MVP:**
- The core feature works reliably
- A new user can complete the primary action without getting stuck
- It looks at least OK — "otherwise you simply turn people away"
- Bugs on secondary features are acceptable
- Missing features are acceptable
- Rough design is acceptable

**What does NOT qualify as an MVP:**
- An email signup box. "An email signup box IS NOT a product, it's an email signup box. Don't launch it." It tells you nothing about whether users want your product. It tells you that some people type their email into boxes.
- A landing page with no functionality
- A mockup or prototype that cannot process real actions
- A form that collects data but does nothing with it

**Pre-launch verification procedure:**
Go through the new user flow COUNTLESS times before launching. Not once. Not twice. Dozens of times. Pretend you are a new user who has never seen the product. Click every button. Fill every form. Break every assumption. Then have a few other people do the same.

---

## The One Month Rule

Maximum one month from idea to launched MVP. This is a hard deadline, not a guideline.

**The logic:**
- If it takes longer than a month, you are overbuilding
- You are adding features users have not asked for
- You are perfecting things that might not matter
- You are delaying the only thing that matters: user feedback

**After one month:**
1. Launch whatever you have
2. Get real users interacting with it
3. Learn what actually matters from their behavior
4. Build the next iteration based on evidence, not assumptions

"Don't build on an MVP too long." The MVP is not the product. It is the experiment. Ship the experiment. Learn. Then build the product.

---

## The Perfectionism Trap

"9 out of 10 times perfectionism doesn't make things better but just creates inaction."

**What perfectionism actually costs:**
- Days spent choosing between two shades of blue
- Weeks rebuilding a feature that was already functional
- Months delaying launch because "it's not ready"
- Years of nothing shipped because nothing was ever "good enough"

**What does NOT matter at MVP stage:**
- Wrong colors or mismatched branding
- Logo that is not perfect
- Inconsistent spacing or alignment
- Missing edge case handling on secondary flows
- Feature parity with competitors

**What DOES matter:**
- Core flow works
- Users can accomplish the primary task
- It does not crash on the happy path

**The Gmail precedent:** Gmail was in Beta for nearly a decade. Users did not care. They used it daily despite the "Beta" label. If Google can ship imperfect products, so can you.

**The skill to develop:** "Learn to be fine with everything being not fine." This is a practiced skill, not a personality trait. Every time you feel the urge to perfect something before shipping, recognize that urge as the enemy of progress.

**The balance:** Do not make shitty products. There is a difference between "imperfect but functional" and "broken and unusable." The MVP should be good enough that users can evaluate the core value proposition. It should not be so polished that you spent 6 months before a single user touched it.

"You'll always have time to perfect stuff later." Ship first. Polish second. Always in that order.

---

## DIY Advantage: Speed Comparison

The speed difference between doing it yourself and outsourcing is not incremental — it is categorical.

**DIY workflow (one day):**
1. Wake up
2. See bug report from user
3. Open code editor
4. Fix bug in 5 minutes
5. Deploy
6. Done

Over one year: 300-1,000 small tweaks, improvements, and fixes. Each one takes minutes.

**Outsource workflow (one bug):**
1. See bug report from user
2. Write detailed email to developer explaining the bug
3. Developer is on holiday for 3 days
4. Developer reads email, asks clarifying question
5. You answer next day
6. Developer fixes it (maybe correctly, maybe not)
7. Developer deploys (maybe correctly)
8. 3-5 days elapsed for one bug fix

Over one year: 300-1,000 emails, massive delays, constant miscommunication, developer turnover.

"In the time you've sent a bunch of emails, I've already pushed 5 bug fixes and added 2 new features."

---

## DIY vs VC-Funded Teams

NomadList competed against 5 VC-funded companies with $1M-$10M in funding and teams of 10-30 people. All five failed. NomadList won.

"While working alone in my underwear on the side of my hotel bed with my MacBook, I outcompeted million-dollar VC-funded teams of 30+ people."

**What you do NOT need:**
- A team
- Capital
- Connections
- An office
- A business plan
- A pitch deck
- Advisory board members

**What you DO need:**
- Skills (even average skills across multiple domains)
- The ability to ship

"I'm not great at programming or design. I'm pretty average. But because I can do it all well enough, I have an advantage." The advantage is not excellence in one domain — it is competence across all domains needed to ship a product. A solo maker who can do average code, average design, and average marketing will outship a team of specialists arguing about architecture.

---

## Tool Selection Rules

Follow these rules in order when choosing tools and technologies:

**Rule 1: Use what you already know.**
Do not learn a new framework to start a new project. Use whatever you shipped your last project with. Speed comes from familiarity.

**Rule 2: Stop discussing tools.**
"The people discussing what programming language is best are not shipping products." Tool debates are procrastination disguised as research.

**Rule 3: Language does not determine success.**
Facebook runs on PHP. Twitter started with Ruby. Google uses Java. Reddit was built with Python. "It didn't stop them." Your choice of language or framework will not be the reason your product succeeds or fails.

**Rule 4: Learn only what you need right now.**
Do not take a course on React before building. Open the docs, find the one thing you need to implement, implement it. Move on. Repeat. Do not learn entire languages or frameworks speculatively.

**Rule 5: Apply the 10-year test.**
If a technology is 10+ years old, it is probably reliable. PHP, Python, JavaScript, PostgreSQL, MySQL — boring technologies that work. New shiny tools break in production.

**Rule 6: Focus on WHAT, not HOW.**
"The question should be 'why did you make that?' not 'how did you make that?'" Nobody cares about your tech stack. Users care about what the product does for them.

**Rule 7: Switch when you outgrow, not before.**
You can always switch technologies later. Twitter moved from Ruby to Scala when they hit scaling problems — not before. Most products never reach the point where technology choice matters. Build first. Optimize only if forced to.

---

## No-Code MVP Pipeline

Build a fully functional MVP in 30 minutes to a few hours using off-the-shelf tools.

**Core stack: Carrd + Typeform + Zapier + Stripe**

**Step 1 — Landing page (Carrd, Squarespace, or WordPress):**
- Explain what the product does in one sentence
- Show key benefit
- Single call-to-action button
- Takes 5-10 minutes to set up on Carrd

**Step 2 — Data collection (Typeform or Google Forms):**
- CTA button links to a Typeform
- Collect whatever information you need from the user
- Typeform supports conditional logic, file uploads, payment integration

**Step 3 — Processing (Zapier):**
- Connect Typeform submission to downstream actions
- Filter data, transform it, route it to different services
- Zapier connects 3,000+ apps without code

**Step 4 — Communication (MailChimp via Zapier, Twilio for SMS/voice):**
- Auto-send confirmation emails on form submission
- Send SMS notifications to customers or contractors
- Automated drip campaigns for follow-up

**Step 5 — Payments (Stripe via Typeform or Carrd):**
- Typeform can charge credit cards directly via Stripe integration
- Carrd also supports Stripe checkout embeds
- Customer pays, you receive money — that simple

**Step 6 — Task management (Trello via Zapier):**
- Auto-create Trello cards for each new order
- Assign to contractors
- Track fulfillment status

**Proven example — Luggage delivery MVP built in 30 minutes:**

A luggage delivery service where travelers ship bags ahead to their destination.

1. Carrd landing page explains the service
2. CTA links to Typeform with Stripe payment integration
3. Customer fills in pickup/delivery details and pays
4. Zapier triggers on form submission:
   - Sends confirmation email to customer
   - Adds row to Google Sheet (order database)
   - Creates Trello card for the delivery contractor
   - Sends SMS to contractor via Twilio with pickup details
5. Contractor picks up and delivers luggage

"We now have a fully functioning MVP and actually a basic startup. And it took about 30 minutes!"

No code was written. No developer was hired. The product accepts money and delivers a service. That is an MVP.

---

## Web-First Strategy

When choosing between web and native (mobile apps), default to web.

**Web advantages:**
- Faster development cycle
- Instant updates (no app store review delays)
- Link-based sharing (someone sends a URL, recipient is immediately using the product)
- Works inside other native apps (WhatsApp, Messenger, email clients)
- No install friction
- Single codebase for all platforms

**Native advantages:**
- Better UX for specific use cases (camera, GPS, offline)
- App store discovery (but increasingly less relevant)
- Push notifications (web supports these now too)

**Decision procedure:**
1. Do you already have web development skills? Build web.
2. Do you already have native development skills? Build native.
3. Do you have neither? Learn web — it is faster to learn and more versatile.
4. "Choose the platform where you already have skills."

**The migration rule:** "You can ALWAYS go native later." Many successful products started as web apps and added native apps only after proving demand. Starting native before proving demand means months of work that might be wasted on an unvalidated idea.

**Future trend:** Web apps running inside WhatsApp, Messenger, and WeChat browsers. Users tap a link in a message, use the product immediately, share it with friends via another link. No install. No app store. Viral sharing built into the medium.

---

## Constraints as Advantages

Every constraint you have is actually a competitive advantage in disguise.

| Constraint | Why it is actually an advantage |
|---|---|
| No money | Full ownership of the company. No VC telling you what to build. No board meetings. Natural cost discipline forces creativity. |
| No office | Work from anywhere. Access worldwide talent pool (if you ever do hire). Lower overhead = longer runway. |
| No coding skills | Forced to use off-the-shelf tools = faster prototyping. Test more MVPs in less time. No over-engineering. |
| No connections | No monoculture bubble. Underdog appeal resonates with users. More creative thinking because you are not constrained by "how things are done." |

---

## Cost Benchmarks

What things actually cost for a solo indie maker:

- **VPS (server):** $5/month (DigitalOcean, Vultr)
- **Code editor:** Free (VSCode)
- **Apple developer license:** $100/year
- **Domain name:** $10-15/year
- **Developer hourly rate (if outsourcing):** $50-$250/hour
- **Outsourced MVP (100 hours):** $5,000-$25,000
- **Full app outsourced:** $50,000+
- **DIY cost:** Near $0 (just your time and $5/month hosting)

The cost difference between DIY and outsourcing is 100x-1000x. This is why learning to build yourself is the highest-leverage skill.

---

## Anti-patterns

**1. Paying a developer with future equity.**
"Like paying with a $5 lottery ticket." Equity in an unproven startup is worthless. Good developers know this. Only bad developers accept equity-only deals.

**2. Tool obsession.**
Discussing, comparing, and benchmarking tools instead of shipping. Every hour spent debating React vs Vue is an hour not spent building your product.

**3. The VC build narrative.**
Raise money → hire team → rent office → buy espresso machine → host launch party → no traction → money runs out → shut down. This path destroys more startups than competition does.

**4. Email signup box as MVP.**
An email signup page is not a product. It does not validate demand. It validates that people will type their email into a box. Ship something that actually functions.

**5. Spending months learning before starting.**
"I need to learn React before I can build this." No. You need to build this and learn the minimum React required along the way. Learning without building is procrastination.

---

## The Sustainable Build Path

The correct sequence for an indie maker:

1. **Build it yourself** — using skills you have, tools you know
2. **See if it works** — launch, get users, measure
3. **No?** — Build something else. Repeat from step 1.
4. **Yes?** — Monetize it. Add payment. See if people pay.
5. **People pay?** — Hire help if needed (not before). You now have a proven model.
6. **Want to scale further?** — Consider funding only with a proven, profitable product. Funding is optional jet fuel, not a prerequisite for takeoff.

Build → validate → monetize → hire → scale. Always in that order. Never skip steps. Never reverse the order.
