
# MIPS Assembly Emulator 

A simplified MIPS processor simulator built in C for CDA3103C: Computer Organization.  This project emulates the datapath, control signals, and instruction-level behavior of a basic MIPS processor using a modular C implementation.

simulates key components of the MIPS architecture, focusing on:
- Instruction fetch and decode
- ALU operations and control logic
- Memory reads/writes
- Register file reads/writes
- Program counter updates
- Sign extension and branching

The simulator demonstrates the core principles of how a MIPS datapath executes instructions, simulating instruction behavior cycle-by-cycle on a Unix-based system.

## Key Files

- `spimcore.c` – Core logic for datapath and control signal behavior
- `spimcore.h` – Header definitions
- `project.c` – Entry point and integration for testing
- `input_file.asc` – Sample instruction set for simulation
- `test_results.txt` – Expected output for validation

## How to Compile and Run

```bash
gcc -o spimcore project.c spimcore.c
./spimcore
# assembly-emulator
