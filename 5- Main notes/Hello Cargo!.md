
Tags: [[Rust]]

2024-12-17:14:20

> Cargo is Rust’s build system and package manager. Most Rustaceans use this tool to manage their Rust projects

> `cargo new hello_cargo` will create a new cargo project that has 2 things in it 
> Cargo.toml and src directory 

> Using cargo new will create a new repo where it was called , but if there is a repo in the folder 
> it won't create any repos , we can overwrite this by using `cargo new --vcs=git`

`cargo new --help` will give you all available options

## Cargo.toml
```
[package]
name = "hello_cargo"
version = "0.1.0"
edition = "2021"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]

```
`[package]` section heading means that the following statements are configuring a package.
Next three lines are configuration information needed for Cargo to successfully compile my program : name , version and edition of rust to use.

`[dependencies]` start of a section where you list all of your code dependencies.

> Packages in Rust are called *Crates*

> Cargo expect source code in the *src directory* , any other needed config files or license info are placed outside of *src*.

> To migrate a code from not using Cargo to using Cargo just put the source code in *src* and create an appropriate `Cargo.toml` file or just use `cargo init` and it will create the file for you.

`$ cargo build` will create an executable file in target/debug/exectuable_name , Cargo puts the executable in the debug directory because the default build is a debug build .
Also it creates a file called `_Cargo.lock_`, This file keeps track of the exact versions of dependencies in your project.
 You won’t ever need to change this file manually; Cargo manages its contents for you.

`$ cargo run` this command will build and run the executable in one command.

> Note : Cargo only rebuild your project if any file is modified in your source code .

`$ cargo check` this command checks your source code to make sure it compiles ( but without spitting an executable).

> Using check feature periodically as a good practice (it's faster than build ).

> use `cargo build --release` when your code is ready for release.
> . This command will create an executable in _target/release_ instead of _target/debug_.(it will do all optimizations possible for release).

> Benchmark note : If you’re benchmarking your code’s running time, be sure to run `cargo build --release` and benchmark with the executable in _target/release_.

> debug builds take less time than release builds because there will be no optimizations 

## To work with codes on Github you may do the following :
```
$ git clone example.org/someproject
$ cd someproject
$ cargo build

```
