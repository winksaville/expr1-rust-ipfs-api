# Experiment using rust ipfs-api

This cross compiles the program for aarch-64, Raspberry Pi 4.

## Prerequesites

Must have aarch64-unknown-linux-gnu installed.

On Arch Linux:
```
$ sudo pacman -S aarch64-linux-gnu-gcc
```

And then get the rust dependencies:
```
$ rustup target add aarch64-unknown-linux-gnu
```

## Compile and run

./deploy

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
