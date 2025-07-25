# MIPS Communication With IO By UART Protocol In Logisim

A custom UART-inspired serial communication protocol implementation for a single-cycle MIPS processor in Logisim, enabling I/O device synchronization.

## Project Overview

This project implements:
- A simplified UART-like protocol for MIPS processors
- Hardware-level synchronization between:
  - Keyboard input
  - TTY text display 
  - LED output
- Custom MIPS instructions for I/O operations
- Serial data transfer using shift registers

## Key Features

- Added LED, TTY, and KB operations to MIPS ISA 
- MIPS-I/O Communication: Control LEDs, TTY display, and keyboard input using custom MIPS instructions programmed in ROM.
- Ready-to-Run Demos: In test fibo2 you can Type "fib" to display the sequence on TTY and light up LEDs with Fibonacci numbers (1, 1, 2, 3, 5...).
