Prerequisites
Before getting started, ensure you have the following prerequisites installed:

Rust: rustc 1.77.0-nightly
QEMU: Install QEMU
Getting Started
Clone the Repository:

bash
Copy code
https://github.com/AffanPathan02/standalone-kernel.git
cd standalone-kernel
Build the Project:

bash
Copy code
cargo build
Run the Kernel in QEMU:

bash
Copy code
cargo run
This command will compile the project and launch QEMU to run the kernel.

Project Structure
src/: Contains the source code for the kernel.
main.rs: Entry point for the kernel.
vga_buffer.rs: Module for handling VGA buffer operations.
