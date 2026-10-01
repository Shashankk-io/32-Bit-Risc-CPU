# 32-Bit RISC CPU

This project presents the design and implementation of a simplified **32-bit RISC CPU using Verilog HDL**. The CPU was developed as part of the VLSI Design Lab and implemented and synthesized using **Cadence Genus with a 90 nm technology library**.

The processor consists of key components including:

- Program Counter (PC)
- Control Unit
- 32-bit Register File
- 32-bit Arithmetic Logic Unit (ALU)
- Instruction Memory Interface
- Data Memory Interface

The CPU follows a basic **Fetch → Decode → Execute → Memory → Write Back** instruction flow. The ALU supports arithmetic and logical operations such as addition, subtraction, AND, OR, XOR, multiplication, and comparison.

The design was functionally verified using a Verilog testbench and subsequently synthesized using Cadence Genus. **Timing, area, and power reports** were generated as part of the VLSI implementation flow.

### Tools & Technologies

- Verilog HDL
- Cadence Genus
- 90 nm Standard Cell Library
- RTL Simulation
- Logic Synthesis
- SDC Timing Constraints

### Project Results

- **Technology:** 90 nm
- **Cell Count:** 5,628
- **Total Area:** 50,406.511
- **Reported Power:** ~4.56 mW
- **Clock Period:** 10 ns

This project provided practical experience in **digital design, processor architecture, Verilog RTL design, simulation, timing constraints, and VLSI synthesis**.

## Author

**Shashank Mallya**
