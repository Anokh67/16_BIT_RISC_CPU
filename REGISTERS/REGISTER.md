# Overview

Registers are important because they temporarily store data and instructions that the CPU is currently using.  
This design includes a total of 6 registers, divided into two main categories: data registers and control registers.

### Data Registers

These registers are used to store and manipulate data during instruction execution:

1. **AccA** – Accumulator A
2. **AccB** – Accumulator B
3. **X_and_Y** – Shared register for auxiliary data or indexing



#### Control Registers

These registers manage the flow of instruction execution and memory access:

##### Program Counter (PC)

Holds the address of the next instruction the CPU will fetch from memory.

##### Memory Address Register (MAR)

Holds the address of the memory location in RAM that the CPU wants to access for a specific task, such as reading or writing data.

##### Instruction Register (IR)

Holds the actual instruction being executed by the CPU.


