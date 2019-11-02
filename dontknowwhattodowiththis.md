This is my first RFC. It aims to solve a small problem with a simple solution
and you can probably already tell what it does when reading the example in
footnote[^3]. Here it is: [RFC 2782: impl-only glob imports][rfc2782]

[^3]:
```rust
use rayon::prelude::trait * as _;
```
