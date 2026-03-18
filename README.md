# Abarajithan G - [abapages.com](https://abapages.com)

Check out my website for up-to-date info: [abapages.com](https://abapages.com)

## Tech Stack

* **Languages:** SystemVerilog (RTL, DV, SVA), Python, C/C++, OpenCL, Bash, Tcl
* **EDA Tools:** AMD/Xilinx Vivado, Cadence Genus, Cadence Innovus, Synopsys Design Compiler
* **Verification:** Verilator, VCS, Xsim, Questa Formal, SymbiYosys, cocotb
* **Other:** Git, Docker, LaTeX, GitHub Actions

## Main Repositories:

* **[SystemVerilog Course for 300 students](https://github.com/SkillSurf/systemverilog):**
  64-hour short course, collaborating with Synopsys, covering RTL design, randomized transactional testbenches, AXI protocol design, FPGA & ASIC flow labs.

* **[CGRA4ML](https://github.com/KastnerRG/cgra4ml):**
  An open-source, automated framework for scientific edge computing. Maps DNNs from Python to custom, parameterizable SystemVerilog CGRAs with C firmware, targeting FPGAs and custom ASICs. [ACM TRETS paper](https://dl.acm.org/doi/10.1145/3801097)

* **[AXI Stream Systolic Array & FireBridge](https://github.com/abarajithan11/axis-systolic-array):**
  * A lightweight, highly parameterizable systolic array in SV, integrated with Ibex-SoC via AXI DMAs, a custom DMA controller, and corresponding C firmware. Currently being formally verified.
  * A framework for system-level verification enabling rapid Firmware/Hardware co-development. Bridges SystemVerilog AXI subsystems to real C firmware via DPI-C, without simulating a CPU.
  * Used as a testbed with scripts to implement an AXI IP on FPGAs, integrate with Ibex RISC-V CPU, etc.

* **[Formal AXI](https://github.com/abarajithan11/formal_axi):**
  A reusable Formal VIP for AXI4 and AXI5 protocols and for complex IPs like interconnects being built and tested against both open-source and commercial tools.
  
* **[AXI-Stream VIP](https://github.com/abarajithan11/axis_vip):**
  Reusable transaction-level AXI Stream Driver and Sink with parametrized, random stalls to stress-test the designs.
  
* **[UVM in 580-lines](https://github.com/abarajithan11/axis_vip):**
  Simplest possible complete UVM testbench, built as a class project.
  
