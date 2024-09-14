# 2-Input CMOS NAND Gate
## Introduction
A CMOS NAND gate is a fundamental digital logic gate that produces a low (0) output only when both inputs are high (1);
otherwise, it outputs high (1). It is built using complementary PMOS and NMOS transistors.
The CMOS NAND gate is commonly used in digital circuits because of its low power consumption and high noise immunity.

## Working Principle
The 2-input NAND gate follows the logic:

| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

When both inputs (A and B) are 1, the output (Y) is 0.
When either or both inputs (A and/or B) are 0, the output (Y) is 1.

## CMOS Structure:
PMOS transistors are placed in series, and NMOS transistors are placed in parallel.
When both inputs are high, both NMOS transistors are on, and the output is pulled to ground (low).
When either input is low, the PMOS transistors are turned on, pulling the output to VDD (high).

## Applications
**2-Input CMOS NAND gates are used in various digital and analog applications such as:**

*Logic Design: Building blocks of complex digital circuits.*

*Flip-flops and Latches: Essential in sequential logic circuits.*

*Clocking Circuits: Used in clocking systems.*

*Arithmetic Circuits: Forming other gates and functions like AND, OR, NOR, etc.*

## Schematic
![NAND Sch](https://github.com/user-attachments/assets/cc4e11cf-6f9c-4b0e-8532-5d919b0f7ada)

## Symbol
![NAND Sym](https://github.com/user-attachments/assets/76cfd95c-0c85-4b9e-bdb8-b7e1de510398)

## Test Bench
![NAND Tb](https://github.com/user-attachments/assets/3365bd91-8879-4ad2-b7e8-03a7141e85f0)

## Simulation
![NAND Sim](https://github.com/user-attachments/assets/00bbd99e-41ac-4763-ba7c-bef8d800934c)

## Layout
![NAND Layout](https://github.com/user-attachments/assets/9209e3ca-169f-4435-98a1-f576ff805900)

## DRC
![NAND DRC](https://github.com/user-attachments/assets/dc94db4e-2413-46d8-ba94-e17afaf305a3)

## LVS
![NAND LVS](https://github.com/user-attachments/assets/ea7e96aa-b5ee-4816-b626-3cabb082ace7)
