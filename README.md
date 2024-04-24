# serialize-store-test

## Purpose

1. Can we serialize wasmtime Store?
2. Can we write it to disk?
3. Can we restore it?

## Usage

```bash
git clone git@github.com:nick1udwig/serialize-store-test.git
cd serialize-store-test/wasi
cargo build --bin wasi --target wasm32-wasi
cd ..
cargo run
```
