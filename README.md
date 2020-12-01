# Solutions to AOC 2020 in Rune

Rune is an embeddable dynamic programming language for Rust.

See: https://rune-rs.github.io

I'm using AoC 2020 as an ~~excuse~~ opportunity to really take the language for
a spin. So expect **many** updates for every day of AoC.

## Running the project

To run the solutions, you'll need to check out Rune, which requires Rust to
build.

So install Rust from https://rustup.rs, then clone the [Rune project] to a
different directory (`../rune` here, but you get to decide 😉):

```
git clone https://github.com/rune-rs/rune ../rune
```

You can then compile and run the Rune CLI with cargo:

```
cargo run --release --manifest-path ../rune/Cargo.toml --bin rune -- solutions/day01.rn
```

[Rune project]: https://github.com/rune-rs/rune
