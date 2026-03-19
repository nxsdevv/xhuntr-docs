# Setup Guide

Getting started with XHuntr takes under 2 minutes.

## 1. Start the bot

Open Telegram and search for [@XHuntrbot](https://t.me/XHuntrbot), or go directly: [t.me/XHuntrbot](https://t.me/XHuntrbot)

Send `/start` — you'll get a welcome message and a 3-day free trial automatically activated.

## 2. Add accounts to track

Use `/add` followed by an X username (without `@`):

```
/add ansemtrades
/add cobie
/add solbigbrain
```

You can add up to 3 accounts during the free trial. Paid plans allow 15–30 accounts.

## 3. Check your tracked accounts

```
/list
```

Shows all accounts you're currently monitoring with their current community memberships.

## 4. View recent alerts

```
/recent
```

Shows your last 10 alerts. Useful if you missed a notification.

## 5. Remove an account

```
/remove ansemtrades
```

## 6. Check your subscription status

```
/status
```

Shows: plan type, expiry date, accounts used vs. limit.

---

## Alert types you'll receive

Once an account is tracked, you'll get Telegram alerts for:

| Alert | What it means |
|-------|--------------|
| 🚨 Community Created | Tracked account created a new X community |
| 👀 Community Joined | Tracked account joined an existing community |
| 📡 CA in Community | Contract address posted inside an X community |
| 📡 CA Tweet | Tracked account tweeted a Solana CA publicly |
| ✏️ Community Rename | A community changed its name |
| 📌 Pinned Tweet Changed | Tracked account changed their pinned tweet |
| 🔥 Convergence Alert | 2+ tracked accounts joined the same community |

## Tips

- **Convergence alerts are the highest signal** — when two tracked callers independently join the same community, it suggests coordinated conviction
- **CA in Community fires before CA Tweet** — the CA is often posted privately in a community before being tweeted publicly. This is the earliest possible CA signal
- **Track the developer account, not just the caller** — if you know who's building a project, tracking them directly catches the Community Created alert before anyone else
- **Rename alerts are underrated** — a community changing from a generic name to a token ticker is a reliable launch signal

---

## Troubleshooting

**I'm not getting alerts**
- Check that the accounts are active on X (not suspended)
- Use `/list` to verify accounts were added correctly
- Some X accounts have low community activity — check back over a few days

**My trial expired and I want to subscribe**
- Use `/subscribe` to see current plan options

**I want to track more accounts**
- Upgrade to a paid plan via `/subscribe`

**Something isn't working**
- Message [@lukefrostdev](https://t.me/lukefrostdev) on Telegram
