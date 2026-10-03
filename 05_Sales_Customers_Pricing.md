---
title: Sales, Customers and Pricing
as_of: 2026-10-03
---

# 05 · Sales, Customers and Pricing

## Who we sell to today (local)
Local **kiryana (grocery) shops**, a sabzi seller, and walk-in cash buyers near the plant. There are no export or retail-brand customers yet. [stated]

| Ref | Customer (as in the ledger) | Type | [TBD] |
|---|---|---|---|
| PT-0061 | Haji Ashiq — Usmania Kiryana | kiryana shop | location, phone |
| PT-0062 | Hakim Ali — Kiryana Rashida Wali | kiryana shop | location, phone |
| PT-0063 | Haji Irshad — Mani Sabzi | sabzi/grocery shop | location, phone |
| PT-0064 | Abbas — Riyaz Abadi House | shop or household? | location, phone, what he buys for |
| PT-0066 | Cash Counter | walk-in cash sales, no name | — |

No customer phone numbers are in the ledger yet. Add them in the app; JARVIS needs them for reminders.

## Credit (udhaar) practice
- Most shop sales are on **credit**. Collection is **weekly or twice a week**, with no fixed rule. [stated]
- First month: about **74% of sales were on udhaar** (Rs 21,390 of Rs 28,830). [risk: cash tied up]
- Some customers pay **in advance**; the app records this as Customer Advances (2200).
- **CFO rule:** "unpaid over 7 days" = outstanding minus credit sales in the last 7 days. Payments are applied to the oldest invoice first (DB view `v_udhaar_aging`).
- **When a customer pays back:** in the ledger app, use **Receive payment** (Dashboard) or **Receive** (Debtors page). Never enter it as "money in", or the customer will still show as owing.
- [TBD] Credit rule: maximum amount per shop, maximum days, and when to stop supplying.

## Credit invoices to date [from books]
| Invoice | Date | Customer | Items | Amount |
|---|---|---|---|---|
| INV-00037 | 13 Sep | Haji Ashiq | 10 × 20 kg bags | Rs 3,200 (owes 3,200) |
| INV-00038 | 13 Sep | Hakim Ali | 5 man sabit + 2 × 20 kg bags | Rs 3,140 (owes 40) |
| INV-00039 | 14 Sep | Haji Irshad | 15 × 50 kg bags (Rs 5/kg) + 5 man sabit | Rs 6,250 (owes 6,250) |
| INV-00040 | 18 Sep | Abbas | 700 kg @ Rs 15 + 280 kg @ Rs 5 | Rs 11,900 (owes 11,900) |

**Debtors total: Rs 21,390** (as of the last entry; sales after 18 Sep not yet entered).

## How a sale works
- Price is agreed **per bag or per man** and **varies with the quantity** taken. There is no fixed price list. [stated]
- Payment: cash now, credit (udhaar), or part of each.
- Delivery freight (kiraya) is **our expense** (5200) unless the customer pays it. Example: Rs 500 on Abbas's 18 Sep delivery.
- The app shows only products in stock, and warns when the price is below the batch cost (being added, Oct 2026).

## Prices seen in the books (23 Aug – 18 Sep 2026)
| What | Price | Per kg | Seen |
|---|---|---|---|
| Crushed salt, **20 kg bag**, to shops | Rs 320 / bag | **Rs 16.00** | Ashiq, Hakim Ali, walk-in (13–16 Sep) |
| **Sabit** (whole lumps), per man (40 kg) | Rs 500 / man | **Rs 12.50** | Hakim Ali, Haji Irshad |
| Bulk crushed, large lot (700 kg) | — | Rs 15.00 | Abbas, 18 Sep |
| 3 man (120 kg), walk-in | Rs 1,800 | Rs 15.00 | 13 Sep |
| **50 kg bags** / some lots | Rs 250 / 50 kg | **Rs 5.00 ⚠** | Haji Irshad 750 kg (14 Sep), Abbas 280 kg (18 Sep) |
| Small walk-in amounts (1–20 kg) | varies | Rs 14–50 | cash counter |
| **Average** | | **≈ Rs 10.75** | 2,682.5 kg, 16 invoices |

⚠ **Rs 5/kg is below cost.** About 1,030 kg sold this way lost roughly **Rs 4,400 against cost**.
[TBD] Was the Rs 5/kg salt a different, lower grade (dust / chura / reject)? If yes, it needs its own product and cost in the ledger. If not, it was underpriced.

## Cost per kg (for pricing)
- Rock salt (BATCH-001): ≈ **Rs 7.51/kg** landed, before crushing.
- Bought fine powder (BATCH-075): **Rs 9.40/kg** landed.
- Crushed in-house: rock + crushing cost (labour, electricity, diesel) + wastage. [TBD: real figure after the first recorded crush runs]

## Price list [TBD: baba to confirm]
Fill in what baba actually charges, and the **minimum price** below which nobody sells:

| Product | 20 kg | 25 kg | 40 kg / man | 50 kg | per kg (loose) | Minimum per kg |
|---|---|---|---|---|---|---|
| Rock (sabit / dalay) | | | Rs 500 (seen) | | | |
| Fine powder | Rs 320 (seen) | | | | | |
| Coarse (daana) | | | | | | |

## Planned channels
- **Retail (private label):** own delivery → wholesalers → Daraz, in that order. [stated]
- **Export:** see 09.
