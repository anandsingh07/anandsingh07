<h1 align="center">Hey, I'm Anand Singh 👋</h1>

<p align="center">
  <b>Backend & Web3 Engineer — distributed systems, payments infrastructure, and smart contracts</b>
</p>

<p align="center">
  <a href="mailto:anandsingh887472@gmail.com">📧 Email</a> •
  <a href="https://linkedin.com/in/anand-pratap707">💼 LinkedIn</a> •
  <a href="https://github.com/anandsingh07">🐙 GitHub</a>
</p>

---

## 🧑‍💻 About Me

I build production-grade backend systems and decentralized applications — the kind where correctness under concurrency, idempotency, and failure recovery actually matter.

- 🏗️ Currently at **[P2P.me](https://p2p.me)** — an open-source protocol for instant USDC-to-fiat payments over global rails (UPI, PIX, QRIS)
- ⚙️ I like the hard parts: exactly-once scheduling, out-of-order event correction, semantic caching, gas-efficient contracts
- 🌐 Comfortable across the stack — Solidity/EVM on-chain, Node/TypeScript services in the middle, Next.js/React on top
- 🦀 Currently leveling up in **Rust**

---

## 🚀 Featured Projects

### 🧠 [SemanticCache](https://github.com/anandsingh07/semanticcache)
*"Redis, but for AI responses."* A semantic caching proxy for LLM APIs — exact-match hits via Redis in ~7ms, semantically-similar prompts matched via pgvector ANN search (HNSW, cosine), full cost/token accounting, TTL + per-namespace LRU eviction.
`TypeScript · Redis · PostgreSQL/pgvector · Embeddings`

### ⚡ [ChainPulse — Real-Time Event Streaming & Analytics](https://github.com/anandsingh07/cross-chain-indexer)
Horizontally-scalable pipeline that ingests high-throughput blockchain events, persists them **idempotently**, and automatically compensates for chain reorgs (out-of-order / retracted upstream events) with a rolling sequence ledger. Serves live data over REST, GraphQL & WebSocket with Prometheus observability.
`TypeScript · PostgreSQL · EVM · GraphQL · Prometheus`

### 🐝 [CronHive — Distributed Cron Scheduler](https://github.com/anandsingh07/cronHive)
Fault-tolerant distributed scheduler with **exactly-once firing per slot** (DB-level `UNIQUE(jobId, scheduledFor)` guard proven by concurrency tests), at-least-once HTTP delivery, exponential-backoff retries, dead-letter queues, circuit breakers, and leader election with automatic failover.
`Node 22 · TypeScript · BullMQ · PostgreSQL/Prisma · Redis`

### 🔐 [NexusPAY — Smart Contract Wallet](https://github.com/anandsingh07/NexusPAY)
Smart contract wallet built around account-abstraction patterns (ERC-4337 style flows).
`Solidity · Foundry`

### ✍️ [Ethereum Off-Chain Signature Verification](https://github.com/anandsingh07/ethereum-offchain-signature-verification)
Off-chain ECDSA message signing with on-chain verification — the authorization primitive behind meta-transactions, permits, and account abstraction.
`Solidity · JavaScript · Ethers.js`

### 💸 [P2P Merchant Terminal](https://github.com/anandsingh07/-p2p-merchant-terminal)
Merchant-facing payment terminal for crypto-to-fiat flows. [Live demo →](https://p2p-merchant-terminal.vercel.app)
`TypeScript · Next.js`

<details>
<summary><b>More projects…</b></summary>

- 🏦 [EthVault](https://github.com/anandsingh07/EthVault) — gas-efficient ETH deposit/withdrawal vault with full Hardhat test coverage
- 🤝 [SmartFundIT](https://github.com/anandsingh07/SMARTFUND-IT) — fully decentralized crowdfunding dApp (campaigns, contributions, goal-based withdraw/refund) with zero centralized backend
- 📈 [Staking dApp](https://github.com/anandsingh07/Staking-Dapp) — ETH staking with live balances (React + Solidity + Hardhat)
- 🔗 [URL Shortener](https://github.com/anandsingh07/URL-Shortner) — full-stack TypeScript URL shortener ([live](https://url-shortner-psi-ten.vercel.app))
- 📊 [Crypto Analytics Dashboard](https://github.com/anandsingh07/cryptoAnalytic-Dashboard) — real-time market analytics
- 💬 [Group & Personal Chat App](https://github.com/anandsingh07/Group-Personal--Chatting-App) — real-time messaging ([live](https://group-personal-chatting-app.vercel.app))
- 🦀 [rust-prep](https://github.com/anandsingh07/rust-prep) — my Rust learning journey

</details>

---

## 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Backend & Infra**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Blockchain & Web3**

![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-FF6B35?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=for-the-badge&logo=ethereum&logoColor=black)
![ERC-4337](https://img.shields.io/badge/ERC--4337-8B5CF6?style=for-the-badge&logo=ethereum&logoColor=white)

**Frontend & Deploy**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=anandsingh07&theme=tokyonight" alt="GitHub Stats" height="180"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=anandsingh07&theme=tokyonight" alt="Top Languages" height="180"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=anandsingh07&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=anandsingh07&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" width="95%"/>
</p>

---

## 📫 Reach Me

- 📧 **Email:** [anandsingh887472@gmail.com](mailto:anandsingh887472@gmail.com)
- 💼 **LinkedIn:** [anand-pratap707](https://linkedin.com/in/anand-pratap707)

<p align="center"><i>Building the rails where web2 reliability meets web3 trustlessness.</i></p>
