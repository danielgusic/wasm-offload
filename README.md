# WASM Offload

This project provides a set of crates to offload Rust functions to a WebAssembly
runtime. Just annotate any functions you want to offload with `#[offload]` and
define your `OffloadTarget` and your code will seamlessly run in WebAssembly. (Note: The functions you want to offload must be located in a library at the moment.)
An implementation for [wasmtime](https://github.com/bytecodealliance/wasmtime) is already provided.
