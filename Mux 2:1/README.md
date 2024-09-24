# CMOS 2:1 Multiplexer (MUX)

## Introduction
A CMOS 2:1 Multiplexer (MUX) is a fundamental building block in digital circuits,
commonly used for selecting one of two input signals and directing it to the output based on the value of a control signal (select line).
It is composed of CMOS logic circuits that offer low power consumption and high speed,
leveraging complementary p-channel (PMOS) and n-channel (NMOS) transistors to efficiently perform the selection operation.

## Working Principle
The CMOS 2:1 MUX operates with two inputs (A and B), one select line (S), and one output (Y). 
The select line determines which input is passed to the output:

When S = 0, the output Y follows input A.
When S = 1, the output Y follows input B.
The multiplexer is implemented using a combination of PMOS and NMOS transistors in
a logic arrangement that allows efficient switching between the two inputs based on the state of the select line.

## Applications
**CMOS 2:1 MUXs are commonly used in:**

*Data Routing: Selecting between two data inputs in digital systems.*

*Arithmetic Logic Units (ALUs): Used in circuits for controlling data flow in processors.*

*Signal Selection: Choosing between different signal paths in communication systems.*

*Digital Logic Circuits: Building more complex combinational and sequential logic systems.*

## Circuit, Symbol & Simulation
### Schematic
![sch2mux](https://github.com/user-attachments/assets/51a551f6-7c5c-496c-beb9-eb8ed0b43791)

### Symbol
![sym2mux](https://github.com/user-attachments/assets/b2fd2ce2-183c-460d-ba5b-8dd4d2b75a2f)

### Test Bench
![Tb2mux](https://github.com/user-attachments/assets/52b747a5-3059-4cb8-a7fb-5745902aa0f9)

### Simulation
![sim2mux](https://github.com/user-attachments/assets/f1d2fbed-ae87-47aa-b5ed-cd8c9944b2b8)
