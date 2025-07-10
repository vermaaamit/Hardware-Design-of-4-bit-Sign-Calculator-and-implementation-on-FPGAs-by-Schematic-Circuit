# Digital Sign Calculator Verification and Implementation of Verilog HDL via FPGA Simulation

This project presents the design, verification, and implementation of a Digital Sign Calculator using Verilog HDL, with deployment and simulation on an FPGA platform. The module determines whether a signed binary input (in 2's complement form) is positive or negative and drives an appropriate output signal accordingly.

Project Overview

    📁 Language: Verilog HDL
    🎛️ FPGA Platform: Xilinx (Spartan series)
    🧪 Simulation Tool: ISim
    ⚙️ Design Methodology: RTL Modeling and Testbench Verification
    💡 Input: 4-bit 2's complement binary number
    🚦 Output: 1 if positive, 0 if negative

🧠 Functional Description
➕➖ Sign Detection Logic
In 2's complement:

    MSB = 0 → Positive
    MSB = 1 → Negative

So, the sign output is simply:
assign sign = ~in[3];  // Assuming 'in' is 4-bit input\

📷 Screenshots

    ✅ Circuit Schematic Diagram

    🧪 Simulation Waveform

    🔌 FPGA Board Output (LED display or 7-segment)
