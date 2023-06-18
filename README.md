# CheatSheet

## rustc

### Compile Code

```bash
rustc main.rs
```

## Cargo

### New Project

```bash
cargo new my_project
```

### Build Project

```bash
cargo build
```

Executable will be found at `target/debug/my_project`.

### Run Project

```bash
cargo run
```

### Check Project

This won't create a binary, but will check if the code compiles.

```bash
cargo check
```

### Building for Release

```bash
cargo build --release
```

This will create an optimized binary.
Executable will be found at `target/release/my_project`.

### Update dependencies

```bash
cargo update
```

### Open docs

```bash
cargo doc --open
```

### Useful links

- [cargo doc](https://doc.rust-lang.org/cargo/)
- [cargo-watch](https://crates.io/crates/cargo-watch)

## Variables

```rust
let apples = 5; // immutable, default
let mut bananas = 5; // mutable
```
