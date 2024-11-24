# CMOS NAND and NOR Gate
# Objective
To design and simulate CMOS NAND and NOR gates, demonstrating the functionality, power efficiency, and reliability of CMOS technology in digital logic circuits.
# Specifications
* Technology: CMOS
* Power Supply Voltage (Vdd): 5V (or as per requirement)
* Inputs: Two binary inputs (A and B)
* Output: Binary output (Y = NOT (A AND B))
* Transistor Count:
* 2 PMOS (pull-up network)
* 2 NMOS (pull-down network)
* Input Logic Levels: Logic 0: 0V , Logic 1: V𝐷𝐷
* Target Parameters: Propagation Delay: Minimized, Power Dissipation: Optimized for low power, Noise Margin: Sufficient to avoid logic errors.
* Simulation Tool: Cadence Virtuoso / TannerEDA Tools / LTspice.
# Design Description:
* CMOS NAND Gate:
The NAND gate is implemented using CMOS technology, comprising:
1. nMOS transistors in series (pull-down network).
2. pMOS transistors in parallel (pull-up network).
Functionality: The output is LOW (0) only when all inputs are HIGH (1).
* CMOS NOR Gate:
The NOR gate consists of:
1. nMOS transistors in parallel (pull-down network).
2. pMOS transistors in series (pull-up network).
Functionality: The output is HIGH (1) only when all inputs are LOW (0).
# Formulas
* Logical Operation:
NAND Gate Logic: Y=not of (A⋅B)
NOR Gate Logic: Y=not of (A+B)
* Dynamic Power Consumption: 𝑃𝑑𝑦𝑛𝑎𝑚𝑖𝑐=𝐶𝐿⋅𝑉𝐷𝐷2⋅𝑓,
where  𝑓 is the switching frequency.

# CMOS NAND GATE 
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NAND.jpg?raw=true)
# SCHEMATIC CODE
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NAND_Code.jpg?raw=true)
# CMOS NAND GATE OUTPUT 
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NAND_Output.jpg?raw=true)
# CMOS NOR GATE
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NOR.jpg?raw=true)
# SCHEMATIC CODE
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NOR_Code.jpg?raw=true)

# CONCLUSION
The theory of CMOS NAND and NOR gates highlights their fundamental role in digital logic design due to their low power consumption, high noise immunity, and efficient switching characteristics. In CMOS NAND gates, the series configuration of nMOS transistors ensures output is low only when all inputs are high, while the parallel pMOS transistors pull the output high otherwise. Conversely, in CMOS NOR gates, the parallel arrangement of nMOS transistors outputs low when any input is high, with series pMOS transistors providing a high output only if all inputs are low. Both gates exploit complementary nMOS and pMOS operation to achieve robust logic functions while minimizing static power dissipation, making them integral to modern integrated circuits.
# CMOS NOR GATE OUTPUT
![alt text](https://github.com/Vris4420/CMOS-NAND-Gate/blob/main/NOR_Output.jpg?raw=true)
