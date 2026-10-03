---
title: AAATradeHouse — Business Knowledge Base
version: 1.1 (merged with the 28 Sep draft)
as_of: 2026-10-03
owner: Rao Aosaf
---

# AAATradeHouse — Business Knowledge Base

The single reference for how this business works. It is written for people (Rao, baba) AND for AI tools (JARVIS, Claude, ChatGPT, Gemini, anyone else Rao uses). Paste the combined file `AAATradeHouse_KB_ALL.md` into any AI to give it full context.

## How to read this
- **[stated]**: Rao or baba told us directly.
- **[from books]**: read from the live ledger database, with the date it was read.
- **[TBD]**: not known yet. Never guess it. Ask Rao.
- **[risk]**: a legal, compliance or money risk that needs attention.
- Figures from the books are a **snapshot**. Always re-read the live ledger before using any number for a decision.

## Files
| # | File | What's in it |
|---|---|---|
| 01 | Company_Identity | Names, legal form, registrations, contacts, signing rules |
| 02 | People_Roles | Who does what, workers, decision rights |
| 03 | Products | What we sell, grades, bag sizes, units, the retail packs |
| 04 | Operations_Supply | Plant, crushing, batches, suppliers, stock |
| 05 | Sales_Customers_Pricing | Customers, how we sell, credit (udhaar), pricing logic |
| 06 | Finance_Books | Ledger, chart of accounts, current numbers, unit economics, money rules |
| 07 | Compliance_Legal | PFA, PCSIR, halal, iodine, NTN/FBR, claims we may and may not make |
| 08 | Retail_Launch | 500 g / 900 g private-label plan |
| 09 | Export_B2B | Export plan, markets, buyers, lead rules, outreach rules |
| 10 | Systems_Tools | Ledger app, JARVIS, website, email, CRM, phone channel |
| 11 | Glossary | Urdu/Punjabi trade words and units |
| 12 | Rules_Never | The hard rules for people and AI |
| 13 | Open_Questions | Gaps still to fill |
| 14 | Decisions_Log | Dated owner decisions |

## Priority order (90 days, from Sept 2026) [stated]
1. Private-label retail launch in Pakistan: 500 g and 900 g Himalayan pink salt.
2. B2B export outreach, in parallel.
3. Expense tracking and unit costing through the ledger app.

Supporting work: JARVIS (outreach engine and AI COO) and the website (RFQ capture).
**Parked** (no time unless Rao says so): Etsy digital products, COD sprint, fitness/sticker templates, telecom call-center idea.

## Update rule
When a fact changes, update the file AND the "as_of" date. Old facts are corrected, not deleted silently: write "(was X until DATE)".


---

---
title: Company Identity
as_of: 2026-10-03
---

# 01 · Company Identity

## Names
| Use | Name |
|---|---|
| Brand (what buyers see) | **AAATradeHouse** |
| Legal entity (invoices, contracts, bank, Certificate of Origin) | **AAA General Trading** |
| On invoices and contracts | "AAA General Trading (trading as AAATradeHouse)" |

