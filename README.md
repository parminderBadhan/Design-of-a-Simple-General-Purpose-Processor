# 🧑‍💻Design-of-a-Simple-General-Purpose-Processor
FPGA Based Arithmetic Logic Unit (ALU) Design: VHDL, Quartus II, Altera Board

**Project Overview:**
Developed a simple central processing unit (CPU) using VHDL, simulating and deploying it on an Altera FPGA board. The project involved designing all key CPU components including:
- Arithmetic Logic Unit (ALU)
- control unit (FSM + decoder)
- registers
- memory logic

The CPU cycled through instructions using a finite state machine, executed arithmetic/logical operations on two 8-bit inputs, and displayed the results live on 7-segment displays. This project deepened my understanding of hardware design, finite state machines, and digital circuit integration.

**Hardware Implementaion:**
The CPU was implemented on the Altera Cyclone-II EP2C35F672C6 FPGA board. The board’s switches and 7-segment displays were used to input data and display ALU outputs in real-time.
Allowing full hardware validation on VHDL modules including:
- FSM
- Decoder
- Registers
- ALU

<img width="800" height="543" alt="image" src="https://github.com/user-attachments/assets/191b24de-b3ac-451a-8c9b-62c72d0ade20" />


**CPU Block Diagram:**

<img width="581" height="371" alt="image" src="https://github.com/user-attachments/assets/f27e6d47-794d-47d0-9a85-d210b528d465" />

      
      
      
**Decoder Module (VHDL):**
Developed a 4-to-16 line decoder in VHDL with an enable input for use in the custom CPU design.
- Activates one of 16 output lines based on a 4-bit input when enabled
- Uses one-hot encoding
- Integrated into the control unit to generate operation codes for the ALU based on FSM output

<img width="608" height="742" alt="image" src="https://github.com/user-attachments/assets/77438b99-68ef-44b0-b1cd-f7b46a41a503" />
  
  
**Final Processor Schematic:**

<img width="800" height="393" alt="image" src="https://github.com/user-attachments/assets/9f8d26fd-65bf-402d-adb4-30419a72a0b5" />


**Skills and Technologies Gained:**
- Digital Systems
- Field-Programmable Gate Arrays (FPGA)
- Digital Logic Design
- ALU Design
- Register & Decoder Design
- Encoding/Decoding
- Logic Simulation & Timing Analysis
- Altera FPGA Board Operation
- VHDL Programming
- FPGA Design & Programming
- Logic Design
- Quartus Prime Software
- Finite State Machines
- Register & Decoder Implementation
- Binary and BCD Encoding/Decoding
- Clocked Sequential Circuits
- Hardware Testing and Debugging


