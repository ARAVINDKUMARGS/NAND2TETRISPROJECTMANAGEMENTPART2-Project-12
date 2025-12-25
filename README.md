# NAND2TETRISPROJECTMANAGEMENTPART2-Project-12
PROJECT-12

# NAND2TETRISPROJECTMANAGEMENTPART2-Project-12

## Project 12 – Final Integration

**Project Code:** PROJECT12
**Course:** Build a Modern Computer from First Principles (Nand2Tetris Part II)
**Institution:** Hebrew University of Jerusalem

---

## Overview

Project 12 is the **culmination of Nand2Tetris Part II**, integrating all previous projects to build a **fully functioning computer system**. This project demonstrates **end-to-end execution** of Jack programs: from high-level source code, through compilation to VM code, system calls, and hardware execution on the Hack platform.

The project validates the **compiler, OS routines, VM translation, and CPU emulator**, producing a complete software-hardware pipeline.

---

## Objectives

* Compile Jack programs into VM code (from Project 8).
* Execute VM code with OS routines (Projects 9 & 10).
* Run compiled programs in the **CPU Emulator** and **Hardware Simulator**.
* Test full integration with user programs, including I/O, arithmetic, and control flow.
* Verify correctness and performance of the **entire computer system**.

---

## Folder Structure

```
Project12/
│── README.md
│── src/
│   └── CompilerOutput/
│       └── Main.vm
│── lib/
│   └── Sys.vm
│── test/
│   ├── PongGame/
│   ├── ArrayTest/
│   └── StringTest/
│── docs/
│   └── FinalIntegrationGuide.pdf
```

---

## Getting Started

### Step 1: Compile Jack Programs

```bash
cd Project12/src
java JackCompiler CompilerOutput/Main.jack
```

* Produces `.vm` files in `CompilerOutput/`.

### Step 2: Load OS Routines

* Copy `Sys.vm` from Project 10 into the program directory.

### Step 3: Run VM Programs

1. Open the **VM Emulator**.
2. Load `.vm` files together with `Sys.vm`.
3. Observe program execution and verify outputs.

### Step 4: Test on Hardware Emulator

* Load compiled `.hack` programs into the **Hardware Simulator**.
* Verify correct operation of I/O routines, arithmetic, and control flow.

---

## Supported Features

### Full Jack Language

* Variables, arrays, strings, subroutines
* Control structures: `if`, `while`, `do`, `return`

### OS Routines

* Memory management, stack operations
* Screen and keyboard I/O
* Exception handling

### Hardware Execution

* Compatible with CPU Emulator and Hack platform
* Correct execution of arithmetic, logical, and control flow operations

### Example

**Pong Game (`PongGame/Main.jack`):**

* Implements a simple Pong game using Jack language features and OS routines.
* Output is displayed on the Hardware Simulator screen.

---

## Notes

* Project 12 **validates the full system**: compiler + OS + VM + CPU.
* Thorough testing is required to ensure **all components work seamlessly**.
* Demonstrates the power of building a modern computer from first principles.

---

## Author

**Aravind Kumar GS**
Email: `aravindkumar06062006@gmail.com`

---

## License

Educational purposes only. Do not distribute or claim as your own work.