## Legal form [stated]
- **Sole proprietorship** in the name of **M. Shafiq Shaheen** (Rao's father).
- No company, no directors. Never write "Director" for anyone.
- Rao signs as **Operations Manager / Authorised Representative**, backed by a written authority letter from M. Shafiq Shaheen. [TBD: is the letter signed and on file?]

## Registrations held
| Registration | Status |
|---|---|
| NTN | ✅ Held (in M. Shafiq Shaheen's name). Income tax return for 30 Sep 2026: filed. [stated 3 Oct] |
| Chamber of Commerce membership | ✅ Held [stated]. [TBD: which chamber, membership number, expiry] |
| PFA Food Business License | ❌ Not started (needed before retail labels are printed) |
| PCSIR lab report | ⏳ Pending; no old report in hand |
| Halal certificate | ❌ Not held |
| PSQCA | ❌ Not held |
| GS1 / EAN-13 barcodes | ❌ Not yet (not needed for Daraz) |
| PMDC | A **supply connection** (mines are PMDC-leased). It is **not a certificate** held by us. |

## Contact details
- **Office:** Office 42, Valencia Tower, Block K1, Valencia, Lahore. Rent is about Rs 5,700/month (3 months were pending in Sept). [stated]
- **Plant (crushing and packing, owned and run by us):** near Kot Abbas Shaheed, Khanewal.
- **Phone (official, both public):** +92 317 4286226 and +92 300 351 3889. [stated 3 Oct] (The number +92 317 4286225 in older documents is wrong. Check the website and labels for it.)
- **Website:** aaatradehouse.com
- **Social:** @aaatradehouse on Instagram, Facebook and LinkedIn.

## Email [stated]
- Domain mailboxes (Zoho): rao@, sales@, info@ and finance@ aaatradehouse.com.
- **Official sales address: sales@aaatradehouse.com.** Retire or forward all older addresses (e.g. sales@aaageneraltrading.com on Hostinger).
- Zoho is on the free plan, which allows **web only, no SMTP**. Zoho Mail Lite (about $1/user/month) is needed for JARVIS to send.
- unsubscribe@aaatradehouse.com **does not exist yet**. It must exist before any export outreach is sent.
- Ledger app login: the business Outlook account **AAA_Trading.pk@outlook.com**, shared by Rao and baba.

## Signing rule [stated]
- Day-to-day work (emails, quotes, listings, outreach) is signed **Rao Aosaf, AAA General Trading**.
- Legal, banking, registration and government documents are signed **M. Shafiq Shaheen**.
- **If unsure which name a document needs, ask. Never guess.**

## Money accounts
- Payoneer: account holder is M. Shafiq Shaheen; Rao operates it.
- Bank: no business bank account is used in the books yet (account 1050 is "future use"). Cash is the main payment method.
- Starting capital: **Rs 11 lakh** put in by the owner (account 3000).


---

---
title: People and Roles
as_of: 2026-10-03
---

# 02 · People and Roles

## Owners and operators
| Person | Role | Does |
|---|---|---|
| **M. Shafiq Shaheen** ("baba", Rao's father) | CEO, registered owner, 30+ years in the salt supply chain | Full-time at the plant. Runs the plant, local sales and udhaar collection, suppliers, and the daily register (roznamcha). Enters entries in the ledger app on his phone. Does in-person government work (PFA application and inspection). Signs legal documents. |
| **Rao Aosaf** | Operator, sales lead, digital side | Has a day job and works on the business evenings and weekends (about 15–20 hours a week). Builds systems (ledger app, JARVIS, website), labels and design, export outreach, research, paperwork prep. Signs day-to-day business emails. Plans to move to the plant later and enter data through JARVIS voice. |

Family (not business roles): Esha (sister) and Muzna (Rao's wife). Esha's wedding gift of Rs 10,000 is booked as owner drawings.

## Workers at the plant [from books; roles TBD]
| Name | What the books show | [TBD] |
|---|---|---|
| Qasim | Advance salary Rs 10,000 (29 Aug), meals, clothes | Role, monthly pay, start date |
| Rafiq | Medicine, tea | Role, pay |
| Ali | Fare sent to him (Rs 1,500, 4 Sep) | Who is Ali? |
| Makhan | "Kiraya makhan" Rs 300 (3 Sep) | Person or place? |
| Abid, Jabar | Gift/help (suspense clean-up) | One-off or recurring? |
| Mistri (builder) | 7 days of building work (Rs 4,700 + Rs 6,000) | One-off or ongoing? |
| Hamali / mazdoor (day labour) | Loading and unloading labour per job | Rates per bag or per day |

- Father and workers **live at the plant**, so site living costs (meals, milk, tea, eggs) are business expenses in account **5500 Site Meals & Welfare**. [owner decision]
- **PFA requires medical certificates for every food-handling worker** before the licence inspection.

## Decision rights
- Spending, pricing, credit to customers: baba on the ground, Rao for anything structural.
- Anything legal or financial in the business's name: M. Shafiq Shaheen signs.
- JARVIS and any AI: may **never** spend money, send messages to customers, or change the books without Rao's explicit approval. See 12_Rules_Never.


---

---
title: Products
as_of: 2026-10-03
---

# 03 · Products

All products are **Himalayan pink rock salt** from the Salt Range (PMDC-leased mines), crushed and packed at our own Khanewal plant.

## A. Local bulk products (selling now) [stated 3 Oct 2026]
| Product | Urdu / local name | Ledger code | Comes from |
|---|---|---|---|
| **Rock Salt (whole)** | dalay / ڈلے, sabit / ثابت (whole lumps) | SALT_ROCK | Bought as raw rock (BATCH-001) |
| **Fine Powder Salt** | bareek / powder | SALT_BULK (to be renamed "Fine Powder Salt") | Bought crushed (BATCH-075), or crushed in-house from rock |
| **Coarse Salt** | daana / دانہ | SALT_ROCK_COARSE | Crushed in-house from rock |

- **Packing units:** bags of **20, 25, 40 and 50 kg**. Also sold by the **man (40 kg)** and by the kg.
- Other product codes in the ledger (Mesh, Other Grade, 1 kg pouch, Packaged 25/40/50 kg, packaging items) are being **hidden**. They are not real products.
- Bag material ("bardaana", PP sacks) and thread are bought as packing expense, not as stock.

## B. Retail private label (launching) [stated]
| | 500 g | 900 g |
|---|---|---|
| Grades | fine, coarse | fine, coarse |
| Iodised | Yes (owner decision: both sizes iodised) | Yes (the old draft label said "Not iodised" and must change) |
| Pack | Clear PET/PE zipper stand-up pouch | same |
| Label | Matte black die-cut BOPP front label with a mountain-shaped cutout showing the salt; back label with all legal text | same |
| Price plan | About 10–15% premium per gram over National, only if margin is at least 35% after Daraz fees; otherwise a launch discount | Match National |

Move to a fully printed pouch only after sales prove demand.

## C. Export range (offered to buyers; no export sale yet)
- Food-grade fine, coarse and chunks; industrial salt; animal lick salt; bath salt; salt lamps; cooking blocks.
- Grain sizes buyers ask for: 0.3–0.5 mm (fine), 1–2 mm, 2–5 mm, 5–8 mm. [TBD: which sizes our crusher actually makes]
- Packing: 25 kg PP bags, 1-ton jumbo bags, private label. Terms: FOB / CIF.

## Product facts to keep straight
- **Iodine rule (Punjab):** edible salt must be iodised: **30 ppm at production, 15–25 ppm at retail**. 30 ppm iodine ≈ **about 51 mg/kg potassium iodate**. The old 500 g label said "potassium iodate 15 mg/kg", which is about 9 ppm iodine and **too low**. [risk] Confirm the exact figure with PFA, then fix the dose and label.
- Lab figures on any label or website must come from **our own PCSIR report**, never copied from competitors.
- Net weight is written exactly: "Net Wt. 500 g", never "±".


---

---
title: Operations and Supply
as_of: 2026-10-03
---

# 04 · Operations and Supply

## The plant [stated]
- Crushing and packing plant near **Kot Abbas Shaheed, Khanewal**, owned and run by us.
- Baba and the workers live on site.
- Equipment seen in the photos: one small crusher, a sieve, and a weighing scale (Rs 10,000, bought 10 Sep). Electrical goods fixed permanently in the crushing plant cost Rs 13,500 (12 Sep). 3 security cameras cost Rs 11,297 (paid 24 Sep).
- Transport: motorcycle (about Rs 125,000 incl. permit and fit-out). Fuel and petrol in account 5300.
- Packing is done in separate rooms. The packing room must be brought up to PFA standard (see 07).
- Mobile internet at the plant works but is slow and patchy.
- [TBD] Crusher: owned or rented? Capacity (kg/day)? Who runs it, workers per shift?
- [TBD] Plant land: owned or rented? Full postal address (needed for labels and PFA).
- [TBD] Motorcycle "permit" line of Rs 75,000 is flagged "confirm 75,000 vs book".
- [TBD] Raw salt source: which mine/area (Khewra / Warcha / Kalabagh / other)? Price per ton at the mine, and freight per truck to Khanewal? Can we get a written supply letter for export buyers?
- [risk] Capacity claims: the website says "100+ tonnes/month". The books show about 2.7 t sold in the first 4 weeks, and the photos show one small crusher. Any capacity claim must be provable, or say "own plant plus partner network".

## How salt flows (and how the ledger records it)
1. **Buy raw rock salt** (purchase): it becomes a **batch** (e.g. BATCH-001) with a kg quantity and a landed cost per kg.
2. **Crush run**: rock goes in, and **fine and/or coarse** come out, plus weighed **wastage** (stone, dust, moisture). Each output becomes a child batch (e.g. BATCH-001-G1). Its cost = the rock's cost + the crushing cost (labour, electricity, diesel), shared by weight. **Every crush run must be recorded**, or stock and costs go wrong.
3. **Or buy salt already crushed**: a purchase straight into the fine-powder stock (e.g. BATCH-075).
4. **Sell**: the sale takes salt out of a specific batch at that batch's exact cost, so profit per sale is real.

## Batches and stock [from books, 3 Oct 2026; books entered up to ~18–27 Sep only]
| Batch | Product | Came in | Landed cost | On hand |
|---|---|---|---|---|
| BATCH-001 | Rock salt (whole), raw | 3 Sep: 15,210 kg | Rs 114,270 (≈ Rs 7.51/kg) | **15,078 kg** |
| BATCH-075 | Fine powder (bought crushed) | 14 Sep: 250 bags × 50 kg = 12,500 kg | Rs 117,500 (Rs 9.40/kg), bought on credit, **since paid** (suppliers owed = 0) | **9,817.5 kg** |

- Total ≈ 24,895 kg, stock value ≈ Rs 205,563.
- Known issue: sales on 6–13 Sep took stock from BATCH-075 before it arrived (14 Sep). The salt really came from BATCH-001 through an **unrecorded crushing**. Fix this at the first **physical stock count**.

## Suppliers [TBD: mostly unknown]
| What | Supplier | Terms |
|---|---|---|
| Raw rock salt (BATCH-001) | [TBD: name, mine or agent, location] | [TBD] |
| Crushed salt (BATCH-075, 12.5 t) | [TBD: supplier name, standing price] | Bought on credit, since paid (Rs 117,500) |
| Crushing contractor (when not done in-house) | [TBD] | Sometimes on credit [stated] |
| Bardaana (packing bags) | [TBD] | 700 bags for Rs 11,500 (2 Sep) ≈ Rs 16.40/bag, cash |
| Sacks (bori), stitching thread | [TBD] | Rs 3,000 sacks, Rs 1,000 thread (10 Sep), cash |
| Transport (salt moves) | [TBD transporter] | Freight Rs 400 + unloading Rs 2,400 (6 Sep) |
| Retail pouches and label printing | [TBD] | [TBD price per 1,000, MOQ, lead time] |

[stated] We sometimes buy salt and pay for crushing **on credit**, so supplier balances (account 2000) must be tracked by name.

## Daily routine (target)
- Baba writes the roznamcha (paper register) **and** enters the same day in the ledger app.
- Every grinding or crush run goes in "Crush Salt" the same day.
- A weekly physical stock count of each product, compared with the app.
- A weekly cash count, compared with the app's cash.


---

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


---

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


---

---
title: Compliance and Legal
as_of: 2026-10-03
---

# 07 · Compliance and Legal

## Retail (Pakistan): the PFA path
Each step needs the one before it:
1. **PFA Food Business License** for the plant.
2. **Halal certificate + PCSIR lab report.**
3. **PFA Label Approval** (about 12–14 days).
4. **PFA Product Registration** (Rs 5,800 per product per year).
5. Print labels and sell.

### Step 1: PFA License (baba applies)
- Apply through the PFA app ("Apply for License"), or in person at the Directorate of Licensing, 120-B New Muslim Town, Lahore, or the Khanewal district office.
- **Documents:** M. Shafiq Shaheen's CNIC (front and back), his photo, a photo of the business, a location map, and **medical certificates for every worker**.
- A PFA officer inspects the plant; the fee is paid after that.
- **Fee** (SMEDA guide, verify): Rs 10,000 (small-scale) or Rs 50,000 (manufacturing unit). Valid to 31 Dec, renewed yearly.
- **Inspection standards:**
  - smooth impervious floor (no bare brick where food is handled)
  - smooth, washable, light-coloured walls and ceiling
  - pest-proofing
  - safe water
  - hand-wash point with soap
  - staff medical records
- **From the plant photos:** the wooden or rusty crusher and sieve, bags on bare brick, and unfinished walls need fixing, at least in the packing room, before the visit.
- **Status: NOT STARTED.** This is the main blocker for the retail launch.

### Step 2: Halal and lab report
- PFA's label-approval checklist lists a **Halal certificate as required**.
- Punjab Halal Development Agency (PHDA): phda.gop.pk, 042-99333704-5.
- The PCSIR report doubles as the nutrition and analysis report.

### Label must show
- Product name in Urdu and English
- Exact net weight
- Ingredients
- PFA license number
- Batch/lot number
- Manufacturing date and Best Before date
- Retail price
- Packer name and address
- Nutrition facts
- Allergen information and storage instructions
- "Product of Pakistan"

## Claims: what we may and may NOT say
| Claim | Allowed? |
|---|---|
| "Mined, crushed and packed by us" | ✅ True |
| "Sourced from PMDC-licensed mines" | ✅ Only if verified for our supplier |
| "PMDC-certified" | ❌ PMDC leases mines; it doesn't certify salt |
| "Halal certified" | ❌ Not held |
| "PCSIR tested" / lab figures | ❌ Not until OUR report arrives; then only our figures |
| ISO / HACCP / PSQCA | ❌ Not held |
| "Iodised" | ✅ Only if that batch is iodised at the legal level |
| "100+ tonnes/month" | ⚠️ Only if provable |
| "15-day shipment" | ❌ Owner decided not to add it |

- **Rule: never print or publish a certification, logo or claim we don't hold, even if competitors do.** Leave empty badge slots and reprint when certificates arrive.
- [risk] **The website still claims "halal certified", "PCSIR tested" and "PMDC certification".** The owner chose to keep this wording for now (decision of 27 Sep). It is a false-claim risk with buyers and with PFA. Recommendation: fix it before any export outreach starts.

## Export compliance (to plan)
- Chamber of Commerce membership (held) → **Certificate of Origin** for each shipment.
- A lab analysis for each shipment.
- **USA:** FDA Food Facility Registration + a US agent.
- **EU:** labelling handled through the importer.
- Written authorisation from M. Shafiq Shaheen for Rao to act for the business.

## Email outreach law (US CAN-SPAM / EU)
- A real physical postal address in the footer.
- A working unsubscribe (unsubscribe@ must exist) and bounce handling **before the first send**.
- Warm-up limits: week 1 max 10/day, +5/week, ceiling 40/day.

## Contracts
- **Commission agent contract (abroad):** drafted, **not ready to sign**. It still has Canva placeholders (phone, email, address, "Arowwai Industries", date 31 Mar 2031), commission slabs that overlap with gaps (7–8 containers not covered), no commission base (FOB or CIF?), no non-circumvention clause, attribution window, term or agent details, and the wrong "Director" title.


---

---
title: Retail Launch (Private Label, Pakistan)
as_of: 2026-10-03
---

# 08 · Retail Launch: 500 g and 900 g

**Goal:** a branded Himalayan pink salt pack in Pakistan, sold through our own delivery first, then wholesalers, then Daraz. [stated order]

## Plan
| Item | Decision |
|---|---|
| Sizes | 500 g and 900 g |
| Grades | Fine and coarse |
| Iodised | Both sizes [owner decision] |
| Pack | Clear zipper stand-up pouch + matte black die-cut label with a mountain cutout + back label |
| Budget | Under Rs 100,000; flexible only for necessary spend |
| Positioning | "Mined, crushed and packed by us": traceable, lab-verified (once the report is in), a premium look at a mass-market price |
| Price | Match National on 900 g; about 10–15% premium per gram on 500 g, only if margin is at least 35% after Daraz fees; otherwise a launch discount |
| Competitors to benchmark | National, Shan, others [TBD: gap analysis with shelf prices] |

## Status (3 Oct 2026)
- Label drafts for 500 g and 900 g, front and back (Urdu checked), exist as previews.
- **The labels can't be printed yet.** They need:
  - the PFA license number
  - our PCSIR figures
  - the iodine dose fixed to the legal level (old draft: 15 mg/kg KIO₃ is too low; 900 g said "Not iodised")
- PFA license: not started.
- Halal: not held (required by PFA label approval).

## Next actions (in order)
1. Baba: prepare the packing room to PFA standard, plus worker medicals.
2. Baba: apply for the PFA license.
3. Halal (PHDA): ask the fee and timeline.
4. PCSIR report arrives → put the real figures on the label.
5. Cost sheet for each pack (salt + iodine + pouch + label + labour + Daraz fee) → confirm 35% margin → set prices.
6. Label approval → product registration → print → sell.


---

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


---

---
title: Systems and Tools
as_of: 2026-10-03
---

# 10 · Systems and Tools

## Ledger app (the books)
- **Live:** https://aaatradehouse-ledger.vercel.app. Install it on the phone as an app.
- **Code:** laptop folder `C:\Users\786\Desktop\AAATradeHouse\app-repo` (GitHub repo).
  - React/Vite, auto-deploys from GitHub `main` to Vercel project "aaatradehouse-ledger".
- **Database:** Supabase project `lceijfagzgmroxridgua` (free plan, so **no automatic backups**; a nightly backup is planned).
- **Login:** AAA_Trading.pk@outlook.com, shared by Rao and baba. Sign-ups are off. Signing out affects only that device.
- **Screens:**
  - Dashboard
  - Cash Book
  - Debtors & Sales (with Receive payment)
  - Sell Salt
  - Buy Salt
  - Crush Salt
  - Money Out
  - Capital
  - Deleted entries (with Restore)
- **Safety:**
  - Every entry is checked by the database (debits = credits, no negative cash, no negative stock).
  - A save tapped twice is recorded once.
  - Deletes are audited and restorable.
- **Errors:** Sentry project `aaatradehouse-ledger`.
- **Being fixed (3 Oct):**
  - crush runs fail
  - the product list
  - plain-English error messages
  - below-cost warning
- **Still to come:**
  - correct-entry button
  - date guards
  - pay supplier
  - advances
  - stock count
  - nightly backup

### Ledger app: how it works (plain words)
- **Numbering:** EV-000xxx entries, INV invoices, DSP dispatches, BATCH stock lots, PT customers. **Numbers are never reused**; gaps are normal (dry runs, deleted tests).
- **Offline:** the last copy can be read, but nothing can be saved. A banner shows when offline. The app updates when fully closed and reopened with signal.
- **Money Out** starts on "Pick one…" (no default). Asset types: Vehicle 1400, Livestock 1450, Equipment 1500.
- **Delete** ("…" → "Delete entry…"):
  - It shows a preview and needs a reason.
  - It removes the whole entry in one go, then re-checks the books.
  - It refuses when something depends on the entry, and says what to delete first.
- **Who can do what:**
  - Rao/baba (shared login): read and write everything, including delete and restore.
  - JARVIS (role "assistant"): read only. Later it can make proposals, which Rao approves and the database posts.
  - Anyone else: nothing.

## JARVIS (AI COO on Rao's laptop)
- Voice-first assistant on Windows 11 (Dell Latitude 5420, Python 3.12).
- Folder: `C:\Users\786\Desktop\Mark-XXXIX-OR-main`. GitHub: raoaosaf4544-cell/Jarvis (master).
- Voice through Gemini Live (free tier, so customer names are hidden in voice).
- Memory: Obsidian vault `C:\Users\786\Desktop\JARVIS_Memory`. CRM: HubSpot.
- **CFO** (finance specialist): reads the ledger with its own **read-only** login. Ledger writes only after Rao approves.
- **Approvals:** every risky action becomes a numbered item (APR-n). Approve by voice, on the deck, or (soon) from the phone.
- Tests: always run with `.venv\Scripts\python.exe -m pytest` (707 passing on 3 Oct).
- Kill it with `Get-Process python | Stop-Process -Force`.

## Phone channel (being built)
- JARVIS → Supabase mailbox → **Telegram bot** (all updates, approvals, briefs) + **ntfy** ringing for urgent items.
- Urgent = an approval waiting 2h+, a buyer reply or hot lead, or JARVIS crashed.
- Snooze: say "I'm sleeping, don't disturb for 2 hours", or `/snooze 2h`, `/wake`.
- 8 am and 8 pm briefs. A free cloud AI answers when the laptop is off (read-only, can't approve anything).
- Status: cloud half steps 1–2 done; paused for the ledger fixes. Laptop half built, switched off (`PHONE_BRIDGE=off`).

## Website
- aaatradehouse.com: Vite + React, prerendered, on Vercel. Laptop folder `AAATradeHouse/website/website2.0`.
- The enquiry/RFQ form posts straight to HubSpot (portal 246642088). n8n is **not used** (dropped).
- [risk] Contains certification claims not held (see 07).

## Other
- Email: Zoho (free, web only). Claude Projects and memory hold this knowledge base.
- Tools deliberately dropped: n8n, Excel CRM (backup only), WhatsApp automation (unofficial libraries can get the number banned).
- **Secrets** (API keys, passwords, tokens) live only in `.env` files or the Supabase dashboard. Never in chat, never in GitHub.


---

---
title: Glossary
as_of: 2026-10-03
---

# 11 · Glossary (local words in the register and in conversation)

| Word | Meaning |
|---|---|
| **Roznamcha** | Daily cash register (paper), baba's original record |
| **Udhaar** | Credit: goods given now, paid later (Accounts Receivable) |
| **Kharch** | Expense |
| **Aamdan** | Income / money in |
| **Namak** | Salt |
| **Sabit / ثابت** | Whole (rock salt sold as whole lumps), **not** "sabiqa" (old debt). Earlier misreading, corrected 27 Sep |
| **Dalay / ڈلے** | Lumps of rock salt |
| **Daana / دانہ** | Coarse grain salt |
| **Bareek / powder** | Fine ground salt |
| **Man / من** | 40 kg |
| **Bori / bag** | Sack: 20, 25, 40 or 50 kg |
| **Bardaana** | Empty sacks/bags (packing material) |
| **Kiraya** | Freight/fare: delivery transport (5200) or travel (5600) |
| **Hamali / mazdoori** | Loading/unloading labour |
| **Mistri** | Builder/mason |
| **Bijli** | Electricity |
| **Kiryana** | Small grocery shop (our main local customer) |
| **Sabzi** | Vegetables (customer "Mani Sabzi" sells vegetables) |
| **Khana / chai / doodh / anday** | Food / tea / milk / eggs (site meals 5500) |
| **Dawai** | Medicine |
| **Baba** | Father: M. Shafiq Shaheen |
| **Batch** | One lot of salt bought or crushed, tracked separately for cost |
| **Crush run** | Turning rock into fine/coarse salt; recorded in "Crush Salt" |
| **COGS** | Cost of the salt that was sold |
| **FOB / CIF** | Export price terms: FOB = we deliver to the port in Pakistan; CIF = we pay shipping and insurance to the buyer's port |
| **MOQ** | Minimum order quantity |
| **RFQ** | Request for quote |
| **PFA** | Punjab Food Authority |
| **PCSIR** | Pakistan Council of Scientific & Industrial Research (lab) |
| **PMDC** | Punjab Mineral Development Corporation (leases the salt mines) |
| **PHDA** | Punjab Halal Development Agency |
| **APR-n** | A JARVIS approval request number |


---

---
title: Rules (for people and AI)
as_of: 2026-10-03
---

# 12 · Rules: Never and Always

## NEVER
1. **Never claim a certificate, test or figure we don't hold**: halal, PCSIR, PMDC-certified, ISO, HACCP, PSQCA. Not on labels, the website, emails or quotes.
2. **Never invent numbers, leads, customers or prices.** If it's not in the books or stated by Rao or baba, say "unknown".
3. **Never send any message to a customer, buyer or supplier without Rao's approval of that exact message.**
4. **Never spend money autonomously**: no purchases, subscriptions, top-ups or checkout.
5. **Never change the books without approval.** Corrections only through the app's correct or delete functions.
6. **Never put secrets in chat or GitHub.** Rotate anything that leaks.
7. **Never score leads with an AI.** Use `lead_scorer.py` only.
8. **Never break email warm-up limits** (10/day in week 1, +5/week, max 40/day).
9. **Never round numbers up to sound better.** Honest bad news early.
10. **Never guess which name signs a document.** Ask.

## ALWAYS
1. **Legal, banking and government documents are signed by M. Shafiq Shaheen; everyday business by Rao Aosaf.**
2. Invoices and contracts: "AAA General Trading (trading as AAATradeHouse)".
3. Enter the register in the app the same day, including crush runs, credit purchases and customer payments.
4. Check figures against the live ledger before using them.
5. Say when the books are out of date ("no sales entered since …").
6. Report failures plainly ("ERROR: …"). Never say "done" unless it was verified.
7. Prefer the cheapest reliable option; explain WHY / EFFECT / RISK for any change.
8. One change → verify → save/commit → next.
9. Ask one clear question when unsure, with options.


---

---
title: Open Questions (gaps to fill)
as_of: 2026-10-03
---

# 13 · Open Questions

Answer these to complete the knowledge base. Each answer goes into the file shown.

| # | Question | File |
|---|---|---|
| 1 | Usual selling price today for each product (rock / fine / coarse) and bag size (20/25/40/50 kg); lowest price baba accepts | 05 |
| 2 | Who supplies the raw rock (name, mine or agent, location, terms)? | 04 |
| 3 | Who supplied the 12 t of crushed salt (BATCH-075)? Has the Rs 117,500 been paid? | 04, 06 |
| 4 | Crushing: always in-house, or sometimes a contractor? Crusher capacity per day? | 04 |
| 5 | Workers: names, roles, monthly pay (Qasim, Rafiq, Ali, others) | 02 |
| 7 | Chamber of Commerce: which chamber, membership number, expiry | 01, 07 |
| 8 | Is Rao's authority letter from M. Shafiq Shaheen signed? | 01 |
| 9 | Customer phone numbers and areas | 05 |
| 10 | Udhaar rule: maximum credit per customer and payment deadline? | 05 |
| 11 | Grain sizes our crusher produces for fine and coarse (mm) | 03 |
| 12 | Competitor shelf prices: National / Shan 800 g–1 kg in local shops | 08 |
| 13 | Physical stock count: actual kg of rock and fine at the plant today | 04 |
| 14 | Was the Rs 5/kg salt a lower grade (dust / chura)? | 05 |
| 15 | Crusher owned or rented? Plant land owned or rented? Full plant postal address | 04, 01 |
| 16 | Raw salt mine/area, price per ton at the mine, freight per truck | 04 |
| 17 | Who/what is "Makhan"? Are Abid and Jabar recurring? | 02 |
| 18 | Motorcycle permit line Rs 75,000: correct? | 04 |
| 19 | Exact office rent and its due date | 01, 06 |
| 20 | Retail pouch and label suppliers: price per 1,000, MOQ, lead time | 04, 08 |


---

---
title: Decisions Log
as_of: 2026-10-03
---

# 14 · Decisions Log (dated, newest last)

| Date | Decision | By |
|---|---|---|
| 27 Sep 2026 | Sole proprietorship in M. Shafiq Shaheen's name; Rao signs as Operations Manager / Authorised Representative | Rao |
| 27 Sep 2026 | Both 500 g and 900 g retail packs will be iodised | Rao |
| 27 Sep 2026 | Site living costs (meals, living, motorcycle) stay business expenses, split into production vs site overhead | Rao |
| 27 Sep 2026 | One shared ledger login for Rao and baba; baba enters on his phone (English UI) | Rao |
| 27 Sep 2026 | JARVIS reads the ledger freely; every ledger write needs Rao's approval | Rao |
| 27 Sep 2026 | Website PMDC/halal wording kept for now (risk flagged); the "15-day shipment" claim not added | Rao |
| 27 Sep 2026 | Retail distribution order: own delivery → wholesalers → Daraz | Rao |
| 27 Sep 2026 | Suspense list resolved line by line with the register; register wins over Excel | Rao |
| 28 Sep 2026 | "Delete entry" added to the ledger app (audited, restorable), only for Rao and baba | Rao |
| 28 Sep 2026 | n8n dropped (licence blocks SaaS resale); WhatsApp automation dropped | Rao |
| 28 Sep 2026 | JARVIS = COO with specialist agents; first specialist = CFO (complete finance expert) | Rao |
| 28 Sep 2026 | Phone channel: Telegram bot via Supabase (24/7) + ntfy for urgent rings; only Rao approves; snooze supported; free cloud AI answers when the laptop is off | Rao |
| 28 Sep 2026 | JARVIS voice hides customer names while on the Gemini free tier | Rao |
| 3 Oct 2026 | Local products reduced to three: Rock (whole/dalay), Fine Powder, Coarse (daana); bags 20/25/40/50 kg + man + kg | Rao |
| 3 Oct 2026 | BATCH-075 (bought crushed, 14 Sep) is fine powder | Rao |
| 3 Oct 2026 | Business knowledge base: master on the Desktop, copy in the JARVIS vault, private GitHub backup, copy in the Claude Project | Rao |
| 3 Oct 2026 | Official phones: +92 317 4286226 and +92 300 351 3889 | Rao |
| 3 Oct 2026 | Etsy fully parked: JARVIS never raises it unless Rao does | Rao |


---

