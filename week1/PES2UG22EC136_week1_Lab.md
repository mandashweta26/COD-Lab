Program 1:
Statement: Convert a 32-bit value from Little Endian to Big Endian format using RISC-V assembly
Name of file:
PES2UG22EC136_week1_LAb.s

### Observation - Explanation
Byte Reordering: The program rearranges the bytes of a 32-bit value to switch from Little Endian to Big Endian format.
Shift and Mask Operations: It uses bitwise shifts and masks to isolate and reposition each byte correctly.
Output Storage: The final converted value is stored in an output register after reordering

### Observation - Single Cycle
- **Cycles:** 17
- **Frequency:** 12.35Hz 
- **CPI:** 1
- **IPC:** 1

### Observation - 5 Stage
- **Cycles:** <22
- **Frequency:** 3.03 Hz
- **CPI:** 1.29
- **IPC:** 0.773

### Memory Mapping
0x10000004 - 0x78563412
0x10000000 - 0x12345678


![prgm1](image.png)
