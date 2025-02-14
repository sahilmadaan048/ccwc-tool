# Custom wc Utility - Rust

A Rust-based implementation of the Unix `wc` (word count) command, which counts the number of lines, words, and characters in a file.

## Features

- Supports counting:
  - Lines
  - Words
  - Characters
- Handles multiple files as input
- Efficient file reading and parsing
- Error handling for invalid files and edge cases

## Installation

Ensure you have Rust installed. You can install Rust using [rustup](https://rustup.rs/).

```sh
git clone https://github.com/sahilmadaan048/ccwc-tool.git
cd ccwc-tool
cargo build --release
