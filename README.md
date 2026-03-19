# ShelbyStream

> A decentralized video streaming platform built on [Shelby Protocol](https://shelby.xyz) — upload once, stream forever, earn APT every time someone watches.

🔴 **[Live Demo →](https://izmiradami.github.io/Shelbystream-)**

---

## What is ShelbyStream?

ShelbyStream is an open-source decentralized video platform built on top of the Shelby Protocol. Creators upload their videos to the Shelby network, where content is stored as immutable blobs with cryptographic commitments on the Aptos blockchain. Every time a viewer pays to watch, the creator earns APT through Shelby's micropayment channel system.

No platform can delete your content. No algorithm decides who sees it. You own it, permanently.

---

## The Problem

Today's video platforms are broken for creators:

- Content can be removed without warning or explanation
- Bandwidth costs are unpredictable and controlled by a single company
- Creators earn fractions of what their content is worth
- There is no true ownership — your account can be suspended at any time

---

## Why Shelby?

Shelby's infrastructure is purpose-built for exactly this use case:

- **Paid reads** — Every view generates a micropayment directly to the creator
- **Dedicated fiber network** — Fast, consistent streaming without public internet bottlenecks
- **Erasure coding** — Content is redundantly stored across the network, no single point of failure
- **Aptos blockchain** — Cryptographic commitments ensure permanent availability and ownership
- **Novel auditing system** — Storage providers are continuously verified to keep content intact

---

## Features

- 📤 **Video & image upload** — drag and drop, multiple files at once
- 💰 **Micropayment gate** — viewers pay APT per view via Shelby payment channels
- 🦊 **Petra wallet integration** — connect your Aptos wallet in one click
- 📊 **Earnings dashboard** — track total earned, plays, average per view, storage used
- 📋 **Transaction history** — every payment and upload recorded on Aptos
- 🗂️ **Creator profile** — your channel, your videos, your earnings
- ♾️ **Permanent availability** — content lives on the Shelby network forever

---

## Roadmap

### Phase 1 — Core (Current)
- [x] Video & image upload with Shelby SDK simulation
- [x] Blob ID generation and on-chain commitment simulation
- [x] Micropayment modal with Petra wallet connection
- [x] Earnings dashboard and transaction history
- [x] Creator profile page

### Phase 2 — Real Shelby Integration
- [ ] Full Shelby TypeScript SDK integration (pending early access)
- [ ] Real blob storage and retrieval on Shelby testnet
- [ ] Live Aptos micropayment channels
- [ ] Actual video streaming from Shelby fiber network

### Phase 3 — Creator Tools
- [ ] Custom pricing per video
- [ ] Subscription model (monthly APT)
- [ ] Analytics — viewer geography, watch time, revenue over time
- [ ] Video collections and playlists

### Phase 4 — Ecosystem
- [ ] Public discovery feed
- [ ] Creator-to-creator tipping
- [ ] Mobile PWA
- [ ] API for third-party integrations

---

## Tech Stack

| Layer | Technology |
|---|---|
| Storage | Shelby Protocol |
| Blockchain | Aptos |
| SDK | `@shelby-protocol/sdk` |
| Wallet | Petra (Aptos native) |
| Frontend | HTML · CSS · Vanilla JS |
| Smart Contracts | Move |

---

## Getting Started

> ⚠️ Shelby is currently running on testnet. Full SDK integration pending early access approval.

```bash
# Install Shelby SDK (when early access is granted)
npm install @shelby-protocol/sdk

# Install Shelby CLI
npm install -g @shelby-protocol/cli
```

Or just open `index.html` in your browser to try the demo.

---

## Contributing

This project is in early development. Contributions, ideas, and feedback are welcome. Open an issue or submit a pull request.

---

## License

MIT

---

*Built during Shelby Early Access Testnet — powered by Shelby Protocol & Aptos*
