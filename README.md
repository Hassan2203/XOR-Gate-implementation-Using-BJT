📖 Project Overview

This project demonstrates the implementation of an XOR (Exclusive-OR) logic gate using Bipolar Junction Transistors (BJTs).

The circuit is designed using five PN2222 transistors along with resistors and biasing components to achieve the XOR logic functionality.

The XOR gate produces HIGH output (1) only when the two inputs are different.

🧠 XOR Truth Table
Input A	Input B	Output Y
0	0	0
0	1	1
1	0	1
1	1	0
⚙ Components Used
🔹 Hardware

5 × PN2222 Transistors

Resistors

LED

Breadboard

DC Power Supply (8V)

Connecting Wires

🔹 Software

Proteus Simulation Software

🔬 Methodology

Designed XOR circuit in Proteus.

Simulated all four input cases.

Observed transistor regions:

Cutoff Region

Saturation Region

Implemented hardware circuit on breadboard.

Measured voltages and currents.

Verified results with XOR truth table.

📊 Simulation & Hardware Results

The circuit was tested for all four possible input combinations:

Case 1: A=0, B=0 → LED OFF

Transistors in cutoff region. No complete current path.

Case 2: A=0, B=1 → LED ON

One transistor saturates allowing current flow.

Case 3: A=1, B=0 → LED ON

Alternate transistor path completes circuit.

Case 4: A=1, B=1 → LED OFF

Output transistor in cutoff region.

Results match XOR truth table successfully.

🔍 Transistor Operating Regions Observed

Cutoff Region (V_BE < 0.7V)

Saturation Region (V_BE ≈ 0.7V and V_CE small)

🏗 Circuit Design

The XOR logic was achieved by carefully biasing multiple BJTs such that:

Only one active input allows current flow.

Both high inputs block output stage.

Both low inputs result in no conduction.

💡 Applications of XOR Gate

Arithmetic circuits (Half Adder / Full Adder)

Parity checking

Cryptography

Digital comparators

Subtractors

Pseudo-random number generation

🎯 Key Learning Outcomes

Practical implementation of digital logic using analog devices.

Understanding BJT switching behavior.

Region of operation analysis.

Hardware vs simulation comparison.

Transistor-level digital circuit design.

🚀 Future Improvements

Reduce transistor count

Implement CMOS-based XOR

Design using IC 7486 and compare results

PCB implementation

Power optimization analysis

📂 Project Structure

Simulation files

Hardware implementation images

Circuit diagram

Full project report

Measured results
