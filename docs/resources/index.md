---
title: Curated Resources
description: Curated Resources page in the Web3 Security Resources 2026 hub.
---

# Curated Resources

Use this section as a working index. The tiers are editorial judgments based on
practical security value, maintenance, accessibility, and reputation.

## Must Learn

| Resource | Category | Track | Note |
| --- | --- | --- | --- |
| [OWASP Smart Contract Top 10 2026](https://owasp.org/www-project-smart-contract-top-10/) | Standard | EVM, protocol | Current shared vocabulary for high-impact smart contract risks. |
| [OWASP SCSVS](https://scs.owasp.org/SCSVS/) | Standard | Auditor | Verification standard for smart contract assessments. |
| [OWASP SCSTG](https://scs.owasp.org/SCSTG/) | Testing guide | Auditor | Test guide aligned to smart contract security controls. |
| [OpenZeppelin Readiness Guide](https://www.openzeppelin.com/readiness-guide) | Audit readiness | Protocol | Practical preparation model before external review. |
| [SEAL Frameworks](https://frameworks.securityalliance.org/) | Operations | Protocol | Security program and incident readiness frameworks. |
| [Foundry Book](https://book.getfoundry.sh/) | Tooling | EVM | Core EVM development and audit test framework. |
| [Solidity Docs](https://docs.soliditylang.org/) | Language | EVM | Primary compiler and language reference. |
| [Solodit](https://solodit.cyfrin.io/) | Vulnerability intel | Auditor | Searchable public finding and contest intelligence. |
| [DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) | Exploit study | Auditor | Reproduce historical DeFi incidents. |
| [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) | Fundamentals | Beginner | Durable blockchain and EVM background. |

## Use in Real Audits

| Resource | Category | Track | Note |
| --- | --- | --- | --- |
| [Slither](https://github.com/crytic/slither) | Static analysis | EVM | Fast bug triage, inheritance graphs, and printers. |
| [Aderyn](https://github.com/Cyfrin/aderyn) | Static analysis | EVM | Auditor-oriented static analysis and reports. |
| [Echidna](https://github.com/crytic/echidna) | Fuzzing | EVM | Property-based fuzzing. |
| [Medusa](https://github.com/crytic/medusa) | Fuzzing | EVM | High-performance stateful fuzzing. |
| [Halmos](https://github.com/a16z/halmos) | Symbolic testing | EVM | Symbolic execution for Foundry tests. |
| [Tenderly](https://tenderly.co/) | Debugging | EVM | Transaction simulation, forks, and debugging. |
| [Sourcify](https://sourcify.dev/) | Verification | EVM | Source-code verification metadata. |
| [Immunefi](https://immunefi.com/) | Bug bounty | Protocol | Bounty hosting and disclosure workflows. |
| [Sherlock](https://www.sherlock.xyz/) | Contests | Auditor | Competitive audits and coverage markets. |
| [Cantina](https://cantina.xyz/) | Contests | Auditor | Competitive audits, bounties, and private engagements. |
| [Pashov Audits](https://github.com/pashov/audits) | Reports | Auditor | Large public archive of independent audit reports. |
| [Pashov Skills](https://github.com/pashov/skills) | AI-assisted audit | EVM | Practical Solidity auditor and x-ray skills. |
| [Burp Suite](https://portswigger.net/burp) | Web/API testing | Full-stack | Baseline proxy for offchain auth, API, and admin-surface testing. |

## Situational / Advanced

| Resource | Category | Track | Note |
| --- | --- | --- | --- |
| [ERC-4337 Resources](https://docs.erc4337.io/resources/) | Account abstraction | EVM, wallet | Primary hub for smart accounts, bundlers, paymasters, and UserOperations. |
| [ERC-4337 Simulation Requirements](https://docs.erc4337.io/bundlers/simulation-requirements.html) | Account abstraction | EVM, wallet | Bundler simulation expectations that should inform reviews. |
| [OpenZeppelin EIP-4337 Audit](https://www.openzeppelin.com/news/eth-foundation-account-abstraction-audit) | Audit report | EVM, wallet | Public report with paymaster, bundler, and EntryPoint failure modes. |
| [Solana Program Security Course](https://solana.com/developers/courses/program-security) | Chain-specific security | Solana | Solana signer, owner, PDA, CPI, and lifecycle vulnerability classes. |
| [Mollusk](https://solana.com/docs/programs/testing/mollusk) | Testing | Solana | Fast instruction-level tests for Solana programs. |
| [Anchor LiteSVM](https://www.anchor-lang.com/docs/testing/litesvm) | Testing | Solana | Lightweight local Solana tests for CI-friendly security coverage. |
| [Surfpool](https://docs.surfpool.run/) | Testing | Solana | Local Solana network and simulation environment. |
| [BlockSec Phalcon Simulator](https://docs.blocksec.com/phalcon/phalcon-explorer/simulator) | Simulation | EVM, IR | Transaction simulation for exploit reproduction and privileged action review. |
| [Tenderly Docs](https://docs.tenderly.co/) | Simulation | EVM | Forks, traces, simulations, monitoring, and incident reproduction. |
| [Safe Transaction Service](https://docs.safe.global/core-api/transaction-service-overview) | Multisig operations | Protocol | Monitoring and timeline evidence for Safe-controlled operations. |
| [Chainlink Feed Selection](https://docs.chain.link/data-feeds/selecting-data-feeds) | Oracle security | DeFi | Feed freshness, deviation, fallback, and selection guidance. |
| [Wormhole Security](https://docs.wormhole.com/protocol/security/) | Bridge security | Multi-chain | Security-program reference for bridge and messaging assumptions. |
| [CosmWasm Docs](https://cosmwasm.com/build) | Chain-specific security | Cosmos | Wasm smart contract development and testing reference. |
| [Sui Security](https://www.sui.io/security) | Move security | Sui | Public reports and security resources for Sui and Move. |
| [Aptos Move Docs](https://aptos.dev/en/build/smart-contracts) | Move security | Aptos | Primary Aptos Move smart contract reference. |
| [RISC Zero Docs](https://dev.risczero.com/) | zkVM | ZK | zkVM proof, guest, receipt, and verifier reference. |
| [SP1 Repository](https://github.com/succinctlabs/sp1) | zkVM | ZK | Source and release reference for SP1 integrations. |
| [Certora Prover](https://www.certora.com/prover) | Formal methods | EVM | Specification and formal verification for high-value systems. |
| [Runtime Verification](https://runtimeverification.com/) | Formal methods | Multi-chain | Semantics and verification services. |
| [0xPARC](https://learn.0xparc.org/) | ZK | ZK | Strong ZK education and research community. |
| [zkSecurity](https://www.zksecurity.xyz/) | ZK | ZK | ZK audit research and vulnerability guidance. |
| [Starknet Docs](https://docs.starknet.io/) | Chain docs | Cairo | Current Starknet platform documentation. |
| [Move Book](https://move-book.com/) | Language | Move | Practical Move language reference. |
| [Anchor Docs](https://www.anchor-lang.com/docs) | Framework | Solana | Solana program development and account constraints. |
| [Token-2022](https://spl.solana.com/token-2022) | Token standard | Solana | Extension-heavy token surface. |
| [Kontrol](https://kontrol.runtimeverification.com/) | Formal methods | EVM | Foundry-integrated formal verification using K semantics. |
| [ItyFuzz](https://github.com/fuzzland/ityfuzz) | Fuzzing | EVM | Snapshot-based fuzzing and exploit-generation research. |
| [TestMachine EVMbench](https://testmachine.ai/evmbench/) | AI benchmark | AI-assisted | Benchmark context for EVM exploit reasoning claims; not an audit-tool endorsement. |
| [Paradigm EVMbench](https://www.paradigm.xyz/2026/02/evmbench) | AI benchmark | AI-assisted | Research framing for EVM exploit-generation benchmarks. |
| [Re-Evaluating EVMBench](https://arxiv.org/abs/2603.10795) | AI benchmark | AI-assisted | Cautionary paper for interpreting benchmark scores. |

## Paid / Certification

| Resource | Category | Track | Note |
| --- | --- | --- | --- |
| [Certora Prover](https://www.certora.com/prover) | Formal methods | EVM | Commercial tooling; valuable for protocols with formal specs. |
| [AuditBase](https://www.auditbase.com/) | Training/tools | EVM | Paid security learning and scanning options. |
| [Offensive Security](https://www.offsec.com/) | General security | Full-stack | Useful for web, infra, and attacker methodology. |
| [SANS SEC554](https://www.sans.org/cyber-security-courses/blockchain-smart-contract-security/) | Training | Protocol | Structured paid blockchain and smart contract security training. |
| [Octane Security](https://www.octane.security/) | AI security | EVM | Commercial AI security tool to evaluate carefully. |
| [Almondo](https://almondo-labs.ai/) | AI security | Multi-chain | Commercial AI audit service to evaluate carefully. |
| [TRM Labs](https://www.trmlabs.com/) | Blockchain intelligence | Compliance | Investigations, monitoring, and wallet risk intelligence. |
| [Chainalysis](https://www.chainalysis.com/) | Blockchain intelligence | Compliance | Investigations, compliance, and ecosystem intelligence. |
| [Elliptic](https://www.elliptic.co/) | Blockchain intelligence | Compliance | Crypto risk intelligence and wallet screening. |
| [zeroShadow](https://www.zeroshadow.io/) | Incident response | Protocol | Web3 IR, investigations, threat intel, and vSOC. |

## Watchlist

| Resource | Category | Track | Note |
| --- | --- | --- | --- |
| [AIxCC](https://aicyberchallenge.com/) | AI security | AI-assisted | Watch for program-analysis lessons that transfer to audits. |
| [Wake](https://github.com/Ackee-Blockchain/wake) | Testing | EVM | Growing Python-based Solidity testing and analysis framework. |
| [GoPlus Security](https://gopluslabs.io/) | User protection | Full-stack | Transaction and token risk APIs for wallet/app defenses. |
| [Blockaid](https://www.blockaid.io/) | User protection | Full-stack | Wallet and dapp threat detection. |
| [Hypernative](https://www.hypernative.io/) | Monitoring | Protocol | Real-time risk and exploit detection platform. |
| [VANTAGE by DigiBastion](https://vantage.digibastion.com/) | External trust monitoring | Full-stack | Maintainer-labeled monitoring for domain, DNS, frontend, phishing, and Web3 trust risk. |
| [Pashov AI Web3 Security](https://github.com/pashov/ai-web3-security) | AI security | AI-assisted | Source list for AI audit tools, skills, and commercial products. |

The machine-readable catalog lives in [resources.yml](../data/resources.yml).
