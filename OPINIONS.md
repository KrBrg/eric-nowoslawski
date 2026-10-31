# OPINIONS

Sourced public positions from his public writing and speech.

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

## Claude Code for the data plumbing, Clay for the last mile (stored YT body s2hShfYo7Wo "How We Send 8M Cold Emails/Month with Claude and Clay.com", Eric solo; undated, cites a February analytics week; captions approx.)

- **Why a pipeline at all:** Clay queues rate limits well, but his team kept hammering endpoints at 8 a.m. while uploading CSVs, so now everything processes at 2 a.m. He also needs to forecast how many sendable leads a list really holds, since only about 50–70% of found emails validate.
- **Claude Code builds the boring, repeatable parts:** a Prospeo search scrape into Supabase, deduped on LinkedIn URL and email, a cached email waterfall run hourly via edge functions, and trigger.dev firing webhooks to Clay tables each night. He says it replaced three people whose whole job was moving CSVs.
- **Email waterfall order:** cache first (reuse if validated under 90 days ago, else re-verify), then Prospeo (fast, BounceBan-validated catch-alls he chose not to re-verify), then Smartlead's lookup last because it is slower but built on real sending data.
- **Clay stays as the final-mile layer:** he rejects the "Eric only uses Claude Code now" story. For segmentation, per-title messaging and AI enrichment he wants a visual table he can inspect and a host that runs it, not a brittle vibe-coded tool (his own internal tool "breaks all the time").
- **Scale guidance:** under about 5,000 emails a day just use Clay natively; from roughly 1,000–2,000 a day start caching found emails to save money. Practical tip: Clay webhooks are limited per workspace, so send about 25 contacts per webhook.


## Data-brokering offer: highest-responding lists (X 2026-10-14 — 2110413976307675326)

- For the **data brokering** offer (selling company data to AI labs / similar), the lists that respond highest for Growth Engine X, ranked: (1) **people near retirement age** guessed from college graduation year; (2) **bankrupt companies**; (3) **founders with sales backgrounds** — “By far the absolute best”; (4) **people that responded** (prior responders; post text cuts off there).
- Treats data-brokering as **side work**, not a full-time reinvention: when peers change their whole offer for it, he pushes back — “This is just side work” / “How could you work full-time on something that’s printing leads right now managed by AI?” (reply 2110414411500257581).

## AI-generated lead magnets / testing machine / five GTM builds / Maps owner finder (Growth Drops site writeups 2026-02-09→2026-02-11, coldoutbound.com, first-person on Growth Engine X's site; distilled 2026-10-16)

First-party site writeups of his videos, written in first person on his agency site (coldoutbound.com, where growthenginex.com now redirects). Tool names and prices are his examples, not endorsements. Numbers are his stated results.

