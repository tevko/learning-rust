## Notes on Learning rust

### Following https://doc.rust-lang.org/beta/book/title-page.html

- using a ! means that you’re calling a macro instead of a normal function in rust
`println!` is a macro, while `println` is a function

- `rustc` is the command that compiles a file and generates a binary
- Cargo is Rust’s package manager and build system
- Cargo handles building code, as well as downloading and installing dependencies
- Cargo comes preinstalled on official channels

```
$ cargo new hello_cargo
$ cd hello_cargo
```

- above command creates a new directory called hello_cargo ready for rust development and with a newly initiated git repository. The default program is a hello world program
- the TOML file is the configuration file for the project
- packages (crates) are listed in this TOML file
- Cargo expects your source files to live inside the src directory
