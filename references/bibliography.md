# Bibliography

This bibliography tracks primary and supporting references for the QoreChain academic research paper. It is organized by research area and uses a simple IEEE-oriented format that can later be converted into BibTeX or a formal publication style.

## Primary Standards and Cryptography

[1] National Institute of Standards and Technology, "FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard," 2024. DOI: https://doi.org/10.6028/NIST.FIPS.203. Available: https://csrc.nist.gov/pubs/fips/203/final

[2] National Institute of Standards and Technology, "FIPS 204: Module-Lattice-Based Digital Signature Standard," 2024. DOI: https://doi.org/10.6028/NIST.FIPS.204. Available: https://csrc.nist.gov/pubs/fips/204/final

[3] National Institute of Standards and Technology, "Post-Quantum Cryptography Standardization Project." Available: https://csrc.nist.gov/projects/post-quantum-cryptography

[4] P. W. Shor, "Algorithms for Quantum Computation: Discrete Logarithms and Factoring," Proceedings of the 35th Annual Symposium on Foundations of Computer Science, 1994.

## Blockchain Foundations

[5] S. Nakamoto, "Bitcoin: A Peer-to-Peer Electronic Cash System," 2008. Available: https://bitcoin.org/en/bitcoin-paper

[6] V. Buterin, "Ethereum Whitepaper," 2014. Available: https://ethereum.org/whitepaper/

## Execution Environments and Virtual Machines

[7] G. Wood, "Ethereum: A Secure Decentralised Generalised Transaction Ledger," Ethereum Yellow Paper. Available: https://ethereum.github.io/yellowpaper/paper.pdf

[8] Ethereum Foundation, "Ethereum Execution Specifications." Available: https://github.com/ethereum/execution-specs

[9] CosmWasm Documentation, "CosmWasm Smart Contract Documentation." Available: https://docs.cosmwasm.com/

[10] CosmWasm Documentation, "The CosmWasm Book." Available: https://book.cosmwasm.com/

[11] Solana Documentation, "Solana Runtime." Available: https://solana.com/docs/core/runtime

[12] Solana Documentation, "Solana Programs." Available: https://solana.com/docs/core/programs

## Interoperability and Multi-Chain Architecture

[13] G. Wood, "Polkadot: Vision for a Heterogeneous Multi-Chain Framework," 2016. Available: https://assets.polkadot.network/Polkadot-whitepaper.pdf

[14] J. Kwon and E. Buchman, "Cosmos: A Network of Distributed Ledgers," 2016. Available: https://github.com/cosmos/cosmos/blob/master/WHITEPAPER.md

[15] Cosmos Network Documentation, "Inter-Blockchain Communication Protocol Documentation." Available: https://docs.cosmos.network/ibc/

[16] Interchain Standards, "Inter-Blockchain Communication Protocol Specifications." Available: https://github.com/cosmos/ibc

## Security and Smart Contract Analysis

[17] N. Atzei, M. Bartoletti, and T. Cimoli, "A Survey of Attacks on Ethereum Smart Contracts," Principles of Security and Trust, 2017.

[18] L. Luu, D. H. Chu, H. Olickel, P. Saxena, and A. Hobor, "Making Smart Contracts Smarter," Proceedings of the ACM SIGSAC Conference on Computer and Communications Security, 2016.

## QoreChain-Specific Primary Sources

[19] QoreChain Core Repository, "QoreChain Core Documentation and Architecture Materials." Available: https://github.com/qorechain/qorechain-core

[20] QoreChain Light Node Repository, "QoreChain Light Node Documentation." Available: https://github.com/qorechain/qorechain-lightnode

[21] QoreChain Website and Public Documentation. Available: https://qorechain.io

## Community Research and Supporting Materials

[22] Satoshi-Qore, "QoreChain Guides: Community Documentation Hub." Available: https://github.com/satoshi-Qore/qorechain-guides

[23] Satoshi-Qore, "QoreChain Tools: Community Infrastructure Notes and Examples." Available: https://github.com/satoshi-Qore/qorechain-tools

[24] Satoshi-Qore, "QoreChain Notes: Research and Infrastructure Notes." Available: https://github.com/satoshi-Qore/Qorechain-notes

## Citation Use Map

| Paper Area | Suggested Sources |
|---|---|
| Post-quantum cryptography | [1], [2], [3], [4] |
| Blockchain foundations | [5], [6] |
| EVM execution and Ethereum comparison | [6], [7], [8], [17], [18] |
| CosmWasm execution | [9], [10], [14], [15] |
| Solana/SVM execution | [11], [12] |
| Multi-VM and interoperability | [7], [9], [11], [13], [14], [15], [16] |
| Smart contract security | [17], [18] |
| QoreChain architecture | [19], [20], [21] |
| Community ecosystem analysis | [22], [23], [24] |

## Source Quality Notes

- NIST FIPS documents should be treated as primary references for ML-KEM and ML-DSA terminology.
- Bitcoin and Ethereum whitepapers should be treated as foundational blockchain architecture references.
- The Ethereum Yellow Paper and execution specifications should be used for EVM-level execution analysis.
- CosmWasm and Solana documentation should be used as primary project documentation for VM-specific concepts, while avoiding claims that require independent benchmark evidence.
- Polkadot, Cosmos, and IBC materials should be used for interoperability and multi-chain architecture context.
- QoreChain repositories and website materials should be cited as project-specific primary sources, not as independent validation.
- Community repositories should be cited only for ecosystem documentation and contributor activity, not for protocol-level claims.

## Maintenance Notes

Future revisions should:

- Add access dates for all online sources.
- Convert this bibliography into BibTeX if the paper moves to LaTeX.
- Add peer-reviewed tokenomics, governance, and validator-incentive papers.
- Add more peer-reviewed literature on WebAssembly-based smart contracts and Solana program security.
- Separate confirmed mainnet data from pre-mainnet documentation once public network data becomes available.