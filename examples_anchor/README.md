# README

### Fix for error[E0658]: use of unstable library feature 'build_hasher_simple_hash_one'
Downgrade ahash
```
cargo build
cargo update -p ahash@0.8.7 --precise 0.8.6
cargo build
cargo deploy
```
Change the IDs and run again
```
cargo build
cargo deploy
```
Run tests
```
yarn install
cargo run test1
cargo run test2
```