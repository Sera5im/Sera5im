# Serafim Somin

Smart Contract Security Researcher  
Bridges, Cross-chain Systems, and Application-Layer Flow Logic

I focus on manual smart contract security review with an emphasis on bridges, cross-chain systems, token-routing paths, and protocol edge cases. My workflow combines flow decomposition, trust-boundary analysis, invariant extraction, Foundry-based fuzzing, and PoC validation to check whether a bug is real, reachable, and economically meaningful.

## Focus Areas

- Bridge and cross-chain contract logic
- ERC20 token paths, gateways, wrappers, adapters, and settlement flows
- Flow decomposition and trust-boundary analysis
- Invariant-driven reasoning and exploitability validation
- Foundry fuzzing for critical path assumptions
- Audit-style technical writeups and local PoC labs

## Review Workflow

1. Map the full execution flow and identify the trust boundary.
2. Compare normal and alternate paths to find divergence.
3. Extract the invariants that should hold across those paths.
4. Validate the strongest assumptions with PoCs and fuzzing.
5. Reduce the result into a concise root cause, impact statement, and remediation direction.

## Selected Work

- [LayerZero V2 OFT Review](https://github.com/Sera5im/Sera5im-layerzero-v2-oft-review-en)
- [Push Chain Cross-Chain Core Review](https://github.com/Sera5im/Sera5im-push-chain-cross-chain-core-review-en)
- [Rhino.fi Deposit Policy Bypass Report](https://github.com/Sera5im/Sera5im-rhinofi-deposit-policy-bypass-report)
- [Bridge Disclosed Issues Lab](https://github.com/Sera5im/Sera5im-bridge-disclosed-issues-lab)

## Working Style

- Manual review first
- Fuzzing used to validate critical invariants, not replace reasoning
- PoC-driven confirmation before escalation
- Strong attention to path inconsistency, accounting drift, trust assumptions, and cross-chain edge cases

## Current Interests

- Bridge and interoperability systems
- Omnichain token flows
- Gateway and adapter contracts
- Settlement correctness
- Cross-chain accounting failures
- Path inconsistency bugs

## Contact

- GitHub: [Sera5im](https://github.com/Sera5im)
- Email: `serafyntop@gmail.com`
