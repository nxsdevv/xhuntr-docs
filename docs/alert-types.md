# Understanding XHuntr Alerts

Each alert type fires at a different point in the token launch timeline. Here's what to do with each one.

---

## 🚨 Community Created

**What it means:** A tracked account just created a brand-new X community.

**When it fires:** Immediately when the community is created — often days before any public announcement.

**Why it matters:** Developers and alpha hunters create X communities as their first organizational step. The community exists before the token exists, before the tweet, before anything. This is the earliest possible signal.

**Example alert:**
```
🚨 Community Created
@ansemtrades created a new X community
Community: "Solana Builders DAO"
Members: 1
Created: just now
```

**What to do:** Start watching the community. Look for other tracked accounts joining it. Look for a CA to appear.

---

## 👀 Community Joined

**What it means:** A tracked account joined an existing X community.

**When it fires:** Within seconds of the join event.

**Why it matters:** When a caller or dev you respect joins a community, it reveals what they're paying attention to. Multiple independent joins = conviction signal.

**Example alert:**
```
👀 Community Joined
@cobie joined "Solana Builders DAO"
Community size: 47 members
```

---

## 🔥 Convergence Alert

**What it means:** 2+ tracked accounts joined the same community within a short time window.

**When it fires:** Triggered when the second (or third, fourth...) tracked account joins.

**Why it matters:** Independent actions converging on the same community is the strongest signal in XHuntr. Coordinated action without an obvious public signal driving it.

**Example alert:**
```
🔥 CONVERGENCE — 3 accounts joined the same community
Community: "PUMP"
@ansemtrades joined 14 min ago
@cobie joined 8 min ago
@solbigbrain just joined
```

**What to do:** This is highest priority. Act on convergence alerts before doing additional research.

---

## 📡 CA in Community

**What it means:** A tracked account posted a contract address inside an X community.

**When it fires:** Before the public tweet in most cases.

**Why it matters:** Developers often share CAs with their community first as a soft launch or test. XHuntr catches this message before it leaves the community.

**Example alert:**
```
📡 CA in Community (FIRST!)
@devaccount posted a CA inside "PUMP"
CA: Abc123...xyz
Community: PUMP
⚡ DexScreener | 🚀 Buy on Trojan
```

The alert includes a DexScreener link and a Trojan quick-buy link.

---

## 📡 CA Tweet

**What it means:** A tracked account tweeted a Solana contract address publicly.

**When it fires:** When the CA appears in a public tweet.

**Note:** If you're tracking the account and they also posted the CA in a community first, you would have already received a `CA in Community` alert earlier.

**Example alert:**
```
📡 CA Tweet
@ansemtrades tweeted a CA
CA: Abc123...xyz
Tweet: "launching something we've been building for months..."
⚡ DexScreener | 🚀 Buy on Trojan
```

---

## ✏️ Community Rename

**What it means:** An X community changed its name.

**When it fires:** Immediately on rename.

**Why it matters:** Communities often start with generic names ("Solana Builders") and rename to a token ticker when the launch is imminent. A rename is frequently a launch signal.

**Example alert:**
```
✏️ Community Renamed
"Solana Builders" → "PUMP"
Community size: 312 members
Rename detected: just now
```

**What to do:** Treat a rename like a launch signal. Check if tracked accounts are members.

---

## 📌 Pinned Tweet Changed

**What it means:** A tracked account changed their pinned tweet.

**When it fires:** Immediately on change.

**Why it matters:** Changing a pinned tweet is a deliberate, public declaration. When a caller or developer changes their pinned tweet, they're usually promoting something they currently want people to see.

**Example alert:**
```
📌 Pinned Tweet Changed
@cobie changed their pinned tweet
New: "been trading this for 2 weeks. thoughts: [link]"
```

---

## Alert priority guide

| Priority | Alert | Action |
|----------|-------|--------|
| 🔴 Highest | Convergence Alert | Act immediately |
| 🔴 High | CA in Community | Check DexScreener, consider entry |
| 🟡 Medium | Community Created | Watch and wait |
| 🟡 Medium | Community Rename | Check community members, near-term action |
| 🟢 Monitor | Community Joined | Note conviction from tracked accounts |
| 🟢 Monitor | CA Tweet | Usually after price already moved; confirm on DexScreener |
| ⚪ FYI | Pinned Tweet Changed | Context signal, rarely actionable alone |
