# Abarajithan G - [abapages.com](https://www.abapages.com)

I am a PhD student in Kastner Research Lab @ UCSD CSE, focusing on hardware security and verification, building robust hardware/software co-designs, and accelerating AI/ML at the edge.

## Tech Stack

* **Languages:** SystemVerilog (RTL, DV, SVA), Python, C/C++, OpenCL, Bash, Tcl
* **EDA Tools:** AMD/Xilinx Vivado, Cadence Genus, Cadence Innovus, Synopsys Design Compiler
* **Verification:** Verilator, VCS, Xsim, Questa Formal, SymbiYosys, cocotb
* **Other:** Git, Docker, LaTeX, GitHub Actions

## Projects

* **[SoC Fuzzing Benchmark](https://abapages.com/soc-fuzzing-benchmark/)**
  A standardized testbed to evaluate hardware fuzzers like Intel PreSiFuzz and RFuzz. Maps their bytestreams into AXI and tests them on SoC IPs with automatically injected bugs.

* **[CGRA4ML](https://abapages.com/cgra4ml/)**
  An open-source, automated framework for scientific edge computing. Maps DNNs from Python to custom, parameterizable SystemVerilog CGRAs with C firmware, targeting FPGAs and custom ASICs.
  
* **[FireBridge](https://abapages.com/firebridge/)**
  A framework for system-level verification enabling rapid Firmware/Hardware co-development. Bridges SystemVerilog AXI subsystems to real C firmware via DPI-C, without simulating a CPU.

* **[SystemVerilog Course for 300 students](https://abapages.com/systemverilog-course/)**
  64-hour short course, collaborating with Synopsys, covering RTL design, randomized transactional testbenches, AXI protocol design, FPGA & ASIC flow labs.

* **[Formal AXI Verification Stack](https://abapages.com/formal-axi/)**
  A reusable Formal VIP for AXI4 and AXI5 protocols and for complex IPs like interconnects being built and tested against both open-source and commercial tools.

* **[AXI Stream Systolic Array](https://abapages.com/axis-systolic-array-testbed/)**
  A lightweight, highly parameterizable systolic array in SV, integrated with Ibex-SoC via AXI DMAs, a custom DMA controller, and corresponding C firmware. Currently being formally verified.

## Publications

* **CGRA4ML: A Hardware/Software Framework to Implement Neural Networks for Scientific Edge Computing**. G Abarajithan, Z Ma, R Munasinghe, F Restuccia, R Kastner. *ACM Transactions on Reconfigurable Technology and Systems, 2026/2024.*
* **Tailor: Altering Skip Connections for Resource-Efficient Inference**. O Weng, G Marcano, V Loncar, A Khodamoradi, G Abarajithan, et al. *ACM Transactions on Reconfigurable Technology and Systems 17 (1), 1-23, 2024.*
* **Within-Camera Multilayer Perceptron DVS Denoising**. A Rios-Navarro, S Guo, G Abarajithan, K Vijayakumar, et al. *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops, 2023.*
* **Kraken: An Efficient Engine with a Uniform Dataflow for Deep Neural Networks**. G Abarajithan, CUS Edussooriya. *arXiv preprint arXiv:2112.02793, 2021.*
* **A mostly-online CAS teaching experience**. C Wijenayake, K Wickremasinghe, G Abarajithan, A Madanayake, et al. *2022 IEEE International Symposium on Circuits and Systems (ISCAS), 1783-1787, 2022.*
* **Machine Learning on Heterogeneous, Edge, and Quantum Hardware for Particle Physics (ML-HEQUPP)**. J Gonski, J Ott, S Abbaszadeh, S Addepalli, M Cremonesi, J Dickinson, et al. *2026.*
