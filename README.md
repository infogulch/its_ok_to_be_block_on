# It's ok to be `block_on`

Sometimes you just need `block_on`, without an entire bloated futures runtime.

It's ok.

This crate copies and exports the per-thread `block_on` implementation (and
license) from the [`futures` package](https://github.com/rust-lang/futures-rs),
minimizing the size of the code and the dependency tree.

## Does it work?

It compiles. ¯\\_(ツ)_/¯
