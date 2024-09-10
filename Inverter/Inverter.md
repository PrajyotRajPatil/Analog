# CMOS Inverter
## Introcuction
The CMOS Inverter is a fundamental building block in digital circuits, composed of a p-channel (PMOS) and an n-channel (NMOS) MOSFET.
It is widely used in digital logic designs, acting as a NOT gate by inverting the input signal. 
The CMOS Inverter is known for its low power consumption and high noise margins, making it the preferred choice for most modern digital circuits.

## Working Principle
The CMOS Inverter operates with complementary PMOS and NMOS transistors:
When the input is 0 (low), the PMOS is on, and the NMOS is off, resulting in a high output (1).
When the input is 1 (high), the PMOS is off, and the NMOS is on, resulting in a low output (0).

## Applications
**CMOS Inverters are used in various digital and analog circuits, including:**

*Logic Gates: Basic building blocks of digital circuits.*

*Oscillators: Inverter chains used in ring oscillators.*

*Amplifiers: Used as gain stages in analog circuits.*

*Buffers: Signal strength amplification and isolation.*

*Level Shifters: Converting signal levels between different voltages.*

## Circuit, Symbol, Simulation And Synthesis
### Schematic
![inv](https://github.com/user-attachments/assets/2fe5358d-6330-4d5f-87ff-576b2bedfdd8)
### Symbol
![inv_sym](https://github.com/user-attachments/assets/6d1aab09-5ec8-4502-9675-0ed81a4ccecb)
### Test Bench
![Inv_tb](https://github.com/user-attachments/assets/da879362-6a34-42ac-8cbe-5219883a7f4c)
### Simulation (Transient and DC Response)
![Graph](https://github.com/user-attachments/assets/a269c708-14d4-4d19-b597-1aa151fd969a)
### Layout
![Layout](https://github.com/user-attachments/assets/fbcc69d8-95a1-45ed-b43b-75bd2deff494)
### DRC
![Inv DRC](https://github.com/user-attachments/assets/9365baaa-52f1-419e-98d6-b6ced7409f99)
### LVS
![Inv LVS](https://github.com/user-attachments/assets/2150c82d-d3e4-4696-89d5-041851e209d0)
