![Canton Foundation](assets/banner.png)

# Awesome Canton

> A curated guide to building on the Canton Network: where to start based on who you are, the links that matter, and **What to build**.

Canton is a public, privacy-enabled Layer 1 built for regulated finance. Smart contracts are written in Daml, each party sees only the data it is entitled to, and apps across the network can settle atomically through the Global Synchronizer.

If you're new here, pick your persona below and follow the route. If you already know how to build and you're asking *"okay, but what should I build?"*, skip to **[Use Cases We Want Built](#use-cases-we-want-built)**.

## Contents

- [Start Here: Pick Your Route](#start-here-pick-your-route)
  - [I'm new to blockchain development](#im-new-to-blockchain-development)
  - [I'm coming from Ethereum / Solidity](#im-coming-from-ethereum--solidity)
  - [I'm coming from another chain (Solana, Cosmos, etc.)](#im-coming-from-another-chain-solana-cosmos-etc)
  - [I'm an architect, PM or institution evaluating Canton](#im-an-architect-pm-or-institution-evaluating-canton)
  - [I'm integrating a wallet, exchange or custody product](#im-integrating-a-wallet-exchange-or-custody-product)
  - [I want to run a validator](#i-want-to-run-a-validator)
  - [I'm a system integrator or dev shop](#im-a-system-integrator-or-dev-shop)
  - [I want funding or to shape the protocol](#i-want-funding-or-to-shape-the-protocol)
- [Essential Links](#essential-links)
  - [Documentation](#documentation)
  - [Build Tools and SDKs](#build-tools-and-sdks)
  - [APIs](#apis)
  - [Source Code](#source-code)
  - [Explorers and Network Data](#explorers-and-network-data)
  - [Rewards and Tokenomics](#rewards-and-tokenomics)
  - [Community and Support](#community-and-support)
- [Use Cases We Want Built](#use-cases-we-want-built)

## Start Here: Pick Your Route

Each route is a short, ordered path. Do the steps in order, and don't skip LocalNet. It's the fastest way to make the concepts click.

### I'm new to blockchain development

1. **[Five-Minute Overview](https://docs.canton.network/overview/understand/five-minute-overview)**: what Canton is and why it exists, in plain terms.
2. **[Core Concepts](https://docs.canton.network/overview/understand/core-concepts)**: parties, contracts, validators and synchronizers. Read this before touching code.
3. **[Module 1: Understanding Canton](https://docs.canton.network/appdev/modules/m1-understanding-canton)**: the mental model you'll use for everything after.
4. **[Module 3: Daml Smart Contracts](https://docs.canton.network/appdev/modules/m3-dev-environment)**: set up your environment and write your first Daml template.
5. **[Module 4: Building Applications](https://docs.canton.network/appdev/modules/m4-building-apps-intro)**: a full-stack app with backend, frontend and the JSON Ledger API.

### I'm coming from Ethereum / Solidity

1. **[Canton for Ethereum Developers](https://docs.canton.network/appdev/modules/m2-canton-for-ethereum-devs)**: maps what you already know to Canton equivalents.
2. **[Privacy Model](https://docs.canton.network/overview/learn/privacy-model)**: the biggest mindset shift. Privacy is the default, and you *declare* who can see data.
3. **[Module 3: Daml Smart Contracts](https://docs.canton.network/appdev/modules/m3-dev-environment)**: start writing Daml.
4. **[Module 4: Building Applications](https://docs.canton.network/appdev/modules/m4-building-apps-intro)**: ship an end-to-end app.

### I'm coming from another chain (Solana, Cosmos, etc.)

1. **[Five-Minute Overview](https://docs.canton.network/overview/understand/five-minute-overview)**
2. **[Architecture Overview](https://docs.canton.network/overview/learn/architecture)**: how Canton's network of networks differs from a single global state machine.
3. **[Canton MCP](https://github.com/canton-network-devs/Build-on-Canton-MCP)**: the Canton Foundation's MCP server for your AI coding assistant. Tell it your background, whether that's Solana, Cosmos or enterprise stacks like C# and C++, and it will guide you through building on Canton from where you already are. Install it with `npx @canton-network-devs/canton-mcp-server install`.
4. **[Module 3: Daml Smart Contracts](https://docs.canton.network/appdev/modules/m3-dev-environment)**

### I'm an architect, PM or institution evaluating Canton

1. **[Five-Minute Overview](https://docs.canton.network/overview/understand/five-minute-overview)**
2. **[The Problem Canton Solves](https://docs.canton.network/overview/understand/the-problem)**: why public chains and private ledgers each fall short for regulated finance.
3. **[Canton's Solution](https://docs.canton.network/overview/understand/cantons-solution)**
4. **[Use Cases](https://docs.canton.network/overview/understand/use-cases)**
5. **[Architecture Overview](https://docs.canton.network/overview/learn/architecture)**

### I'm integrating a wallet, exchange or custody product

1. **[Integrations Overview](https://docs.canton.network/integrations/overview)**: start here to see which integration path fits your product.
2. **[Integrating with the Canton Network](https://docs.canton.network/integrations/wallets-and-exchanges/integrating-with-canton)**: the core guide for wallets and exchanges.
3. **[Wallet Gateway Quickstart](https://docs.canton.network/integrations/wallet-gateway/quickstart)**: connect dApps to wallets and sign transactions.
4. **[Integration Patterns](https://docs.canton.network/integrations/integration-patterns)**: common architectures to copy.

### I want to run a validator

1. **[Introduction to Node Operations](https://docs.canton.network/global-synchronizer/understand/introduction)**: what running a node involves.
2. **[Validator Roles and Responsibilities](https://docs.canton.network/global-synchronizer/understand/validator-roles)**
3. **[Validator Onboarding Process](https://docs.canton.network/global-synchronizer/deployment/onboarding-process)**: how to get sponsored and whitelisted.

### I'm a system integrator or dev shop

1. **[Canton Developer Certification](https://certification.canton.foundation)**: get your team certified on Daml 3.
2. **[Canton Partners](https://directory.canton.foundation/)**: the directory of SIs and dev studios with proof of work.

### I want funding or to shape the protocol

1. **[Canton Dev Fund](https://github.com/canton-foundation/canton-dev-fund)**: open-source grants for tools, infrastructure and apps that grow the network. Browse approved proposals before writing your own.

2. **[Canton Improvement Proposals (CIPs)](https://github.com/canton-foundation/cips)**: the source of truth for network standards, such as CIP-56, the token standard.

4. **[cip-announce and cip-discuss mailing lists](https://lists.sync.global)**: follow new proposals and join the discussion before votes happen.

## Essential Links

### Documentation

| Link | Use it for |
|---|---|
| [Canton Network Docs](https://docs.canton.network/) | The main Canton Network documentation. Start here for almost everything. |
| [Choose Your Path](https://docs.canton.network/appdev/get-started/choose-your-path) | The official persona-based learning paths and the module sequence. |
| [CN QuickStart](https://docs.canton.network/appdev/quickstart) | The fastest way to a working Canton app. A full reference app plus LocalNet that you can fork for your own project. |
| [Global Synchronizer](https://docs.canton.network/global-synchronizer/understand/overview) | Understand what Canton and Splice actually are, and how the Global Synchronizer, validators, Canton Coin and rewards fit together. Read this before you go anywhere near a real network. |
| [Canton MCP](https://github.com/canton-network-devs/Build-on-Canton-MCP) | The Canton Foundation's MCP server for Claude and other AI coding assistants. It gives your assistant real Canton and Daml knowledge so it can guide you, review your code and answer questions. Install with `npx @canton-network-devs/canton-mcp-server install`. |


### Build Tools and SDKs

| Link | Use it for |
|---|---|
| [Canton Developer Hub](https://dev-hub.canton.foundation/) | A directory of developer tools across the ecosystem, with AI-assisted search. |
| [App Builder Guide](https://guide.canton.foundation/) | A guided walkthrough for building your first Canton app. |
| [QuickStart](https://docs.canton.network/appdev/quickstart) | A full reference app (Java backend, React frontend) plus LocalNet. Fork it to bootstrap a real project. |
| [LocalNet](https://docs.canton.network/sdks-tools/development-tools/localnet) | A full Canton network on your laptop. Use it to deploy and test your own Daml code without the QuickStart app. |
| [Sandbox](https://docs.canton.network/sdks-tools/development-tools/sandbox) | A single-participant ledger for the fastest Daml logic testing. |
| [DPM](https://docs.canton.network/sdks-tools/cli-tools/dpm) | The package manager and CLI for Daml projects. Install it first: it's how you create, build, test and run Canton projects. |

### APIs

| Link | Use it for |
|---|---|
| [API Reference](https://docs.canton.network/api-reference) | The entry point for every Canton and Splice API. |
| [Ledger API](https://docs.canton.network/sdks-tools/api-reference/ledger-api) | Submit commands and read transactions (gRPC and JSON). This is how your backend talks to Canton. |
| [Splice APIs Overview](https://docs.canton.network/sdks-tools/api-reference/splice-overview) | Scan, Validator and Wallet APIs for Canton Coin, rewards and network data. |
| [Wallet Gateway dApp API](https://docs.canton.network/integrations/wallet-gateway/reference/dapp-api) | Connect your frontend to users' wallets. |

### Source Code

| Repo | What's inside |
|---|---|
| [canton-network/splice](https://github.com/canton-network/splice) | The open-source reference apps behind the Global Synchronizer: Canton Coin, wallet, Scan, validator and SV apps. |
| [digital-asset/cn-quickstart](https://github.com/digital-asset/cn-quickstart) | The QuickStart reference app and LocalNet setup. |
| [canton-foundation/cips](https://github.com/canton-foundation/cips) | All Canton Improvement Proposals. |
| [canton-foundation/canton-dev-fund](https://github.com/canton-foundation/canton-dev-fund) | Dev Fund process, proposals and milestones. |

### Explorers and Network Data

| Link | Use it for |
|---|---|
| [CC View](https://ccview.io) | Explorer for looking up transactions, parties, tokens and network activity. |
| [Lighthouse by Five North](https://lighthouse.cantonloop.com) | Live data from Super Validators and validators, governance decisions, and how featured apps interact with the network. |

### Rewards and Tokenomics

| Link | Use it for |
|---|---|
| [Traffic-Based App Rewards](https://docs.canton.network/global-synchronizer/splice-fundamentals/traffic-based-app-rewards) | How apps earn Canton Coin rewards for the activity they generate. Read this before you design your app's transaction flow. |
| [Reward Sharing](https://docs.canton.network/global-synchronizer/splice-fundamentals/reward-sharing) | Sharing rewards with users, partners or other apps. |
| [Minting Delegations](https://docs.canton.network/global-synchronizer/splice-fundamentals/rewards-minting) | How rewards are minted and delegated. |
| [Synchronizer Traffic](https://docs.canton.network/global-synchronizer/deployment/synchronizer-traffic) | How traffic fees work, so you can budget your app's network costs. |

### Community and Support

| Link | Use it for |
|---|---|
| [Canton Forum](https://forum.canton.network/) | The primary place for technical questions, Dev Fund proposals and announcements. Search here first; someone has probably hit your error before. |

## Use Cases We Want Built

You can Build a Canton dApp, **So what do you actually build?**

Below are the use cases the Canton ecosystem needs most right now. They're grounded in what's already live on the network: tokenized Treasuries and repo, stablecoins like USDCx and USD1, institutional trading venues and early DeFi. 

### Institutional capital markets

| Use Case | What to Build | Existing Projects |
|---|---|---|
| **Collateral management, mobility and financing** | Build collateral eligibility, optimization, margin-call and automated substitution workflows across tokenized Treasuries, bonds, MMFs and deposits. Enable collateral to be pledged, transferred, substituted and released across custodians and financial institutions for repo, securities lending and derivatives margin, with integration into existing custody and settlement infrastructure. | — |
| **OTC derivatives lifecycle and margin management** | Automate trade confirmation, exposure calculation, collateral thresholds, variation and initial margin calls, dispute resolution and settlement across bilateral derivatives portfolios. Integrate ISDA/CSA terms, valuation data and eligible collateral to reduce reconciliation and manual margin operations. | — |
| **Tokenized fund operations middleware** | This covers transfer agency, subscriptions and redemptions, 24/7 redemption into USDCx or USD1, and MMF units used as collateral. | — |
| **Non-USD cash and FX PvP** | Almost all live cash on Canton is USD. EUR, GBP and JPY tokenized deposits or stablecoins, plus payment-versus-payment FX, would unlock cross-border repo properly. | — |
| **Securities lending marketplace** | DTCC's July production event already included securities lending alongside collateral and repo. No dedicated app yet handles locate, borrow, recall, rebates and corporate-action passthrough on tokenized equities & Treasuries, On-chain asset servicing & Corporate actions infrastructure. | — |

### Payments and treasury

| Use Case | What to Build | Existing Projects |
|---|---|---|
| **Corporate treasury and private B2B payments** | Use cases include payroll, B2B payments & Remittances, invoice-to-settlement, and idle-cash sweeps into tokenized MMFs. | — |

### Onchain markets and DeFi

| Use Case | What to Build | Existing Projects |
|---|---|---|
| **Credit and risk primitives** | Lending needs liquidation engines, oracle-aware risk parameters, and rating-aware collateral haircuts for RWAs. | — |
| **Prime brokerage and cross-venue margin** | A portfolio-margin layer could net exposures across spot, perps and loans, so a market maker posts collateral once. | — |
| **Liquidity routing and aggregation** | Build a swap and route aggregator across Canton DEXs. | — |

### Compliance, data and infrastructure

| Use Case | What to Build | Existing Projects |
|---|---|---|
| **Reusable credentials, KYC and Travel Rule services** | This means a credential layer other apps can query instead of re-KYCing everyone. Bank caution about permissionless exposure is real. | — |
| **Regulatory reporting, audit and accounting** | Build regulator and auditor views using selective disclosure, sub-ledger exports for fund admins, and PQS-backed reconciliation and tax reporting. | — |

> **Built something in one of these areas? Get it listed.**
>
> The **Existing Projects** column is empty on purpose. It's waiting for you. If you've built a project that fits a use case above, open a pull request that adds it to the right row in this format:
>
> ```
> [Project Name](https://link-to-project) — one-line description
> ```
>
> Separate multiple projects in the same cell with `<br>`. To be listed, your project should:
> - be deployed on Canton (LocalNet demos don't count; DevNet, TestNet or MainNet do),
> - have a public repo, live app or docs page we can link to, and
> - actually address the use case in that row.
>
> Want to build one of these and need support? Check the [Canton App Dev Forum](https://forum.canton.network/).

## Contributing

This list is community-maintained, and contributions are welcome.