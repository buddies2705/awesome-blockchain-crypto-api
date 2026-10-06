# Awesome Blockchain & Crypto APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**The most comprehensive curated list of blockchain & crypto data APIs, RPC providers, indexers, market-data feeds, DEX/NFT/DeFi APIs, oracles, embedded wallets, MEV streams, and developer infrastructure for 2026.**

> **300+ APIs and data services** across multi-chain data, RPC providers, EVM indexers, Solana-native APIs, Bitcoin & Lightning, market & DEX data, NFT, DeFi, MEV, oracles, wallet-as-a-service, embedded wallets, streaming (Kafka/gRPC/WebSocket), historical archives, AI/MCP, and SDKs.

> Awesome PRs Welcome — see [Contributing](#-contributing).

---

## ⭐ Featured: Bitquery — The Universal Blockchain Data API

> **The most complete blockchain data infrastructure for builders — DEX trades, OHLC candles, market cap, wallet PnL, decoded transactions across 8+ chains, in GraphQL, Kafka, gRPC, and MCP.**

[![Bitquery API](https://img.shields.io/badge/API-bitquery.io-blue?style=for-the-badge)](https://bitquery.io/)
[![Chains](https://img.shields.io/badge/Chains-Solana%20%7C%20Ethereum%20%7C%20BSC%20%7C%20Base%20%7C%20Tron%20%7C%20Polygon%20%7C%20Arbitrum%20%7C%20Optimism-green?style=for-the-badge)](https://docs.bitquery.io/)
[![Streams](https://img.shields.io/badge/Streams-GraphQL%20%7C%20Kafka%20%7C%20gRPC%20%7C%20WebSocket%20%7C%20MCP-orange?style=for-the-badge)](https://docs.bitquery.io/)

🔗 **[Bitquery](https://bitquery.io/)** powers the data layer behind hundreds of trading bots, dashboards, AI agents, alpha groups, and analytics platforms in crypto.

| Feature | Details |
| --- | --- |
| **Chains** | Solana, Ethereum, BSC, Base, Arbitrum, Optimism, Polygon, Tron + many more |
| **Coverage** | DEX trades, OHLCV, market cap, FDV, wallet PnL, NFT, transfers, decoded smart-contract events |
| **Pump.fun / LetsBonk / Four.meme / SunPump** | Real-time + historical, bonding-curve aware |
| **Real-time streams** | GraphQL subscriptions, WebSocket, Kafka, gRPC |
| **MCP** | [`mcp.bitquery.io`](https://mcp.bitquery.io/) — plain-English queries from Claude / Cursor / ChatGPT |
| **No-code dashboard** | [DEXrabbit](https://dexrabbit.bitquery.io/) — DexScreener-alternative UI on top of the API |
| **Free tier** | Yes — generous public-good limits, scale up with paid plans |
| **Use cases** | Trading bots, alpha groups, DeFi dashboards, AI agents, exchange listings, tax engines |

🔗 **Quick links:** [Pump.fun API](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/) · [DEXrabbit dashboard](https://dexrabbit.bitquery.io/) · [Bitquery MCP](https://mcp.bitquery.io/) · [GraphQL IDE](https://ide.bitquery.io/) · [Docs](https://docs.bitquery.io/)

---

## 📖 About

**Awesome Blockchain & Crypto APIs** is a deeply curated directory of every API, data service, RPC provider, indexer, oracle, and SDK that crypto builders need in 2026. Whether you're building a trading bot, AI agent, DeFi dashboard, NFT marketplace, wallet, or institutional analytics platform — this list points you at the right data source for every layer.

### What this list covers

- 🌐 **Multi-chain blockchain data APIs** — Bitquery, Alchemy, Moralis, Tatum, Nodit, Covalent
- 🔌 **RPC providers** — Helius, QuickNode, Alchemy, Chainstack, Triton, Shyft, GetBlock, Ankr, dRPC, OnFinality
- 🟣 **Solana-specific APIs** — Helius DAS, Solana Tracker, Birdeye, Bitquery Solana, Triton Geyser
- ⛓️ **EVM-specific APIs** — Etherscan, Blockscout, BaseScan, BscScan
- 🟠 **Bitcoin & Lightning APIs** — Mempool.space, Blockchair, BlockCypher, Voltage, Lightning Loop
- 📊 **Market & price data** — CoinGecko, CoinMarketCap, CryptoCompare, Messari, Kaiko, Amberdata
- 💱 **DEX data APIs** — DexScreener, GeckoTerminal, DexPaprika, DexTools, Defined.fi, DEXrabbit
- 🎨 **NFT data APIs** — OpenSea, Reservoir, NFTGo, Magic Eden, Bitquery NFT
- 🏦 **DeFi-specific data** — DefiLlama, Token Terminal, Dune, Flipside, Pulsar, Onchain Insights
- 🐳 **Smart-money / on-chain intelligence** — Nansen, Arkham, Lookonchain, Cielo, GMGN
- 👛 **Wallet & portfolio APIs** — Zerion, Zapper, DeBank, Octav, CoinStats, Step Finance
- 🌉 **Bridge & cross-chain** — deBridge, LiFi, Squid Router, Socket
- ⚔️ **MEV / mempool** — Flashbots, Eigenphi, BloXroute, Jito, Helius Mempool
- 🔬 **Tx simulation / tracing** — Tenderly, Alchemy Sim, Phalcon, Rivet
- 🌊 **Streaming APIs** — Bitquery Kafka/gRPC, Helius Webhooks, QuickNode Streams, Substreams
- 🗄️ **Historical / archive** — Bitquery, Dune, Flipside, Allium, Goldsky
- 🪙 **Oracles** — Chainlink, Pyth, RedStone, Stork, Switchboard, API3
- 🔐 **Embedded wallets / WaaS** — Privy, Dynamic, Magic, Web3Auth, Turnkey, Coinbase WaaS, Para
- 📈 **Subgraphs / custom indexing** — The Graph, Goldsky, Subsquid, Substreams, Envio, Subgraph Studio
- 🤝 **AI / MCP** for blockchain data (cross-link to [Awesome Crypto MCPs](https://github.com/buddies2705/awesome-crypto-mcp))
- 🛠️ **SDKs & libraries** — web3.js, ethers, viem, wagmi, anchor, solana/web3.js, hyperliquid SDK
- 🌍 **DePIN data networks** — Grass, Hivemapper, IoTeX
- 🆓 **Free public APIs** for hobbyists and indie builders

### Pricing reality (2026)

| Tier | Typical use | Examples |
| --- | --- | --- |
| **Free / Hobbyist** | < 100K req/day | Bitquery free tier, CoinGecko Demo, DexScreener, GeckoTerminal, Helius Free, Alchemy Sandbox |
| **Pro / Indie ($50–$500/mo)** | Indie SaaS, small bots | Helius Pro, QuickNode Build, CoinMarketCap Hobbyist, Birdeye Pro |
| **Business ($500–$5K/mo)** | Production apps | Bitquery Business, Alchemy Growth, Moralis Pro, CoinGecko Pro |
| **Enterprise ($5K+/mo)** | Exchanges, funds | Bitquery Enterprise, Kaiko, Messari Pro, Nansen Pro, TaxBit |

### Choosing the right API

- **Building a trading bot?** Bitquery (real-time + outlier-filtered) or Helius for Solana speed
- **Building a wallet UI?** Zerion / Zapper / DeBank / Bitquery / Moralis NFT API
- **Building an AI agent?** Bitquery MCP + Solana Agent Kit + Hyperliquid MCP
- **Building a tax engine?** Bitquery raw trades + CoinLedger / TaxBit / Awaken APIs
- **Building a DeFi dashboard?** DefiLlama API + Token Terminal + Dune
- **Indie hacker on a budget?** DexScreener API + GeckoTerminal + CoinGecko Demo (all free)

> **Disclaimer:** Pricing, free-tier limits, and feature sets change constantly. Always verify on the provider's pricing page before integrating. Some links in this list are affiliate / referral links (marked 🎟️) — they don't change the price you pay.

---

## 📑 Table of Contents

- [⭐ Featured: Bitquery — The Universal Blockchain Data API](#-featured-bitquery--the-universal-blockchain-data-api)
- [📖 About](#-about)
- [🌐 Multi-Chain Blockchain Data APIs](#-multi-chain-blockchain-data-apis)
- [🔌 RPC Providers](#-rpc-providers)
- [🟣 Solana-Specific Data APIs](#-solana-specific-data-apis)
- [⛓️ EVM-Specific Data APIs](#-evm-specific-data-apis)
- [🟠 Bitcoin & Lightning Data APIs](#-bitcoin--lightning-data-apis)
- [🔍 Block Explorer APIs](#-block-explorer-apis)
- [📊 Crypto Market & Price Data APIs](#-crypto-market--price-data-apis)
- [💱 DEX Data APIs](#-dex-data-apis)
- [🎨 NFT Data APIs](#-nft-data-apis)
- [🏦 DeFi Data APIs](#-defi-data-apis)
- [🐳 Smart Money & On-Chain Intelligence APIs](#-smart-money--on-chain-intelligence-apis)
- [👛 Wallet & Portfolio APIs](#-wallet--portfolio-apis)
- [💵 Stablecoin Data APIs](#-stablecoin-data-apis)
- [🌉 Bridge & Cross-Chain Data APIs](#-bridge--cross-chain-data-apis)
- [⚔️ MEV, Mempool & Block-Builder APIs](#-mev-mempool--block-builder-apis)
- [🔬 Transaction Simulation & Tracing APIs](#-transaction-simulation--tracing-apis)
- [🌊 Streaming APIs (Kafka, gRPC, WebSocket)](#-streaming-apis-kafka-grpc-websocket)
- [🗄️ Historical & Archive Data APIs](#-historical--archive-data-apis)
- [📈 Subgraph & Custom Indexing](#-subgraph--custom-indexing)
- [🪙 Oracle APIs](#-oracle-apis)
- [🔐 Embedded Wallet & Wallet-as-a-Service APIs](#-embedded-wallet--wallet-as-a-service-apis)
- [🔑 Authentication, Identity & Social Login APIs](#-authentication-identity--social-login-apis)
- [🤝 MCPs for Blockchain Data (AI Agents)](#-mcps-for-blockchain-data-ai-agents)
- [🌍 DePIN Data Networks](#-depin-data-networks)
- [🏛️ CEX / Exchange APIs](#-cex--exchange-apis)
- [🛠️ SDKs & Libraries](#-sdks--libraries)
- [🆓 Free Public APIs](#-free-public-apis)
- [📚 Resources & Guides](#-resources--guides)
- [🔗 Related Awesome Lists](#-related-awesome-lists)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🔍 Related Searches](#-related-searches)
- [📈 Popular Use Cases](#-popular-use-cases)

> **Legend** — 🟢 Live · 🟡 Beta / Limited · 🔴 Inactive · ⚡ Top-tier · 🆕 Launched 2025/26 · 🎟️ Affiliate link · 🆓 Free / open-source

---

## 🌐 Multi-Chain Blockchain Data APIs

The "data warehouse" layer — query indexed blockchain data across many chains via GraphQL, REST, or streams.

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ ⭐ **Bitquery** | 8+ chains (Solana, ETH, BSC, Base, Tron, Polygon, Arb, Op + more) | DEX trades, OHLCV, market cap, wallet PnL, bonding-curve aware, GraphQL + Kafka + gRPC + MCP | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| ⚡ **Alchemy** | 30+ chains | Token / NFT / Portfolio APIs, SDK, sandbox tier | 🟢 Live | [alchemy.com](https://www.alchemy.com) |
| ⚡ **Moralis** | EVM + Solana | Wallet, Token, NFT, DeFi APIs, Webhook streams | 🟢 Live | [moralis.io](https://moralis.io) |
| ⚡ **Helius** | Solana | Enhanced APIs, Webhooks, DAS, Mempool | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| ⚡ **QuickNode** | 25+ chains | RPC + add-on marketplace + Streams | 🟢 Live | [quicknode.com](https://www.quicknode.com) |
| **Tatum** | 130+ networks | Unified blockchain API, simple SDK | 🟢 Live | [tatum.io](https://tatum.io) |
| **Nodit Labs** | EVM + Solana | Multi-chain Web3 API | 🟢 Live | [nodit.io](https://nodit.io) |
| **Covalent** | 200+ chains | Unified token + balance + tx API | 🟢 Live | [covalenthq.com](https://www.covalenthq.com) |
| **Mobula** | Multichain | Real-time data + execution layer, no caching | 🟢 Live | [mobula.io](https://mobula.io) |
| **Blockscout APIs** | EVM | Open-source explorer APIs | 🟢 Live | [blockscout.com](https://www.blockscout.com) |
| **Pinax** | Multichain | The Graph-backed substreams | 🟢 Live | [pinax.network](https://pinax.network) |
| **Allium** | Multichain | Enterprise-grade structured blockchain data | 🟢 Live | [allium.so](https://allium.so) |
| **Footprint Analytics** | Multichain | Unified chain data + dashboards | 🟢 Live | [footprint.network](https://www.footprint.network) |

---

## 🔌 RPC Providers

Raw JSON-RPC + Web3-RPC endpoints for sending transactions, querying state, and powering wallets/dApps.

| Provider | Chains | Notable Features | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Alchemy** | 30+ | Sandbox tier, smart contract APIs | 🟢 Live | [alchemy.com](https://www.alchemy.com) |
| ⚡ **QuickNode** | 25+ | Lowest p50 latency in many tests | 🟢 Live | [quicknode.com](https://www.quicknode.com) |
| ⚡ **Helius** | Solana | Premium Solana RPC, DAS, Webhooks | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| ⚡ **Chainstack** | 70+ | Elastic Nodes, geo-load-balanced | 🟢 Live | [chainstack.com](https://chainstack.com) |
| **Triton One** | Solana | Premium Solana, gRPC + Geyser | 🟢 Live | [triton.one](https://triton.one) |
| **Shyft** | Solana | RPC + APIs | 🟢 Live | [shyft.to](https://shyft.to) |
| 🎟️ **GetBlock** | 50+ | Multi-chain RPC | 🟢 Live | [getblock.io](https://account.getblock.io/sign-in?ref=ZjNkNmIxMjItOTVlNC01NDk0LWEwOGEtMDU0MGU3NGZmOGVi) |
| **Ankr** | 50+ | Production RPC, premium tiers | 🟢 Live | [ankr.com](https://www.ankr.com) |
| **dRPC** | 60+ | Decentralized RPC marketplace | 🟢 Live | [drpc.org](https://drpc.org) |
| **OnFinality** | 80+ | Multi-chain RPC + indexing | 🟢 Live | [onfinality.io](https://onfinality.io) |
| **Dwellir** | 60+ | EU-based premium RPC | 🟢 Live | [dwellir.com](https://www.dwellir.com) |
| **Infura (Consensys)** | 20+ | The OG EVM RPC | 🟢 Live | [infura.io](https://infura.io) |
| **LYFTIUM** | Ethereum Mainnet | Plain RPM pricing, `X-Api-Key` header, fail-closed tip (HTTP 503) | 🟢 Live | [lyftium.com](https://www.lyftium.com) |
| **HypeRPC** | Hyperliquid | First dedicated Hyperliquid RPC | 🟢 Live | [hyperpc.app](https://hyperpc.app) |
| **PublicNode** | 30+ | Free public RPC | 🟢 Live | [publicnode.com](https://www.publicnode.com) |
| **NodeReal** | EVM | BSC + opBNB + EVM RPC | 🟢 Live | [nodereal.io](https://nodereal.io) |
| **BlastAPI** | 70+ | Multi-chain RPC | 🟢 Live | [blastapi.io](https://blastapi.io) |
| **Tenderly Web3 Gateway** | EVM | RPC + simulation in one | 🟢 Live | [tenderly.co](https://tenderly.co) |
| **Lava Network** | EVM + Solana | Decentralized RPC marketplace | 🟢 Live | [lavanet.xyz](https://www.lavanet.xyz) |
| **Glif** | Filecoin | Filecoin RPC + APIs | 🟢 Live | [glif.io](https://www.glif.io) |
| **Solana Foundation Public RPC** | Solana | Free, rate-limited | 🟢 Live | [docs.solana.com](https://docs.solana.com) |

---

## 🟣 Solana-Specific Data APIs

For Solana builders — DAS (Digital Asset Standard), SPL tokens, NFTs, DEX trades, MEV, Geyser streams.

| API | Strengths | Status | Website |
| --- | --- | --- | --- |
| ⚡ **Helius** | DAS, Webhooks, Enhanced Tx, Photon, Mempool | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| ⚡ **Bitquery Solana** | Pump.fun, Raydium, Jupiter, full DEX coverage | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Triton One Geyser** | Sub-millisecond Solana streams | 🟢 Live | [triton.one](https://triton.one) |
| **Shyft** | Solana APIs + RPC + Webhooks | 🟢 Live | [shyft.to](https://shyft.to) |
| **Birdeye** | Solana + multi-chain pricing API | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **Solana Tracker** | Solana memecoin data + APIs | 🟢 Live | [solanatracker.io](https://www.solanatracker.io) |
| **Jupiter API** | DEX aggregator, swap routing | 🟢 Live | [jup.ag](https://jup.ag) |
| **Jupiter Price API** | Solana token prices | 🟢 Live | [station.jup.ag](https://station.jup.ag) |
| **Pyth Network (Solana)** | High-frequency oracle prices | 🟢 Live | [pyth.network](https://pyth.network) |
| **Solscan API** | Solana explorer data | 🟢 Live | [solscan.io](https://pro-api.solscan.io) |
| **Solana FM API** | Jupiter Labs explorer API | 🟢 Live | [solana.fm](https://solana.fm) |
| **MadeOnSol API** | Solana KOL trades, deployer reputation | 🟢 Live | [madeonsol.com](https://madeonsol.com/developer) |
| **Dialect** | Solana wallet messaging | 🟢 Live | [dialect.to](https://www.dialect.to) |
| **Photon Memescope** | Pump.fun + Moonshot scan API | 🟢 Live | [photon-sol.tinyastro.io](https://photon-sol.tinyastro.io) |

---

## ⛓️ EVM-Specific Data APIs

For Ethereum, Base, Arbitrum, Optimism, Polygon, BSC, Avalanche, and other EVM chains.

| API | Strengths | Status | Website |
| --- | --- | --- | --- |
| **Alchemy Enhanced APIs** | Token / NFT / Trace / Sim | 🟢 Live | [alchemy.com](https://www.alchemy.com) |
| **Etherscan API** | Full EVM tx history, contract verification | 🟢 Live | [etherscan.io](https://docs.etherscan.io) |
| **BscScan API** | BSC block explorer API | 🟢 Live | [bscscan.com](https://bscscan.com/apis) |
| **BaseScan API** | Base block explorer API | 🟢 Live | [basescan.org](https://basescan.org) |
| **Blockscout API** | Open-source EVM explorer API | 🟢 Live | [blockscout.com](https://www.blockscout.com) |
| **Bitquery EVM** | DEX trades + decoded events | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Moralis EVM** | Wallet, Token, NFT, DeFi APIs | 🟢 Live | [moralis.io](https://moralis.io) |
| **Covalent EVM** | Unified balances + tx history | 🟢 Live | [covalenthq.com](https://www.covalenthq.com) |
| **The Graph (EVM)** | Subgraphs for any EVM chain | 🟢 Live | [thegraph.com](https://thegraph.com) |
| **Goldsky** | EVM real-time indexing | 🟢 Live | [goldsky.com](https://goldsky.com) |
| **Subsquid** | EVM indexer | 🟢 Live | [subsquid.io](https://www.subsquid.io) |
| **Envio** | High-performance EVM indexer | 🟢 Live | [envio.dev](https://envio.dev) |
| **DefiLlama API** | TVL + DeFi data per chain | 🟢 Live | [defillama.com/docs/api](https://defillama.com/docs/api) |

---

## 🟠 Bitcoin & Lightning Data APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| **Mempool.space** | Bitcoin | Public API for fees, mempool, blocks | 🟢 Live | [mempool.space](https://mempool.space) |
| **Blockchain.com API** | Bitcoin | Classic Bitcoin block + tx API | 🟢 Live | [blockchain.com](https://www.blockchain.com/api) |
| **BlockCypher** | Bitcoin + EVM | Multi-chain unified API | 🟢 Live | [blockcypher.com](https://www.blockcypher.com) |
| **Blockchair** | Bitcoin + 17 chains | Bitcoin-first multi-chain API | 🟢 Live | [blockchair.com](https://blockchair.com) |
| **mempool.space API** | Bitcoin | Real-time fee + mempool API | 🟢 Live | [mempool.space/docs](https://mempool.space/docs/api) |
| **Voltage** | Lightning | Lightning-as-a-service | 🟢 Live | [voltage.cloud](https://voltage.cloud) |
| **LNbits** | Lightning | Self-hosted Lightning wallet API | 🟢 Live | [lnbits.com](https://lnbits.com) |
| **Lightning Loop API** | Lightning | Submarine-swap + LSP API | 🟢 Live | [lightning.engineering](https://lightning.engineering) |
| **OpenNode** | Lightning | Bitcoin + Lightning payments API | 🟢 Live | [opennode.com](https://www.opennode.com) |
| **Bitkern API** | Bitcoin | Bitcoin tx data | 🟢 Live | [bitkern.com](https://bitkern.com) |
| **Bitcoin Core RPC** | Bitcoin | Run-your-own RPC | 🟢 Live | [bitcoincore.org](https://bitcoincore.org) |

---

## 🔍 Block Explorer APIs

| Explorer | Chain | Notable | Status | Website |
| --- | --- | --- | --- | --- |
| **Etherscan API** | Ethereum | The standard EVM explorer API | 🟢 Live | [etherscan.io](https://docs.etherscan.io) |
| **Solscan API** | Solana | Solana standard explorer API | 🟢 Live | [solscan.io](https://pro-api.solscan.io) |
| **Solana FM API** | Solana | Jupiter Labs explorer | 🟢 Live | [solana.fm](https://solana.fm) |
| **BscScan API** | BNB Chain | BSC explorer API | 🟢 Live | [bscscan.com](https://bscscan.com/apis) |
| **BaseScan API** | Base | Base explorer API | 🟢 Live | [basescan.org](https://basescan.org) |
| **PolygonScan API** | Polygon | Polygon explorer API | 🟢 Live | [polygonscan.com](https://polygonscan.com) |
| **Arbiscan API** | Arbitrum | Arbitrum explorer API | 🟢 Live | [arbiscan.io](https://arbiscan.io) |
| **Optimism Etherscan API** | Optimism | OP explorer API | 🟢 Live | [optimistic.etherscan.io](https://optimistic.etherscan.io) |
| **Tronscan API** | Tron | Tron explorer API | 🟢 Live | [tronscan.org](https://apilist.tronscanapi.com) |
| **Blockscout API** | Multi-EVM | Open-source explorer API | 🟢 Live | [blockscout.com](https://www.blockscout.com) |
| **HyperEVMScan** | Hyperliquid | HL explorer (Etherscan team) | 🟢 Live | [hyperevmscan.io](https://hyperevmscan.io) |
| **Arkham Explorer** | Multi | Entity-mapped block explorer | 🟢 Live | [arkm.com](https://arkm.com/register?ref=03c4c435-9a97-4553-850d-c91faf29c7b8) |

---

## 📊 Crypto Market & Price Data APIs

| API | Strengths | Free Tier | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **CoinGecko API** | 14K+ coins, 2.5M+ pairs, free demo, hobbyist-friendly | ✅ Demo | 🟢 Live | [coingecko.com/api](https://www.coingecko.com/en/api) |
| ⚡ **CoinMarketCap API** | The original, broad market intelligence + DEX API | ✅ Basic | 🟢 Live | [coinmarketcap.com/api](https://coinmarketcap.com/api/) |
| **CryptoCompare** | OHLC, news, social data | ✅ | 🟢 Live | [cryptocompare.com](https://www.cryptocompare.com/api) |
| **Messari API** | Institutional research + protocol metrics | Limited | 🟢 Live | [messari.io/api](https://messari.io/api) |
| **Kaiko** | Institutional, regulated-grade data | Paid | 🟢 Live | [kaiko.com](https://www.kaiko.com) |
| **Amberdata** | Institutional crypto data + DeFi | Paid | 🟢 Live | [amberdata.io](https://www.amberdata.io) |
| **CoinAPI** | Unified crypto market data API | ✅ Trial | 🟢 Live | [coinapi.io](https://www.coinapi.io) |
| **CoinPaprika API** | Free coin metrics + market data | ✅ Free | 🟢 Live | [coinpaprika.com](https://api.coinpaprika.com) |
| **CoinLore API** | Free crypto data + tickers | ✅ Free | 🟢 Live | [coinlore.com](https://www.coinlore.com/cryptocurrency-data-api) |
| **Bitquery Price API** | Outlier-filtered DEX prices, OHLCV | ✅ Free | 🟢 Live | [bitquery.io](https://docs.bitquery.io/docs/trading/crypto-price-api/introduction/) |
| **Birdeye API** | Solana + multi-chain pricing API | ✅ | 🟢 Live | [docs.birdeye.so](https://docs.birdeye.so) |
| **Defined.fi API** | Real-time pair data API | Paid | 🟢 Live | [defined.fi/api](https://www.defined.fi/api) |
| **Pyth Benchmark** | Pyth oracle benchmark prices | ✅ Free | 🟢 Live | [pyth.network](https://pyth.network) |
| **Glassnode API** | Bitcoin + Ethereum on-chain metrics | Paid | 🟢 Live | [glassnode.com](https://glassnode.com) |
| **IntoTheBlock** | Institutional on-chain analytics API | Paid | 🟢 Live | [intotheblock.com](https://www.intotheblock.com) |
| **Santiment** | On-chain + social + dev metrics | ✅ + Paid | 🟢 Live | [santiment.net](https://santiment.net) |
| **LunarCrush** | Social sentiment + Galaxy Score | ✅ + Paid | 🟢 Live | [lunarcrush.com](https://lunarcrush.com) |
| **CryptoAPIs** | Unified market API | ✅ Trial | 🟢 Live | [cryptoapis.io](https://cryptoapis.io) |

---

## 💱 DEX Data APIs

For real-time DEX trades, pairs, liquidity, and OHLCV.

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Bitquery DEX** | 8+ chains | Outlier-filtered, decoded, GraphQL/Kafka | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| ⚡ **DexScreener API** | Multichain | The default DEX data API, free | 🟢 Live | [docs.dexscreener.com](https://docs.dexscreener.com) |
| ⚡ **GeckoTerminal API** | Multichain | CoinGecko's free DEX API | 🟢 Live | [geckoterminal.com](https://www.geckoterminal.com/api) |
| **DexPaprika** | 20+ chains | Real-time DEX data, 5M+ tokens | 🟢 Live | [dexpaprika.com](https://docs.dexpaprika.com) |
| **DexTools API** | Multichain | DEX discovery + audits | 🟢 Live | [dextools.io](https://dextools.io) |
| **Defined.fi API** | Multichain | Pro-grade pair data API | 🟢 Live | [defined.fi/api](https://www.defined.fi/api) |
| **DEXrabbit** | 8+ chains | Bitquery-powered, no-code dashboard + API | 🟢 Live | [dexrabbit.bitquery.io](https://dexrabbit.bitquery.io/) |
| **0x API** | EVM | Aggregator + swap quotes | 🟢 Live | [0x.org](https://0x.org/docs/api) |
| **1inch API** | EVM | Aggregator + Pathfinder | 🟢 Live | [1inch.io/docs](https://1inch.io/api/) |
| **Uniswap Subgraph** | Uniswap | Official Uniswap subgraph data | 🟢 Live | [uniswap.org/docs](https://docs.uniswap.org/api/subgraph/overview) |
| **Jupiter API** | Solana | DEX aggregator API | 🟢 Live | [jup.ag](https://jup.ag) |
| **CowSwap API** | EVM | MEV-protected swaps | 🟢 Live | [cow.fi](https://cow.fi) |
| **DappLooker HL Perp API** | Hyperliquid | Hyperliquid perp data + indicators | 🟢 Live | [dapplooker.com](https://docs.dapplooker.com) |

---

## 🎨 NFT Data APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| **OpenSea API** | Multichain | The standard NFT marketplace API | 🟢 Live | [opensea.io](https://docs.opensea.io) |
| **Reservoir API** | EVM | Cross-marketplace NFT API | 🟢 Live | [reservoir.tools](https://reservoir.tools) |
| **NFTGo** | Multichain | NFT analytics + market data | 🟢 Live | [nftgo.io](https://nftgo.io) |
| **Magic Eden API** | 17 chains | Cross-chain NFT marketplace API | 🟢 Live | [docs.magiceden.io](https://docs.magiceden.io) |
| **Helius DAS** | Solana | Digital Asset Standard for Solana NFTs | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| **Bitquery NFT** | Multichain | Decoded NFT trades + transfers | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Alchemy NFT API** | Multichain | Token + metadata + ownership | 🟢 Live | [alchemy.com](https://www.alchemy.com/nft-api) |
| **Moralis NFT API** | Multichain | NFT metadata + collections | 🟢 Live | [moralis.io/nft-api](https://moralis.io) |
| **SimpleHash** | Multichain | Unified NFT API | 🟢 Live | [simplehash.com](https://simplehash.com) |
| **Tensor API** | Solana | Solana NFT marketplace API | 🟢 Live | [tensor.trade](https://tensor.trade) |
| **CryptoPunks API** | Ethereum | CryptoPunks-specific data | 🟢 Live | [cryptopunks.app](https://cryptopunks.app) |
| **DappRadar NFT API** | Multichain | NFT collection rankings | 🟢 Live | [dappradar.com](https://dappradar.com) |
| **NFTPort** | Multichain | NFT minting + data API | 🟢 Live | [nftport.xyz](https://www.nftport.xyz) |
| **Center API** | Multichain | NFT discovery + metadata | 🟢 Live | [center.dev](https://center.dev) |
| **Rarify** | Multichain | NFT pricing + valuation | 🟢 Live | [rarify.tech](https://rarify.tech) |

---

## 🏦 DeFi Data APIs

For TVL, protocol-level metrics, lending markets, perps, vaults, yields.

| API | Coverage | Strengths | Free Tier | Status | Website |
| --- | --- | --- | --- | --- | --- |
| ⚡ **DefiLlama API** | All major DeFi | The standard for TVL + DEX volumes + perps + stablecoins | ✅ Free | 🟢 Live | [defillama.com/docs/api](https://defillama.com/docs/api) |
| **Token Terminal** | DeFi protocols | Revenue + earnings + cohort metrics | Paid | 🟢 Live | [tokenterminal.com](https://tokenterminal.com) |
| **Dune Analytics API** | Multichain | SQL-on-blockchain, custom dashboards | ✅ Free + Paid | 🟢 Live | [dune.com](https://dune.com) |
| **Flipside Crypto** | Multichain | Curated SQL on Solana, EVM, Cosmos | ✅ Free | 🟢 Live | [flipsidecrypto.xyz](https://flipsidecrypto.xyz) |
| **Allium** | Multichain | Enterprise structured DeFi data | Paid | 🟢 Live | [allium.so](https://allium.so) |
| **Footprint Analytics** | Multichain | Unified DeFi data + dashboards | ✅ Free | 🟢 Live | [footprint.network](https://www.footprint.network) |
| **DappRadar API** | Multichain | dApp rankings + DeFi metrics | Paid | 🟢 Live | [dappradar.com/api](https://dappradar.com) |
| **Pulsar API** | Multichain | Wallet behaviour + DeFi flows | Paid | 🟢 Live | [pulsar.fi](https://pulsar.fi) |
| **Aave Subgraph** | Aave | Aave protocol data | ✅ Free | 🟢 Live | [aave.com](https://aave.com) |
| **Lido API** | Lido | Liquid staking metrics | ✅ Free | 🟢 Live | [lido.fi](https://lido.fi) |
| **Pendle API** | Pendle | Yield trading data | ✅ | 🟢 Live | [pendle.finance](https://www.pendle.finance) |
| **EigenLayer API** | EigenLayer | Restaking metrics | ✅ | 🟢 Live | [eigenlayer.xyz](https://www.eigenlayer.xyz) |
| **Yearn API** | Yearn | Vault data | ✅ Free | 🟢 Live | [yearn.fi](https://yearn.fi) |
| **Curve API** | Curve | Curve pools + gauges | ✅ | 🟢 Live | [curve.fi](https://curve.fi) |

---

## 🐳 Smart Money & On-Chain Intelligence APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Nansen API** | Multichain | 500M+ labeled wallets, smart-money flows | 🟢 Live | [nansen.ai](https://nansen.ai) |
| ⚡ **Arkham API** | Multichain | Entity de-anonymisation, KOL tags | 🟢 Live | [arkm.com](https://arkm.com/register?ref=03c4c435-9a97-4553-850d-c91faf29c7b8) |
| **Cielo API** | 30+ chains | Cross-chain wallet tracking | 🟢 Live | [cielo.finance](https://cielo.finance) |
| **GMGN API** | Multichain | Smart-money + KOL feeds (memecoin focus) | 🟢 Live | [gmgn.ai](https://gmgn.ai) |
| **Lookonchain** | Multichain | Real-time whale tracking | 🟢 Live | [lookonchain.com](https://lookonchain.com) |
| **Bubblemaps API** | Multichain | Holder cluster visualisation | 🟢 Live | [bubblemaps.io](https://bubblemaps.io) |
| **MadeOnSol API** | Solana | KOL trades + deployer reputation | 🟢 Live | [madeonsol.com/developer](https://madeonsol.com/developer) |
| **Hyperbot API** | Hyperliquid + Aster | Whale + copy-trading API | 🟢 Live | [hyperbot.network](https://hyperbot.network) |
| **HyperStats API** | Hyperliquid | Wallet PnL + leaderboards | 🟢 Live | [hyperstats.org](https://hyperstats.org) |
| **Glassnode** | BTC + ETH | Institutional on-chain metrics | 🟢 Live | [glassnode.com](https://glassnode.com) |
| **IntoTheBlock** | Multichain | Token holder + flow analytics | 🟢 Live | [intotheblock.com](https://www.intotheblock.com) |
| **Santiment** | Multichain | On-chain + dev + social | 🟢 Live | [santiment.net](https://santiment.net) |
| **Bitquery Wallet PnL** | 8 chains | Wallet-level PnL via GraphQL | 🟢 Live | [bitquery.io](https://bitquery.io/) |

---

## 👛 Wallet & Portfolio APIs

For wallet UIs, portfolio dashboards, and balance/PnL aggregation.

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| **Zerion API** | EVM | Wallet portfolio + DeFi positions | 🟢 Live | [zerion.io](https://developers.zerion.io) |
| **Zapper API** | EVM | DeFi portfolio + tx history | 🟢 Live | [zapper.xyz](https://docs.zapper.xyz) |
| **DeBank Open API** | EVM + Hyperliquid | Wallet activity + DeFi tracking | 🟢 Live | [open.debank.com](https://open.debank.com) |
| **Octav API** | 20+ chains | Multi-chain portfolio tracking | 🟢 Live | [octav.fi](https://octav.fi) |
| 🎟️ **CoinStats API** | Multi | Mobile portfolio + alerts | 🟢 Live | [coinstats.app](https://coinstats.app/r/coincodecap/) |
| **Step Finance API** | Solana | Solana portfolio dashboard | 🟢 Live | [step.finance](https://step.finance) |
| **Birdeye Wallet API** | Solana + Multi | Wallet PnL + holdings | 🟢 Live | [birdeye.so](https://birdeye.so) |
| **HyperFolio API** | HyperEVM + Hyperliquid | HL wallet + positions | 🟢 Live | [hyperfolio.xyz](https://hyperfolio.xyz) |
| **Helius Wallet API** | Solana | Solana wallet + DAS | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| **Bitquery Portfolio** | 8 chains | Wallet + multi-chain holdings | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Rabby OpenAPI** | EVM | Used by Rabby Wallet | 🟢 Live | [openapi.rabby.io](https://openapi.rabby.io) |
| **Bigmoon Portfolio** | Multichain | Cross-chain holdings | 🟢 Live | [bigmoon.io](https://bigmoon.io) |

---

## 💵 Stablecoin Data APIs

| API | Strengths | Status | Website |
| --- | --- | --- | --- |
| **DefiLlama Stablecoins** | TVL + supply + chain breakdown | 🟢 Live | [defillama.com/stablecoins](https://defillama.com/stablecoins) |
| **Allium Stablecoin API** | Enterprise stablecoin metrics | 🟢 Live | [allium.so](https://allium.so) |
| **Visa Onchain Stablecoin** | Visa-curated stablecoin volume | 🟢 Live | [visaonchainanalytics.com](https://visaonchainanalytics.com) |
| **Bitquery Stablecoin** | Stablecoin transfers + flows | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Tether Transparency API** | USDT supply + reserves | 🟢 Live | [tether.to/transparency](https://tether.to/en/transparency) |
| **Circle USDC Data** | USDC supply, mint/burn | 🟢 Live | [circle.com](https://www.circle.com) |
| **MakerDAO API** | DAI supply + stability fees | 🟢 Live | [makerdao.com](https://makerdao.com) |
| **Frax API** | Frax stablecoin metrics | 🟢 Live | [frax.finance](https://frax.finance) |

---

## 🌉 Bridge & Cross-Chain Data APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| **deBridge API** | 30+ chains | Cross-chain swap routing + fees | 🟢 Live | [debridge.finance](https://debridge.finance) |
| **LiFi API** | Multichain | Bridge aggregator + routing | 🟢 Live | [li.fi](https://li.fi) |
| **Squid Router API** | Multichain | Axelar-based cross-chain | 🟢 Live | [squidrouter.com](https://www.squidrouter.com) |
| **Socket API (formerly Bungee)** | Multichain | Bridge aggregator API | 🟢 Live | [socket.tech](https://socket.tech) |
| **Stargate API** | LayerZero chains | Stablecoin bridge | 🟢 Live | [stargate.finance](https://stargate.finance) |
| **Wormhole API** | 30+ chains | Cross-chain messaging | 🟢 Live | [wormhole.com](https://wormhole.com) |
| **Across API** | EVM | Across bridge metrics | 🟢 Live | [across.to](https://across.to) |
| **Synapse API** | Multichain | Bridge data | 🟢 Live | [synapseprotocol.com](https://synapseprotocol.com) |
| **Orbiter Finance API** | EVM L2s | L2-to-L2 bridge | 🟢 Live | [orbiter.finance](https://orbiter.finance) |
| **DefiLlama Bridges** | All bridges | TVL + volume per bridge | 🟢 Live | [defillama.com/bridges](https://defillama.com/bridges) |

---

## ⚔️ MEV, Mempool & Block-Builder APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| **Flashbots Relay API** | Ethereum | MEV-Boost relay data | 🟢 Live | [flashbots.net](https://flashbots.net) |
| **Eigenphi** | Multichain | MEV / sandwich analytics API | 🟢 Live | [eigenphi.io](https://eigenphi.io) |
| **BloXroute** | Multichain | High-performance mempool + MEV | 🟢 Live | [bloxroute.com](https://bloxroute.com) |
| **MEV-Inspect** | EVM | Open-source MEV indexer (Flashbots) | 🟢 Live | [GitHub](https://github.com/flashbots/mev-inspect-py) |
| **Jito Labs API** | Solana | Solana MEV + bundle relays | 🟢 Live | [jito.network](https://www.jito.network) |
| **Helius Mempool** | Solana | Solana pre-confirmation mempool | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| **Helius Photon** | Solana | Real-time tx subscription | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| **Manifold Finance** | Multichain | MEV-protected RPC | 🟢 Live | [manifoldfinance.com](https://www.manifoldfinance.com) |
| **mev.fyi** | Multichain | MEV research database | 🟢 Live | [mev.fyi](https://mev.fyi) |
| **Sandwich.dev** | EVM | Sandwich attack detection | 🟢 Live | [sandwich.dev](https://sandwich.dev) |

---

## 🔬 Transaction Simulation & Tracing APIs

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Tenderly** | EVM | Tx simulation + debugger + alerts | 🟢 Live | [tenderly.co](https://tenderly.co) |
| **Alchemy Simulation API** | EVM | Pre-confirm tx simulation | 🟢 Live | [alchemy.com](https://www.alchemy.com) |
| **Phalcon (BlockSec)** | EVM | Tx tracing + threat detection | 🟢 Live | [phalcon.blocksec.com](https://phalcon.blocksec.com) |
| **Rivet** | EVM | Open-source tx debugging | 🟢 Live | [rivet.sh](https://rivet.sh) |
| **Foundry / Anvil** | EVM | Local fork + simulation (open-source) | 🟢 Live | [getfoundry.sh](https://book.getfoundry.sh) |
| **Helius Tx Sim** | Solana | Solana tx pre-flight simulation | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| **Fork.so** | EVM | Fork-based simulation | 🟢 Live | [fork.so](https://fork.so) |
| **Ethereum Tracer** | Ethereum | trace_call, trace_block via Geth | 🟢 Live | [Ethereum Docs](https://geth.ethereum.org) |

---

## 🌊 Streaming APIs (Kafka, gRPC, WebSocket)

For low-latency, real-time blockchain data feeds — essential for trading bots, monitoring, and high-frequency analytics.

| Provider | Streams | Coverage | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Bitquery Kafka + gRPC** | Trades, transfers, OHLC, blocks | 8+ chains | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| ⚡ **Helius Webhooks + Photon** | Solana | Solana | 🟢 Live | [helius.dev](https://www.helius.dev/) |
| ⚡ **QuickNode Streams** | Block, log, trace | 25+ chains | 🟢 Live | [quicknode.com](https://www.quicknode.com) |
| **Triton Geyser** | Solana | Sub-ms Solana streams | 🟢 Live | [triton.one](https://triton.one) |
| **Substreams (StreamingFast)** | Subgraph-style streams | EVM + Solana + Cosmos | 🟢 Live | [substreams.streamingfast.io](https://substreams.streamingfast.io) |
| **Goldsky Streams** | EVM | EVM real-time indexing | 🟢 Live | [goldsky.com](https://goldsky.com) |
| **Alchemy Notify** | EVM | Webhook notifications | 🟢 Live | [alchemy.com/notify](https://www.alchemy.com/notify) |
| **Moralis Streams** | EVM + Solana | Webhook + WebSocket | 🟢 Live | [moralis.io/streams](https://moralis.io) |
| **Web3.py / Web3.js Subscriptions** | EVM | WebSocket subscriptions | 🟢 Live | [web3py.readthedocs.io](https://web3py.readthedocs.io) |
| **BloXroute BDN** | Multichain | High-perf mempool stream | 🟢 Live | [bloxroute.com](https://bloxroute.com) |
| **Drift Grafana / WebSocket** | Solana (Drift) | Real-time perp metrics | 🟢 Live | [drift.trade](https://drift.trade) |
| **Hyperliquid WebSocket** | Hyperliquid | Order book + trade stream | 🟢 Live | [hyperliquid.gitbook.io](https://hyperliquid.gitbook.io) |
| **Pyth WebSocket** | Multichain | High-frequency oracle prices | 🟢 Live | [pyth.network](https://pyth.network) |

---

## 🗄️ Historical & Archive Data APIs

For backtesting, research, audit, and long-tail analytics.

| API | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Bitquery Historical** | Multi-year, 8+ chains | DEX trades + events going back years | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| ⚡ **Dune Analytics** | Multichain | SQL on Spellbook tables | 🟢 Live | [dune.com](https://dune.com) |
| ⚡ **Flipside Crypto** | Multichain | Curated SQL tables | 🟢 Live | [flipsidecrypto.xyz](https://flipsidecrypto.xyz) |
| **Allium** | Multichain | Enterprise structured archive | 🟢 Live | [allium.so](https://allium.so) |
| **Goldsky Mirror** | EVM | Postgres-style historical indexing | 🟢 Live | [goldsky.com/mirror](https://goldsky.com) |
| **Google BigQuery (Crypto Public Datasets)** | BTC + ETH + Solana | Free public datasets | 🟢 Live | [Google Cloud](https://console.cloud.google.com/marketplace/browse?filter=category:web3) |
| **AWS Public Blockchain Data** | EVM + Solana | AWS-hosted public datasets | 🟢 Live | [aws.amazon.com](https://aws.amazon.com/blockchain) |
| **Chainalysis Reactor API** | Multichain | Compliance + investigation | 🟢 Live | [chainalysis.com](https://www.chainalysis.com) |
| **TRM Labs API** | Multichain | Compliance + risk data | 🟢 Live | [trmlabs.com](https://www.trmlabs.com) |
| **Footprint Analytics** | Multichain | Historical chain data | 🟢 Live | [footprint.network](https://www.footprint.network) |
| **CoinAPI Historical** | Markets | Historical OHLCV across exchanges | 🟢 Live | [coinapi.io](https://www.coinapi.io) |

---

## 📈 Subgraph & Custom Indexing

For builders who need their own indexed data (custom subgraphs, processors, ETL).

| Tool | Strengths | Status | Website |
| --- | --- | --- | --- |
| ⚡ **The Graph** | Decentralised subgraph network | 🟢 Live | [thegraph.com](https://thegraph.com) |
| ⚡ **Goldsky** | Real-time EVM indexing + Mirror | 🟢 Live | [goldsky.com](https://goldsky.com) |
| ⚡ **Substreams (StreamingFast)** | Stream-based indexing | 🟢 Live | [substreams.streamingfast.io](https://substreams.streamingfast.io) |
| **Subsquid** | Open-source indexer | 🟢 Live | [subsquid.io](https://www.subsquid.io) |
| **Envio** | High-performance HyperIndex | 🟢 Live | [envio.dev](https://envio.dev) |
| **Subgraph Studio** | The Graph hosted IDE | 🟢 Live | [thegraph.com/studio](https://thegraph.com/studio) |
| **Ponder** | Open-source EVM indexing framework | 🟢 Live | [ponder.sh](https://ponder.sh) |
| **Indexer 2.0 (Pinax)** | The Graph-backed substreams | 🟢 Live | [pinax.network](https://pinax.network) |
| **Hyperindex** | Envio's indexing engine | 🟢 Live | [envio.dev](https://envio.dev) |
| **Anchor IDL Indexer** | Solana | Anchor-based Solana indexer | 🟢 Live | [GitHub](https://github.com/coral-xyz/anchor) |
| **DipDup** | Tezos + EVM | Multi-chain framework | 🟢 Live | [dipdup.io](https://dipdup.io) |
| **Sentio** | EVM + Solana | Indexer + analytics framework | 🟢 Live | [sentio.xyz](https://www.sentio.xyz) |

---

## 🪙 Oracle APIs

| Oracle | Coverage | Strengths | Status | Website |
| --- | --- | --- | --- | --- |
| ⚡ **Chainlink Data Streams** | Multichain | High-frequency push oracle | 🟢 Live | [chain.link/data-streams](https://chain.link/data-streams) |
| ⚡ **Pyth Network** | Multichain | Sub-second prices, 1900+ feeds | 🟢 Live | [pyth.network](https://pyth.network) |
| **Stork Oracle** | Multichain | Sub-millisecond oracle | 🟢 Live | [stork.network](https://stork.network) |
| **RedStone** | Multichain | Modular oracle, on-demand | 🟢 Live | [redstone.finance](https://redstone.finance) |
| **API3** | Multichain | First-party oracles | 🟢 Live | [api3.org](https://api3.org) |
| **Switchboard** | Solana + EVM | Permissionless oracle | 🟢 Live | [switchboard.xyz](https://switchboard.xyz) |
| **Band Protocol** | Multichain | Multi-chain oracle | 🟢 Live | [bandprotocol.com](https://www.bandprotocol.com) |
| **DIA** | Multichain | Open-source data feeds | 🟢 Live | [diadata.org](https://www.diadata.org) |
| **UMA Oracle** | Multichain | Optimistic oracle | 🟢 Live | [uma.xyz](https://uma.xyz) |
| **Tellor** | Multichain | Decentralised reporter | 🟢 Live | [tellor.io](https://tellor.io) |
| **eOracle** | Multichain | EigenLayer-secured oracle | 🟢 Live | [eoracle.io](https://www.eoracle.io) |

---

## 🔐 Embedded Wallet & Wallet-as-a-Service APIs

For building wallets into your app — passkeys, social logins, MPC, account abstraction.

| Provider | Strengths | Status | Website |
| --- | --- | --- | --- |
| ⚡ **Privy** | Email + social + passkey + MPC, full wallet lifecycle | 🟢 Live | [privy.io](https://www.privy.io) |
| ⚡ **Dynamic** | Multi-wallet, social login, account abstraction | 🟢 Live | [dynamic.xyz](https://www.dynamic.xyz) |
| ⚡ **Magic** | Email-based magic-link wallets | 🟢 Live | [magic.link](https://magic.link) |
| ⚡ **Web3Auth (Tor.us)** | Social login + MPC | 🟢 Live | [web3auth.io](https://web3auth.io) |
| ⚡ **Turnkey** | Programmable wallet infrastructure (used by Padre, GRVT) | 🟢 Live | [turnkey.com](https://www.turnkey.com) |
| **Coinbase WaaS** | Coinbase MPC + EVM | 🟢 Live | [docs.cdp.coinbase.com](https://docs.cdp.coinbase.com) |
| **Para (formerly Capsule)** | Programmable embedded wallets | 🟢 Live | [getpara.com](https://www.getpara.com) |
| **OpenZeppelin Defender** | Secure relays + automation | 🟢 Live | [defender.openzeppelin.com](https://defender.openzeppelin.com) |
| **Fireblocks** | Institutional MPC custody + ops | 🟢 Live | [fireblocks.com](https://www.fireblocks.com) |
| **Copper** | Institutional custody + settlement | 🟢 Live | [copper.co](https://copper.co) |
| **Anchorage** | Federally chartered crypto bank | 🟢 Live | [anchorage.com](https://www.anchorage.com) |
| **Lit Protocol** | Decentralized key management | 🟢 Live | [litprotocol.com](https://litprotocol.com) |
| **ZenGo SDK** | MPC mobile-first wallet | 🟢 Live | [zengo.com](https://zengo.com) |
| **Particle Network** | Smart wallet + intent layer | 🟢 Live | [particle.network](https://particle.network) |
| **Crossmint** | Embedded wallets + onramps + minting | 🟢 Live | [crossmint.com](https://www.crossmint.com) |
| **Pimlico** | Account-abstraction infra (bundler/paymaster) | 🟢 Live | [pimlico.io](https://www.pimlico.io) |
| **Biconomy** | Account abstraction stack | 🟢 Live | [biconomy.io](https://www.biconomy.io) |
| **Stackup** | ERC-4337 bundler + paymaster | 🟢 Live | [stackup.sh](https://www.stackup.sh) |
| **ZeroDev** | Smart accounts + AA infra | 🟢 Live | [zerodev.app](https://zerodev.app) |
| **Safe (formerly Gnosis Safe)** | Multi-sig wallet infra | 🟢 Live | [safe.global](https://safe.global) |

---

## 🔑 Authentication, Identity & Social Login APIs

| Provider | Strengths | Status | Website |
| --- | --- | --- | --- |
| **SIWE (Sign-In with Ethereum)** | The standard EIP-4361 flow | 🟢 Live | [login.xyz](https://login.xyz) |
| **Sign-In with Solana** | Solana equivalent | 🟢 Live | [Solana docs](https://docs.solana.com) |
| **WalletConnect** | Wallet → dApp protocol | 🟢 Live | [walletconnect.com](https://walletconnect.com) |
| **Reown (formerly WalletConnect Cloud)** | Hosted WC infrastructure | 🟢 Live | [reown.com](https://reown.com) |
| **AppKit** | Reown's React/Web SDK for wallet UX | 🟢 Live | [reown.com](https://reown.com) |
| **Privy** | Social login + embedded wallets | 🟢 Live | [privy.io](https://www.privy.io) |
| **Lens API** | Social graph + identity | 🟢 Live | [lens.xyz](https://www.lens.xyz) |
| **Farcaster API (Neynar)** | Farcaster social + identity | 🟢 Live | [neynar.com](https://neynar.com) |
| **ENS API** | Ethereum name service lookups | 🟢 Live | [ens.domains](https://ens.domains) |
| **Unstoppable Domains API** | Crypto domain resolution | 🟢 Live | [unstoppabledomains.com](https://unstoppabledomains.com) |
| **Lit Protocol** | Decentralised access control | 🟢 Live | [litprotocol.com](https://litprotocol.com) |
| **Push Protocol** | Web3 notifications | 🟢 Live | [push.org](https://push.org) |
| **XMTP** | Web3 messaging | 🟢 Live | [xmtp.org](https://xmtp.org) |
| **Gitcoin Passport** | Sybil-resistance identity | 🟢 Live | [passport.gitcoin.co](https://passport.gitcoin.co) |
| **Worldcoin (World ID)** | Proof-of-personhood | 🟢 Live | [worldcoin.org](https://worldcoin.org) |

---

## 🤝 MCPs for Blockchain Data (AI Agents)

Connect AI agents (Claude / Cursor / ChatGPT / Codex) directly to blockchain data via Model Context Protocol. See **[Awesome Crypto MCPs](https://github.com/buddies2705/awesome-crypto-mcp)** for the complete list.

| MCP | Source | Capabilities | Status | Link |
| --- | --- | --- | --- | --- |
| ⭐ **Bitquery MCP** | Bitquery | DEX trades, OHLC, market cap, wallet PnL across 8 chains in plain English | 🟢 Live | [mcp.bitquery.io](https://mcp.bitquery.io/) |
| **Alchemy MCP** | Alchemy | 159 tools for token / NFT / tx history / contract sim across 100+ chains | 🟢 Live | [Alchemy MCP](https://www.alchemy.com/docs/alchemy-mcp-server) |
| **Chainstack MCP** | Chainstack | Manage nodes, search docs, infra mgmt | 🟢 Live | [Chainstack MCP](https://docs.chainstack.com/docs/chainstack-mcp-server) |
| **QuickNode MCP** | QuickNode | Endpoint config, usage, billing | 🟢 Live | [QuickNode MCP](https://github.com/quiknode-labs/qn-mcp) |
| **Tatum MCP** | Tatum | 130+ networks via Tatum API | 🟢 Live | [Tatum MCP](https://github.com/tatumio/blockchain-mcp) |
| **Nodit MCP** | Nodit | Multi-chain Web3 API access | 🟢 Live | [Nodit MCP](https://github.com/noditlabs/nodit-mcp-server) |
| **Moralis MCP** | Moralis | Wallet activity, token metrics, dapp usage | 🟢 Live | [Moralis MCP](https://github.com/moralisweb3/moralis-mcp-server) |
| **thirdweb AI** | thirdweb | Insight + Engine + Storage + Nebula | 🟢 Live | [thirdweb AI](https://github.com/thirdweb-dev/ai) |
| **Blockscout MCP** | Blockscout | EVM explorer data via MCP | 🟢 Live | [Blockscout MCP](https://github.com/blockscout/mcp-server) |
| **Dune Analytics MCP** | Dune | SQL on indexed chains via AI | 🟢 Live | [Dune MCP](https://docs.dune.com/api-reference/agents/mcp) |
| **The Graph MCP** | The Graph | Search subgraphs, GraphQL queries | 🟢 Live | [Graph MCP](https://github.com/Data-Nexus-Web3/thegraph-mcp) |
| **Etherscan MCP** | Etherscan | Pull EVM tx history into AI agent | 🟢 Live | [Etherscan MCP](https://github.com/crazyrabbitLTC/mcp-etherscan-server) |
| **Solana Agent Kit MCP** | SendAI | 40+ Solana actions for AI agents | 🟢 Live | [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit) |
| **Bird Eye MCP** | Birdeye | Real-time Solana on-chain data | 🟢 Live | [Birdeye](https://birdeye.so) |
| **Pyth Network MCP** | Pyth | 1,930+ feeds, real-time prices, TWAP | 🟢 Live | [Pyth MCP](https://github.com/itsOmSarraf/pyth-network-mcp) |
| **Chainlink Feeds MCP** | Chainlink | Real-time decentralized prices | 🟢 Live | [Chainlink MCP](https://github.com/kukapay/chainlink-feeds-mcp) |
| **DexScreener Trending MCP** | DexScreener | Trending tokens feed | 🟢 Live | [DexScreener MCP](https://github.com/kukapay/dexscreener-trending-mcp) |
| **Dappier MCP** | Dappier | Real-time crypto + finance content | 🟢 Live | [Dappier MCP](https://github.com/DappierAI/dappier-mcp) |

---

## 🌍 DePIN Data Networks

Decentralized data networks providing alternative bandwidth, scraping, and indexing infrastructure.

| Network | Type | Status | Website |
| --- | --- | --- | --- |
| 🎟️ **Grass** | Bandwidth-as-a-service for AI training | 🟢 Live | [getgrass.io](https://app.getgrass.io/register/?referralCode=148m_QcPsljgrdg) |
| **Hivemapper** | Decentralized mapping network | 🟢 Live | [hivemapper.com](https://hivemapper.com) |
| **IoTeX** | DePIN platform + DePIN-RPC | 🟢 Live | [iotex.io](https://iotex.io) |
| **Helium** | Decentralized 5G + IoT | 🟢 Live | [helium.com](https://www.helium.com) |
| **Filecoin** | Decentralized storage | 🟢 Live | [filecoin.io](https://filecoin.io) |
| **Arweave** | Permanent storage protocol | 🟢 Live | [arweave.org](https://www.arweave.org) |
| **Akash Network** | Decentralized cloud compute | 🟢 Live | [akash.network](https://akash.network) |
| **Render Network** | Decentralized GPU compute | 🟢 Live | [rendernetwork.com](https://rendernetwork.com) |

---

## 🏛️ CEX / Exchange APIs

For builders who need both on-chain and off-chain (CEX) data.

| Exchange | API Strengths | Status | Website |
| --- | --- | --- | --- |
| 🎟️ **Binance API** | Largest spot + futures, broad | 🟢 Live | [binance.com](https://www.binance.com/join?ref=UARTH1S1) |
| 🎟️ **Bybit API** | Derivatives-focused, strong futures + options | 🟢 Live | [bybit.com](https://partner.bybit.com/b/coinmonks) |
| 🎟️ **OKX API** | Spot + Web3 wallet API | 🟢 Live | [okx.com](https://okx.com/join/8432835) |
| 🎟️ **MEXC API** | Wide altcoin coverage | 🟢 Live | [mexc.com](https://www.mexc.com/en-US/register?inviteCode=mexc-17Kqs) |
| 🎟️ **KuCoin API** | Strong altcoin + futures | 🟢 Live | [kucoin.com](https://www.kucoin.com/ucenter/signup?rcode=rJ45SVB) |
| **Coinbase API** | US-regulated, institutional | 🟢 Live | [coinbase.com](https://www.coinbase.com) |
| 🎟️ **Kraken API** | Mature spot + margin + futures | 🟢 Live | [kraken.com](https://kraken.pxf.io/Rygayv) |
| 🎟️ **Gate.io API** | Wide altcoin coverage | 🟢 Live | [gate.io](https://www.gate.io/signup/VFlEA1AK?ref_type=103) |
| 🎟️ **Bitget API** | Copy trading + derivatives | 🟢 Live | [bitget.com](https://partner.bitget.com/bg/L94TTF) |
| **Bitstamp API** | EU-regulated | 🟢 Live | [bitstamp.net](https://www.bitstamp.net) |
| **Crypto.com API** | Retail + institutional | 🟢 Live | [crypto.com](https://crypto.com) |
| **Deribit API** | Crypto options + futures | 🟢 Live | [deribit.com](https://www.deribit.com) |
| **CoinAPI Unified** | Unified across CEXs + DEXs | 🟢 Live | [coinapi.io](https://www.coinapi.io) |
| **CCXT** | Open-source unified CEX library | 🟢 Live | [ccxt.com](https://ccxt.com) |

---

## 🛠️ SDKs & Libraries

| SDK | Language | Coverage | Status | Website |
| --- | --- | --- | --- | --- |
| **ethers.js** | JS / TS | EVM | 🟢 Live | [ethers.io](https://ethers.io) |
| **viem** | TS | EVM (modern, type-safe) | 🟢 Live | [viem.sh](https://viem.sh) |
| **wagmi** | TS / React | EVM React hooks | 🟢 Live | [wagmi.sh](https://wagmi.sh) |
| **web3.js** | JS | EVM | 🟢 Live | [web3js.readthedocs.io](https://web3js.readthedocs.io) |
| **web3.py** | Python | EVM | 🟢 Live | [web3py.readthedocs.io](https://web3py.readthedocs.io) |
| **Alloy** | Rust | EVM (modern Rust) | 🟢 Live | [alloy.rs](https://alloy.rs) |
| **Foundry** | Rust | EVM dev framework | 🟢 Live | [getfoundry.sh](https://getfoundry.sh) |
| **Hardhat** | JS / TS | EVM dev framework | 🟢 Live | [hardhat.org](https://hardhat.org) |
| **@solana/web3.js** | TS | Solana | 🟢 Live | [solana-labs.github.io](https://solana-labs.github.io/solana-web3.js) |
| **@solana/kit** | TS | Solana 2.0 SDK | 🟢 Live | [solanakit.com](https://www.solanakit.com) |
| **Anchor** | Rust | Solana smart-contract framework | 🟢 Live | [anchor-lang.com](https://www.anchor-lang.com) |
| **Solders** | Python | Solana | 🟢 Live | [GitHub](https://github.com/kevinheavey/solders) |
| **Solana Agent Kit** | TS | AI-agent toolkit (SendAI) | 🟢 Live | [GitHub](https://github.com/sendaifun/solana-agent-kit) |
| **GOAT SDK** | TS / Python | Multi-chain AI-agent SDK | 🟢 Live | [GitHub](https://github.com/goat-sdk/goat) |
| **Hyperliquid Python SDK** | Python | Hyperliquid | 🟢 Live | [GitHub](https://github.com/hyperliquid-dex/hyperliquid-python-sdk) |
| **CCXT** | Python / JS / PHP | CEX unification | 🟢 Live | [ccxt.com](https://ccxt.com) |
| **Bitcoin Core libbitcoin** | C++ | Bitcoin | 🟢 Live | [libbitcoin](https://libbitcoin.info) |
| **lncli / LND SDK** | Go | Lightning | 🟢 Live | [lightning.engineering](https://lightning.engineering) |
| **Bitquery SDKs** | TS / Python | GraphQL client wrappers | 🟢 Live | [bitquery.io](https://bitquery.io/) |
| **Helius SDK** | TS | Solana | 🟢 Live | [helius.dev](https://www.helius.dev) |

---

## 🆓 Free Public APIs

For hobbyists, side-projects, and indie hackers who want to avoid signups.

| API | Coverage | Status | Website |
| --- | --- | --- | --- |
| 🆓 **CoinGecko Demo** | Prices + market cap | 🟢 Live | [coingecko.com/api](https://www.coingecko.com/en/api) |
| 🆓 **DexScreener** | All DEX pairs | 🟢 Live | [docs.dexscreener.com](https://docs.dexscreener.com) |
| 🆓 **GeckoTerminal** | DEX data | 🟢 Live | [geckoterminal.com/api](https://www.geckoterminal.com/api) |
| 🆓 **DefiLlama** | TVL + DEX volumes | 🟢 Live | [defillama.com/docs/api](https://defillama.com/docs/api) |
| 🆓 **Bitquery free tier** | Cross-chain GraphQL | 🟢 Live | [bitquery.io](https://bitquery.io) |
| 🆓 **CoinPaprika** | Free market data | 🟢 Live | [coinpaprika.com](https://api.coinpaprika.com) |
| 🆓 **CoinLore** | Free price data | 🟢 Live | [coinlore.com](https://www.coinlore.com/cryptocurrency-data-api) |
| 🆓 **Mempool.space** | Bitcoin mempool | 🟢 Live | [mempool.space](https://mempool.space) |
| 🆓 **Blockchain.com** | Bitcoin data | 🟢 Live | [blockchain.com](https://www.blockchain.com/api) |
| 🆓 **Solana RPC (public)** | Solana | 🟢 Live | [docs.solana.com](https://docs.solana.com) |
| 🆓 **PublicNode** | EVM RPC public endpoints | 🟢 Live | [publicnode.com](https://www.publicnode.com) |
| 🆓 **Etherscan (free tier)** | EVM tx history | 🟢 Live | [etherscan.io](https://etherscan.io) |
| 🆓 **Solscan free** | Solana explorer data | 🟢 Live | [solscan.io](https://solscan.io) |
| 🆓 **Uniswap subgraphs** | Uniswap data | 🟢 Live | [uniswap.org](https://uniswap.org) |

---

## 📚 Resources & Guides

### Comparison & benchmarks

- [CoinCodeCap — Solana gRPC: Helius vs Bitquery vs QuickNode vs Shyft](https://coincodecap.com/solana-grpc-helius-vs-bitquery-vs-quicknode-vs-shyft-which-one-should-you-choose)
- [CoinCodeCap — Top 7 Solana gRPC Providers (2026)](https://coincodecap.com/top-7-solana-grpc-providers-for-real-time-data)
- [Alchemy — Best Blockchain APIs for Onchain Apps](https://blog.alchemyapi.io/overviews/best-blockchain-apis-for-building-onchain-applications)
- [CoinMarketCap — Best Cryptocurrency APIs of 2026](https://coinmarketcap.com/academy/article/best-cryptocurrency-apis-of-2026)
- [CoinMarketCap — Top 10 CoinGecko API Alternatives](https://coinmarketcap.com/academy/article/top-10-coingecko-api-alternatives-for-crypto-data-in-2026)
- [Coinmonks Medium — 5 Best On-Chain Data APIs (2026)](https://medium.com/coinmonks/5-best-onchain-data-apis-for-developers-in-2026-1cf68e1c4920)
- [OnchainDeck — Best RPC & Infrastructure Tools 2026](https://onchaindeck.cc/rpc-infrastructure)
- [Chainstack — Best Ethereum RPC Providers 2026](https://chainstack.com/best-ethereum-rpc-providers-in-2026/)
- [QuickNode — Best Ethereum RPC Providers Full Comparison](https://blog.quicknode.com/best-ethereum-rpc-providers-a-full-comparison/)

### Bitquery deep-dives

- [Bitquery Docs](https://docs.bitquery.io/)
- [Bitquery Pump.fun API](https://docs.bitquery.io/docs/blockchain/Solana/Pumpfun/Pump-Fun-API/)
- [Bitquery Crypto Trades API](https://docs.bitquery.io/docs/trading/crypto-trades-api/trades-api/)
- [Bitquery Crypto Price API](https://docs.bitquery.io/docs/trading/crypto-price-api/introduction/)
- [Bitquery Price Index Algorithm](https://docs.bitquery.io/docs/trading/crypto-price-api/price-index-algorithm/)
- [Bitquery MCP — Overview](https://docs.bitquery.io/docs/mcp/mcp-server/)
- [DEXrabbit (free dashboard)](https://dexrabbit.bitquery.io/)

### Tutorials & how-tos

- [How to add an MCP server to Cursor](https://docs.cursor.com/context/model-context-protocol)
- [How to add an MCP to Claude Desktop](https://modelcontextprotocol.io/quickstart/user)
- [Helius Solana RPC Quickstart](https://docs.helius.dev)
- [Anchor Solana Programs Tutorial](https://www.anchor-lang.com)
- [Hardhat EVM Smart Contract Tutorial](https://hardhat.org/tutorial)
- [Foundry Book](https://book.getfoundry.sh)

### Communities

- [The Graph Discord](https://thegraph.com/discord)
- [Bitquery Telegram](https://t.me/Bloxy_info)
- [Helius Discord](https://discord.gg/helius)
- [Solana Stack Exchange](https://solana.stackexchange.com)
- [Ethereum Stack Exchange](https://ethereum.stackexchange.com)

---

## 🔗 Related Awesome Lists

- [**Awesome Crypto MCPs**](https://github.com/buddies2705/awesome-crypto-mcp) — 110+ MCP servers (Bitquery, Alchemy, Helius, etc.) for AI-agent integrations.
- [**Awesome Memecoin Trading**](https://github.com/buddies2705/awesome-memecoin-trading) — 295+ memecoin trading tools — many built on the APIs in this list.
- [**Awesome Perp DEXs**](https://github.com/buddies2705/awesome-perp-dex) — 200+ perp DEXs + analytics tools — also API consumers.
- [**Awesome Crypto Tax**](https://github.com/buddies2705/awesome-crypto-tax) — 150+ crypto tax tools — most use the APIs in this list as their data layer.
- [**Awesome Prediction Markets**](https://github.com/buddies2705/awesome-prediction-market) — Polymarket, Kalshi, Limitless platforms + tools.

---

## 🤝 Contributing

PRs welcome — the API/infrastructure space ships fast.

1. **Fork** this repo, create a feature branch (e.g. `feature/add-foo-api`).
2. **Match the table format** of the section you're editing.
3. **Quality bar:**
   - API must be live (or in beta — mark 🟡)
   - Must serve real builders (no marketing-page-only projects)
   - Free-tier or pricing transparency required
   - Not abandoned
4. **Use the legend** consistently (🟢 / 🟡 / 🔴 / ⚡ / 🆕 / 🎟️ / 🆓).
5. **No referral spam.** One affiliate link per row max.
6. Open a PR with a one-line summary.

For corrections (broken links, dead projects, wrong free-tier limits) — open an issue or PR.

---

## 📄 License

MIT — see [LICENSE](LICENSE).

---

**Note**: API pricing, free-tier limits, and feature sets change weekly. Always verify on the provider's pricing page before integrating into production. Some links in this list are affiliate / referral links (marked 🎟️) — they don't change the price you pay.

Made with ⚡ for the on-chain builder community.

---

## 🔍 Related Searches

If you arrived here looking for any of the following, you're in the right place:

`blockchain API` · `crypto data API` · `Bitquery` · `Alchemy` · `Moralis` · `Helius` · `QuickNode` · `Solana RPC` · `Ethereum RPC` · `crypto market data API` · `DEX API` · `NFT API` · `wallet API` · `embedded wallet` · `Privy` · `Dynamic` · `WaaS` · `MCP for blockchain` · `crypto streaming API` · `Kafka blockchain` · `gRPC Solana` · `subgraph` · `The Graph` · `Goldsky`

---

## 📈 Popular Use Cases

- **Trading bot builder** — Bitquery (real-time + outlier-filtered) + Helius / Triton for Solana speed + Pyth for sub-second prices.
- **AI trading agent** — Bitquery MCP + Solana Agent Kit MCP + Hyperliquid MCP — drop into Claude / Cursor for plain-English data + execution.
- **DeFi dashboard** — DefiLlama + Token Terminal + Dune for protocol metrics; Bitquery + The Graph for raw protocol events.
- **NFT marketplace / aggregator** — Reservoir + OpenSea + Magic Eden + Helius DAS for Solana.
- **Wallet UI** — Zerion / Zapper / DeBank for EVM portfolio; Step Finance / Helius for Solana; Privy / Dynamic for embedded auth.
- **Crypto tax engine** — Bitquery raw trades + CoinLedger / TaxBit / Awaken APIs for tax-form generation. (See [Awesome Crypto Tax](https://github.com/buddies2705/awesome-crypto-tax).)
- **Memecoin scanner** — Bitquery Pump.fun / LetsBonk + DexScreener + Birdeye for daily flow + GMGN / MadeOnSol for KOL signals.
- **Smart-money copy-trading** — Cielo + Nansen + Arkham + GMGN smart-money APIs feeding a trading bot.
- **Compliance / forensics** — Chainalysis + TRM Labs + Arkham + Bitquery audit trail.
- **Embedded wallet for a consumer app** — Privy or Dynamic for social login + Pimlico / Stackup for AA + Coinbase WaaS for MPC.
- **Indie hacker on a budget** — DexScreener + GeckoTerminal + DefiLlama + CoinGecko Demo (all 100% free).
- **Hyperliquid trader / builder** — HyperRPC + Bitquery + Hyperliquid Python SDK + Helius (for Solana cross-asset) + Hyperdash analytics.
- **Cross-chain swap router** — LiFi + Squid + Socket + deBridge for multi-bridge routing.
- **Researcher / analyst** — Dune + Flipside + Allium + Footprint for SQL-based crypto research.
- **MEV bot** — Flashbots + Jito + bloXroute + Bitquery for back-running detection.

