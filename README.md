# Asynchronous FIFO
Verilog based Asynchronous FIFO Design for safe data transfer between two clock domains. Includes full/empty logic, CDC Techniques, testbench, and simulation support
This project implements an asynchronous FIFO using Verilog/SystemVerilog. It supports write and read operations in different clock domains and includes testbenches for simulation.

## Features
- Dual clock domain support
- Full and empty flag logic
- Parameterizable depth and width
- Synthesized using Cadence Genus tool
- Power, Area, and RTL Schematic analysis included

## Files
- `FIFO.v.v`: Main FIFO module
- `FIFO_tb.v`: Testbench
