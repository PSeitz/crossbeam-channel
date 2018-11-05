## NOTE: This crate has been moved into the [crossbeam](https://github.com/crossbeam-rs/crossbeam) repository.

Do not use this repository.

# Multi-producer multi-consumer channels for message passing

[![Build Status](https://travis-ci.org/crossbeam-rs/crossbeam-channel.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam-channel)
[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg)](https://github.com/crossbeam-rs/crossbeam-channel)
[![Cargo](https://img.shields.io/crates/v/crossbeam-channel.svg)](https://crates.io/crates/crossbeam-channel)
[![Documentation](https://docs.rs/crossbeam-channel/badge.svg)](https://docs.rs/crossbeam-channel)

This library is an alternative to [`std::sync::mpsc`] with more features and better performance.

[`std::sync::mpsc`]: https://doc.rust-lang.org/std/sync/mpsc/index.html

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies]
crossbeam-channel = "0.3"
```

Next, add this to your crate:

```rust
#[macro_use]
extern crate crossbeam_channel;
```

The minimum required Rust version is 1.26.

## License

Licensed under the terms of MIT license and the Apache License (Version 2.0).

See [LICENSE-MIT](LICENSE-MIT) and [LICENSE-APACHE](LICENSE-APACHE) for details.
