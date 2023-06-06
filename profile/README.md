# Kogarashi Project

**Kogarashi Network** is working on cryptography research and development.

1. Trustless Oracle Parachain
2. Zero Knowledge Proof Library Compatible with Polkadot Ecosystem

## Motivation

Our motivation is to implement **modern design pallets** next-generation blockchain infrastructure. Traditional blockchain is inefficient to process cryptographic schemes because of their `VM` and `data structure`, and it's hard to upgrade. We implement `a cryptography-friendly` runtime environment and structure, and it's easy to import to `Parachain`. Our libraries can be imported by every `Parachain` project and are efficient to process because it's compatible with `Polkadot`. These libraries allow more various functionalities.

## Pallets

### [**confidential_transfer**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/confidential_transfer)

Confidential transfer pallet which allows us to transfer assets by hiding the exact amount.

### [**encrypted_balance**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/encrypted_balance)

Encrypted balance pallet which allows us to use encrypted balance by additive homomorphic encryption.

### [**plonk**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/plonk)

plonk pallet which allows us to use plonk verification in the runtime environment.

## Libraries

### [**zero-crypto**](https://github.com/KogarashiNetwork/core) [![crates.io badge](https://img.shields.io/crates/v/zero-crypto.svg)](https://crates.io/crates/zero-crypto)

Cryptography primitive implementation `Field`, `Curve` and `Pairing`, `Fft`, `Kzg`.

### [**zero-jubjub**](https://github.com/KogarashiNetwork/jubjub) [![crates.io badge](https://img.shields.io/crates/v/zero-jubjub.svg)](https://crates.io/crates/zero-jubjub)

Twisted Edward curve `jubjub` implementation used for zero-knowledge circuit arithmetic domain.

### [**zero-bls12-381**](https://github.com/KogarashiNetwork/bls12_381) [![crates.io badge](https://img.shields.io/crates/v/zero-bls12-381.svg)](https://crates.io/crates/zero-bls12-381)

Pairing-friendly `bls12 381` curve used for polynomial operation arithmetic domain.

### [**zero-elgamal**](https://github.com/KogarashiNetwork/elgamal) [![crates.io badge](https://img.shields.io/crates/v/zero-elgamal.svg)](https://crates.io/crates/zero-elgamal)

Additive homomorphic ElGamal encryption based on `jubjub` curve.
