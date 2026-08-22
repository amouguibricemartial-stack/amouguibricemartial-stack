# Martial A. (Brice Martial Amougui)
### Lead Software Engineer | Web3 Systems & Smart Contract Security Auditor

[![GitHub Followers](https://img.shields.io/github/followers/amouguibricemartial-stack?style=social)](https://github.com/amouguibricemartial-stack)
[![AW3SS Stars](https://img.shields.io/github/stars/amouguibricemartial-stack/AW3SS?style=social)](https://github.com/amouguibricemartial-stack/AW3SS)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?logo=solidity&logoColor=white)](https://soliditylang.org/)
[![Rust](https://img.shields.io/badge/Rust-Anchor%20Framework-black?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Python](https://img.shields.io/badge/Python-FastAPI%20%2F%20AsyncIO-3776AB?logo=python&logoColor=white)](https://python.org/)
[![Foundry](https://img.shields.io/badge/Foundry-Forge%20Testing-E57373?logo=ethereum&logoColor=white)](https://getfoundry.sh/)
[![Docker](https://img.shields.io/badge/Docker-Sandboxed%20Execution-2496ED?logo=docker&logoColor=white)](https://docker.com/)
[![Slither](https://img.shields.io/badge/Static%20Analysis-Slither-blueviolet)](https://github.com/crytic/slither)

---

## Executive Summary

Software Engineer specializing in **fintech payment platforms, decentralized protocol architecture, and offensive smart contract security** across EVM and Solana ecosystems.

Proven track record designing and developing production-grade payment gateway systems (**AfricPay**) and autonomous multi-chain security engines (**AW3SS**). Core capabilities span high-throughput backend engineering, transaction integrity, automated invariant fuzzing, AST data-flow analysis, and deterministic Proof of Concept (PoC) exploit verification.

---

## Key Engineered Platforms

### AfricPay — Digital Payment Gateway & Financial Aggregator
*Enterprise-grade payment gateway aggregating mobile money, card payments, and digital wallet transactions.*
- **Architecture & APIs:** Engineered high-availability asynchronous REST APIs for merchant checkout, wallet settlements, and payment status callbacks.
- **Transaction Security:** Implemented cryptographic HMAC signature verification, idempotent transaction handling, and automated webhook event delivery.
- **Data Integrity:** Designed database transaction atomicity ensuring zero-reconciliation discrepancies across concurrent multi-provider payment flows.

### AW3SS — Multi-Agent Web3 Security & Invariant Fuzzing Engine
*Autonomous multi-chain security scanner for smart contracts combining AST static analysis, AI agents, and sandboxed fork testing.*
- **Automated Verification:** Executes automated invariant testing and generates reproducible Foundry PoC tests in isolated Docker containers (`--cap-drop=ALL`).
- **Multi-Chain Coverage:** Scans EVM (Solidity), Solana (Rust / Anchor), Cairo, and TON/TVM protocols for critical reentrancy, oracle, and logic flaws.
- **Self-Healing PoC Loop:** Autonomous 3-tier temperature retry mechanism automatically repairing compilation pragmas, interfaces, and state parameters.

---

## Core Technical Competencies

### Smart Contract Security & Formal Auditing
- **EVM Vulnerability Analysis:** Read-Only & Cross-Function Reentrancy, Oracle Price Feed Manipulation (Chainlink / TWAP), Token Accounting Precision Loss, Access Control Flaws, EIP-712 Signature Replay.
- **Solana / Anchor Security:** Missing Signer/Owner validations, PDA derivation flaws, Account Cosplay, Cross-Program Invocation (CPI) security.
- **Verification Tooling:** Foundry (`forge test`), Slither AST analysis, Invariant Fuzzing, Sandboxed Docker Execution.

### Web3 Architecture & Protocol Development
- **DeFi & Vault Engineering:** ERC-4626 Tokenized Vaults, Yield Engines, Liquidity Lockers, Staking Mechanics.
- **Account Abstraction:** ERC-4337 Smart Accounts, Paymasters for gasless flows, Session Key authorization.
- **Tokenomics & GameFi:** Gas-optimized ERC-20 / SPL tokens, ERC-721A & ERC-1155 digital assets with Merkle tree whitelists and EIP-712 vouchers.
- **Backend & Relayers:** Python (Web3.py, FastAPI), Node.js (Ethers.js), EIP-712 typed signature verification, On-chain Event Listeners.

---

## Featured Repositories

| Repository | Focus Area | Technology Stack |
| :--- | :--- | :--- |
| **[AW3SS](https://github.com/amouguibricemartial-stack/AW3SS)** | Multi-Agent Web3 Security Scanner & Autonomous Invariant Fuzzing Engine. | Python, LangGraph, Foundry, Slither, Docker, Rust |
| **[production-solidity-templates](https://github.com/amouguibricemartial-stack/production-solidity-templates)** | Gas-optimized ERC-4626 staking vaults, GameFi vouchers with 100% Foundry test coverage. | Solidity ^0.8.20, Foundry, OpenZeppelin |
| **[web3-security-reviews](https://github.com/amouguibricemartial-stack/web3-security-reviews)** | Formal audit reports, vulnerability breakdowns, and reproducible Foundry PoCs. | Solidity, Foundry, Slither |

---

## Professional Services & Contact

- **Services:** Protocol Security Audits, Custom Smart Contract Development, and Fintech / Web3 Backend Architecture.
- **GitHub:** [@amouguibricemartial-stack](https://github.com/amouguibricemartial-stack)
- **LinkedIn:** [Brice Martial Amougui](https://www.linkedin.com/)
- **Availability:** Open for private audits, contest collaborations, and senior engineering roles.
