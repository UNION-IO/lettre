# lettre
[![Build Status](https://travis-ci.org/lettre/lettre.svg?branch=master)](https://travis-ci.org/lettre/lettre)
[![Build status](https://ci.appveyor.com/api/projects/status/mpwglemugjtkps2d/branch/master?svg=true)](https://ci.appveyor.com/project/amousset/lettre/branch/master)
[![Crate](https://img.shields.io/crates/v/lettre.svg)](https://crates.io/crates/lettre)
[![Docs](https://docs.rs/lettre/badge.svg)](https://docs.rs/lettre/)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Gitter](https://badges.gitter.im/lettre/lettre.svg)](https://gitter.im/lettre/lettre?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

This is an email library written in Rust.

## Features

Lettre provides the following features:

* Multiple transport methods
* Unicode support (for email content and addresses)
* Secure delivery with SMTP using encryption and authentication
* Easy email builders

## Example

See https://github.com/lettre/lettre/blob/master/lettre_email/examples/smtp.rs
for a simple example of how to build and send an email.

## Documentation

Released versions:

* [latest](https://docs.rs/lettre/)
* [v0.7.0](https://docs.rs/lettre/0.7.0/lettre/)
* [v0.6.2](https://docs.rs/lettre/0.6.2/lettre/)
* [v0.6.1](https://docs.rs/lettre/0.6.1/lettre/)
* [v0.6.0](https://docs.rs/lettre/0.6.0/lettre/)
* [v0.5.1](https://docs.rs/lettre/0.5.1/lettre/)

## Install

This library requires rust 1.18 or newer.
To use this library, add the following to your `Cargo.toml`:

```toml
[dependencies]
lettre = "0.7"
```

## Testing

The tests require an open mail server listening locally on port 2525 and the `sendmail` command.

## Code of conduct

Anyone who interacts with Lettre in any space, including but not limited to
this GitHub repository, must follow our [code of conduct](https://github.com/lettre/lettre/blob/master/CODE_OF_CONDUCT.md).

## License

This program is distributed under the terms of the MIT license.

See [LICENSE](./LICENSE) for details.
