# Kogarashi
[![Twitter Follow](https://img.shields.io/twitter/follow/KogarashiCrypto?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=KogarashiCrypto) [![Discord](https://dcbadge.vercel.app/api/server/g3q7tsHKTd?style=social&compact=true)](https://discord.gg/g3q7tsHKTd)

<div align="center">
    <img alt="image" src="https://github.com/KogarashiNetwork/Kogarashi/assets/39494661/5a40d34b-8501-4fe4-a59e-2d097bde154d">
</div>

**Kogarashi Network** is a Dapp platform that gives centralization convenience and decentralization transparency to Dapp via trustless and low-cost access to the Internet.

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

|Library|Version|Description|
|---|---|---|
|[**zero-crypto**](https://github.com/KogarashiNetwork/core)|[![crates.io badge](https://img.shields.io/crates/v/zero-crypto.svg)](https://crates.io/crates/zero-crypto)|Cryptography primitive implementation `Field`, `Curve` and `Pairing`, `Fft`, `Kzg`.|
|[**zero-jubjub**](https://github.com/KogarashiNetwork/jubjub)|[![crates.io badge](https://img.shields.io/crates/v/zero-jubjub.svg)](https://crates.io/crates/zero-jubjub)|Twisted Edward curve `jubjub` implementation used for zero-knowledge circuit arithmetic domain.|
|[**zero-bls12-381**](https://github.com/KogarashiNetwork/bls12_381)|[![crates.io badge](https://img.shields.io/crates/v/zero-bls12-381.svg)](https://crates.io/crates/zero-bls12-381)|Pairing-friendly `bls12 381` curve used for polynomial operation arithmetic domain.|
|[**zero-elgamal**](https://github.com/KogarashiNetwork/elgamal)|[![crates.io badge](https://img.shields.io/crates/v/zero-elgamal.svg)](https://crates.io/crates/zero-elgamal)|Additive homomorphic ElGamal encryption based on `jubjub` curve.|

## Follow Us

[Website](https://kogarashi-network.com/) | [Twitter](https://twitter.com/KogarashiCrypto) | [Discord](https://discord.gg/g3q7tsHKTd) | [Github](https://github.com/KogarashiNetwork) | [Documentation](https://kogarashinetwork.github.io/Kogarashi/)
