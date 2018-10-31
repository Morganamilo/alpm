# libalpm (A wrapper round libalpm, the Arch Linux Package Manager)

This fork compiles on stable rust: [https://crates.io/crates/libalpm-fork](https://crates.io/crates/libalpm-fork)

The code is taken from here: https://github.com/jameslzhu/alpm  and published.
Unfortunately, the real author of the code didn't publish it.

Hopefully it'll be resolved over time and "jameslzhu" will publishe their code themselves.

----

I've changed some function names to match rust convention (e.g. no 'get',
`get_value() => value()`, no shortened words `desc => description`).

Currently linux-only.
