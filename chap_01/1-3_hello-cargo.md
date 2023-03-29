# Hello cargo!

``` shell
$ cargo new hello_cargo
     Created binary (application) `hello_cargo` package
$ cd hello_cargo
```

Good to know:

> Git files won’t be generated if you run cargo new within an existing Git repository; you can override this behavior by using `cargo new --vcs=git`.

``` shell
$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.04s
     Running `target/debug/hello_cargo`
Hello, world!
```

A summary from the book:

> Let’s recap what we’ve learned so far about Cargo:
>
>    We can create a project using `cargo new`.
>    We can build a project using `cargo build`.
>    We can build and run a project in one step using `cargo run`.
>    We can build a project without producing a binary to check for errors using `cargo check`.
>    Instead of saving the result of the build in the same directory as our code, Cargo stores it in the `target/debug directory`.
>    When your project is finally ready for release, you can use `cargo build --release` to compile it with optimizations. This command will create an executable in `target/release` instead of `target/debug`.
