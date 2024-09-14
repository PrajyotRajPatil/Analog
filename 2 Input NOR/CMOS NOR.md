# 2-Input CMOS NOR Gate
## Introduction
The 2-input CMOS NOR gate is a fundamental digital logic gate that performs the logical NOR operation.
It outputs a logic 1 only when both inputs are at logic 0; otherwise, the output is logic 0.
In CMOS technology, the NOR gate is implemented using complementary PMOS and NMOS transistors, 
providing advantages in terms of low power consumption and high noise margins. 
The NOR gate serves as a building block for a variety of digital circuits, including flip-flops, memory elements, and logic families.

## Working Principle
A 2-input CMOS NOR gate consists of:
Two PMOS transistors in parallel: When either input is 0, the output is pulled to VDD (logic 1).
Two NMOS transistors in series: When both inputs are 1, the output is pulled to ground (logic 0).
| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

## Transfer Characteristics
Threshold Voltage (Vth): Determines the voltage level at which the gate switches states.
Noise Margins: Defines the acceptable range of input voltages that produce valid logic levels.

## Application
**CMOS NOR gates are used in:**

*Combinational Logic Circuits: Basic logic operations in processors and controllers.*

*Digital Memory Circuits: Fundamental element for implementing SRAM and DRAM cells.*

*Oscillators: Used in various timing circuits.*

*Control Logic: Central component in logic families.*

## Schematic
![NOR Sch](https://github.com/user-attachments/assets/225b6bc8-754d-4e9b-8b84-1602da74e877)

## Symbol
![NOR Sym](https://github.com/user-attachments/assets/ed269958-484f-429b-989b-190a4cdd53f8)

## Test Bench
![NOR TB](https://github.com/user-attachments/assets/ada6bb4d-7411-4072-afde-01c0e820c5ed)

## Simulation
![NOR Sim](https://github.com/user-attachments/assets/4685831a-c713-4316-b5a4-c88a3501d14e)

## Layout
![NOR Layout](https://github.com/user-attachments/assets/4c190fde-c59c-4a42-8388-47ca0e29da5f)

## DRC
![NOR DRC](https://github.com/user-attachments/assets/9c4346c3-b78e-49b6-a3a9-cdbf845cb68f)

## LVS
![NOR LVS](https://github.com/user-attachments/assets/f8aaef21-cbb9-47cb-b5fc-a7145bf90285)
