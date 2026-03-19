<div align="center">

<img src="https://raw.githubusercontent.com/nxsdevv/xhuntr-docs/main/assets/homepage.png" alt="XHuntr — Track what alpha hunters do before they post it" width="100%" />

<br />
<br />

[![Telegram](https://img.shields.io/badge/Telegram-@XHuntrbot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/XHuntrbot)
[![Website](https://img.shields.io/badge/Website-xhuntr.com-black?style=for-the-badge&logo=safari&logoColor=white)](https://xhuntr.com)
[![Network](https://img.shields.io/badge/Network-Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://xhuntr.com)
[![Alerts](https://img.shields.io/badge/Alerts_sent-1%2C357+-00C4B4?style=for-the-badge)](https://xhuntr.com)

</div>

---

## What is XHuntr?

XHuntr monitors X (Twitter) accounts for community activity and fires instant Telegram alerts the moment something happens — before any token is deployed, before any wallet has moved.

Most Solana trading tools are on-chain: they fire after a transaction executes. XHuntr covers the social preparation layer that precedes every organized launch.

---

## The Timeline

```
T-48h   Developer creates a private X community
T-36h   KOLs invited and join privately
T-6h    CA posted inside the community (not tweeted yet)
T=0     CA tweeted publicly to all of CT
T+1m    On-chain buys begin  ← wallet trackers fire here
T+1h    CT amplifies, retail discovers it
```

**XHuntr fires at T-48h. Wallet trackers fire at T+1m.**

---

## 7 Alert Types

| Alert | When it fires | What it signals |
|-------|--------------|-----------------|
| 🚨 **Community Created** | Tracked account creates a new X community | Developer organizing — earliest possible signal |
| 👀 **Community Joined** | Tracked account joins a community | Conviction — they were invited |
| 🔥 **Convergence** | 2+ tracked accounts join the same community | Coordinated action — highest confidence signal |
| 📡 **CA in Community** | Contract address posted inside a community before the public tweet | Before any wallet tracker has data |
| 📡 **CA Tweet** | Tracked account tweets a Solana CA publicly | Includes live DexScreener data |
| ✏️ **Community Renamed** | Community changes name | Launch timing signal |
| 📌 **Pinned Tweet Changed** | Account changes pinned tweet | Public declaration of current focus |

---

## How It Works

X community data isn't in the public Twitter API. Community membership lives in X's internal GraphQL endpoints — which require authenticated sessions, continuous polling, and rate limit management.

XHuntr maintains those sessions and polls each tracked account every 10–30 seconds. Detection latency is typically under 30 seconds from event to Telegram alert.

---

## Setup

```
1. Open @XHuntrbot on Telegram
2. /start
3. /track @username  — add each account you want to monitor
```

**Commands**

```
/start          Activate account
/track @user    Add to monitoring list
/untrack @user  Remove from list
/list           Show all tracked accounts
/help           Command reference
```

---

## How It Compares

| Tool | Monitors | Fires when |
|------|----------|-----------|
| **XHuntr** | X community activity | T-48h — before any token exists |
| Cielo Finance | On-chain wallet transactions | T+1m — after the buy |
| GMGN | On-chain analytics + trending | T=0 — when token is live |
| KolScan | KOL historical performance | Research only — no live alerts |

XHuntr is the only tool covering the social layer. Use it alongside Cielo or GMGN for full coverage — XHuntr catches the preparation, on-chain tools catch the execution.

---

## Recommended Starting List

- 2–4 active Solana developers who have launched multiple tokens
- 5–8 KOLs with verified early-access track records
- 2–4 smaller discovery accounts you've personally seen be early

Keep it focused. 15–20 accounts is the right size. Quality beats quantity.


---

## Documentation

| Guide | Description |
|-------|-------------|
| [Setup Guide](docs/setup.md) | Get started in 2 minutes — add accounts, understand the bot commands |
| [Alert Types](docs/alert-types.md) | What each alert means and when to act |
| [Which Accounts to Track](docs/which-accounts-to-track.md) | How to build a high-signal tracked list |

---
<div align="center">

**→ [xhuntr.com](https://xhuntr.com) · [Start on Telegram](https://t.me/XHuntrbot)**

</div>
