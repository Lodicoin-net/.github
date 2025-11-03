<!-- Lodicoin Org Profile README (mobile-optimized, uncut) -->
<p align="center">
  <img src="https://talkimg.com/images/2025/11/02/U6Cnjd.png"
       alt="Lodicoin Logo"
       width="480">
</p>

<h1 align="center">⚜️ LODICOIN ($LODI) v2 ⚜️</h1>
<p align="center"><i>From chaos rises the crown - community-run on
Solana.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Built_on-Solana-000?logo=solana">
  <img src="https://img.shields.io/badge/CTO-Community_Takeover-gold">
  <img src="https://img.shields.io/badge/Status-Active-success">
  <img src="https://img.shields.io/badge/License-MIT-blue">
</p>

---

## 👑 What is Lodicoin?

**Lodicoin ($LODI)** is a Solana-based, community-driven project that
gamifies influence and reputation across creators and KOLs.

> Compete for rank. Earn $LODI. Build the crown together.

---

───────────────────────────────────────────────────────────────
⚡ CLI SHOWCASE (DEV PREVIEW)
───────────────────────────────────────────────────────────────
# Install globally
npm install -g @lodicoin/cli

# Initialize a Next.js + Solana dApp
lodi init my-app --template next-solana

# Rename the CLI namespace
lodi rename --name crowdking

# Check version
crowdking version

# Link socials for KOL scoring
lodi link --telegram @yourhandle --discord yourname#1234

# View leaderboard (top 20)
lodi leaderboard --top 20

# Verify on-chain proof
lodi verify --address <WALLET> --proof proof.json

# Tip another KOL
lodi tip --to <WALLET> --amount 5 --memo "ggs"

───────────────────────────────────────────────────────────────
🏆 SAMPLE LEADERBOARD OUTPUT
───────────────────────────────────────────────────────────────
➜ lodi leaderboard

RANK  HANDLE          SCORE   TG       DISC
1     @alpha_kol      15940   linked   linked
2     @pixelqueen     15110   linked   linked
3     @chainbard      14780   linked   linked
4     @sol_samurai    13920   linked   linked
...

───────────────────────────────────────────────────────────────
🔌 API QUICK DEMO
───────────────────────────────────────────────────────────────
# Fetch leaderboard (top 10)
curl -s "https://api.lodicoin.net/v1/leaderboard?limit=10"

# Submit an engagement proof
curl -s -X POST "https://api.lodicoin.net/v1/proofs" \
  -H "Authorization: Bearer $LODI_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "platform": "telegram",
    "handle": "@yourhandle",
    "signature": "0xdeadbeef",
    "weight": 3.2
  }'

───────────────────────────────────────────────────────────────
📦 SAMPLE API RESPONSE
───────────────────────────────────────────────────────────────
{
  "items": [
    { "rank": 1, "handle": "@alpha_kol", "score": 15940 },
    { "rank": 2, "handle": "@pixelqueen", "score": 15110 }
  ],
  "updatedAt": "2025-11-03T00:00:00Z"
}
───────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────
🧩 CORE FEATURES
───────────────────────────────────────────────────────────────
🪙  $LODI Token          →  Utility + governance on Solana  
🏆  KOL Leaderboard      →  Telegram & Discord integration  
⚔️  Community Takeover   →  Proposals, voting & influence power  
🔍  Transparent APIs     →  Real-time on-chain metrics & proofs  
🧰  Dev Tools            →  CLI, SDKs & scoring adapters for builders  
───────────────────────────────────────────────────────────────

───────────────────────────────────────────────────────────────
🗂 MONOREPO SNAPSHOT
───────────────────────────────────────────────────────────────
lodicoin/
├─ apps/
│  ├─ web/         →  Next.js site & leaderboard
│  └─ api/         →  REST API (leaderboard, proofs)
│
├─ packages/
│  ├─ cli/         →  @lodicoin/cli — TypeScript CLI tools
│  ├─ sdk-js/      →  Lodicoin SDK (JS / TS)
│  └─ scoring/     →  Reputation & scoring engine
│
└─ docs/
   ├─ whitepaper/  →  Vision, API specs, branding
   └─ media/       →  Assets, logos, press material
───────────────────────────────────────────────────────────────

───────────────────────────────────────────────────────────────
🗺 ROADMAP
───────────────────────────────────────────────────────────────
[ ] 🔹 Public API & Documentation  
[ ] 🔸 KOL Verification & Profile Badges  
[ ] 🪙 Reward & Quest Engine  
[ ] 💬 Telegram + Discord Adapters  
[ ] ⚙️ SDKs: JavaScript / TypeScript / Python  
[ ] 🛡️ Guardian Program (Community Moderation)
───────────────────────────────────────────────────────────────


───────────────────────────────────────────────────────────────
🌐 OFFICIAL LINKS
───────────────────────────────────────────────────────────────
🌎 Website      →  https://lodicoin.net  
💬 Telegram     →  https://t.me/lodicoin  
🐦 X / Twitter  →  https://x.com/lodicoins
───────────────────────────────────────────────────────────────

───────────────────────────────────────────────────────────────
⚠️ DISCLAIMER
───────────────────────────────────────────────────────────────
Lodicoin is a community-driven experimental initiative built on
Solana. Participation is voluntary and at your own risk.

Nothing in this repository, its documentation, or community
communications should be interpreted as financial advice.

Always do your own research (**DYOR**) before engaging with any
crypto asset, smart contract, or community project.

───────────────────────────────────────────────────────────────
💠 THE COMMUNITY TAKES THE CROWN 💠
───────────────────────────────────────────────────────────────
           ⚜️  LODICOIN V2 — POWERED BY YOU  ⚜️
───────────────────────────────────────────────────────────────
