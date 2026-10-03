# OPINIONS

Sourced public positions. Every item has evidence in the public evidence grounding for this distillation.

## Diagnose campaigns in three buckets

- Problems are **infrastructure**, **list**, or **offer/copy** — check in that order before tweaking random variables.
- Positive replies come from how you send, who you email, and what you say (offer + copy + strategy).

## Deliverability ladder (ops, not vibes)

- Warm-up reputation alone is not enough; treat sub-~99 as suspicious and auto-pull ~92%.
- Seed tests are directional only (seed inboxes never mark spam like humans).
- Real gate: domains/inboxes with ≥100 sends and **&lt;1% reply rate** get cancelled / pulled (Friday automation).
- Keep **insurance / backup capacity** (~50% extra) warming so swaps have zero downtime.
- Dead-mailbox auto-reply pools: expect ~80% bounce-back; **kill under ~60%**.
- Prolong inbox life with high-positive side campaigns (candidate sourcing, partnerships), not only warmup bots Google already recognizes.
- Sudden drops (e.g. 1.5% → 0.2%) warrant immediate spam-trap / fingerprint checks; add **spintax** on body, signatures, unsubscribes when needed.
- Never send cold volume from the **main domain**.
- Warming on cheap SMTP then switching to Google when needed can work (operator claim).

## Offers over shallow personalization

- Craft **cold-traffic offers**; prefer make-money framing over pure save-time/save-money when possible.
- Offer so strong prospects would pay for the discovery call; answer why they wouldn’t respond up front.
- Free / risk-reversed test campaigns remove buyer risk.
- “Creative ideas” campaign (constrain AI to real offerings, personalize application per company) is a top evergreen performer across clients.
- AI in email should recreate what a manual researcher would write (often 1–12 words), not summarize LinkedIn bio / college / past jobs as “personalization.”
- Don’t let AI invent deliverables you can’t ship — constrain bullets to real capabilities.
- Personalized first lines only when you genuinely have data tied to pain — not generic “saw you help people with…” filler.

## Lists, TAM, fit

- Cold outbound fits large TAMs (article: **&gt;100k** contacts; site: **100k+** best fit / under ~40k usually not) and healthy unit economics (article: LTV **&gt;$10k**, CAC:LTV ideally 1:10 / ok 1:3; site: lifetime gross profit over ~$5k, sales team in place).
- Signals alone are not a silver bullet; test broadly and find durable winners.
- ICP classification and enrichment at Clay-scale; push volume through Clay webhooks / Supabase for GTM data.

## Volume / infra mindset

- Run many campaign variations fast; find winners, then pile on.
- Kill weak domains weekly (Friday &lt;1% reply; bottom decile rotation in LinkedIn ops posts).
- ~30 emails/day/inbox is a tested safe sending pace vs burning at 50–60 after short warmup.
- Stack tools pragmatically (Clay, Smartlead, Hypertide/Zapmail, Supabase, ClickUp for non-technical version history).


## Three cold-email campaign components (problem / proof / magnet)

- Best campaigns stack **problem sniffing**, **extremely relevant social proof**, and a **lead magnet so good they can’t say no**; components also work alone, and everyone can use a lead magnet when the first two aren’t available.
- Problem sniffing: research (manual or automated) to name a specific public problem and offer to fix it (Yelp/G2 reviews, declining traffic, hiring, raises).
- Extremely relevant social proof: niche the case study to a near-twin (e.g. credit union with wealth management, not “another bank”) — cold email is “outrunning the bear.”
- Lead magnets sit on a **value vs effort** line: high value, low fulfillment effort; lean on economies of scale and market insights. Prefer magnets people already pay for elsewhere (or don’t know are possible) over fake “usually $2,497” free courses / mediocre webinars.
- Strong agency opener: **already-found leads** (“I’ve already found these leads for you”) beats generic performance guarantees — but it’s high effort, so use sparingly.
- Brand/content is a fourth layer: prospects look up the site after the email; outbound alone with empty social proof underperforms.

## GTM engineering bar

- “GTM engineering” should be real engineering (audits, systems, automations), not only dashboards + launching campaigns.


## Cold vs warm traffic + 5-point cold offer (YT 2026-09-29 talk)

