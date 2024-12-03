## Rust on Espressif microcontrollers

This organization is home to several projects enabling the use of the [Rust programming language] on various SoCs and modules produced by [Espressif Systems].

If you are just getting started writing Rust for ESP devices, please first read [The Rust on ESP book].

For a curated list of resources for development including tools and projects, see [Awesome ESP Rust].

### Hardware Abstraction Layer

We offer two choices for **H**ardware **A**bstraction **L**ayers:

| Repository           | Description                                                | Support status |
| -------------------- | ---------------------------------------------------------- |----------------|
| [esp-rs/esp-hal]     | _Without_ support for the Rust standard library (`no_std`) | ![Support status](https://img.shields.io/badge/Support_status-Official-green?style=flat-square) |
| [esp-rs/esp-idf-hal] | _With_ support for the Rust standard library (`std`)       | ![Support status](https://img.shields.io/badge/Support_status-Community-blue?style=flat-square) |

### Build Tools

This organization contains a fork of the Rust compiler with added support for the Xtensa ISA. Pre-built binaries for said compiler fork are additionally provided for most common operating systems and architectures.

| Repository          | Description                                                             |
| ------------------- | ----------------------------------------------------------------------- |
| [esp-rs/rust]       | Rust compiler fork with Xtensa support                                  |
| [esp-rs/rust-build] | Pre-built binaries of the Rust compiler fork, plus installation scripts |


[rust programming language]: https://www.rust-lang.org/
[espressif systems]: https://www.espressif.com/
[the rust on esp book]: https://esp-rs.github.io/book/
[Awesome ESP Rust]: https://github.com/esp-rs/awesome-esp-rust

[esp-rs/rust]: https://github.com/esp-rs/rust
[esp-rs/rust-build]: https://github.com/esp-rs/rust-build
[esp-rs/esp-idf-hal]: https://github.com/esp-rs/esp-idf-hal
[esp-rs/esp-hal]: https://github.com/esp-rs/esp-hal
