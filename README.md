cis4930-project-1
=================

## Building

1. Install Rust 64-bit 0.12.0 and Cargo nightly
2. Install CSFML 2.1*
3. Run `cargo build`
4. Run `cargo run`**

*Note: if installed manually, ensure that CSFML libs are discoverable by the linker (e.g., on Windows, `$env:LIBRARY_PATH = "C:\CSFML-2.1-windows-64bits\CSFML-2.1\lib\gcc"`)

**Note: if installed manually, ensure that CSFML runtime libs are discoverable by the executable (e.g., on Windows, the DLLs from CSFML can be copied to the directory in which the executable resides)
