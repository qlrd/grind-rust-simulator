# grind-rust-simulator

This script is for educational-only purposes and is not intended for production.

It performs a proof-of-work's simulation of genesis block given:

- `dificulty_hex`: `0x000000001`;
- `target`: `0x00000000ffff0000000000000000000000000000000000000000000000000000`
- `prefix`: `Hello Wolrd!`
- `nonce`: it receive an increment until find a value less than `target`;

## Install

```bash
git clone https://github.com/qlrd/grind-rust-simulator
```

## Build

```bash
cargo build
```

## Run

```bash
./target/debug/grind-rust-simulator
```

## WARNING

This will increase CPU usage. For best performance, close all unused programs.

So far, tested on:

- MacOS M2 (arm64): `CPU ~= 75-80%` and found hash in ``
- 12th gen i5, 16 threads: `CPU ~= ?%` and found hash in `239.49s` 
