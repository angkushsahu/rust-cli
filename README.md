# RUST CLI

A simple command line interface using rust from the [rust lang book](https://doc.rust-lang.org/book/). Learning rust from the Rust lang book by building a minigrep version for searching a particular word from a given text file.

## Commands

Print the lines containing the words you are searching for.

format: cargo run \<search-query> \<file-name>

```bash
cargo run to poem.txt
```

*Through the above query, we are searching for the word `to` inside the `poem.txt` file.*

Print the lines containing the words you are searching for inside a file which will be created in the root directory of the project.

format: cargo run \<search-query> \<file-name> > \<output-file-name>

```bash
cargo run to poem.txt > output.txt
```

*Through the above query, we are searching for the word `to` inside the `poem.txt` file and print the available lines in a file*

## Tech Stack

![Rust](https://skillicons.dev/icons?i=rust&theme=dark)
