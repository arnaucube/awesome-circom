# Awesome Circom

> A curated list of repos related to [Circom](https://github.com/iden3/circom).

## Contents
- [Cryptographic primitives](#cryptographic-primitives)
   - [In Circom](#cryptographic-primitives-in-circom)
   - [In other languages](#cryptographic-primitives-in-other-languages)
- [Provers](#provers)
- [Code editors](#code-editors)
- [Tutorials & docs](#tutorials--docs)
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

## Code editors
- [zkrepl](https://github.com/0xPARC/zkrepl) - Online playground for Circom circuits
- [vscode plugin](https://github.com/iden3/circom-highlighting-vscode) - VSCode syntax highlighting plugin
- [vim plugin](https://github.com/iden3/vim-circom-syntax) - Vim syntax highlighting plugin

## Tutorials & docs
- [docs.circom.io](https://docs.circom.io/) - official Circom docs
- [Circom & Snarkjs talk](https://www.youtube.com/watch?v=-9TJa1hVsKA) - Jordi Baylina's talk at zkSummit 2019
- [Electron Labs - Intro to Circom](https://docs.electronlabs.org/intro-to-circom) - Usage of language syntax and programming practices
- [BattleZips Zero Knowledge Crash Course](https://www.youtube.com/channel/UCcVGZqz46ELMsjVRIr0VOxw) - Tutorial on building a battleship game on Ethereum & Circom

## Projects using Circom
- [hermeznetwork/circuits](https://github.com/hermeznetwork/circuits) - Hermez network circuits
- [iden3/circuits](https://github.com/iden3/circuits/) - Circom circuits used by the iden3 core protocol
- [appliedzkp/maci](https://github.com/appliedzkp/maci) - Minimal anti collusion infrastructure
- [appliedzkp/semaphore](https://github.com/appliedzkp/semaphore) - A privacy gadget for creating anonymous proof of membership on Ethereum
- [tornadocash/tornado-core](https://github.com/tornadocash/tornado-core) - Non-custodial private transactions on Ethereum
- [worldcoin/semaphore-rs](https://github.com/worldcoin/semaphore-rs) - Rust support library for using semaphore
- [0xPARC/zk-group-sigs](https://github.com/0xPARC/zk-group-sigs) - Group signatures implemented with zkSNARKs
- [vocdoni/zk-franchise-proof-circuit](https://github.com/vocdoni/zk-franchise-proof-circuit) - Census proof anonymous voting circuit
