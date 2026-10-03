---
title: Finance and the Books
as_of: 2026-10-03 (figures read live; books entered up to ~27 Sep)
---

# 06 · Finance and the Books

## Where the truth lives
1. **Baba's paper register (roznamcha)** is the original record. [stated]
2. **The ledger app** (aaatradehouse-ledger.vercel.app, Supabase database) is the digital copy, in double-entry, in **paisa** (1 PKR = 100 paisa). App entries must match the register.
3. JARVIS's CFO reads the ledger (read-only) and never invents a number.

## Snapshot [from books, read 3 Oct 2026]
| Item | PKR |
|---|---|
| Cash on hand | **506,148.00** |
| Debtors (customers owe us) | 21,390 |
| Stock value (rock + fine) | ≈ 205,563 |
| Motorcycle (incl. helmet and fit-out) | 135,670 |
| Other fixed assets (scale, plant electricals, cameras) | 35,197 |
| Goats (side asset) | 55,000 |
| Owner capital in | 1,100,000 |
| Owner drawings | 10,000 |
| Sales revenue to date | 30,580 |
| Cost of salt sold (COGS) | 26,207 → **gross margin ≈ 14%** |

**Books are behind:** no sales have been entered since 18 Sep, so the figures above are out of date until baba's register (19 Sep onwards) is entered.

## Unit economics (first month, 23 Aug – 19 Sep) [audit]
- Sold ≈ 2,682 kg for ≈ Rs 28,830 → **≈ Rs 10.75/kg**. Cost ≈ Rs 9.40/kg → gross profit ≈ **Rs 1.35/kg**.
- Operating spend ≈ Rs 85,000–97,000 a month (includes one-time setup costs).
- At Rs 1.35/kg, covering overhead needs about **72 tonnes/month** of loose sales. **Loose local bulk can't carry the business.** The margin has to come from **branded retail and export**.
- **Runway:** cash ÷ last-30-day operating spend ≈ **6 months** (506,148 ÷ 84,979, as of 28 Sep). The CFO and the bot use one shared definition (DB view `v_cfo_runway`).

## Chart of accounts (what each account means)
| Code | Account | Plain meaning |
|---|---|---|
| 1000 | Cash on Hand | The cash box |
| 1050 | Cash — Bank | Future use |
| 1100 | Accounts Receivable | Udhaar: customers owe us |
| 1200 | Inventory — Raw Salt | Rock salt not yet crushed |
| 1210 | Inventory — Bulk Processed | Fine/coarse crushed salt |
| 1220 / 1230 | Packaged goods / packaging material | For the retail packs later |
| 1300 / 1310 / 1240 | WIP accounts | Used inside crush runs |
| 1400 | Vehicle (Motorcycle) | Bike, permit, helmet, fit-out (⚠ cameras were once posted here by mistake and corrected) |
| 1450 | Livestock (Goats) | Side asset, not salt business |
| 1500 | Other Fixed Assets | Scale, plant electricals, cameras |
| 1900 | Suspense | Must always be 0 |
| 2000 | Accounts Payable | We owe suppliers (credit purchases, crushing on credit) |
| 2200 | Customer Advances | Customers paid before getting salt (2050 is a duplicate, unused) |
| 3000 | Owner Capital | Money baba put in |
| 3100 | Owner Drawings | Money taken out for family (e.g. Esha's gift) |
| 4000 | Salt Sales Revenue | Sales |
| 4100 | COGS | Cost of the salt that was sold |
| 4900 | Other Income | |
| 5000 | Labour | Wages, advances, loading/unloading |
| 5100 | Utilities | Electricity, mobile and house bills |
| 5200 | Freight | Delivery kiraya on sales |
| 5250 | Wastage | Crushing loss |
| 5300 | Fuel | Petrol, diesel, bike oil |
| 5400 | Packaging consumed | Bags, sacks, thread |
| 5500 | Site Meals & Welfare | Food, tea and milk at the plant |
| 5600 | Travel | Fares, Indrive, rickshaw |
| 5700 | Repairs & Maintenance | Mistri, bulbs, cables, repairs |
| 5800 | Admin & Office | Office rent (Valencia) etc. |
| 5900 | Other Business Expense | |
| 5950 | Personal/Unclassified | For review |

## Money rules
- Business vs household: site living costs stay as business expense (owner decision), but tag one-time vs recurring, and production vs site overhead.
- Monthly Valencia office rent (~Rs 5,700) must be entered every month.
- Corrections: through the app's correct or delete functions only (audited and restorable). Never edit the database by hand.
- Cash must never go negative on any day; the app refuses such entries.
- Every crush run, purchase on credit and customer payment gets entered the same day.

## Tax
- NTN held in M. Shafiq Shaheen's name. TY2026 return: filed (confirmed 3 Oct).
- [TBD] Sales tax / other FBR obligations once retail and export sales start.
