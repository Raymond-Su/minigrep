# Minigrep
A simple rust program that clones the functionality of egrep

## How to run
Using Rust's package manager we can simply run
```
cargo run [selector] [file]
```
where
- `selector` is the string to be matched 
- `file` is the path to a text file

Case sensitivity can be toggled using the env variable `CASE_INSENSITIVE`