- **He changed his mind on AI personalization:** the old goal, an email as good as 10 minutes of research, is now “an A-tier email. Not bad. Still great. But not S-tier.” S-tier asks what value you can give prospects “without ever speaking to them, at scale.” His best-responding customers all have “something easy to say yes to.”
- **Three buckets of AI lead magnets:** knowledge (intelligence reports, e.g. a Parallel.ai query run after a positive reply for about $1, dropped into Gamma), micro apps (a weekend Lovable/Cursor tool such as a free email finder off your own send database, an audit, a lighter product with no security review), and agentic service trials (they cracked an AI-run first campaign for qualified prospects: at least one salesperson, B2B, TAM over 100,000, LTV $5,000+; the email becomes “we got you a lead”). Mistake to avoid: building before anyone cares. “Test demand first, build second.” Give 80% of the value up front, hook the last 20% to the call.
- **Cold email testing should work like Facebook ads:** the clients who test the most win (1,500 campaigns and 60,000+ positive replies last year, analyzed in Supabase with Claude Code). Three Claude skills run it: campaign strategy (broad / focused / niche, 10–20 ideas per client), campaign scoring against rules ~30 sub-agents pulled from past analytics, and copywriting trained on ~20 docs of winners plus copywriters like Josh Braun. Claude Code builds the if/then routing plan and gets asked “Are there any gaps in this plan we haven't thought about?” Clay stays for enrichment; Trigger.dev/Railway workers hold the routing. Smaller, more granular tests help deliverability, learning, risk, and compounding insight.
- **Five GTM builds instead of install tutorials:** (1) enrich your customers and let Claude Code find the true ICP (a client's AE:SDR ratio didn't matter; having a sales ops person did); (2) build the TAM programmatically (Prospeo search: 1 credit = 25 contacts) and tier it; (3) dump every Fathom transcript into one file and mine it; (4) store it all in Supabase without knowing databases; (5) recursive data-quality tests of providers and prompts against first-party truth, “the spiciest project.” His context: never coded before, “over 2 million lines of code in the last 39 days.”
- **Google Maps owner finder:** scraping Maps is solved and cheap; the hard part is the owner. Waterfall: LinkedIn first, then a plain Node fetch of the homepage plus up to 20 second-level pages, then an open-source model on a rented Vast.ai GPU (~$0.69/hour, 13–16 requests/second) asked who the owner is with proof, verified a second time because it is nearly free, then Google search fallback. Emails: Prospeo → Smartlead finder (real send/bounce data) → website generic emails; even info@ works when you can say “Hey, Bob.” One run: 10,000 businesses → 7,542 owner names and 3,246 emails.

## Social volume (X 2026-10-15)

- **Inundate the feed:** on who first crushed B2B socials: “Info businesses in my opinion,” Lemlist as the first B2B SaaS he can think of “from 6 years ago,” and his own pitch at Clay: post like Grant Cardone, “we need to inundate the feed.” Agrees that “Quantity is a quality of itself.”

## Late-2025 Growth Drops backlog: first principles, 10M-email lessons, meetings per positive, deliverability update (coldoutbound.com site writeups 2025-10-15→2025-11-17, first-person on Growth Engine X's site; distilled 2026-10-17)

Dated late 2025. Where a newer 2026 take above differs (super spintax, LLM spam filters, unlimited data providers), the 2026 take wins. Tool names (Porkbun, Dynadot, Hypertide, Clay, Exa, Ocean.io, OpenRouter, Lead Magic) are his examples, not endorsements. Numbers are his stated results.

- **Three pillars, not permission questions:** “Am I allowed to send images in a cold email?” is the wrong question; “The right question is: does it work?” Every question comes back to deliverability (they see it), list quality (right person), and campaign strategy (valuable to them). Deliverability guide: “What do spammers do, and how can I do the opposite?”
- **Disposable domains, insurance pool:** “Today? Throw it away.” Fixing “a $12 domain with a $6 inbox” is wasted time; keep a 1:1 insurance pool (minimum 1:2), build 5,000/day capacity even when a client starts at 500–1,500, and keep inboxes in three states: active, insurance, fresh orders. “Dead inboxes don't recover.” Cancel, swap, reorder.
- **Four kill signals (2025-10-15 version):** campaign reply rate under 1% (0.8% in a hard market), inbox warm-up reputation under 98% (automated), weekly domain-level reply rate under 1% or bottom 10%, bounce rate over 2%. A month later he also lists open tracking for two days as a last-resort check, while the earlier piece says “We Stopped Tracking Open Rates” because replies dropped on tracking days. Treat open tracking as contested; he leans against it.
- **Volume and aging:** start at 30 emails per inbox per day, up to 50 on a 2%+ campaign; if you must start on day one, 5 a day at 1 an hour. Domain age matters more over time: four weeks of warm-up minimum, six as the aim; stagger batches at 2 weeks, 4 weeks and 2 months; buy domains in bulk on registrar sales and let them age about 3 months. Outlook and Proofpoint need aged domains and shorter copy; send Gmail-only for the first 2–3 weeks if ROI isn't there yet. “Domain Names Do Not Matter as Much as You Think,” per the heading.
- **Lists forward, backward, circular:** forward from database filters; backward from the client's customer and pipeline list (“This is the approach I want my team doing most often”); circular lookalike loops with a cheap reasoning model as judge and a kill condition (under 15% good fits after 10 batches). The 10-minute rule: what would you check researching a company for 10 minutes, then automate it. Record yourself on Loom talking through the manual check and turn that into the prompt.
- **Campaign craft (2025):** problem-aware markets can just say what you do; crowded offers need a lead magnet or creative offer. Creative ideas campaign (three custom bullets) is the top format “for three and a half years.” Explain why you need their time in the CTA (his reputation-management CTA rewrite did 2.5x). Preview text over subject lines. Tie the lead magnet to the call. Test whole chunks of messaging, not single words. Only three things go wrong: the copy, not enough Email 1s, or burned inboxes. “The offer often matters more than the personalization.”
- **Meetings per positive reply:** reply fast with two specific times plus a calendar link; multi-thread with LinkedIn and a call; never “just checking in.” Raise the stakes instead: match them to a specific case study, do free work in the email, then combine. Status alignment: “I lost Tuesday at 10 to another person.” Bold move: send a calendar invite marked as available.
- **Writing for the reader's AI (X 2026-10-16):** “If we think they are using superhuman, we send way more context in the email and literally say "this part of the email is written for your AI".”

