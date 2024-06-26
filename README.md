# Mini - Risc - 32-bit RISC Processor Design

## Overview
This project implements a custom 32-bit RISC processor, inspired by the MIPS architecture. It was developed as part of the Computer Organization Laboratory course under the guidance of Prof. Indranil Sengupta, Prof. Sarani Bhattacharya, and Prof. Soumyajit Dey.

## Features
- 32-bit RISC architecture
- Custom Instruction Set Architecture (ISA) with 32 instructions
- Multi-cycle execution pipeline
- Implemented in Verilog HDL
- Optimized for Nexys A7-100T FPGA board

## Components
- ALU (Arithmetic Logic Unit)
- Control Unit
- Register File
- Memory Modules
- Python-based Assembler

## Instruction Set
The custom ISA includes:
- Arithmetic operations
- Bitwise operations
- Branch instructions
- Memory load-store operations

## Assembler
A custom assembler written in Python translates assembly code into machine instructions executable by the processor. It features:
- Mnemonic mapping for opcodes
- Support for all 32 instructions in the custom ISA

## FPGA Implementation
The processor is synthesized and implemented on a Nexys A7-100T FPGA board, demonstrating practical hardware deployment.

## Repository Structure
- `/verilog`: Contains all Verilog HDL files for processor components
- `/assembler`: Python scripts for the custom assembler
- `/docs`: Documentation including ISA specifications and design details
- `/testbenches`: Verilog testbenches for component verification
- `/fpga`: Files specific to FPGA implementation

## Getting Started
1. Clone the repository
2. Navigate to the `/verilog` directory to view the processor implementation
3. Check the `/assembler` directory for the Python-based assembler
4. Refer to the documentation in `/docs` for detailed usage instructions

## Requirements
- Verilog HDL simulator (e.g., ModelSim, Icarus Verilog)
- Python 3.x for running the assembler
- Xilinx Vivado for FPGA synthesis and implementation

## Contributors
[Your Name]

## Acknowledgements
Special thanks to Prof. Indranil Sengupta, Prof. Sarani Bhattacharya, and Prof. Soumyajit Dey for their guidance throughout this project.
