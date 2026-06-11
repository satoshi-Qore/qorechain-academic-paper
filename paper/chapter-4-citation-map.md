# Chapter 4 Citation Map

This note maps the major claims in Chapter 4, "Multi-VM Architecture and Cross-Environment Execution," to appropriate source categories. It is intended to support later citation refinement, peer review preparation, and possible conversion to an IEEE-style reference format.

## Purpose

Chapter 4 discusses QoreChain's multi-VM direction as a research hypothesis. The chapter should not treat EVM, CosmWasm, or SVM compatibility as confirmed advantages without implementation evidence. Instead, it should connect each architectural claim to sources that clarify execution models, interoperability assumptions, security risks, and validation needs.

## Section-to-Source Map

| Chapter Section | Main Claim Type | Recommended Sources | Evidence Status |
|---|---|---|---|
| 4.1 Definition and Architectural Foundations | Execution environments define state transition behavior, resource accounting, and contract interaction models | Ethereum Yellow Paper, Ethereum execution specifications, CosmWasm documentation, Solana runtime documentation | Supported by primary project documentation |
| 4.2 Triple-VM Design Principles | A Triple-VM model may connect developer communities from Ethereum, Cosmos, and Solana ecosystems | Ethereum whitepaper, CosmWasm documentation, Solana program documentation, QoreChain core documentation | QoreChain-specific claim remains a research hypothesis |
| 4.3 Comparative Analysis | Ethereum, Solana, and Cosmos represent different execution and interoperability philosophies | Ethereum execution specifications, Solana runtime documentation, Cosmos whitepaper, IBC specifications | Supported as comparative architecture context |
| 4.4 Technical Advantages | Multi-VM support may improve developer optionality and application diversity | EVM tooling sources, CosmWasm documentation, Solana program documentation, public developer activity metrics | Requires future QoreChain implementation and adoption evidence |
| 4.5 Technical Limitations and Challenges | Multi-VM systems increase complexity around state, fees, ordering, indexing, and cross-runtime messaging | IBC specifications, Ethereum execution specifications, smart contract security literature | Supported conceptually; QoreChain-specific validation pending |
| 4.6 Security Implications | Multi-VM architecture expands the audit surface and requires clear runtime boundaries | Ethereum smart contract attack surveys, smart contract analysis literature, runtime documentation | Requires independent review and QoreChain-specific threat modeling |
| 4.7 Developer Experience and Ecosystem Impact | Developer experience depends on tooling, examples, documentation, and migration paths | Official VM documentation, SDK documentation, public repositories, issue activity | Requires longitudinal ecosystem tracking |
| 4.8 Evidence Gaps and Future Research Directions | Compatibility, interoperability, performance, and security claims require staged validation | QoreChain repositories, future audit reports, benchmarks, mainnet metrics | Currently open research area |
| 4.9 Chapter Conclusion | Triple-VM architecture is significant only if implementation, tooling, security, and performance evidence mature over time | Full Chapter 4 source set | Provisional conclusion |

## Recommended Inline Citation Strategy

Later revisions of Chapter 4 should add citations in a restrained way:

- Use Ethereum sources when discussing EVM execution, gas/resource accounting, and smart contract ecosystem maturity.
- Use CosmWasm sources when discussing WebAssembly-based contracts, Rust-oriented development, and Cosmos ecosystem integration.
- Use Solana sources when discussing SVM-style execution, account-based program design, and performance-oriented runtime assumptions.
- Use Cosmos and IBC sources when discussing cross-chain communication, message passing, and interoperability design.
- Use smart contract security literature when discussing reentrancy, access-control failures, runtime-specific vulnerabilities, and expanded audit surface.
- Use QoreChain official sources only for QoreChain-specific architecture claims, and label those claims as project-specific primary-source evidence unless independently validated.

## Validation Criteria for Future Revisions

The following evidence would strengthen Chapter 4:

| Validation Area | Evidence Needed |
|---|---|
| EVM compatibility | Public deployment examples, wallet/tooling tests, Solidity contract examples |
| CosmWasm integration | WASM runtime documentation, Rust contract examples, contract lifecycle documentation |
| SVM compatibility | Runtime implementation details, account model behavior, program deployment examples |
| Cross-VM interoperability | Message specifications, state transition rules, failure handling, replay protection |
| Security | Independent audit reports, threat model, runtime isolation documentation, test coverage |
| Performance | Benchmarks for throughput, latency, resource usage, and validator load |
| Developer adoption | Public repositories, SDK usage, issue activity, external contributors, deployed applications |

## Research Notes

The strongest academic position is to treat QoreChain's Triple-VM direction as a structured research question rather than a completed conclusion. Chapter 4 should therefore preserve cautious wording such as "may," "could," "requires validation," and "future research should examine." This protects the paper from promotional overstatement while keeping the technical idea visible and research-worthy.