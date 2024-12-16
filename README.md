# Rust Raw Pointer Vector Modification Bug
This repository demonstrates a common error in Rust involving the unsafe use of raw pointers with vectors.  Modifying a vector through a raw pointer after the vector's capacity has been exceeded can lead to unexpected behavior, including crashes or data corruption.

The `bug.rs` file shows the erroneous code. The `bugSolution.rs` demonstrates the safe and correct way to modify vector elements.