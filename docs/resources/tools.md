---
title: Tools
description: Tools page in the Web3 Security Resources 2026 hub.
---

# Tools

## EVM Development, Testing, and Debugging

| Tool | Tier | Use |
| --- | --- | --- |
| [Foundry](https://book.getfoundry.sh/) | Must learn | Compile, test, fuzz, fork, script, and debug EVM systems. |
| [Hardhat](https://hardhat.org/) | Use in real audits | Common project framework; many scopes still use it. |
| [Remix](https://remix.ethereum.org/) | Situational / advanced | Quick experiments and education. |
| [Tenderly](https://tenderly.co/) | Use in real audits | Transaction simulation and debugging. |
| [Sourcify](https://sourcify.dev/) | Use in real audits | Verified source metadata and contract lookup. |
| [Etherscan](https://etherscan.io/) | Use in real audits | Contract, transaction, and event inspection. |
| [Dune](https://dune.com/) | Situational / advanced | On-chain analytics and incident queries. |

## Static Analysis

| Tool | Tier | Use |
| --- | --- | --- |
| [Slither](https://github.com/crytic/slither) | Use in real audits | Static analysis, printers, inheritance, and call graph views. |
| [Aderyn](https://github.com/Cyfrin/aderyn) | Use in real audits | Solidity static analysis with report output. |
| [Mythril](https://github.com/ConsenSysDiligence/mythril) | Situational / advanced | Symbolic analysis for EVM bytecode. |
| [Manticore](https://github.com/trailofbits/manticore) | Situational / advanced | Symbolic execution platform. |
| [Semgrep](https://semgrep.dev/) | Use in real audits | Custom source-code rules for frontends, APIs, and Solidity patterns. |
| [Solhint](https://github.com/protofire/solhint) | Use in real audits | Solidity linting and style/security rules. |
| [Wake](https://github.com/Ackee-Blockchain/wake) | Watchlist | Python-based Solidity testing and static analysis framework. |

## Dynamic Analysis and Debugging

| Tool | Tier | Use |
| --- | --- | --- |
| [Foundry Fork Testing](https://book.getfoundry.sh/forge/fork-testing) | Must learn | Reproduce mainnet state and incident paths locally. |
| [Tenderly](https://tenderly.co/) | Use in real audits | Transaction simulation, trace debugging, and monitoring. |
| [Dune](https://dune.com/) | Situational / advanced | Incident dashboards, protocol queries, and anomaly research. |
| [DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) | Must learn | Runnable exploit reproductions for historical incidents. |

## Fuzzing

| Tool | Tier | Use |
| --- | --- | --- |
| [Foundry Invariant Testing](https://book.getfoundry.sh/forge/invariant-testing) | Must learn | Invariant and stateful fuzz testing in the standard EVM workflow. |
| [Echidna](https://github.com/crytic/echidna) | Use in real audits | Property-based fuzzing. |
| [Medusa](https://github.com/crytic/medusa) | Use in real audits | Stateful EVM fuzzing. |
| [ItyFuzz](https://github.com/fuzzland/ityfuzz) | Situational / advanced | Snapshot-based fuzzing and exploit-generation research. |
| [Wake](https://github.com/Ackee-Blockchain/wake) | Watchlist | Python-driven Solidity tests, fuzzing, and analysis. |

## Formal Methods and Symbolic Execution

| Tool | Tier | Use |
| --- | --- | --- |
| [Halmos](https://github.com/a16z/halmos) | Use in real audits | Symbolic testing from Foundry tests. |
| [hevm](https://github.com/ethereum/hevm) | Situational / advanced | EVM symbolic execution and testing. |
| [Certora Prover](https://www.certora.com/prover) | Paid / certification | Formal verification with executable specs. |
| [Kontrol](https://kontrol.runtimeverification.com/) | Situational / advanced | Foundry-integrated formal verification using K semantics. |
| [K Framework](https://kframework.org/) | Situational / advanced | Semantics framework behind several verification efforts. |

## AI-Assisted Security

| Tool | Tier | Use |
| --- | --- | --- |
| [Pashov AI Web3 Security](https://github.com/pashov/ai-web3-security) | Must learn | Curated AI Web3 security tools and skills list. |
| [Pashov Skills](https://github.com/pashov/skills) | Use in real audits | Solidity auditor and x-ray skills for AI-assisted review. |
| [Octane Security](https://www.octane.security/) | Paid / certification | Commercial AI security tool to evaluate with normal vendor diligence. |
| [Almondo](https://almondo-labs.ai/) | Paid / certification | Commercial AI audit service for EVM, Solana, Move, Stellar and Cosmos; evaluate with normal vendor diligence. |
| [Nethermind AuditAgent](https://auditagent.nethermind.io/) | Watchlist | Nethermind-backed AI audit agent; verify outputs manually. |
| [TestMachine EVMbench](https://testmachine.ai/evmbench/) | Watchlist | Benchmark context for AI EVM exploit reasoning. |
| [Paradigm EVMbench](https://www.paradigm.xyz/2026/02/evmbench) | Watchlist | Research framing for EVM exploit-generation benchmarks. |
| [Re-Evaluating EVMBench](https://arxiv.org/abs/2603.10795) | Watchlist | Cautionary paper for interpreting benchmark claims. |

## Chain-Specific Tooling

| Tool | Tier | Use |
| --- | --- | --- |
| [Anchor](https://www.anchor-lang.com/docs) | Must learn | Solana framework and account constraints. |
| [Starknet Foundry](https://foundry-rs.github.io/starknet-foundry/) | Use in real audits | Cairo contract testing. |
| [Scarb](https://docs.swmansion.com/scarb/) | Use in real audits | Cairo package manager and build tool. |
| [Move Prover](https://aptos.dev/en/build/smart-contracts/prover) | Situational / advanced | Specification and verification for Move. |
| [Circom](https://docs.circom.io/) | Must learn | Circuit language for SNARK circuits. |
| [Noir](https://noir-lang.org/docs) | Watchlist | ZK DSL with improving developer experience. |

## Monitoring and User Protection

| Tool | Tier | Use |
| --- | --- | --- |
| [Forta](https://forta.org/) | Use in real audits | Detection bots and on-chain monitoring. |
| [OpenZeppelin Defender](https://docs.openzeppelin.com/defender) | Use in real audits | Admin operations, monitoring, and automation. |
| [Hypernative](https://www.hypernative.io/) | Paid / certification | Real-time protocol monitoring and exploit detection. |
| [Blockaid](https://www.blockaid.io/) | Paid / certification | Wallet and dapp transaction protection. |
| [GoPlus](https://gopluslabs.io/) | Use in real audits | Token, address, and transaction risk APIs. |
| [Socket](https://socket.dev/) | Use in real audits | Supply-chain risk for JavaScript packages. |
| [OpenSSF Scorecard](https://github.com/ossf/scorecard) | Use in real audits | Open-source dependency health checks. |
| [VANTAGE by DigiBastion](https://vantage.digibastion.com/) | Watchlist | External domain, DNS, frontend, phishing, and Web3 trust-risk monitoring. |
