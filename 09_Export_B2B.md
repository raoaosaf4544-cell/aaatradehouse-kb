---
title: Export (B2B)
as_of: 2026-10-03
---

# 09 · Export (B2B)

**Status:** no buyer contacts and no export sale yet. Outreach system built but not sending. [stated]

## Our pitch (honest version)
- Direct supply: rock from PMDC-leased mines, crushed and packed at **our own plant**, with a family of **30+ years** in the salt supply chain.
- Can supply bulk (25 kg bags, 1-ton jumbo bags), private label, FOB/CIF.
- Do NOT claim certifications we don't hold (see 07).

## Markets
USA, UK, Germany, France, Australia, UAE, Saudi Arabia, Qatar.

## Buyers and what each cares about
| Buyer type | Lead with |
|---|---|
| Importer / wholesaler | Bulk price, MOQ, supply consistency, FOB terms |
| Grocery chain | Certifications, packaging, shelf-ready |
| Health food store | Natural, premium, wellness |
| Spice distributor | Variety, private label |
| Amazon reseller | Competitive price, documents, fast shipping |

## Lead rules
- **Qualified lead** = real company + working business email + genuinely imports or distributes food, spice, wellness or home products + in a target market. **Anything less is a research note.**
- Scoring is deterministic in `lead_scorer.py`: Hot ≥ 70, Warm 40–69, Cold < 40. **Never score with an AI. Never invent leads.**
- Sources:
  1. Apollo
  2. Import/trade data (companies already importing salt or food from Pakistan; highest weight, +25)
  3. Directories and trade-show lists
- CRM: HubSpot portal 246642088. Pipeline: New Lead → Email Sent → Replied → Sample Requested → Quote Sent → Negotiation → Closed Won / Lost.
- The 22 deals currently in HubSpot are **test data**, not real prospects.

## Before the first email goes out
1. Zoho Mail Lite (SMTP) bought.
2. unsubscribe@ created; bounce handling live.
3. Website claims fixed (halal, PCSIR, PMDC).
4. Full postal address in the footer.
5. Every send approved by Rao; warm-up limits respected.

## Commission agent
A contract for an overseas agent is drafted but not ready (see 07).
