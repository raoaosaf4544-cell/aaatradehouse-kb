---
title: Finance and the Books
as_of: 2026-10-03 (figures from the ledger; sales entered to 18 Sep, expenses to 27 Sep)
---

# 06 · Finance and the Books

## Where the truth lives
1. **Baba's paper register (roznamcha) is the real record.** [stated] The app must match it; differences are investigated, never guessed.
2. **The ledger app** (aaatradehouse-ledger.vercel.app, Supabase) is the digital copy. It uses double-entry, with money in **paisa** (Rs 1 = 100 paisa) and weight in grams.
3. **JARVIS CFO** reads the ledger read-only and never invents a number. **Live numbers (cash, udhaar, stock) must always be read fresh** from the app, JARVIS or the phone bot (`/cash`, `/udhaar`, `/runway`). The figures below are a dated snapshot.

## Snapshot [from books]
| Item | Rs |
|---|---|
| Owner capital put in (M. Shafiq Shaheen) | 1,100,000 |
| Owner drawings (Eisha's marriage) | 10,000 |
| **Cash on hand** (essentially the whole pot) | **506,148.00** |
| Udhaar owed by customers | 21,390 |
| Stock (raw 113,278.68 + crushed 92,284.50) | 205,563.18 |
| Motorcycle (incl. permit, helmets, fit-out) | 135,670 |
| Goats (side activity) | 55,000 |
| Other fixed assets (scale, plant electricals, cameras) | 35,197 |
| Revenue 30,580 + other income 800 | 31,380 |
| Cost of salt sold (COGS) | 26,206.82 |
| Operating expenses to date | 136,205 |
| **Result to date** | **−131,031.82 (loss)** |

Check: assets 958,968.18 = capital 1,100,000 − drawings 10,000 − loss 131,031.82 ✓

**The books are behind:** no sales have been entered since 18 Sep. Baba's register (19 Sep onwards) is being entered from Oct 2026.

## Operating expenses to date by account
| Code | Account | Rs |
|---|---|---|
| 5000 | Labour (wages, advances, hamali, mazdoori) | 16,155 |
| 5100 | Utilities (house bill, mobile, electricity) | 1,958 |
| 5200 | Freight on deliveries (kiraya, unloading) | 3,300 |
| 5300 | Fuel (petrol, diesel, bike oil) | 8,340 |
| 5400 | Packaging consumed (bardaana, sacks, thread) | 15,500 |
| 5500 | Site meals & welfare | 12,030 |
| 5600 | Travel | 16,504 |
| 5700 | Repairs & maintenance | 23,510 |
| 5800 | Admin & office (incl. Valencia rent) | 26,878 |
| 5900 | Other business expense | 12,030 |
| | **Total** | **136,205** |

## Key ratios
- **Runway ≈ 6.0 months** = cash 506,148 ÷ last-30-day operating spend 84,979 (28 Sep).
  - Definition: net debits to expense accounts (type expense, kind general), excluding 4100 COGS and 5250 wastage.
  - This is one shared definition (DB view `v_cfo_runway`), used by JARVIS CFO and the phone bot.
- **Loose local salt:** average price ≈ Rs 10.75/kg, cost ≈ Rs 9.40/kg, gross profit ≈ Rs 1.35/kg (≈ 12.5%).
- **Break-even reality:** at Rs 1.35/kg, covering current overhead needs about **72 tonnes/month** of loose sales. The first month was 2.7 t. **Loose local bulk cannot carry the business. Branded retail and export margin are the lever.**

## Money rules (decided)
1. The paper roznamcha is the real record; the app must match it.
2. **Site living costs are business expenses**, because baba and the workers live at the plant (food, tea, milk, medicine, the motorcycle). Split them into **production** vs **site overhead**, and tag one-time setup costs. [TBD: split not built yet]
3. **Personal or family money → Owner Drawings (3100)**, never expenses. Example: Eisha's marriage, Rs 10,000.
4. **Goats are a side activity** (1450), not salt costs.
5. **Assets go to asset accounts:** motorcycle (1400), goats (1450), equipment and fixed items (1500).
6. **Delivery freight on a sale is our expense** unless the customer pays it.
7. **Valencia office rent (~Rs 5,700) must be entered every month.** Three months were pending in Sep 2026.
8. **Never enter the same register line twice.** Example: the 24 Sep camera line is already entered.
9. **Fix mistakes with the app's correct or delete functions** (audited, restorable). Never edit the database by hand.
10. **Nothing is invented.** Unknown lines go to **Suspense (1900)** and are cleared with the owner. Suspense has been 0 since 27 Sep.
11. Cash can never go negative on any day, and stock can never go negative; the app refuses such entries.
12. Enter every crush run, credit purchase and customer payment **the same day**.

## Where does this kharch go? (quick guide)
| It's… | Account |
|---|---|
| Worker wage, advance, loading/unloading labour (hamali, mazdoori) | 5000 Labour |
| Electricity bill, house bill, mobile bill | 5100 Utilities |
| Kiraya to deliver salt to a customer | 5200 Freight |
| Petrol, diesel, bike oil | 5300 Fuel |
| Bags, sacks, thread used for packing | 5400 Packaging |
| Food, tea, milk, sabzi for people at the plant | 5500 Site meals |
| Bus, Indrive, rickshaw, fare for business trips | 5600 Travel |
| Mistri, electrician, bulb, wire, bike repair | 5700 Repairs |
| Office rent, stationery, admin fees | 5800 Admin |
| Something permanent (equipment, cameras, fitted electricals) | 1500 Other Fixed Assets |
| Anything for family or personal use | 3100 Owner Drawings |
| Not sure | 1900 Suspense, and ask |

## Chart of accounts in plain words
| Code | Account | Meaning |
|---|---|---|
| 1000 | Cash on Hand | cash with baba / in the business |
| 1050 | Cash — Bank | future bank account |
| 1100 | Accounts Receivable | **udhaar**: customers owe us |
| 1200 / 1210 / 1220 / 1230 | Inventory | raw rock / crushed salt / packed goods / packing material |
| 1240, 1300, 1310 | WIP pools | used inside crush runs (internal) |
| 1400 | Vehicle | motorcycle |
| 1450 | Livestock | goats (side activity) |
| 1500 | Other Fixed Assets | scale, plant electricals, cameras |
| 1900 | Suspense | unknown lines; keep at 0 |
| 2000 | Accounts Payable | we owe suppliers (credit purchases, crushing on credit) |
| 2100 | Accrued Expenses | costs owed, not yet paid |
| 2200 | Customer Advances | customers paid before delivery (2050 is an unused duplicate) |
| 3000 / 3100 / 3200 | Capital / Drawings / Retained earnings | owner's money in / out / past results |
| 4000 / 4100 / 4900 | Sales / COGS / Other income | |
| 5000–5900 | Expenses | see the table above; 5250 Wastage = crushing loss |
| 5950 | Personal/Unclassified | review bucket |
| 5990 | Opening Balance Offset | setup only |

## Tax
- NTN held by M. Shafiq Shaheen. **Tax year 2026 return: filed** (confirmed 3 Oct 2026).
- [TBD] Sales tax and other FBR obligations once retail and export sales start.