## Rejoining Clay; Growth Engine X keeps running (X 2026-10-17..19 + LinkedIn ~2026-10-13)

- **Status (time-bound, as of 2026-10-19):** I'm back at Clay as an employee (“395 first day back at @clay”). Growth Engine X keeps running with my team and me as an advisor: “They offered me a stock deal to come back I couldnt turn down. my team is running it with me as an advisor. they closed 3 deals last week.” Gabe Emerson on the team now runs the free-campaign sales process.
- **Free test before payment pays off in LTV:** “the lifetime value of a customer who passes a free test is four times that of a customer who doesn't pass a free test.” An agent launches free campaigns with the same success rate as manual launches, so they can accept as many as they want. “Yes, we do a lot of work that goes nowhere. But it's been completely worth it when you look at our LTV.” Mission stays: only ask people to pay after we prove results.
- **Speak the buyer's language to show expertise:** credits Oren Klaff's “flash roll” for the idea of speaking in the specific language of the person you're talking to, so the expertise is undeniable.
- **Cheap search plus AI is game changing for GTM:** on a new combined search-and-AI tool, “Cheapest that I know of with search and AI combined. Going straight to a Google scraper is still cheaper but you still need to process the output.”

## Work backwards from the customer list (Growth Drops backlog 2026-01-14, “Building Cold Outreach Lead Lists in 2026 with AI”, distilled 2026-10-20)

- **The data problem is self-reported LinkedIn input, not the tool:** “People love to blame the platform, but the platform is just scraping what LinkedIn gives them. The real issue is the quality of user input.”
- **Workflow:** enrich the existing customer list (titles, tenure, past companies, headline, industry, headcount), let a strong model find the buyer titles and industries, pull the full universe of matching companies (even the weird industries), score with a cheap model on cached inputs plus the batch API, then pull the real buyer titles from customer data. Aim for about 80% TAM coverage where every company is a real fit.
- **Self-checking prompt:** mix confirmed customers into the scoring set; if any fail, the prompt is wrong and should ask for more inputs. “Do not let the AI take the easy way out by just pattern-matching company descriptions.”
- **Cheap AI makes outlier industries worth pulling:** 60,000 companies scored “for pennies”; even 1,000 good fits are worth it.

## Unlimited search in Clay; Maps data is free (X 2026-10-21)

