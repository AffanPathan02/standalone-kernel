# Standalone Kernel

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

Rust: rustc 1.77.0-nightly

QEMU: Follow the instructions to install QEMU for your operating system: https://www.qemu.org/
## Getting Started

Clone the Repository:

```bash
  
git clone https://github.com/AffanPathan02/standalone-kernel.git
cd standalone-kernel
```



Build the Project:
```bash
cargo build
```

Run the Kernel in QEMU:
```bash
cargo run
```

This command will compile the project and launch QEMU to run the kernel.

## Project Structure

src/: Contains the source code for the kernel.
main.rs: Entry point for the kernel.
vga_buffer.rs: Module for handling VGA buffer operations.
