# Tramfolio ($TRAMFOLIO)

> **The Automated Airdrop Tram on Solana**

Every 5 minutes, creator fees from `$TRAMFOLIO` buy the next coin on the line via Jupiter and airdrop it directly to holders. 14 stops along the track, then it loops continuously.

---

## 🚃 How the Tram Engine Works

1. **Claim Fees**: The protocol engine claims accumulated trading fees in SOL.
2. **Buy the Stop**: The fee budget purchases the current stop's token through Jupiter DEX routing.
3. **Snapshot Holders**: Every `$TRAMFOLIO` holder wallet is snapshotted on-chain (bonding curves, liquidity pools, and creator wallets excluded).
4. **Airdrop**: The purchased token is distributed proportionally to all eligible holders.
5. **Continuous Loop**: 14 stops along the line, looping indefinitely with real-time on-chain Solscan transparency.

---

## ⚡ Features

- **Live Tram Line & Track**: Interactive map tracking the electric tram moving stop-by-stop across the 14 tokens.
- **Timetable & Departure Board**: Upcoming departure schedule and verified Solscan distribution ledger.
- **Bag Calculator**: Real-time earnings estimator projecting per-stop, per-lap, and daily airdrop dividends.
- **Solana Wallet Lookup**: Connect Phantom / Solflare to inspect holdings, share percentage, and received airdrop drops.
- **Audit Ledger**: Comprehensive historical audit page (`/ledger`) linking every buy, burn, and airdrop batch.

---

## 🚀 Deployment

### Deploy on Vercel
Pre-configured with `vercel.json` for static SPA routing and API fallbacks:

```bash
vercel deploy
```

### Local Development
```bash
npx serve .
# or
python -m http.server 3000
```

---

## 📄 License
MIT License
