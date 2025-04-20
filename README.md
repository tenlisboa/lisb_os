## Pre-requisites

Nightly Rust version:
```sh
rustup override set nightly
rustc --version
```

Rust components
```sh
rustup component add rust-src llvm-tools-preview
```

Tools for BIOS bootimage creation
```sh
cargo install bootimage
```

For easily running the OS
```sh
brew install qemu
```
