# Cascode Common Source Amplifier
## Introduction
The Cascode Common Source Amplifier is an analog circuit configuration that combines a common source (CS) stage with a common gate (CG) stage. 
This structure improves gain, bandwidth, and output resistance, making it highly suitable for high-frequency and high-gain applications. 
It is commonly implemented using MOSFETs in integrated circuits.

## Working Principle
The circuit consists of two transistors: the bottom transistor operates in the common source configuration, providing voltage gain, while the top transistor acts 
as a common gate stage, buffering the output and boosting output impedance. The cascode structure effectively reduces the Miller effect, 
thereby extending bandwidth and improving frequency response.

## Applications
Cascode amplifiers are widely used in:

RF Amplifiers: Where high gain and bandwidth are required.

Analog Front Ends: In ADCs and sensor interfaces.

Operational Amplifiers: As gain-boosting stages.

Low-Noise Amplifiers (LNAs): For minimizing noise in sensitive circuits.

High-Speed Circuits: Due to improved frequency characteristics.

## Design Parameters
Total Width: P<sub>mos</sub> = 40µ
             
  N<sub>mos</sub> = 30µ
             
Power Supply: V<sub>bias</sub> = -250 mV
              
  V<sub>in</sub> - AC Mangnitude = 1V, Amplitude = 10 mV, Freqyency = 1K Hz.
              
   V<Sub>dd</sub> = 1 V
              
   V<Sub>ss</sub> = -1 V

## Results 
Vin<sub>peak</sub> = 9.953 mV

Vout<sub>peak</sub> = 1.19 V

Gain is, A<sub>v</sub> = vout / vin

   A<sub>v</sub> = 1.19 V / 9.953 mV ≈ 119.5       

## Circuit, Simulation And Synthesis
### Schematic
![Schematic](https://github.com/user-attachments/assets/b6118fe3-00be-4af3-930d-987d62f8a15c) 

### Test Bench
![TB](https://github.com/user-attachments/assets/bb115ecb-027d-4d50-a56b-610e5878649c)

### Transient Response
![Trans An](https://github.com/user-attachments/assets/0d4ef18c-61c1-41f1-a7dc-0a8705714306)

### DC Response
![DC An](https://github.com/user-attachments/assets/5fc1ff77-ca67-48a1-beb8-0933b9ede7e4)

### AC Response
![AC An](https://github.com/user-attachments/assets/18d512a7-5af3-4807-a187-83c8f621d08c)

### Layout
![Syn](https://github.com/user-attachments/assets/c1baa16d-73ba-44d9-85da-3dddb0f91ff7)

**[Layout Design Video_1.webm](https://github.com/user-attachments/assets/9a22e254-c5a8-4d5d-ad80-3ad037004e1f)**

**[Layout Design Video_2.webm](https://github.com/user-attachments/assets/04856c95-0284-41ff-b164-937828d9df4a)**

### DRC
![DRC](https://github.com/user-attachments/assets/254a91c1-cf20-4395-b99f-bccf8a935182)

### LVS
![LVS](https://github.com/user-attachments/assets/29b4ce80-24ef-4693-826f-f01ecf468ad4)
