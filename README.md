# Ziglings
## Like Rustlings, but in Zig

Welcome to Ziglings! This project contains a series of tiny
broken programs (and one nasty surprise).  By fixing them, you'll
learn how to read and write [Zig](https://ziglang.org/) code.

![Ziglings](images/ziglings.jpg "Ziglings")

This project was directly inspired by the brilliant and fun
[rustlings](https://github.com/rust-lang/rustlings)
project for the [Rust](https://www.rust-lang.org/) language.
Indirect inspiration comes from [Ruby Koans](http://rubykoans.com/)
and the Little LISPer/Little Schemer series of books.

## What's Covered

The primary goal for Ziglings is to cover the core Zig language.

- Zig Core Language
- Zig Standard Library

## Getting Started
Install a development build of the Zig compiler. (See the "master" section of the downloads page.)

Verify the installation and build number of zig like so:

```
$ zig version
```

0.12.0-dev.xxxx+xxxxxxxxx

Clone the ziglings repository with Git

Then run zig build and follow the instructions to begin!

```bash
$ zig build
```

## Troubleshooting

If it doesn't build nor run the tests, it means you are too far in the future and above "0.12.0-dev.2618" version. At time of writing, zig is not stable yet and breaking changes are to be expected.