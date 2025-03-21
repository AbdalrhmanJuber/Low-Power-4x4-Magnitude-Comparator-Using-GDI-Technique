# Low Power 4x4 Magnitude Comparator Using GDI Technique
![image](https://github.com/user-attachments/assets/d6e5804d-44ca-4b6b-bcc2-56cc2eedea1b)
![image](https://github.com/user-attachments/assets/56a94cbe-1d9b-4d40-800f-fcb96b0cd436)

## Project Overview
This project involves the design and implementation of a low-power 4x4 bit magnitude comparator using the Gate Diffusion Input (GDI) technique. The primary objective is to demonstrate significant improvements in terms of power consumption, propagation delay, and transistor count compared to conventional CMOS implementations.

## Project Goals
- Implement a 4x4 magnitude comparator using the GDI technique.
- Compare performance metrics (transistor count, power consumption, and delay) with conventional CMOS implementations.
- Demonstrate substantial reductions in power consumption, delay, and chip area.

## Comparator Design
### 1. Comparator Basics
- Compares two 4-bit binary numbers and outputs signals indicating greater (G), equal (E), or less (L).
- Includes cascading capabilities to compare numbers larger than 4 bits.

### 2. GDI Technique
- Utilizes fewer transistors and offers lower power consumption and faster operation than conventional CMOS.
- Basic cell consists of inputs: Gate (G), PMOS source/drain input (P), and NMOS source/drain input (N).

### 3. Implemented Gates and Components
- 5-input AND gate
- 5-input OR gate
- 2-input XOR gate

### 4. Performance Metrics
- GDI Comparator: 130 transistors
- CMOS Comparator: 226 transistors
- Power Consumption: GDI - 0.35 µW; CMOS - 2.5 µW
- Propagation Delay: GDI - 40.8 ns; CMOS - 70.92 ns
- Chip Area: Reduced by 57.85% compared to CMOS.

## Simulation and Verification
- Simulation performed using Electric EDA tool at 45 nm process technology.
- Verified functionality and measured worst-case propagation delays and critical paths.

## Results
- Power Reduction: 86%
- Delay Reduction: 5.64%
- Transistor Count Reduction: Significant improvement from 226 to 130 transistors.

## How to Run the Project
1. Clone the repository.
2. Open the project files using the Electric EDA tool.
3. Run the provided simulations to verify the functionality and evaluate performance.

## University
Birzeit University, Faculty of Engineering and Technology, Department of Computer Engineering.

## Date
June 2024

