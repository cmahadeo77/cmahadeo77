# Chris Mahadeo

**Founder · AI Payments & Automation · Mission Commerce**

Building at the intersection of AI, stablecoin payments, and supply chain automation — focused on personal care, natural ingredients, and mission-driven commerce.

---

## What I'm Building

### Payments & Stablecoin Infrastructure
Modernizing B2B payment rails for ingredient sourcing and distribution using programmable stablecoins. Focus on personal care brands sourcing globally — shea cooperatives in Ghana, botanicals from India and Brazil, fragrance houses in France.

- Smart contract escrow replacing letters of credit
- USDC on Stellar for cross-border supplier payments
- Settlement automation tied to logistics delivery oracles

### Visa Direct & Card Payment Networks
Mock server and test harness for Visa Direct OCT (push funds) and AFT (pull from source/wallet) — built for learning the real API schemas, response codes, and 2-leg payment flows without needing Visa sandbox credentials.

- Amount-based scenario triggers for all major response codes (RC 00, 05, 51, 57, 62, 63, 94...)
- Paired AFT→OCT flow simulating the full pull-then-push money movement sequence
- Frontend UI with live JSON request/response viewer and transaction log

### AI-Powered Business Intelligence
n8n-based intelligence systems that monitor payments signals, score market moves, and surface actionable insights before markets open.

- Real-time stablecoin + fintech signal monitoring (CBDC, FedNow, interchange)
- Claude-powered signal classification: Buy / Watch / Noise
- Automated delivery to Slack + Notion

### Automation & Outreach Systems
End-to-end campaign and outreach automation for mission-driven brands — from email prioritization to social publishing.

- Email curation + prioritization workflows
- B2B outreach systems with AI-drafted personalization
- Social media publishing pipelines

---

## Repos

| Repo | Description | Stack |
|---|---|---|
| [stablecoin-b2b-sourcing](https://github.com/cmahadeo77/stablecoin-b2b-sourcing) | USDC escrow payment system for ingredient sourcing | Solidity · USDC · Stellar · Streamlit |
| [visa-direct-mock](https://github.com/cmahadeo77/visa-direct-mock) | Visa Direct OCT + AFT mock server — scenario triggers, 2-leg paired flow, live JSON UI | Node.js · Express |
| [n8n-payments-intelligence](https://github.com/cmahadeo77/n8n-payments-intelligence) | AI-powered payments signal monitor (stablecoin, CBDC, fintech) | n8n · Claude · Notion |
| [n8n-business-intelligence](https://github.com/cmahadeo77/n8n-business-intelligence) | Market intelligence workflow — feeds → Claude → Notion | n8n · Claude · Notion |
| [n8n-workflows](https://github.com/cmahadeo77/n8n-workflows) | Full automation stack: signals, email, social, outreach | n8n · Gmail API · LinkedIn |
| [q2-outreach](https://github.com/cmahadeo77/q2-outreach) | B2B outreach + Gmail automation + daily business intelligence report | Node.js · Gmail API · FedEx API |

---

## Focus Areas

```
Stablecoin Payments    ████████████░░░  Payments infrastructure for B2B sourcing
Supply Chain Finance   ██████████░░░░░  Escrow, trade finance, settlement automation
AI Automation          ████████████████  n8n + Claude for intelligence + workflows
Mission Commerce       █████████░░░░░░  Natural / organic personal care supply chain
```

---

## Stack

`Python` · `Solidity` · `Node.js` · `n8n` · `Streamlit` · `USDC / Stellar` · `Claude API` · `Visa Direct API` · `Circle Payments API` · `Gmail API` · `FedEx Track API` · `Notion API`

---

## Background

Founder of [Arikina](https://www.arikina.com) — a trading and consulting company operating across personal care, natural products, and mission-driven commerce. Previously built distribution networks for brands like Sunshine Naturals.

The automation and payments work here is both product and operational infrastructure — tools I use in the business, built to be open and replicable for other founders navigating similar supply chain and payment challenges.

---

`hello@arikina.com` · [arikina.com](https://www.arikina.com) · [cmahadeo77.github.io](https://cmahadeo77.github.io)
