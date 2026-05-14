# Fork in the Road — Project Training Manual

> This manual covers what is unique to this repo.
> All global standards live in andredavisme/warrior-x-docs/operations/training-manual.md.

## What This Repo Is
A project workspace for Fork in the Road, a downtown Portland, Maine pizza shop. This repo holds the business plan, marketing strategy, community program design, and a simple web-based management tool the owner (or a helper) can use to organize pizza offerings and community connections.

## Who It Serves
- **The Owner** — a solo operator who needs dead-simple tools, not complexity
- **André** — ecosystem steward, strategy and build partner
- **Community** — high school students, local businesses, hotel guests, travel groups, bohemian diners

## The Business in Plain Language
Fork in the Road is a one-man pizza shop in downtown Portland, ME. The owner makes unique, non-traditional pizza. His mom helps cook. He takes requests. The food is exceptional but it's not a typical street-traffic pizza place — it shines for group lunches, workshop catering, hotel recommendations, and adventurous eaters.

## Tech Stack
- **Docs/Planning:** Markdown in this repo
- **Management Tool:** Static HTML/CSS/JS (no backend required initially)
- **Future option:** Supabase if the tool needs persistence and the owner wants to self-manage
- **Hosting:** GitHub Pages or Netlify Drop (zero-cost, zero-ops)

## Key Conventions
- All planning docs live in `/docs/`
- The management tool lives in `/tool/`
- Marketing templates live in `/marketing/`
- Branch pattern: `feat/description`, `docs/description`, `fix/description`
- Commit types: feat | fix | docs | schema | chore | refactor

## Security Rules
- No customer data stored without consent
- No API keys in this repo — ever
- If Supabase is added later: RLS on every table, no service role key in frontend

## How to Contribute
1. Branch from main
2. Do the work
3. Open a PR with a clear description
4. André reviews and merges

## Document Structure

| Path | Purpose |
|---|---|
| `/docs/business-plan.md` | Business strategy, customer segments, revenue levers, quick wins |
| `/docs/pay-it-forward-program.md` | Pay-It-Forward slice program design (pending) |
| `/marketing/playbook.md` | Full marketing playbook: Google, Instagram, hotel, B2B, one-pager |
| `/marketing/outreach-templates.md` | Ready-to-send B2B outreach templates (pending) |
| `/tool/menu-manager.html` | Static pizza menu management tool (pending) |

## Pay-It-Forward Program
Core concept: A customer (or business) pre-pays for a slice. A high school student who can't afford their lunch gets to redeem it. Inspired by suspended coffee programs seen in bars. Tone must preserve dignity — community-first, not charity-feeling. Program tracking options:
- **Analog:** Chalkboard behind the counter with tally marks
- **Digital:** Simple counter in the management tool (increment/decrement)
- **Voucher:** Printed cards the owner gives out or that community orgs distribute

## Competitive Positioning (established 2026-05-14)
- **vs. Panera:** More personal, more memorable, more customizable — not Panera, not boring
- **vs. Portland House of Pizza:** More distinctive identity, stronger story, better for group hosts and adventurous eaters

## Marketing Channels (established 2026-05-14)
1. Google Business Profile — highest-leverage discovery channel
2. Instagram — visual storytelling via request-based pizza content
3. Direct B2B outreach — hotels, workshop hosts, offices, tour operators
4. Leave-behind one-pager — for hotel front desks and local business partners
5. Word-of-mouth — fueled by memorable pizzas and community storytelling

## Chapter 15 — Post-Mortems & Lessons Learned
*No post-mortems yet. This section will be updated as the project evolves.*
