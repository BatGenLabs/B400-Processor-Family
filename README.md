# B400-Processor-Family
A 4-bit Processor Family

# Overview

B400 is a processor family consisting of three 4-Bit processors that share the same underlying architecture: Single-clock fetch-decode-execute cycle, Harvard architecture, 4-Bit length instruction Word, single clock-cycle multiplier block and a dedicated instruction to drive peripherals.

I designed the B400 family to be simple, deterministic and user expandable. To ensure single clock-cycle behaviour remains consistent and to keep the design minimalistic, I didn't implement any user-accessible registers. But I kept the input and output pins seperate, exposed the adress bus and added a program (P') pin (disables the input interface subcircuit and puts the internal RAMs into "write" mode) to make it easier for the user to implement external peripherals such as regiters or state machines.

# Instruction Table
All B400 variants share the same instruction set given in the table below:
<img width="466" height="411" alt="B400_InstructionTable" src="https://github.com/user-attachments/assets/45ddc1d2-34cb-4ef4-89a8-0d3fd6b3de5c" />

For more information, please refer to a README file for the specific variant.
