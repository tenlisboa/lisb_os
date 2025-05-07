# Lisb_OS (Micro-Kernel)

Have you challenge yourself enough to have complete trust on what you are capable of? Well, this is my "green card" to a zone of self respect never reached before by myself.

Building an Micro-Kernel, with real functions, drivers and stuff is pretty difficult to digest previouslly (nd currently too).

So, as a person that loves challenge, real challenge, I am creating one.

You can see a more detailed "blog" or something on the Wiki -> https://github.com/tenlisboa/lisb_os/wiki

## If you want to run on your machine

### Here's some pre-reqs

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

And finally:
```sh
cargo run
```

__If this does not work, create an issue and I'll check it out__
