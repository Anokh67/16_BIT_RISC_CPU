# 16_BIT_RISC_CPU --> I will be creating my own 16 bit cpu


First, I will be creating the ALU it will have the following operations:
1. ADDER
2. SUBTRACTOR
3. AND
4. OR
Since this is only an RISC CPU, it will only have 4 operations. I will be using a 4:1 multiplexer to select a specific operation and compute the results to be output. To make an adder I made a truth table:
| Cin | A | B | Cout | S |
|------|------|------|------|------|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 |
| 0 | 1 | 0 | 0 | 1 |
| 0 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 0 | 1 |
| 1 | 0 | 1 | 1 | 0 |
| 1 | 1 | 0 | 1 | 0 |
| 1 | 1 | 1 | 1 | 1 |


