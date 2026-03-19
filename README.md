# XHuntr — X Community Sniper for Solana Alpha

**The only Telegram bot that monitors X (Twitter) community activity in real-time for crypto traders.**

→ [xhuntr.com](https://xhuntr.com) | [Start on Telegram](https://t.me/XHuntrbot) | 3-day free trial, no card

---

## What It Does

XHuntr watches the X accounts you specify and fires instant Telegram alerts when they do anything in the X social layer — before any token is deployed, before any wallet has moved.

Most Solana trading tools are on-chain: they fire when a wallet buys. By then, the smart money is already in. XHuntr monitors the coordination that happens **before** the on-chain trade — in X communities where organized launches are prepared.

## The 7 Alert Types

| Alert | When it fires | What it means |
|-------|--------------|---------------|
| 🚨 Community Created | A tracked account creates a new X community | Developer organizing — earliest signal, often 48h+ before launch |
| 👀 Community Joined | A tracked account joins any community | Conviction signal — they were invited |
| 🔥 Convergence | 2+ tracked accounts join the same community | Coordinated action — highest confidence signal |
| 📡 CA in Community | Contract address posted inside a community | Before the public tweet — fires first |
| 📡 CA Tweet | Tracked account tweets a CA publicly | Includes live DexScreener data + Trojan quick-buy link |
| ✏️ Community Renamed | Community changes name | Launch timing signal |
| 📌 Pinned Tweet Changed | Account changes pinned tweet | Public declaration of current focus |

## Why the Social Layer Matters

Every organized Solana launch follows the same sequence:

```
T-48h  Developer creates X community
T-36h  KOLs invited and join privately
T-6h   CA posted inside community
T=0    CA tweeted publicly
T+1m   On-chain buys start (wallet trackers fire here)
T+1h   CT amplifies (retail finds out here)
```

XHuntr fires at T-48h. Wallet trackers fire at T+1m. Everything in between is the edge.

## How It Works Technically

X community data is not in the public Twitter API. Community membership shows up in X's internal GraphQL endpoints, which require:
- Authenticated X sessions
- Continuous polling (not webhook-based)
- Rate limit management across all tracked accounts
- Event deduplication to avoid duplicate alerts

XHuntr maintains authenticated sessions and polls each tracked account every 10–30 seconds. Detection latency is typically under 30 seconds from event to Telegram alert.

## Setup (2 minutes)

1. Open [@XHuntrbot](https://t.me/XHuntrbot) on Telegram
2. `/start` — activates 3-day free trial immediately
3. `/track @username` — add each account you want to monitor
4. Alerts arrive in real-time as Telegram messages

### Recommended starting list
- 2–4 active Solana developers who have launched multiple tokens
- 5–8 KOLs verified for early access (use DexCheck + KolScan to vet)
- 2–4 smaller discovery accounts you've personally seen be early

Keep to 10–20 accounts. More accounts = more noise.

## Bot Commands

```
/start          Activate account (3-day trial)
/track @user    Add account to monitoring list
/untrack @user  Remove account
/list           See all tracked accounts
/subscribe      View and upgrade subscription
/help           Command reference
```

## Pricing

| Plan | Price | Duration | Accounts |
|------|-------|----------|----------|
| Free Trial | 0 SOL | 3 days | 3 accounts |
| Weekly | 0.50 SOL | 7 days | 15 accounts |
| Monthly | 1.75 SOL | 30 days | 20 accounts |
| Lifetime | 15 SOL | Forever | 30 accounts |

Payment in SOL on-chain. No auto-renewal. No accounts or signups beyond Telegram.

## How It Compares to Other Tools

| Tool | What it monitors | When it fires |
|------|-----------------|--------------|
| **XHuntr** | X community activity | T-48h — before any token exists |
| Cielo Finance | On-chain wallet transactions | T+1m — after the buy |
| GMGN | On-chain analytics + trends | T+0 — when token is live |
| DexCheck | Historical KOL call accuracy | Research tool, no live alerts |
| KolScan | KOL wallet performance | Research tool, no live alerts |
| Trojan / BullX | Execution | When you decide to trade |

XHuntr is the only tool covering the social layer. Use it alongside Cielo for full coverage: XHuntr catches the preparation, Cielo catches the execution.

## Links

- **Website:** [xhuntr.com](https://xhuntr.com)
- **Telegram Bot:** [@XHuntrbot](https://t.me/XHuntrbot)
- **Documentation / Blog:** [xhuntr.com/blog](https://xhuntr.com/blog)
- **KOL Tracker:** [xhuntr.com/kols](https://xhuntr.com/kols)
- **Comparisons:** [xhuntr.com/vs/cielo-finance](https://xhuntr.com/vs/cielo-finance)

---

*3-day free trial, no card → [t.me/XHuntrbot](https://t.me/XHuntrbot)*
