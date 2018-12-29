# Ferrugo

[![CircleCI](https://circleci.com/gh/maekawatoshiki/ferrugo.svg?style=shield)](https://circleci.com/gh/maekawatoshiki/ferrugo)
[![codecov](https://codecov.io/gh/maekawatoshiki/ferrugo/branch/master/graph/badge.svg)](https://codecov.io/gh/maekawatoshiki/ferrugo)
[![](http://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

Ferrugo is a JVM implementation written in Rust.

*Just for fun*

*JVM in Rust. Sounds great, isn't it?*

# Building from Source

## Building on Linux

1. Install Rust

  Run the command below and follow the onscreen instructions. 

```sh
curl https://sh.rustup.rs -sSf | sh
```

2. Use Rust Nightly

```sh
rustup override set nightly
```
3. Test 

```sh
cargo test
```

4. Build and Run

```sh
cargo run --release example/Hello.class
```

## Building on other platforms

I don't know. Maybe almost the same as Linux.
