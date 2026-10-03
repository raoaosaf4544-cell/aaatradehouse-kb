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
