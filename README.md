# Skia Binaries

[This repository's releases tab](https://github.com/rust-skia/skia-binaries/releases) contains binary builds for Skia, the skia-bindings library, and the Rust bindings `src/bindings.rs`. These files are generated on the CI server in the [rust-skia repository](https://github.com/rust-skia/rust-skia) for each commit to the master branch.

If the platform, configuration, and feature set matches, binaries are automatically downloaded by cargo crates that were generated with the same hash. If no binary is found, Skia, the skia-bindings library, and the `src/bindings.rs` file will be generated when the cargo package is built as a dependency.