# mini-grep
Grep is a command-line tool commonly used in Unix and similar operating systems to search and process text or patterns within files. The term "grep" stands for Global Regular Expression Print.

This Rust implementation is inspired by an exercise in Chapter 12 of The Rust Programming Language book.

## How to Use
The program requires two arguments:
1. The text you want to search for
2. The file where the search will be performed

As an example,
```sh
cargo run -- rust poem.txt > output.txt
```
Will search for the string `rust` in `poem.txt` and write the lines containing that string to output.txt.