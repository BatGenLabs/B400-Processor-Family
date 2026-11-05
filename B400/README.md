# B400

# Introduction
B400 is a Harvard architecture single-clock Fetch-Decode-Execute (FDE) cycle, Single Instruction, Single Data (SISD) processor featuring 4-bit instruction word and an 8-bit-wide input bus (divided into two 4-bit sections, Data0 and Data1). B400 also features a single clock-cycle hardware multiplier and a dedicated instruction to drive peripherals.

B400 is designed for simplicity, predictability, reliability, and expandability. It does not feature any user-acessible registers, but with its Program' (P') pin, separate input-output pins, and address output bus, it is possible to add external peripherals ranging from registers to custom digital systems.

# Pinout and Block Diagram
<img width="482" height="612" alt="pinout" src="https://github.com/user-attachments/assets/9af091de-6b00-4313-b309-78f52338a783" />
<img width="478" height="352" alt="B400_BlockDiagram" src="https://github.com/user-attachments/assets/fa41ee87-ed1e-480b-b783-9b3483890b99" />

# Instructions
<img width="466" height="411" alt="B400_InstructionTable" src="https://github.com/user-attachments/assets/a030be1c-c297-4113-b452-f3ed72da6a80" />
