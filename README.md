# Sera5im

**Smart Contract Security Researcher**
Solidity · DeFi · Bridges & Cross-Chain · Invariant Fuzzing

I focus on smart contract security research, with a particular interest in **DeFi, bridges, cross-chain systems, protocol accounting, and state-machine vulnerabilities**.

My review workflow combines:

* Manual protocol-flow analysis
* Function-level security reasoning
* Invariant and property verification
* AI-assisted invariant generation
* Protocol-specific stateful fuzzing
* Adversarial validation of findings
* Reproducible Foundry PoCs
* Impact and root-cause analysis

## Security Research

I work primarily with **Solidity / EVM protocols**, focusing on complex protocol behavior rather than only isolated code patterns.

Areas of interest:

* Bridges and cross-chain messaging
* DeFi accounting
* Vaults and token flows
* Access-control boundaries
* State-transition bugs
* Broken protocol invariants
* Cross-function interactions
* Edge-case and sequence-dependent vulnerabilities

## Invariant Fuzzing

A major part of my workflow is **protocol-specific invariant fuzzing**.

Instead of relying only on generic fuzz tests, I build fuzzing environments around the actual protocol logic:

`Protocol analysis → invariant generation → invariant verification → stateful fuzzing → failure analysis → PoC → impact validation`

AI agents assist with invariant generation, harness development, failure triage, and adversarial review, while findings are validated against executable protocol behavior.

## Selected Work

### Bridge & Cross-Chain Security

* **LayerZero V2 OFT Bug Lab**
  Invariant-break scenarios, bridge-path failures, and exploit-style PoCs.

* **Bridge Disclosed Issues Lab**
  Local reconstructions of publicly disclosed bridge and cross-chain vulnerabilities with runnable PoCs.

* **Arbitrum ERC20 Bridge Review**

* **Optimism ERC20 Bridge Review**

* **Orbit L3 ERC20 Bridge Review**

* **Push Chain Cross-Chain Core Review**

### Methodology

* **Security Review Methodology**
  My approach to protocol scope, flow analysis, review layers, invariant drafting, verification, and AI-assisted security research.


## Tools

`Solidity` · `Foundry` · `Invariant Fuzzing` · `Stateful Fuzzing` · `AI-Assisted Security Research`

