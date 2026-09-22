# OPINIONS

Sourced public positions from Eric’s public writing and speech (X, YouTube, Growth Engine X / LinkedIn, attributed interviews).

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

## GTM engineering bar

- “GTM engineering” should be real engineering (audits, systems, automations), not only dashboards + launching campaigns.
