# daggy2 [![Actions Status](https://github.com/azriel91/daggy2/workflows/daggy2/badge.svg)](https://github.com/azriel91/daggy2/actions) [![Crates.io](https://img.shields.io/crates/v/daggy.svg)](https://crates.io/crates/daggy) [![Crates.io](https://img.shields.io/crates/l/daggy.svg)](https://github.com/azriel91/daggy2/blob/master/LICENSE-MIT) [![docs.rs](https://docs.rs/daggy2/badge.svg)](https://docs.rs/daggy2/)

> [!NOTE]
> This is a fork of [`daggy`](https://github.com/mitchmindtree/daggy), with updated dependencies. This fork can be abandoned when `daggy` is able to be maintained.

A [directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph) data structure for Rust.

It is Implemented on top of [petgraph](https://github.com/petgraph/petgraph)'s [Graph](https://docs.rs/petgraph/latest/petgraph/graph/struct.Graph.html) data structure and attempts to follow similar conventions where suitable.


Usage
-----

Please see the [tests directory](https://github.com/azriel91/daggy2/tree/master/tests) for some basic usage examples.

Use daggy in your project by adding it to your Cargo.toml dependencies like so:

```toml
[dependencies]
daggy2 = "0.8.1"
```


License
-------

Dual-licensed to be compatible with the petgraph and Rust projects.

Licensed under the Apache License, Version 2.0 http://www.apache.org/licenses/LICENSE-2.0 or the MIT license http://opensource.org/licenses/MIT, at your option. This file may not be copied, modified, or distributed except according to those terms.

