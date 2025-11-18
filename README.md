<p align="center">
  <img src="/assets/defiscape-logo.png" width="170" alt="DEFIscape Logo">
</p>

<h1 align="center">DEFIscape — Recover Assets from Abandoned(Dead) & Life DeFi Protocols</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success.svg">
  <img src="https://img.shields.io/badge/chains-10%2B-blue.svg">
  <img src="https://img.shields.io/badge/license-Custom-lightgrey.svg">
  <img src="https://img.shields.io/badge/built%20with-SvelteKit-ff3e00.svg">
</p>

---

**DEFIscape** is a Web3 recovery platform that helps users reclaim assets stuck inside abandoned or deprecated DeFi protocols.  
When UIs vanish, teams disappear, or hosting is shut down, staking contracts and LP vaults remain on-chain — but become inaccessible.

**DEFIscape restores access to these assets safely and transparently.**

---

## 🚨 Why DEFIscape Exists

Across EVM ecosystems, hundreds of millions of dollars are locked in outdated or abandoned systems:

| Problem | Description |
|--------|-------------|
| 🧱 Staking Contracts | Users cannot call `withdraw()` or `exit()` because the UI is dead |
| 🧪 Deprecated LP Pools | LP tokens remain idle in V1/V2 vaults |
| 👻 Abandoned Farms | Teams vanished, websites offline |
| 🎁 Reward Systems | Unclaimed rewards stuck in reward contracts |
| 🕳 UI-less Protocols | Contracts function, but no interface exists |

Your funds aren’t lost — **they are simply inaccessible without a proper interface**.

---

## 🛠 Core Features

### 🔍 **Multi-Chain Wallet Scanner**
Automatically detects:

- Abandoned staking positions  
- Deprecated LP pools  
- Unclaimed rewards  
- Recoverable contract functions  
- Protocol status (active / risky / abandoned)  

🧠 Powered by **DeBank API** + custom dead-protocol classifier.

---

### 🧰 **Contract Interaction Engine**
Interact directly with DeFi contracts:

- Unstake from abandoned farms  
- Withdraw LP tokens  
- Claim pending rewards  
- Trigger `withdraw()`, `exit()`, `unstake()`, etc.  
- 100% non-custodial & wallet-based interactions  

All transactions are executed **from the user’s wallet only**.

---

## 🖥 Screenshot

<p align="center">
  <img src="/assets/defiscape-ui.gif" width="800" alt="DEFIscape App UI">
</p>

---

## 📡 Protocol Status Directory

Public directory: **https://defiscape.io**

Includes:

- Protocol health (active / risky / abandoned)  
- Metadata & contract links  
- Stuck TVL indicators  
- User reports  
- Integration suggestions  

---

## 🛡 Security

- No private key storage  
- No backend signing  
- No custody of user funds  
- Direct contract interactions  
- Fully client-side architecture  

---

## 🧩 Architecture Overview

/core Smart Contract Interaction Engine
/scanner Multichain Scanner (DeBank + custom logic)
/web SvelteKit Frontend + WalletConnect support
/catalog Protocol Metadata + Directory


Lightweight, decentralized-first, deterministic.

---

## 🌍 Supported EVM Chains

| Chain | Status |
|-------|--------|
| Ethereum | ✅ |
| BNB Chain | ✅ |
| Polygon | ✅ |
| Avalanche | ✅ |
| Fantom | ✅ |
| Arbitrum | ✅ |
| Optimism | ✅ |
| Cronos | ✅ |
| HECO | 🟡 Partial |

---

## 📈 Current Status

- ✔ Live App — https://app.defiscape.io  
- ✔ 25+ integrated protocols  
- ✔ Secure contract call system  
- ✔ Multi-chain scanning  
- ✔ Protocol directory online  
- ✔ Telegram support bot  

DEFIscape is already used to recover real assets from abandoned DeFi protocols.

---

## 🧭 Roadmap

### **Q4 2025**
- Improved protocol metadata  
- Guided recovery UI  
- DeBank-independent detection  

### **Q1 2026**
- Universal Claim Module  
- AI contract analyzer  
- Global stuck TVL analytics  

### **Q2 2026**
- DEFIscape SDK  
- Dead-pool notifications  
- 100+ protocol integrations  

---

## 🤝 Grants & Collaboration

DEFIscape contributes to:

- Capital efficiency  
- User protection  
- Ecosystem transparency  
- Long-term protocol safety  

We welcome collaborations from:

- Foundation Grants  
- L2 Ecosystem Funds  
- Research & Security Programs  
- Tooling Grants  

📧 Contact: **grants@defiscape.io**

---

## 📬 Community

- Website → https://defiscape.io  
- App → https://app.defiscape.io  
- Telegram → https://t.me/DEFIscape  
- Twitter → https://x.com/DEFIscapeApp  
- Youtube → https://youtube.com/@DEFIscape  

---

## 📄 License

Documentation in this repository is open.  
The main application code remains private until the SDK release.

---

## 🙌 Contributions

Create an issue to propose:

- New protocol integrations  
- UX improvements  
- Smart contract suggestions  
- Security recommendations  

Community feedback is welcome.