- **Unlimited search was the bet:** on cheap LinkedIn-scale data getting commoditized, “I pushed Clay so hard for unlimited search in the platform because I saw this coming.” Compares Blitz API at about $500 a month with “unlimited search on all clay tiers.”
- **Google Maps data in Clay is free:** “No need for serper.” It currently takes a small front-end workaround, which he says he is having engineering fix (status as of 2026-10-21, while back at Clay).

## Running Clay at scale: table rules and AI prompting rules (Growth Drops backlog 2025-10-20, “Lessons on Using Clay.com From Their Largest User”, distilled 2026-10-22)

Dated 2025, before he rejoined Clay. Model picks (GPT-4o mini) are dated; the habits are the point. Numbers are his stated results at the time.

- **Scale context:** 37 million rows in Clay in a single week, roughly 18 million contacts a month, 400+ active tables.
- **Conditional formulas on every paid integration:** “I don't care if the conditional formula is just "first name must not be empty." The point is building the habit.” No exceptions.
- **Functions for shared workflows:** one centralized workflow (for example CRM lookup, update or create) called by many tables, so a change happens once.
- **Save every paid enrichment:** Clay is middleware, not a database you own. Push anything you paid for to the CRM or Supabase; Supabase at about $30 a month held 11.4 million validated emails after the CRM API could not keep up.
- **Evergreen campaigns run themselves:** load the whole TAM into a cheap HubSpot, make a segment, connect it as a scheduled source so Clay keeps processing without CSV uploads.
- **Formulas over AI for anything deterministic:** cleaning, if/then, scoring, abbreviations. If it must be right every time and is not content generation, use a formula.
- **Prompting rules:** the 10-minute manual research rule (“Who cares what other people are doing?”); only let each AI call do one thing; give a single fallback keyword (“purple”) when nothing is found instead of trusting confidence scores; always include 3–4 hand-written examples; use a metaprompter and answer its clarifying questions out loud; ask for reasoning before the answer; expect 80% of the build to be edge-case prompting, fixed with rules and examples rather than bigger models.

## Clay CLI speed / key rotation (incremental 2026-10-23 — X 2026-10-22) and lead magnets (Growth Drops backlog 2025-07-18)

First-party X and coldoutbound.com Growth Drops (first person). Alex Hormozi frameworks are credited to Hormozi by Eric.

