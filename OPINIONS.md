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

## Buying-signal tier list (YT 2026-07-16 — hxolLxHiydg)

- Ranks signals on **effectiveness**, **accessibility**, **scalability** (from 8M+ sends/month across ~50 customers); “take this video with a grain of salt.”
- **S-tier:** custom triggers built for your business (e.g. new negative Google review for reputation management; a friend's satellite parking-lot AI) — “nothing beats custom triggers”; later adds **new in role** and **look-alike companies** (“I ran outbound for clay.com. You are a competitor…”) to S.
- **A-tier:** general growth signals (used as a **filter**, not in copy — first list is often just 1% headcount growth in last 6 months; “more growth means more problems to solve”), competitor movements (“Everybody loves hearing about what their competitors are doing”), customer complaints (public reviews), job-post **descriptions** mined for problems/tech stack (not “I noticed you're hiring an SDR”), tech-stack signals (displace/integrate/filter sophistication), website visitors (score first, never reveal), social activity (filter only, never mention).
- **B-tier:** department growth, marketing-channel intelligence, lawsuits/compliance (let time pass so it isn't predatory). **C-tier:** search-visibility gaps (S only for SEO-type sellers), funding (filter only — banned from copy), pricing change (not scalable). **D-tier:** M&A/PE activity, cost-cutting/layoffs (“they're not buying anything”), product launch (“you missed the boat”).

## Speedrun $50k affiliate sprint + reply framework (YT 2026-09-10 — -LjvwKOIH9Y)

- ~106k emails in <30 days → 373 positives (1 per 286) → ~62% booking → 231 meetings, pay-per-attended-call; “We never do performance deals, but this offer was so great” he took the upside.
- Speed came from **always keeping generic inboxes warming** (a fraction of spend always in warmup) and **aged domains** (“The age of the domain 100% matters” — ~3–4 days warmup then full tilt); tradeoff is losing brand control, so rarely for clients.
- Layer data providers (Sales Navigator as source of truth; none perfect, layered = best coverage) + LeadMagic catch-all validation + Clay filters (e.g. >80% US team).
- **Reply framework** (run by a Grok bot connected to calendar API): reply fast with two times **and** a calendar link (some hate links, some only book via links); next day “I lost both of those times” (Oren Klaff); third follow-up adds a company-specific reason to take the call; fourth repeats lost-times; then a warm caller.
- Takeaway: “cold email absolutely still works. You just need an offer that can really rip” — fundamentals (inbox-landing domains, right people, something interesting to say) never change.

## Opus 5 / company brain ops (YT 2026-08-11 — 4Kf3CkdvFTY)

- Agent-first ops: “I don't open our databases anymore… give the API keys to Claude.” Hundreds of skill files; newer models resolve ambiguity from past work.
- **Company brain** in Obsidian (SOPs, skills, all client comms) so the agent isn't bouncing to Fathom/Slack.
- Personal benchmark: dump all open ClickUp tasks (each with a plan) → one big plan with finish conditions → sub-agents do it. Also uses it for productized onboarding (~15 standard tasks), week-over-week performance diffs (deliverability vs list vs variables), domain monitoring with inbox-placement tests via browser automation, skills that survive compaction, and video→LinkedIn posts with no em dashes / “it's not this, it's this.”
- Cost matters: a model that is great but burns the week's usage in a day is “not even worth using.”

## Segmentation, spam keywords, infra (Felipe Fuhr podcast 2026-05-22 — kvwCrwZCcqA)

- AI/Codex makes **unlimited segmentation** cheap — pull the whole TAM with every data point up front, let AI propose variants; “you're now only bottlenecked by what you as a human can review.” Segment-level base copy (no AI) → spintax → light AI on top.
- Stays in control of the message: “I only want to AI generate the parts of the message that need to be AI generated.” Cheap token tactics: batch/flex API, cached prompt prefix, Claude/Codex sub-agents for small lists.
- Hypothesis (self-flagged “I might retract this”): **copy burns faster in spam filters than domains** — ran Codex goal-mode loops with ~1,000 MailReach placement tests to find spam keywords per customer (e.g. advisor, AI, billing, CRM, outreach, retainer, Stripe…), removed them, saw reply rates rise; plans weekly.
- Infra (May 2026): half Google (Zapmail) / half Outlook (Hypertide), Maildoso as over-provisioned redundancy; worth paying the premium vs self-building inbox setup. Friday reply-rate report; **~0.8% reply rate minimum** (ex-OOO) with variance allowance (May 2026; his later Sept 2026 posts state the Friday cut at <1% — treat ~1% as current); decisions purely on reply rate; spike in sender bounces → spintax hard. Microsoft placement feels out of his control — just shift to Google-only leads when a customer dips.
- List building: pick entry point (Google Maps vs LinkedIn bulk; customer-industry expansion + AI cleanup; Ocean/DiscoLike look-alikes + Exa loop with a kill rule; skip to look-alikes for un-LinkedIn niches); merge Blitz/Prospeo/QuickEnrich; store found emails, revalidate after 45 days. ~67% of ClickUp tasks were list building → codified one TAM workflow.
- Generic (role) emails at volume over personal emails (cost); personal emails never felt like the missing fix — “there's always another problem.”
- Excited by **auto-research for cold email** (Karpathy-style loop): AI reads positives/negatives, proposes next campaigns for approval — but give it all the data up front instead of letting it improvise enrichment.
- (May 2026) GEX handed positives to customers rather than appointment setting; Master Inbox service if a customer needs booking.

## Data market inflection / cancelled Apollo for a Claude list-building skill (YT 2026-08-16 — aq5r3_CMh-s)

- Cancelled Apollo mostly on price: “I think we're living in an inflection point in the data market right now.” What he actually needs is “a second copy of the LinkedIn database” with verified emails — now available from unlimited providers. Apollo is still useful for non-technical sales teams that want calls/sequences/tracking in one place.
- Company list first: “as soon as you get a really great company list, finding the contacts is the easy part, especially with AI.”
- Industry fields are self-reported and miss niche ICPs (“there's no such thing as a peptide manufacturing industry”), so: seed from the customer's do-not-contact / closed-won list → find every industry and keyword those seeds carry → lookalike expansion (Prospeo, Exa Find Similar, Parallel entity search) → pull everything that could match → cheap model judge (GPT-5 Nano) → homepage audit. Claims ~85% of TAM; peptide example 70 companies vs 32 from one provider alone.
- Discloses relationships: pays full price for GetLeads, Blitz, QuickEnrich; gets limited free Prospeo credits.

## Layer unlimited data providers (YT 2026-09-03 — 1oMFYHCau68; 2026-09-08 — VkWbdCTACYM)

- Coverage test vs Sales Navigator sample (2,500 random profiles → 966 companies → 452k employees): Blitz 58%, GetLeads 55%, Prospeo 49%, QuickEnrich lowest; union 82%. “if you can afford it, you should really be buying all of the data providers.” One tool only → Blitz (“best second copy of LinkedIn”). Run the $8 test on your own market.
- Each tool has a lane: Prospeo best company/job filters (but likely drops people with multiple current roles); GetLeads includes mobiles; QuickEnrich for off-LinkedIn owners/founders; Blitz adds unlimited jobs.
- Department headcount can matter more than total headcount: in their B2B database 76% of companies had zero salespeople; Clay Audiences now filters by department size directly, which saves the old count-then-pull API loop.

## Boring AI workflows that still win (YT 2026-07-14 — Ct4AUtQnIYE)

- Simple systems over sophistication: a scheduled research agent (Parallel task API in Slack, Claude Code/Codex scheduled tasks) that finds “three leads every single day” matching a high-intent criterion, deduped against past suggestions.
- Event sponsor/attendee lists via a research agent; then find decision makers with Clay/Prospeo.
- Dream 100 → Dream 1,000/10,000: read the job description they're hiring for, do a slice of that work with your own skills/APIs, and send it as free value. Research is the easy part to automate; “The hardest part is writing the message.”

## Full outbound stack 2026 — sourcing, email finding, sequencers, recycling (Aimfox livestream 2026-07-01 — BzexTQOt0NM)

Guest livestream (host Aimfox; Eric labeled). Backlog body fetched 2026-10-07. Caption wording approximate. Host's Aimfox pitches are not his.

- **Sourcing:** “very Prospector first” for its filters (even Google-keyword filters), then Blitz API (~$500/month, 10M credits) to pull everyone and trim with AI; Clay audiences (mixes 3–5 providers underneath). Four kinds of list building: bulk (one source is fine, e.g. PE owners 10–100 employees or Google Maps plumbers) vs messy industries.
- **Messy industries → reverse-enrich + ICP prompt loop:** enrich the customer's do-not-contact list backwards to see how buyers show up in each database, pull every company in any industry they self-tag (cheap to score), then run an “ICP prompt loop” — sub-agents review 10 at a time, he corrects by voice, good examples get added to the prompt. The frontier model (“the A student”) writes the prompt; a cheap model (“the B student”) runs it via batch API or local open-source models. AI look-alikes alone miss breadth.
- **Models:** uses Gemma/open-source locally for cost; “I refuse to use the Chinese model.”
- **Contact & email finding:** for local owners, plain Google search + scrape beat seven AI search providers; SMTP permutation finder gets ~40%; then catch-all solvers in a cost/rate-limit waterfall (Quick Enrich → Blitz → ICPs → Prospeo/BounceBan → Smartlead finder → LeadMagic). No owner email? “Hey, Todd” to info@ works (dentists reply from info@). Sales Navigator only when you must be 100% sure they work there now (new hires, active posters).
- **Benchmarks:** ~1% reply rate (ex-OOO) is fine; 10–20% of replies positive; over 20% may mean you're off-ICP. “all conversion rates trend towards zero” — his positive ratio went from ~1/350 two years ago to ~1/600. UK (e.g. financial advisors) replies unusually high.
- **Sequencers/inboxes are commodities:** “the technology that underlies all of these platforms is all the same” — pick for integrations/APIs; Instantly = iPhone (beginners), Smartlead = Android (customizable); Google inboxes via cheap admin-console providers; moved off Azure/Outlook to Google after a reply-rate crisis. Put the effort into offers instead.
- **Offers: show what they didn't know was possible:** campaign order — make more money, then save time, then save money “in a way that you didn't know was possible” (e.g. $3 vs $7 Google inboxes). GEO-audit openers (“I asked ChatGPT…”) are now table stakes — do something cooler.
- **LinkedIn alongside email:** priority-scheduled campaigns — positive email replies get an instant connection request; ICP website visitors next; no-email targets with 500+ connections fill spare capacity. Rented avatar accounts make it scale; a 2–3-rep day-1/day-3 multichannel cadence won't.
- **Recycling + brand:** don't reuse a lead for a quarter; sequences are two emails, three at worst; people don't remember cold emails (“Can you name the company that cold emailed you?”) — you hurt your brand only by being atrociously wrong or ignoring unsubscribes; space sends so their business can change.
- **Deliverability:** for Microsoft/Mimecast/Proofpoint only domain age matters (aged or expired domains; “nobody cares about what domain you're sending from”); judge by reply rate per domain and kill outliers; ~3 inboxes per domain (1 too careful, 10 wrong); “when an inbox is dead, it's dead” — keep warmed insurance inboxes rather than rotating. AI reply handling should be a skill, not if-then rules. Screenshots of 15% reply rates are usually no-brainer offers, re-engagements or event coffees.

## List building + list-is-the-message (Smartlead Cold to Close Ep 1, 2026-04-20 — BRZJjgou7ic)

Guest podcast (Smartlead host; Eric addressed by name). Backlog body fetched 2026-10-07.

- Likes wholesale B2B (fasteners, labels, Bissell vacuums to hotels) because those industries “have not picked up on the cold email best practices” SaaS has. Hardest part is the list: Google Maps every US zip code × keywords to cover buyers without LinkedIn, then exclude-and-expand via Disco Like MCP, ICP-score with Claude Code/Codex sub-agents on cheaper models, and look-alike search (Parallel/Exa) through the same ICP prompt loop.
- “the list is the message” (not his line); generic AI personalization's edge is gone — rule of thumb: “if another one of our customers were able to use this AI prompt, we probably shouldn't use it.” Uses AI only when it recreates the best manual email (e.g. citing bad Google reviews).
- GEX by end of 2026: the team manages agents doing most of the work, ships more experiments faster, and invests in client-facing talent instead of “the button clicking.”


## Perfect cold email anatomy + five pillars of a cold-traffic offer (Cold Outbound Clips 2026-07-27 — xytg7S_yUGQ; 2026-08-12 — oBoYmrI4Nhk)

Solo videos on his Cold Outbound Clips channel (auto-captions; wording approximate). Deepens the five-point cold-offer rubric above.

- **Most offers are warm-traffic offers pushed at cold audiences:** that's the main reason outbound, ads and marketing fail. Decide whether you're capturing existing demand or generating new demand.
- **Pillar 1 — the offer:** of the B2B offers (make money, save time, save money, reduce risk), “make more money offers convert better than anything else.” Save time/money only lands when it's ~90% / demonstrable (Instantly's flat-price inboxes vs per-seat tools, until the mechanism became known). Reduce-risk offers: “I have never seen that work in a cold email campaign. Just throw it away.” Fold a guarantee into the framing.
- **Pillar 2 — deep research/targeting** creates the offer and is the only rescue for a warm-traffic offer. **Pillar 3 — a mechanism they didn't know was possible** (Salesflare's LinkedIn-to-CRM logging extension, AimLogic's competitor-site audiences); known plays (AEO audits) deteriorate as the market sees them. **Pillar 4 — a free, valuable next step that pulls them closer:** Loom audits and free gifts get yeses but “too many hand raisers and not enough meetings booked” — move the gift behind the call (chocolate: ship chocolate on the call, $200 card after). **Pillar 5 — proof that transfers** (Clay $150K→$2.2M ARR as employee ~10; Reddit advertiser playbook pitched to Twitter).
- **A “perfect” email is one where the framework can't be beaten,** only the copy polished: Google review removal (“Karen's review”, pay only when removed, P.S. naming a second review as an out), LinkedIn scheduler (last post N days ago, reply “post” for a pre-loaded 7-day trial), explainer video (names their plan tiers), Reddit ads (import their Facebook library + $500 credits). Review-removal targeting 3.8–4.3 star businesses ran ~1 positive per 80–120 contacts.
- **Checklist when you can't use every lever:** why them, why now, relevant social proof, proof we actually looked (specificity), cost of the pain, risk reversal, what they get for yes, is the CTA worth taking on its own, pre-handled objection, effort asymmetry, reciprocity — “even just one of them” improves the copy. Always ask what objection the message creates. Skip social proof from names they won't recognize if the offer is strong.

## Cold email takes from X, age-band catch-up (incremental 2026-10-10 — X originals 2023-10→2026-04, API via `x` tools)

Sampled posts from the 6–24 month and 24–36 month bands (spread across time, mostly originals plus a few replies). Not a full timeline; nothing older than 3 years.

- **Offer beats everything:** on a customer who followed him to a new company after only 2 leads at the last one: “Offer is more important than anything.” (https://x.com/ENowoslawski/status/1894160445885293048) And humility about it: “The difference between a great agency owner and a good agency owner is knowing not to brag when your client's offer really did all the work” (…/status/1747422478811464155).
- **Don't obsess over the sending domain:** “we are getting positive responses from domains named "godomainweuseforoutbound"” / “I always laugh when people obsess over the domains they send from” (…/status/1794100253710262470). (Later, 2026, he adds that infrastructure aging and copy variation do matter — see the deliverability section below.)
- **Fix the bottleneck, case studies first:** “I can fix a company's outbound bottleneck for free within 10 minutes and they don't even need to hire me” (…/status/1843338525355454596). Clients ask about case studies “but when we onboard them they don't have case studies to use in their outbound campaigns...” (…/status/1833895278405186044).
- **Start big, learn from volume:** “We start every customer with 200 inboxes.” Small samples are “just not enough volume to know anything.” (…/status/2033988193410851171) In Dec 2023 he posted how many cold emails they send in a month (“I'm a menace to society...”).
- **Onboarding promise (Apr 2024):** Month 1 = full account TAM with scoring, full contact TAM with valid emails/mobiles, message-market fit testing with a four-phase approach of best templates, “Launch in 3 days not 3 weeks.” (…/status/1778547054089740316)
- **Automated Google searches validate accounts:** “Automated Google searches are the secret weapon of B2B account validation” — check company news, case-study-page keywords, careers-page keywords. (…/status/1732398867033805044)
- **Give away list-based lead magnets:** free weekly new-hire reports, a list of VPs of Sales/CROs at B2B SaaS, 15 outbound playbooks, a 53-page doc of 58 campaigns — all via comment-to-get-it. “Just trying to make free stuff so good, it's better than things people pay for.” (…/status/1725178545327018416, …/status/1730231065564807171, …/status/1745843917621248212, …/status/1895584365876588789)
- **Cold-email pet peeves:** promising a Loom and not sending it (“someone saying they have a phenomenal idea about how I could grow my business and that they already made a loom video for me, but not sending the loom video”); calling yourself industry-leading with 2 employees; cold agency owners asking for your email. (…/status/1849434745681121595, …/status/1846265863994831328, …/status/1868691423635349700)
- **Holiday slowdown test:** “One of our customers gets 10-20 leads per day on average... Today we got 26. Keep sending emails” (…/status/1868840214577480115). Early warning on deliverability: “things are feeling a little too good right now. I feel an email deliverability change coming to slap us in the face...” (…/status/1904955553903706277)

## AI tooling stance 2025–2026 (incremental 2026-10-10 — X originals)

- **AI scales a no-code team:** “Whole team getting access to @cursor_ai today. No one on the team can code but it's already having a huge impact on the company.” “It really feels like the promise of AI expanding your team is being fulfilled with things like a cursor and Claude skills in a way that wasn't possible even three months ago.” (…/status/1985704498656842215, …/status/1990200676920774814)
- **Lean stack:** “I usually try to keep my stack really lean so I don't use much outside of ChatGPT and cursor”; uses AI Studio for quick RAGs and Claude Code for sub-agents and task agents. When Claude usage limits bit he set up Codex “so I can use both interchangeably.” (…/status/1997449710593097748, …/status/2039337446635106502)
- **Cheap data APIs are worth testing:** on Blitz API, “So far, accurate contact finding for sure. product is a little young and the filters need to be very exact, but for this pricing, geez.” (…/status/1995338423708569763) He runs bulk jobs like “Automatically processed 1.2M contacts to refill 12 of our campaigns today.” (…/status/1997861222914654644)
- **Give the walkthrough, not the prompt:** “If I create a YouTube video going over the exact step-by-step process of how I did something in @cursor_ai and you then ask me for the prompt I got started with in my DM‘s. I'm sorry, but you're not gonna make it.” (…/status/1990568254524559811)
- **Channel doubt:** “I think all the time about just giving up and moving all my effort to x because I spend most of my time consuming content here and never really look at my own feed.” (…/status/2039882255384838361)

## Deliverability arms race 2026 — Gmail's filter + super spintax (stored YT body wDLLXq9GEpI "Gmail's Spam Filter Started Using LLMs (Here's Our Fix)", Eric solo; captions approx.)

- **Environment:** he believes Google and Outlook now use LLMs in spam filters and that cheap inboxes plus “unlimited data for really, really, really cheap” make it harder; at his agency they generate 200–300 positive responses a day. Example: one client went from a 0.41% reply rate in a bad inbox period to 3.34% after changes, and only one change was infrastructure.
- **Super spintax:** a year earlier he wasn't a fan; now “spin tax absolutely is helping us last longer with inboxes, and then also increase our reply rate.” A 40% sender-bounce rate went away after adding about 20 variations to the subject line and unsubscribe language; also spin the signature (name forms, titles, company variants, even case-study lines). Claude skills write the variants.
- **Change copy, not just domains:** swapping domains and inboxes used to restore reply rates; now when a campaign fades he also rewrites the copy (one case: ~0.2% to ~1.2% from copy alone) to break the spam fingerprint.
- **Buy domains early, keep insurance inboxes:** domains bought and parked so they're about 14 weeks old when used; sizes capacity at roughly double planned sends and keeps ~50% insurance inboxes; 30 emails/day per Gmail inbox; Gmail inboxes only; two inboxes per domain, then stack up to five on outlier winners.
- **Kill weekly:** report all inboxes weekly, kill anything under 1% reply rate (about 10–15% of infrastructure), keep a database of active vs insurance inboxes and rotate in a ready replacement. He credits others for specific tactics (Nikita at Maildoso for super spintax; Felipe for stacking winners and signature variants).
- **Caveat:** results are his own split tests (e.g. an enterprise-hosting inbox product gave roughly 20–50% lift depending on campaign); no vendor recommendation implied.

## 20 playbooks in Clay + agent skills (stored YT body qmi5B-N3Ev8 "My Favorite Cold Email Strategy for Getting Clients (with proof)", Eric solo; captions approx.)

- **Audiences = the list-building upgrade:** ask Clay in plain English for e.g. directors-and-above in the US who started a new role in the last two months; the audience keeps adding new people automatically, and a second table enriches them; he gives the new-in-role list away free.
- **Hiring surge as a signal:** compare headcount of a department against hires in the last six months to get a percentage growth per company.
- **Two-source checks:** technology on website (Prospeo/Wappalyzer first, HTML check second); Facebook ad library via a Google search then an Apify scraper with a second way to find the Facebook URL; case-study pages by guessing common URL paths first (free) and falling back to an AI agent at about a tenth of a cent.
- **Google `site:` filter as a qualifier:** find whether a company mentions e.g. SOC 2 or a law specialty on its own site; use the cheapest Google search providers.
- **Creative ideas campaign:** three bullets on how he'd help the company based on its description and the recipient's title — “This has been the best performing campaign” for large and small clients alike. The AI specificity campaign is one sentence on how he'd help.
