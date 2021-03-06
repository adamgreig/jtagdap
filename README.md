# JTAGDAP

[![crates.io](https://img.shields.io/crates/v/jtagdap.svg)](https://crates.io/crates/jtagdap)
[![docs.rs](https://docs.rs/jtagdap/badge.svg)](https://docs.rs/jtagdap)
![CI](https://github.com/adamgreig/jtagdap/workflows/CI/badge.svg)

JTAGDAP is a library providing arbitrary JTAG access to CMSIS-DAP compatible
probes.

For application binaries, see:

* [ecpdap](https://github.com/adamgreig/ecpdap), which uses jtagdap to provide
  JTAG configuration of ECP5 FPGAs, including programming attached SPI flash,
* [spidap](https://github.com/adamgreig/spidap), which uses jtagdap to provide
  direct access to SPI flash memory using a JTAG port.

## Licence

jtagdap is licensed under either of

* Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.
