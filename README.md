# RISC-V Single Cycle Processor using Verilog HDL

## Overview

This project implements a 32-bit RISC-V Single Cycle Processor using Verilog Hardware Description Language (HDL). The processor executes each instruction in a single clock cycle and demonstrates the fundamental concepts of computer architecture and processor design.

The design supports instruction fetch, instruction decode, execution, memory access, and write-back operations within a single cycle.

## Features

* 32-bit RISC-V Architecture
* Single Cycle Processor Design
* Verilog HDL Implementation
* Instruction Fetch and Decode
* Register File with 32 Registers
* Arithmetic Logic Unit (ALU)
* Data Memory and Instruction Memory
* Immediate Generator
* Branch Handling Logic
* Simulation and Verification

## Processor Architecture

The processor consists of the following modules:

### Program Counter (PC)

Stores the address of the current instruction and updates it every clock cycle.

### Instruction Memory

Stores program instructions and provides instructions based on the PC value.

### Register File

Contains 32 general-purpose registers used for storing operands and computation results.

### Control Unit

Generates control signals such as:

* RegWrite
* MemRead
* MemWrite
* Branch
* ALUSrc
* MemToReg

### Arithmetic Logic Unit (ALU)

Performs arithmetic and logical operations:

* ADD
* SUB
* AND
* OR
* XOR

### Immediate Generator

Generates immediate values for I-Type, S-Type, and B-Type instructions.

### Data Memory

Handles load and store operations.

### Branch Unit

Calculates branch target addresses and controls program flow.

## Supported Instruction Types

* R-Type Instructions
* I-Type Instructions
* Load Instructions
* Store Instructions
* Branch Instructions

## Instruction Execution Flow

Instruction Fetch
→ Instruction Decode
→ Execute
→ Memory Access
→ Write Back

## Tools Used

* Verilog HDL
* ModelSim / Vivado Simulator
* RISC-V ISA
* Computer Architecture Concepts

## Simulation Results

Simulation verifies:

* Correct instruction fetching
* Proper register updates
* Accurate ALU operations
* Successful load/store operations
* Correct branch execution

## Applications

* Computer Architecture Education
* Processor Design Learning
* Embedded Systems Research
* FPGA and ASIC Development

## Future Improvements

* Pipelined RISC-V Processor
* Hazard Detection Unit
* Forwarding Unit
* Cache Memory Integration
* Support for Additional RISC-V Instructions

## References

1. Patterson & Hennessy – Computer Organization and Design (RISC-V Edition)
2. RISC-V Instruction Set Manual
3. M. Mano – Computer System Architecture

## Author

Rajesh Joshi

