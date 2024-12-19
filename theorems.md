[<- Home ](./README.md)

|**Subject**|**Topic**|
|:---:|:---:|
|**Electrical circuits**|**Circuit theorems**|

<br/>
<br/>

| **Cues** | **Notes** |
|----------|-----------|
| **Ohm's Law** | **Definition**: Relates voltage (V), current (I), and resistance (R) in an electrical circuit.<br/> **Formula**: $ V = IR $<br/> **Applications**: Used to calculate the voltage, current, or resistance in a circuit. |
| **Kirchhoff's Voltage Law (KVL)** | **Definition**: The total voltage around a closed loop in a circuit is equal to the sum of voltage drops within the same loop.<br/> **Formula**: $ \sum V = 0 $<br/> **Applications**: Used to find unknown voltages in a circuit loop. |
| **Kirchhoff's Current Law (KCL)** | **Definition**: The total current entering a junction is equal to the total current leaving the junction.<br/> **Formula**: $ \sum I_{in} = \sum I_{out} $<br> **Applications**: Used to find unknown currents at a junction. |
| **Thevenin's Theorem** | **Definition**: Any linear electrical network can be replaced by an equivalent circuit consisting of a single voltage source and series resistance.<br/> **Steps**:<br/><br/> 1. Remove the load resistor.<br/>2. Find the Thevenin equivalent voltage (Vth).<br/> 3. Find the Thevenin equivalent resistance (Rth).<br/> 4. Replace the network with the Vth and Rth in series. |
| **Norton's Theorem** | **Definition**: Any linear electrical network can be replaced by an equivalent circuit consisting of a single current source and parallel resistance.<br/> **Steps**:<br/><br/> 1. Remove the load resistor.<br/> 2. Find the Norton equivalent current (In).<br/> 3. Find the Norton equivalent resistance (Rn).<br/> 4. Replace the network with the In and Rn in parallel. |
| **Superposition Theorem** | **Definition**: In a linear circuit with multiple sources, the response (current or voltage) in any element is the sum of the responses caused by each source acting independently.<br/> **Steps**:<br/><br/> 1. Consider one independent source and turn off all other independent sources (replace voltage sources with short circuits and current sources with open circuits).<br/> 2. Calculate the response due to the active source.<br/> 3. Repeat for all sources and sum the individual responses. |
| **Maximum Power Transfer Theorem** | **Definition**: Maximum power is delivered to a load when the load resistance equals the Thevenin resistance of the network supplying the power.<br/> **Formula**: $ R_{load} = R_{th}$<br/> **Applications**: Used to design circuits for maximum efficiency. |

| **Summary** |
|----------|
|Circuit theorems are essential tools for analyzing and simplifying complex electrical circuits. |
|They include Ohm's Law, Kirchhoff's Laws (Voltage and Current), Thevenin's and Norton's Theorems, Superposition Theorem, and the Maximum Power Transfer Theorem. |
|Each theorem provides a unique approach to understanding circuit behavior and solving for unknown values, making them fundamental to the study and application of electrical engineering.|
