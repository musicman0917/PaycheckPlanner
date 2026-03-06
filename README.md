# 💰 Paycheck Planner

A free, single-file budgeting tool built for the **NeighborhoodofMusic** community. No accounts, no subscriptions, no data sent anywhere — everything runs entirely in your browser.

---

## Features

### Budget Tab

**Income & Expenses**
- Enter your net (take-home) paycheck and pay frequency (weekly, bi-weekly, twice a month, monthly)
- Add recurring expenses organized by **vendor and category** (housing, transport, subscriptions, etc.)
- Set each bill's frequency and the planner converts everything to a per-paycheck cost automatically
- Add **one-off payments** with due dates — the planner flags which ones fall in your next paycheck window

**Per Paycheck Summary**
- Shows your **Bills Transfer** (exact amount to move to savings to cover all bills and one-offs)
- Shows **Left in Checking** — your free spending money after the transfer

**80 / 10 / 10 Split**
- Automatically calculates your paycheck split based on the 80/10/10 budgeting method
- **Bills (80%)** — your actual transfer amount, with your real % of paycheck shown. Flags a warning if bills exceed 80%
- **Debt Snowball (10%)** — 10% of net pay, auto-sent to the Debt Snowball tab as your extra payment
- **Separate Savings (10%)** — 10% earmarked for a second savings account
- **Remaining / Buffer** — what's left after the full split; flags a warning if you're over budget
- Visual bar shows the full split at a glance

**Savings Account**
- Track your current savings balance and APY
- See estimated monthly and yearly interest earned on your current balance
- Check whether your transfer fully covers your monthly bills

**Savings Goals**
- Add multiple savings goals (e.g. Emergency Fund, Japan Trip)
- Each goal tracks a name, target amount, and current balance
- **Priority system** — click the numbered badge on any goal to bump it up in priority
- **Waterfall logic** — the transfer fills the highest-priority goal first, then cascades to the next
- Shows estimated paychecks to completion per goal based on its allotted portion of the transfer
- Progress bar per goal; completed goals show a green ✓ Goal Reached badge
- Lower-priority goals that can't receive any transfer yet show "after higher goals"

---

### Debt Snowball Tab

- Add all your debts with balance, minimum payment, and interest rate
- Enter an **extra monthly payment** — automatically populated from your 10% split on the Budget tab
- Debts are sorted **smallest balance first** — classic snowball method
- The **🎯 Target** debt is always highlighted
- When a debt is paid off, its minimum rolls permanently forward to the next target
- Summary cards show **Total Debt**, **Months to Freedom**, and **Total Interest Paid**
- Side-by-side comparison of payoff date and interest saved **with vs. without** the extra payment
- **Monthly Roadmap table** — expand to see every payment on every debt, every month, until debt-free

---

## Backup & Restore

Your data is saved automatically as you type, but browser cache clears can wipe it. Use the built-in backup system to protect your data.

- **⬇ Export Backup** — downloads a dated `.json` file (e.g. `paycheck-planner-backup-2026-03-06.json`) containing all your categories, vendors, debts, goals, and settings
- **⬆ Import Backup** — opens a file picker, validates the file, and restores everything live without a page reload
- Both actions show a confirmation toast notification

**Recommended:** Export a backup any time you make significant changes, and store it somewhere safe (Google Drive, Dropbox, etc.).

---

## ⚠️ Important: Data is Local to Your Device

This tool saves your data using your browser's **localStorage** — meaning:

- Your data **never leaves your device** and is never sent to any server
- Data is saved **per browser, per device** — if you open it on your phone, it won't have the data from your laptop
- Clearing your browser's site data or cache **will erase your saved information**
- To avoid losing your data, **use the same browser on the same device** consistently, and **export a backup regularly**

---

## How to Use

1. Open `index.html` in any modern web browser — no installation required
2. Fill in your income and bills on the **Budget** tab
3. Review your **80/10/10 split** in the results panel
4. Add savings goals to the **Savings Goals** section
5. Switch to the **Debt Snowball** tab — your 10% extra payment is already pre-filled
6. Add your debts and expand the Monthly Roadmap to see your payoff plan
7. Hit **⬇ Export Backup** to save your data to a file

---

## Running It

**Option 1 — Direct (easiest):** Download `index.html` and open it in your browser. Double-click the file or drag it into a browser window.

**Option 2 — GitHub Pages:** Enable GitHub Pages under Settings → Pages and it'll be live at `https://[your-username].github.io/[repo-name]/`.

**Option 3 — Local server:** Works fine with VS Code Live Server or any local HTTP server.

---

## Credits

Built by [NeighborhoodofMusic](https://twitch.tv/neighborhoodofmusic) and offered free to the community.  
Come hang out on [Twitch](https://twitch.tv/neighborhoodofmusic) 🎸

[YouTube](https://www.youtube.com/channel/UC2E7Z-nqlySUEqLF3uLgOxg) · [TikTok](https://www.tiktok.com/@musicman0917) · [Discord](https://discord.gg/UUWNtJb3qr) · [Spotify](https://open.spotify.com/artist/7y3lOYUJMjdbxRS0KH19LS) · [Bluesky](https://bsky.app/profile/musicman0917.bsky.social) · [Merch](https://neighborhoodofmusic.com)
