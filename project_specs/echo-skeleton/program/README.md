### Environment Setup
1. Install Rust from https://rustup.rs/
2. Install Solana from https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool

### Build and test for program compiled natively
```
$ cargo build
$ cargo test
```

### Build and test the program compiled for BPF
```
$ cargo build-spf
$ cargo test-spf
```

### Reference
https://github.com/johhnsmmith198/solana-bootcamp-lectures/commit/cb4528b89d60cafbf2ee48f540793bf175906bfc#diff-728e563e304dbd0faac48dc9f65fc95919c9177eb38a6808ec8bb92910d4c202
