# Awesome Circom

> A curated list of repos related to [Circom](https://github.com/iden3/circom).

## Contents
- [Cryptographic primitives](#cryptographic-primitives)
   - [In Circom](#cryptographic-primitives-in-circom)
   - [In other languages](#cryptographic-primitives-in-other-languages)
- [Provers](#provers)
- [Code editors & tooling](#code-editors--tooling)
- [Tutorials & docs](#tutorials--docs)
- [Papers](#papers)
- [Projects using Circom](#projects-using-circom)


## Cryptographic primitives

### Cryptographic primitives in Circom
- [circomlib](https://github.com/iden3/circomlib) - main 'standard lib' in Circom
- [circom-ecdsa](https://github.com/0xPARC/circom-ecdsa) - secp256k1 ECDSA operations
- [circom-pairing](https://github.com/yi-sun/circom-pairing) - BLS12-381 curve
- [zk-attestor](https://github.com/yi-sun/zk-attestor) - Scalable on-chain trustless attestations to data from any past Ethereum block or state (ethereum storage proofs)
- [keccak256-circom](https://github.com/vocdoni/keccak256-circom) - keccak256 implementation

### Cryptographic primitives in other languages
> Cryptographic primitives implemented in other languages which are compatible with Circom implementations

- Javascript
   - [circomlibjs](https://github.com/iden3/circomlibjs) - Javascript library to work with circomlib circuits
- Go
   - [go-iden3-crypto](https://github.com/iden3/go-iden3-crypto) - Poseidon & mimc hash, babyjubjub elliptic curve
   - [arbo](https://github.com/vocdoni/arbo) - Efficient MerkleTree compatible with circomlib, which parallelizes computation by CPUs
   - [go-merkletree](https://github.com/iden3/go-merkletree) - MerkleTree compatible with circomlib 
- Rust
   - [poseidon-rs](https://github.com/arnaucube/poseidon-rs) - Poseidon hash function compatible with circomlib
   - [babyjubjub-rs](https://github.com/arnaucube/babyjubjub-rs) - BabyJubJub elliptic curve compatible with circomlib

## Provers
- [snarkjs](https://github.com/iden3/snarkjs) - zkSNARK implementation in JavaScript & WASM
- [rapidsnark](https://github.com/iden3/rapidsnark) - zkSNARK proof generation written in C++ and intel assembly
- [ark-circom](https://github.com/gakonst/ark-circom) - Arkworks bindings to Circom's R1CS, for Groth16 Proof and Witness generation in Rust
- [go-circom-prover-verifier](https://github.com/iden3/go-circom-prover-verifier/) - Go implementation of the Groth16 zkSNARK Prover and Verifier compatible with Circom
- [go-circom-witnesscalc](https://github.com/iden3/go-circom-witnesscalc) - Witness Calculator in go, calling WASM

## Code editors & tooling
- [zkrepl](https://github.com/0xPARC/zkrepl) - Online playground for Circom circuits
- [vscode plugin](https://github.com/iden3/circom-highlighting-vscode) - VSCode syntax highlighting plugin
- [vim plugin](https://github.com/iden3/vim-circom-syntax) - Vim syntax highlighting plugin
- [Shield Cli](https://github.com/xorddotcom/SHIELD) - SHIELD is a development framework for circom developers. SHIELD is a tool to provide libraries, plugins, and testing tools to ensure code quality and security.
- [Circomspect](https://github.com/trailofbits/circomspect) - static analyzer and linter for the Circom programming language

## Tutorials & docs
- [docs.circom.io](https://docs.circom.io/) - official Circom docs
- [Circom & Snarkjs talk](https://www.youtube.com/watch?v=-9TJa1hVsKA) - Jordi Baylina's talk at zkSummit 2019
- [Electron Labs - Intro to Circom](https://docs.electronlabs.org/intro-to-circom) - Usage of language syntax and programming practices
- [BattleZips Zero Knowledge Crash Course](https://www.youtube.com/channel/UCcVGZqz46ELMsjVRIr0VOxw) - Tutorial on building a battleship game on Ethereum & Circom
- [Introduction to Zero Knowledge Proof](https://github.com/enricobottazzi/ZKverse) - Tutorial inspired by the presentation "All About the ZkVerse | Polygon" performed by Jordi Baylina at EthDenver22

## Papers
> Papers on Circom related constructions and primitives implemented in the circomlib standard library

- [CIRCOM: A Robust and Scalable Language for Building Complex Zero-Knowledge CircuitsComplex Zero-Knowledge Circuits](https://www.techrxiv.org/articles/preprint/CIRCOM_A_Robust_and_Scalable_Language_for_Building_Complex_Zero-Knowledge_Circuits/19374986/1/files/34409498.pdf)
- [Sparse Merkle Trees](https://docs.iden3.io/publications/pdfs/Merkle-Tree.pdf)
- [Baby Jubjub Elliptic Curve](https://iden3-docs.readthedocs.io/en/latest/_downloads/33717d75ab84e11313cc0d8a090b636f/Baby-Jubjub.pdf) & [EIP-2494](https://eips.ethereum.org/EIPS/eip-2494)
- [Poseidon: A New Hash Function for Zero-Knowledge Proof Systems](https://eprint.iacr.org/2019/458)

## Projects using Circom
- [hermeznetwork/circuits](https://github.com/hermeznetwork/circuits) - Hermez network circuits
- [iden3/circuits](https://github.com/iden3/circuits/) - Circom circuits used by the iden3 core protocol
- [appliedzkp/maci](https://github.com/appliedzkp/maci) - Minimal anti collusion infrastructure
- [appliedzkp/semaphore](https://github.com/appliedzkp/semaphore) - A privacy gadget for creating anonymous proof of membership on Ethereum
- [tornadocash/tornado-core](https://github.com/tornadocash/tornado-core) - Non-custodial private transactions on Ethereum
- [worldcoin/semaphore-rs](https://github.com/worldcoin/semaphore-rs) - Rust support library for using semaphore
- [0xPARC/zk-group-sigs](https://github.com/0xPARC/zk-group-sigs) - Group signatures implemented with zkSNARKs
- [vocdoni/zk-franchise-proof-circuit](https://github.com/vocdoni/zk-franchise-proof-circuit) - Census proof anonymous voting circuit
- [web3-master/zksnark-sudoku](https://github.com/web3-master/zksnark-sudoku) - Sudoku verifier using zkSNARK and circom.
