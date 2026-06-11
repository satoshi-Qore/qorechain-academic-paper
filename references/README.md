# References

This directory tracks reference sources for the QoreChain academic research paper.

The repository now separates reference management into two layers:

- [bibliography.md](./bibliography.md) contains structured academic references and a citation use map.
- This README explains how references should be evaluated, categorized, and maintained.

## Reference Categories

| Category | Purpose | Status |
|---|---|---|
| Post-quantum cryptography standards | Support cryptographic background and terminology | Initial references added |
| QoreChain official documentation | Provide primary-source technical context | Initial references added |
| Blockchain architecture literature | Support Layer 1 and execution-environment analysis | Expanded |
| EVM and Ethereum execution sources | Support EVM compatibility and Ethereum comparison | Expanded |
| CosmWasm and WASM contract sources | Support CosmWasm integration and Rust/WASM contract analysis | Expanded |
| Solana/SVM execution sources | Support SVM compatibility and performance-oriented execution discussion | Expanded |
| Multi-VM and interoperability research | Support comparative architecture analysis | Expanded |
| Smart contract security literature | Support security implications and audit-surface analysis | Initial references added |
| Tokenomics and governance literature | Support economic and governance analysis | Needs expansion |
| Network and validator research | Support infrastructure and incentive analysis | Needs expansion |

## Current Citation Map

| Citation Area | Primary Sources |
|---|---|
| ML-KEM and post-quantum key encapsulation | NIST FIPS 203 |
| ML-DSA and post-quantum signatures | NIST FIPS 204 |
| Quantum threat model | Shor's quantum algorithm paper and NIST PQC materials |
| Blockchain foundations | Bitcoin whitepaper and Ethereum whitepaper |
| EVM execution | Ethereum Yellow Paper and Ethereum execution specifications |
| CosmWasm execution | CosmWasm documentation and The CosmWasm Book |
| Solana/SVM execution | Solana runtime and program documentation |
| Interoperability and multi-chain systems | Cosmos, IBC, and Polkadot materials |
| Smart contract security | Ethereum smart contract security literature |
| QoreChain-specific architecture | QoreChain repositories, website, and public technical materials |
| Community ecosystem evidence | QoreChain Guides, Tools, and Notes repositories |

## Source Quality Levels

| Level | Description | Example |
|---|---|---|
| Primary standard | Official standards body publication | NIST FIPS 203, NIST FIPS 204 |
| Primary project source | Official project documentation or repository | QoreChain official repositories, Ethereum execution specs, CosmWasm docs, Solana docs |
| Foundational paper | Widely cited original technical paper | Bitcoin whitepaper, Ethereum whitepaper |
| Supporting architecture source | Related protocol or ecosystem documentation | Cosmos IBC, Polkadot whitepaper |
| Academic security literature | Peer-reviewed or widely cited security analysis | Ethereum smart contract attack surveys |
| Community evidence | Community-maintained documentation or contribution records | Satoshi-Qore community repositories |

## Citation Guidance

When adding sources, prefer:

- Official standards documents for cryptographic claims
- Peer-reviewed papers for academic background
- Official project documentation for execution-environment claims
- Official project documentation for QoreChain-specific architecture claims
- Clearly labeled community observations for ecosystem notes

Avoid unsupported claims and avoid using marketing material as the only source for technical conclusions.

## Future Work

- Add complete access dates for online materials.
- Add BibTeX entries if the project moves toward LaTeX or IEEE-style formatting.
- Add peer-reviewed tokenomics and governance sources.
- Add validator incentive and infrastructure reliability literature.
- Add more peer-reviewed literature on WebAssembly smart contracts, Solana program security, and cross-VM interoperability.
- Link individual paper sections to specific bibliography entries.
- Separate pre-mainnet observations from post-mainnet empirical evidence once public network data becomes available.