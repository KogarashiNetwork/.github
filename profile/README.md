# Kogarashi
[![Twitter Follow](https://img.shields.io/twitter/follow/KogarashiCrypto?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=KogarashiCrypto) [![Discord](https://dcbadge.vercel.app/api/server/g3q7tsHKTd?style=social&compact=true)](https://discord.gg/g3q7tsHKTd)

<div align="center">
    <img alt="image" src="https://github.com/KogarashiNetwork/Kogarashi/assets/39494661/5a40d34b-8501-4fe4-a59e-2d097bde154d">
</div>

Kogarashi Network is a **A Next-Generation Composable Hybrid Smart Contract and (De)Centralized Merged Application Platform**

## Features

■ **Real World Hybrid Smart Contract**

Fetch the Internet data through TLS verification protocol with trustless and use it for smart contract executions.

■ **Crypto-Centric Scalable and Private Blockchain**

Recompose blockchain runtime, storage and functions as crypto-friendly, and achieve advanced features with high performance simple usage.

## Motivation

There are two motivations for this platform.

1. Increase data type that can deal with Dapp
2. Manage both advanced features and simple usability

Firstly, typical blockchains can deal with only cryptocurrency balance and crypto-assets. We innovate the data-getting process and bring off-chain data with trustless and low cost. **Dapp on our platform can deal with various types of data from off-chain and realize a completely new use case.**

Secondly, typical blockchains are inefficient to process the latest cryptography scheme like zero-knowledge proof and homomorphic encryption. We innovate blockchain runtime and realize simple usage and fast process. **Users can use various simple-to-use and a little gas cost functionalities**.

## Activities

We have been working on cryptography schemes relevant to privacy, scaling, and off-chain Oracle issues. Our approach involves creating cryptographic libraries from the ground up and ensuring their ability to adapt to changes.

- **Core Thought**

1. Replace with latest algorithms easily
2. Avoid code duplication
3. Compatible with [`no_std`](https://docs.rust-embedded.org/book/intro/no-std.html#a-no_std-rust-environment) and [`Parity SCALE Codec`](https://github.com/paritytech/parity-scale-codec).

- **Pallets**

|Pallet|Description|
|---|---|
|[**confidential_transfer**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/confidential_transfer)|Confidential transfer pallet which allows us to transfer assets by hiding the exact amount.|
|[**encrypted_balance**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/encrypted_balance)|Encrypted balance pallet which allows us to use encrypted balance by additive homomorphic encryption.|
|[**plonk**](https://github.com/KogarashiNetwork/Kogarashi/tree/master/pallets/plonk)|plonk pallet which allows us to use plonk verification in the runtime environment.|

- **Library**

| Name        | Crates.io | Documentation | Description |
|-------------|-----------|-----------|-----------|
| [zkstd](https://github.com/KogarashiNetwork/zkstd) | [![crates.io](https://img.shields.io/crates/v/zkstd.svg)](https://crates.io/crates/zkstd) | [![Documentation](https://docs.rs/zkstd/badge.svg)](https://docs.rs/zkstd) | `Crypto primitives` of **zero knowledge proof** and **homomorphic encryption**. This includes **Field**, **Curve**, **ExtensionField** and **Pairing**, **Fft**. This allows us to easily setup cryptography implementation and test without implementing actual algorithms.
| [jub-jub](https://github.com/KogarashiNetwork/jubjub) | [![crates.io](https://img.shields.io/crates/v/jub-jub.svg)](https://crates.io/crates/jub-jub) | [![Documentation](https://docs.rs/jub-jub/badge.svg)](https://docs.rs/jub-jub) |`Jubjub curve` implementation used for **zero knowledge proof** circuit domain. This includes **finite field** operations and point arithmetic interface of **twisted Edwards curve**.
| [bls-12-381](https://github.com/KogarashiNetwork/bls12_381) |  [![crates.io](https://img.shields.io/crates/v/bls-12-381.svg)](https://crates.io/crates/bls-12-381) | [![Documentation](https://docs.rs/bls-12-381/badge.svg)](https://docs.rs/bls-12-381) |`Bls12 381 curve` implementation used for **zero knowledge proof** polynomial operation domain. This includes finite field operations, point arithmetic interface of the **Weierstrass curve**, and pairing interface.
| [ec-pairing](https://github.com/KogarashiNetwork/pairing) | [![crates.io badge](https://img.shields.io/crates/v/ec-pairing.svg)](https://crates.io/crates/ec-pairing) | [![Documentation](https://docs.rs/ec-pairing/badge.svg)](https://docs.rs/ec-pairing) |`Tate Pairing` implementation. This includes the Miller loop algorithm and pairing construction with pairing-friendly curve.
| [she-elgamal](https://github.com/KogarashiNetwork/elgamal) | [![crates.io](https://img.shields.io/crates/v/she-elgamal.svg)](https://crates.io/crates/she-elgamal) | [![Documentation](https://docs.rs/she-elgamal/badge.svg)](https://docs.rs/she-elgamal) | `ElGamal Encryption` implementation. This includes a public key encryption interface that supports **additive homomorphism**.
| [poly-commit](https://github.com/KogarashiNetwork/polynomial) | [![crates.io](https://img.shields.io/crates/v/poly-commit.svg)](https://crates.io/crates/poly-commit) | [![Documentation](https://docs.rs/poly-commit/badge.svg)](https://docs.rs/poly-commit) | `Kate Polynomial Commitment` implementation. This includes polynomial commitment and operations used for **zero knowledge proof plonk**.
| [red-jubjub](https://github.com/KogarashiNetwork/redjubjub) | [![crates.io](https://img.shields.io/crates/v/red-jubjub.svg)](https://crates.io/crates/red-jubjub) | [![Documentation](https://docs.rs/red-jubjub/badge.svg)](https://docs.rs/red-jubjub) | `Redjubjub` implementation. This includes **RedDSA** interfact and public key encryption algorithm.

## Follow Us

[Website](https://kogarashi-network.com/) | [Twitter](https://twitter.com/KogarashiCrypto) | [Discord](https://discord.gg/g3q7tsHKTd) | [Github](https://github.com/KogarashiNetwork) | [Documentation](https://kogarashinetwork.github.io/Kogarashi/)
