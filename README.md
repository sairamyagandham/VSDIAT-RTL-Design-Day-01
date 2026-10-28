# VSDIAT – Day 1: Introduction to Verilog RTL Design

## Objective
To design a 2:1 multiplexer using Verilog HDL, simulate its functionality, analyze the waveform, and synthesize the design.

## Tools Used
- Icarus Verilog
- GTKWave
- Yosys
- Ubuntu Linux in Oracle VirtualBox

## Design Description
A 2:1 multiplexer selects one of two data inputs based on the select signal.

**Boolean expression:**

`y = sel ? b : a`

- When `sel = 0`, `y = a`.
- When `sel = 1`, `y = b`.

## Project Files
- `mux2.v` – Verilog RTL design
- `tb_mux2.v` – Testbench
- `mux2.vcd` – Simulation waveform data
- `mux2_netlist.v` – Synthesized netlist

## Implementation Steps
1. Designed the 2:1 multiplexer in Verilog.
2. Created a testbench covering all eight input combinations.
3. Simulated the design using Icarus Verilog.
4. Inspected the waveform using GTKWave.
5. Synthesized the RTL using Yosys.

## Results
The simulation waveform was inspected, and Yosys generated a synthesized Verilog netlist.

## Screenshots
Screenshots documenting the RTL code, testbench, simulation, waveform, project files, and synthesis results are included in this repository.

## Conclusion
The introductory RTL exercise demonstrated Verilog coding, functional simulation, waveform analysis, and logic synthesis using open-source tools.