- **Big Clay jobs should take minutes with the CLI:** told someone whose Clay table took 12 hours that “you should be able to do this in under 15 minutes with the clay CLI”, and offered to get an engineer to look.
- **Rotate keys after a platform incident:** “Just finished rotating every key on Railway. do the same if you use them” (2026-10-22); still deciding where to move (“Maybe vercel or render”).
- **Three ways to find a lead magnet:** give away what others charge for (Hormozi), share insights only you have (“knowledge arbitrage”), make the first step of your delivery the lead magnet (Hormozi; e.g. a video agency storyboards your next video free).
- **Three lead-magnet mistakes:** not tied to the sales process (free chocolate got 8% replies and no calls until the demo became sending the box); not valuable enough (“If your lead magnet would not get engagement on LinkedIn, it is not going to get engagement in cold email either”); not qualifying first (free tests taken by people who never approve copy or can't close: “There are holes in the bucket”).
- **Build the magnet around the pattern in your Stripe data:** every Growth Engine X customer past 6 invoices saw results from their first campaign, so the lead magnet became a free first campaign to 2,000 people, after failed tries (DMARC help, free lists, broad new-hire lists) and a filterable new-hire list plus weekly newsletter (about 82% opens). “Marketing is just a fancy word for testing.” (as of 2025-07)

## Clay S tier (X 2026-10-23) and growth-signal lists (Growth Drops backlog 2025-07-25)

First-party X and coldoutbound.com Growth Drops (first person). Clay integrations named are his examples as of 2025-07.

- **Being hard on Clay from the inside:** thanked someone for ranking Clay S tier, “I'm getting hyper critical of the product right now in ways we can improve”, and “I will push to keep it that way” (2026-10-23, as a Clay employee).
- **Growth signals refine the list even if you never mention them:** “You don't have to use a "jobs playbook" outreach email just because you're targeting growing companies.” Use them to reach companies that are active and investing, not stagnant ones.
- **Six signals, cheapest first:** any open job (free with a Clay plan, limit 1 per company); job openings as a percentage of headcount (8% vs 1% tells you who is really hiring); 6-month headcount growth as a filter, used “directionally, not literally”; department headcount growth plus people under 3 months in role; recent hires you can name-drop; hiring in new cities (AI checks a 25-mile radius because keyword matching fails). Bonus: funding via Claygent, web traffic via SimilarWeb or Semrush. Combine signals on top of ICP filters.
- **Employee count vs self-reported size can diverge wildly:** pick the one that makes sense for the industry (freelancer-heavy vs offline workforces).
- **Never cite a growth percentage in the email; name the new hire:** “Do not email someone and say "Hey Google, I saw you've grown by 1.28%." Nobody wants to receive that.” Better: “saw Kunal just recently joined the team”. At 2–50 employees any new person works; at big companies filter by state or city.
- **Ask AI to explain its reasoning:** it makes results verifiable and, in his view, makes answers more accurate; ask for true/false first, then why.

## Feedback coming into the Clay seat (X 2026-10-24), Claygent vs regular AI (Growth Drops backlog 2025-07-29), Grok Bot + Clay setup (Clay blog 2026-10-07)

First-party X and coldoutbound.com Growth Drops (first person). The Clay blog item is a host write-up by Davide Grieco; those points are the host's reporting of what Eric does, not his own words. Tools named are his examples, not endorsements.

- **His product feedback as a Clay employee (time-bound, as of 2026-10-24):** asked for his main feedback coming into the seat, he listed: Clay's contact data loses head-to-head tests only because of the filtering that cleans out junk (good contacts sit in the back end, not the public product; “Clay is pretty unbeatable” for director-level and above), “We need to never lose a contact data request”, the sequencer is basic and should bake in the inbox-health and rotation strategies from his agency, onboarding should be more opinionated for outbound, TAM sourcing and CRM cleanup because there is one right way in about 80% of cases, new models should reach Claygent faster, and the CLI should learn from your existing tables how you like to build. The product should steer toward outcomes while keeping technical surfaces for people who want them. He says these are all known issues and the team “maybe needs to be better communicating we are on top of them.” Wants anyone who opts into outbound to be run through 8 playbooks automatically. On pricing: “all I’ll say is we’re working on pricing.” Tip for heavy users switching to the Clay CLI: ask it to learn how you like to build.
- **Wary of data-partner pitches since rejoining Clay:** he'd want to submit his vendor communications before suggesting a data partner, because people have been throwing a lot at him since the comeback; data partnerships are “a whole other thing”, but he'll bring his own data test to the team.
- **Claygent for live research, regular AI for everything else:** Claygent has internet access, so use it to find things (competitors, company description, recent news); regular AI transforms data, makes decisions and writes the final output. “We never use Claygent to output a sentence that goes into an email” because “you cannot train Claygent with examples. And examples are everything.” His agency rule: at least 2 examples (prefer 3) for one AI sentence, 5–7 for anything more complex.
- **Two-column pattern, one job per call:** Claygent fetches context, regular AI processes it with your examples. Don't ask Claygent to visit a site and decide if a company is B2B SaaS; fetch the description, then classify with regular AI trained on 5 examples. Regular AI with a cheap context source often beats Claygent on cost and quality.
- **Grok Bot as operator, Clay as infrastructure (per Clay blog write-up, 2026-10-07):** one bot per job and per client (per-campaign copywriting bot inside a hand-written template, on-request list building, a daily deliverability bot that drops the worst 30% of domains by replies vs sends, at-risk client checks twice a day); has the model draft prompts, marks the first 50 outputs good/bad by voice before running the full list; GTM Hubs (a ready-made prospecting package for one target company) as the lead magnet; a daily learning loop compares campaigns to positive-response targets, contained by ICP, the real goal (meetings, not replies), data done upfront, and hand-written templates with one marked test slot.

## Testing replies and Clay workflows (X 2026-10-25) and GPT-5 nano vs 4o mini (Growth Drops backlog 2025-08-10)

First-party X replies and coldoutbound.com Growth Drops (first person). Model prices and results are as of 2025-08 and will date fast.

- **Judge the message, and give it enough volume:** when someone shares a reply-rate framework he asks to see the actual message first (“What is the message you’re also sending them?”); adding a pitch helps “because they don’t know why you’re asking”, and a test of about 30 sends tells you nothing yet. Promised to write up a testing-framework (“gauntlet”) article.
- **Use the free sources first:** pointed someone at Clay's Google Maps source because “It’s free”.
- **Clay workflows already cover most asks (as a Clay employee, 2026-10-25):** told a user who wanted more that it “basically already exists in workflows”, that “In workflows things are unlimited”, audiences and plugins are already there, and the real ask is usually a better action price; rate limits are the actual constraint. Says he has raised a data question with Clay's data team.
- **Reasoning models are waste for simple outbound AI tasks (as of 2025-08):** side-by-side in Clay across case-study extraction, company news, first lines and CEO lookup, GPT-5 nano gave the same or worse output and cost more almost every time (2-10x), because reasoning tokens pile up (1,586 vs 38 output tokens for the same result). It also missed CEOs that 4o mini found. His call then: stay on 4o mini for high-volume cold email work, and test open-source models for plain prompt-and-output jobs. He said he used OpenAI exclusively at the time.

## Hard-to-reach contacts and the free Google Maps source (X 2026-10-26) and 11 tips for AI prompting in Clay (Growth Drops backlog 2025-08-22)

First-party X and coldoutbound.com Growth Drops (first person). Tools named are his examples, not endorsements. He speaks as a Clay employee on Clay topics. Model choices are as of 2025-08 and will date.

- **Go after the contacts nobody else emails:** “Contacts who get emailed less than average reply 3.2x more” (his agency's internal data; he says Smartlead puts it nearer 4x). His play: Clay's free Google Maps source with keyword searches (free however many locations you add), score fit with an AI step and skip scoring names that already say the keyword, find contacts with Surfe, and a custom Claygent for the misses. He runs searches with a browser agent and asked engineering to allow more at once.
- **Train a cheap contact finder on good data (in progress, 2026-10-26):** he is having a top model find 1,000 companies where the owner is on the website but has no LinkedIn profile, as training data for a Claygent on a cheaper model, and says he'll give away that Claygent plus any MCPs it needs.
- **Clay workflows over tables, and stale data is rarely the problem:** tables can feel manual, but “workflows should be pretty hands off”; on stale-data complaints he says Clay usually doesn't lose on that and asks for a concrete link. He has “Nothing but respect to the cargo team” and asks critics what they didn't like about Clay so he can take it back. Rates Discolike's company filtering highly.
- **Start from the 10-minute research question:** base all personalization on what you would look up if you had 10 minutes on a prospect, and don't copy other people's Clay workflows: alpha is the gap between what the market does and what you do.
- **AI writes snippets, never the whole email:** keep your proven copy and structure in static text or spintax and let AI fill a sentence or two. Never tell the model it's writing a cold email (frame it as a persuasive writer or topic expert), give each AI column one job, have it reason before a yes/no classification, feed it real enriched data, and treat 3-5 hand-written examples as the biggest quality lever.
- **Protect spend and hygiene:** put run conditions on every expensive column so nothing runs when a prior step failed; lock the team's OpenAI key to one cheap model (he used GPT-4o mini for everything then); add a system prompt that bans corporate jargon on all copy columns.
- **Better prompts from talking:** dictate prompts so you give more context, then ask a chatbot to restructure the prompt and list questions that would improve it (a tip he credits to Yash on the Clay team).

## Write to the outcome, enterprise contacts, cheaper Claygent (X 2026-10-27) and Apify Instagram scraping in Clay (Growth Drops backlog 2025-09-11)

First-party X (several post bodies came back truncated; only visible text used) and coldoutbound.com Growth Drops. Tools named are his examples, not endorsements. He speaks as a Clay employee on Clay topics.

- **Write as close to the outcome as you can:** “Free campaign” got 1 positive reply per 1,000, while “Two meetings on your calendar, free” got 1 per 200 for the same service his team fulfils, “5x the replies”. He credits Sean Longden with a good framework for this.
- **Enterprise follows the same principle, different playbook:** “People that receive less emails respond higher.” In enterprise you find the emails waterfalls miss by finding them publicly and taking more risk on riskier emails.
- **Replicating Claygent cheaply (as a Clay employee, 2026-10-27):** for people who want to rebuild it outside Clay he points to Google search via Serper or OpenWebNinja as likely cheaper than Firecrawl, and says he is pushing the team on search quality. He defends Clay's value by asking whether a critic can get unlimited contact search for $185 a month and AI search at Claygent's cost, and admits Clay may not have shown people how much the product has grown beyond the API marketplace. Clay's CLI launched over the summer.
- **Gracious about competitors:** to a Cargo user, if you're happy with Cargo, keep going with them.
- **Cheap inboxes changed the game:** before Instantly's unlimited-inboxes lifetime deal, tools charged $30-40 per extra inbox.
- **Ops:** his team tracks work in ClickUp as individual tasks that roll up to a project or client. He is offering to run deliverability tests on request (he says Bruno Estrella funded the testing card), drawing on running Growth Engine X.
- **Instagram data in Clay via Apify (as of 2025-09):** get social links from the company site with Zenrows' scrape action (social links only), pull the username with a Clay formula (“look for the pattern that is the same every time”), then run Apify's Instagram Profile Scraper. Never guess the actor's input JSON: run it once in Apify, copy the input, paste it into Clay and swap in your column. The profile scraper usually returns followers, post count and latest-post engagement, so you often don't need the post scraper. Run on 10 rows first and gate the actor with conditions so you don't burn credits on empty rows.


## Clay feedback day: actions vs data pricing, workflows and functions, data coverage (X 2026-10-28) and Cursor company research (Growth Drops backlog 2025-11-02)

First-party X and coldoutbound.com Growth Drops. Tools named are his examples, not endorsements. He speaks as a Clay employee on Clay topics; product timelines are his statements as of 2026-10-28, not commitments.

- **Asks for brutal feedback in public and routes it:** he invited “brutal feedback” on Clay and replied to dozens of users, owning gaps (“No, I see this is our fault. We need to be communicating this better”) and offering calls, access, or demos.
- **Charge for actions, not data:** “charging for data is a losing battle, and actions are a pretty clear value measure”; everyone charges by action (Codex, Railway, Trigger), so he reads most pushback as being about the price of Clay's actions, “not the actions themselves”, and says he is proposing changes on data credits. He is also hearing requests for a lower entry tier.
- **Workflows over tables:** he says he is “never really in the platform now with workflows” and doesn't build inside Clay's UI; “Workflows is to build new things that are durable”, functions are for something you know works and want to share. He turned his common waterfalls into functions and calls them inside workflows. For things not on the CLI he built a headless browser skill.
- **Data quality:** asked about stale data, he says in his tests Clay was “the most correct” and the gap is coverage, which needs fixing; he promises to make his next data test public. Unlimited search is on every plan.
- **Testing offers fast:** he shared his “favorite way to test offers quickly” for rapid feedback on what to scale; used for cold email but works on any channel.
- **Cursor to classify companies (as of 2025-11):** buying SaaS labels from Crunchbase, Apollo, Owler and Ocean.io and scoring overlap was “Highly inaccurate”. Scraping each homepage and having an open-source 20B model on OpenRouter classify it covered 109,000 companies for about $20. Build the prompt with Cursor from about 20 hand-labelled examples, then go deeper via sitemaps (pricing, customers, case studies). Use Python via Cursor for scraping and classification, then push clean data into Clay for enrichment and campaigns; Clay is still the best data integration layer for most workflows.

## Cost caps for agent work, testing CTAs in content (X 2026-10-29) and Cursor for scraping Google Maps (Growth Drops backlog 2025-11-02)

First-party X and coldoutbound.com Growth Drops. Tools named are his examples, not endorsements; prices are as stated in 2025-11. He speaks as a Clay employee on Clay topics.

- **Caps beat estimates for variable agent costs:** agent work varies with what it finds (“what if it checks 3 podcasts?”), so a price range is possible but “a cost cap would maybe help more here than an estimate because the estimate is so hard”. Search in Clay is already unlimited with fair use.
- **Test the content CTA:** put the CTA “at the end of like 5-10 posts” to test it. He is open about tests that didn't move reply rates and willing to rerun them.
- **Google Maps for local businesses:** LinkedIn has the best persona data, but local businesses often aren't there; “If a business isn't on Google Maps, they're probably not a company you want to reach out to anyway.”
- **Cursor replaces janky scrapers:** have Cursor write the scraper against a cheap API (RapidAPI Google Maps Extractor, about $100 for 500,000 requests, or Serper.dev), paste the endpoint docs, be explicit about inputs and outputs, loop over a CSV of zip codes or towns, go 3 to 5 pages deep, and pull reviews for personalization. Then enrich in Clay and send from Smartlead or Instantly. In dense metros, search by zip code.


## What GTM Engineering means, back at Clay (X 2026-10-30) and Cursor GTM use cases (Growth Drops backlog 2025-11-02)

First-party X and coldoutbound.com Growth Drops. Tools named are his examples, not endorsements; the Growth Drop reflects his agency setup in 2025-11. He speaks as a Clay employee on Clay topics.

- **GTM Engineering is owning the revenue system:** “GTM Engineering is about building revenue systems and you hold the bag on the content but also the underlying repeatable system.” In his agency, the people setting up Clay tables and pushing to Smartlead were never called GTMEs.
- **Back at Clay and building:** he says he is working on things he thinks everyone will love; he helps users get into the Clay CLI workflows beta and tells them to connect through the MCP and ask it to make a workflow explicitly. He credits the UGC growth loop that took off after he left Clay to the people who ran it.
- **Ask for the best customer, not the possible ones:** when a product could sell to many businesses, his question is who the best overall customer is.
- **Cursor has three GTM jobs:** launch campaigns faster (create campaigns from copy docs, hot-swap active and insurance inboxes from Supabase into Smartlead, bulk-edit campaign settings), clean and enrich lists, and analyze results by talking to the Smartlead API instead of building Make or n8n sheets.
- **Clay is not replaced by Cursor:** Clay keeps cloud execution, the queuing that handles about 500,000 rows a day for customers, Claygent, and visual workflow building. “Anyone who says you can replace Clay with Cursor isn't thinking at scale.” Cursor becomes the front end for custom automation.
- **Structuring unstructured data is the best use of a code agent:** “This is the single best thing a code agent can do.” Pair Cursor with OpenRouter (or a local open-source model) for qualification and classification.
- **DIY email waterfall:** check Supabase for an earlier validation, test the 6 most common permutations in Million Verifier, then waterfall through providers (Lead Magic first for speed, then ICYPEAS, Prospeo and others).
- **Voice memo to analysis:** record the question while walking the dog, paste the transcript into Cursor's plan mode, and come back to a finished analysis (e.g. comparing positive responders to the full list found two industries drove most positives).
