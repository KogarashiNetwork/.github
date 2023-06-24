# Kogarashi [![Discord](https://dcbadge.vercel.app/api/server/g3q7tsHKTd?style=social&compact=true)](https://discord.gg/g3q7tsHKTd)

**Kogarashi Network** is a Dapp platform that allows smart contracts to access to the Internet information resource.

<div align="center">
    <img alt="image" src="https://github.com/KogarashiNetwork/tls_notary/assets/39494661/dafe9630-78bd-4a5b-a15c-d15f5a83cb18">
</div>

## Motivation

There are two motivations for this platform.

1. Increase data type that can deal with Dapp
2. Manage both advanced features and simple usability

Firstly, typical blockchains can deal with only cryptocurrency balance and crypto-assets. We innovate the data-getting process and bring off-chain data with trustless and low cost. Dapp on our platform can deal with various types of data from off-chain and realize a completely new use case.

Secondly, typical blockchains are inefficient to process the latest cryptography scheme like zero-knowledge proof and homomorphic encryption. We innovate blockchain runtime and realize simple usage and fast process. Users can use various simple-to-use and a little gas cost functionalities.

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
