# Set up VS Code to work with Embedded Rust

- Windows 7 x64;
- VS Code 1.64.2;
- Rust 1.24.3;
- OpenOCD x64 0.11.0+dev;
- GNU Arm Embedded Toolchain 10.3-2021.10 x32.

Before, don't forget:
```
cargo install cargo-binutils
rustup component add llvm-tools-preview
rustup target add thumbv7em-none-eabihf
```

Avaliable tasks: release (default: ctrl+B) or debug.
To use debug mode (F5): insert breakpoint -> start debugging.

Tested on NUCLEO-H743ZI development board (simple hello-world example included)
