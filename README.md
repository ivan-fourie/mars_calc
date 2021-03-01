# mars_calc

A small program demonstrating the following concepts in Rust:
 * Basic data types
 * Functions
 * Macros
 * Mutability
 * The Standard Library
 * Ownership
 * References and Borrowing

Also explored Ownership and Borrowing in GDB.

**What to know:**

All variables are immutable by default

The three ownership rules are:
 * Each value in Rust is owned by a variable
 * When the owner goes out of scope the value will be deallocated
 * There can only be one owner at a time

References can be either mutable or immutable
There can be multiple immutable references at the same time
Rust supports both signed and unsigned integers.

**Getting Rust debugging going in VSCode:**
 * Install - C/C++ (Windows) & CodeLLDB (Linux) extentions
 * Debug -> Add Config - C++ (Windows) & LLDB (Linux)
 * It detecst Config.toml, save the launch.json and good to go
 * src: https://www.forrestthewoods.com/blog/how-to-debug-rust-with-visual-studio-code/