- **Cold vs warm is the first fork:** When someone asks for a new marketing channel, ask whether they can convert *cold* traffic or only *warm*. Some businesses can never create a cold-traffic offer (e.g. funeral homes) — they need warm demand.
- **Warm-traffic offers fail as cold outbound:** Paid events, cybersecurity/SOC2, sales coaching/consulting — people don’t buy these cold. Free events can work cold; paid events won’t. Treat warm offers as warm playbooks (partners, ads, organic), not spam cannons.
- **Cold-traffic offer examples that crush:** “Do you want to be in Forbes?” (100+ leads/day claimed); Google reputation management on a performance basis (remove negative reviews — only paid after removal). HubSpot/Reddit/ClickUp-scale clients in past book.
- **Five-point cold-offer rubric** (from 6+ month client copy): (1) **New money** promise beats save-money/save-time unless the savings are inordinate — and you can often reframe save-time into make-money; (2) **New mechanism** they’ve never heard of; (3) **Insight/audit** they didn’t know; (4) **Hyper research** narrow ICP moment; (5) **Relevant case studies** near-twin proof.
- **Always-on playbooks:** Warm — close-lost re-engagement, demo abandonment, own-social engagers. Cold — mutual school/company overlap, recently/first hired, tech-stack-in-JD, download sales-team LinkedIn connections + enrich against TAM, social-post keyword liking (message the problem, **don’t say you saw them like the post**), website visitors (**don’t say you saw them on the site**).
- **GTM engineering ≠ Claude + 3 APIs + spam cannon:** Real GTME runs the playbook checklist and engineers cold-traffic offers/lead magnets (programmatic audits, GTM hubs with emails/mobiles/new hires/warm overlap). Validate magnet interest before building (“can I send the Google file?”) — don’t waste time perfecting magnets nobody wants. Prefer giving away for free what others charge for.


## Grokbot + Clay + Jev campaign stack (X browser-fallback 2026-09-22)

- **Role split for launching outbound campaigns:** Grok bot as planner / launch partner; **Jev** to confirm ICP fit and that enrichment data is verifiable; **Clay** to find emails and write custom messaging.
- **Self-prospecting filter:** hunt companies with **make-money offers** and a **wide TAM** (same cold-traffic / economics bar as elsewhere).
- Example campaign ICPs he launched in one stretch: (1) self-prospect make-money + wide TAM, (2) businesses that want to **sell their data to AI labs**, (3) **Shopify** sites with broken integration code that a development agency can repair.


## Past-experience / ex-customer employee playbook (X browser-fallback 2026-09-17)

- **Favorite list playbook:** enrich for **past experience**, not only where people work now — “so much gold in people's past experiences.”
- For established businesses, **track people who used to work at your customers**; he says that motion “has never failed for us.”
- Unlimited profile enrichment (called out via **BlitzAPI** in this post) that includes full past experience on the target list makes the playbook cheap to run.
- Workflow: dump customer CSV vs prospect CSV into an agent stack (Claude / Jev / Codex / Cursor / Grok / GrokBot / etc.) and “let it rip.”
- Claimed to work **whether or not** they worked at the company while it was a customer — “The familiarity is everything.”


## Paid media exploration (X browser-fallback 2026-10-02)

- Early learning notes while **starting to try paid media** (not a finished media-buying doctrine).
- Pattern he keeps hearing in demos: (1) **test way more creative** than you thought; (2) platform UI suggestions / buttons are often a **waste of money**; (3) **match the funnel/offer** to how your sales team sells and to your financial model.
- Tone: amused at how every “getting into media buying” demo is basically “yeah they make this suggestion, but that’s a waste of money — don’t do that.”


## Clay CLI + agent build loop (YT 2026-09-03)

- Prefer building Clay tables via **Clay CLI** directed by voice/agent (WhisperFlow → CLI expert → live workspace link) over hand-clicking every column.
- Typical enrichment chain shown: normalize name/title → **Prospectio** work email → **Million Verifier** → only then enrich company → push to **SmartLead**; ship the build to **GrokBot** to finish or watch live.
- Treat GrokBot as the closer for shipping the table once the CLI scaffold exists.


## Competitor LinkedIn engagement lists (YT 2026-09-04)

- Favorite list play: people engaging with **competitors’ LinkedIn** (company or person pages) — problem-and-solution aware; name-drop case studies they already trust (e.g. ClickUp) without surveillance openers.
- **Never** email “Hey, I saw you liking this person’s post…” — use engagement only as **list filtering**; send the best problem/offer message.
- **Punch up:** steal engagement from industry titans / larger companies; weird to harvest niche up-and-comers with ~5k followers.
- Tooling shift: old RapidAPI LinkedIn path **died** (severe rate limits); now prefers **Apify HarvestAPI** even though pricier — “willing to pay the money.”
