# Eventually-rs
Unable to install eventually-rs on Windows 11, and rust nightly.

```nushell
2025-04-09T18:24:28.2473852+08:00 ERROR FetchBuildDataError: error[E0432]: unresolved import `serde::export`
  --> C:\Users\benji\.cargo\registry\src\index.crates.io-1949cf8c6b5b557f\refinery-core-0.3.2\src\runner.rs:11:12
   |
11 | use serde::export::Formatter;
   |            ^^^^^^ could not find `export` in `serde`


For more information about this error, try `rustc --explain E0432`.

error: could not compile `refinery-core` (lib) due to 1 previous error
```