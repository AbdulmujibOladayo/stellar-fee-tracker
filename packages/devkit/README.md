# stellar-devkit

Developer toolkit for testing and simulating the Stellar fee tracker.

This crate was reset and is being rebuilt from scratch. Work is tracked as a sequence of
issues labeled `devkit`, titled "Devkit #1" through "Devkit #125", each building on the one
before it, starting from this foundation.

## Development

```bash
cargo build -p stellar-devkit
cargo test -p stellar-devkit
cargo clippy -p stellar-devkit --all-targets --all-features -- -D warnings
cargo fmt --check -p stellar-devkit
```
