Program 1:
Statement: Convert a 32-bit value from Little Endian to Big Endian format using RISC-V assembly
Name of file:
PES2UG22EC136_week1_LAb.s

### Observation - Explanation
Byte Reordering: The program rearranges the bytes of a 32-bit value to switch from Little Endian to Big Endian format.
Shift and Mask Operations: It uses bitwise shifts and masks to isolate and reposition each byte correctly.
Output Storage: The final converted value is stored in an output register after reordering

### Observation - Single Cycle
- *Cycles:* 17
- *Frequency:* 12.35Hz 
- *CPI:* 1
- *IPC:* 1

### Observation - 5 Stage
- *Cycles:* <22
- *Frequency:* 3.03 Hz
- *CPI:* 1.29
- *IPC:* 0.773

### Memory Mapping
0x10000004 - 0x78563412
0x10000000 - 0x12345678

![alt text](file:///home/shwetamanda/COD-Lab/week1/image.png)


Program 2:
Statement: Write an Assembly Program for addition of 2 64-bit numbers on RV32I
Name of file:
PES2UG22EC136_week12_LAb.s

### Observation - Explanation
adding 2 64 bit num 

### Observation - Single Cycle
- *Cycles:* 13
- *Frequency:* 5.68Hz 
- *CPI:* 1
- *IPC:* 1

### Observation - 5 Stage
- *Cycles:* 19
- *Frequency:* 5.15 Hz
- *CPI:* 1.46
- *IPC:* 0.648

### Memory Mapping
0x1000000c - 0x00101023
0x10000008 - 0x80003012
0x10000004 - 0x80003012
0x10000000 - 0x10000000

![alt text](file:///home/shwetamanda/COD-Lab/week1/Screenshot%20from%202024-11-17%2011-17-35.png)
