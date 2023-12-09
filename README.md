## Hey 👋, I'm [Aba](https://aba-blog.xyz/)

I'm a PhD student at University of California, San Diego, with about 4 years of experience building ML accelerators. Besides digital circuit design, I enjoy [teaching](https://aba-blog.xyz/tag/teaching/), [community work](https://aba-blog.xyz/tag/community/index.html), and [backpacking](https://aba-blog.xyz/tag/travels/index.html).

## DeepSoCFlow

- [An open workflow](https://github.com/abarajithan11/deepsocflow) for hardware research in FPGA/ASIC implementation of DNNs
- Developed software (python library) + hardware (SV modules, TCL flows) + firmware (C runtime)
- Started as self-motivated passion project; being integrated with [HLS4ML library](https://github.com/fastmachinelearning/hls4ml)
- Software:
  - [Python front-end](https://github.com/abarajithan11/deepsocflow/tree/master/deepsocflow/py) to build & train models with Qkeras, run fixed point inference & generate SV, TCL, and C headers.
  - Made into pip package with Sphinx auto-documentation
  - Currently migrating backend from Qkeras to Brevitas
- Hardware:
  - Fully parameterized, dynamically reconfigurable, [high performance AXI engine in SystemVerilog](https://github.com/abarajithan11/deepsocflow/tree/master/deepsocflow/rtl) to fill a given area.
  - Built as a vehicle for hardware research, where users can switch custom MACs, and try their novel ideas.
  - Achieves 250 MHz on FPGA (ZCU104) and 1 GHz on TSMC 65nm LP. Being taped out with [ARM SoCLabs](https://soclabs.org/project/enhancing-hls4ml-accelerating-dnns-fpga-and-asic-scientific-computing)
  - [TCL scripts](https://github.com/abarajithan11/deepsocflow/tree/master/deepsocflow/tcl) to generate SoC with AXI DMAs on Xilinx FPGAs, and for ASIC flow with a given PDK.
- Firmware
  - [C firmware](https://github.com/abarajithan11/deepsocflow/tree/master/deepsocflow/c) to control the DMAs & accelerator to process any given DNN.
  
## SystemVerilog Short Course

- 64-hour hands-on short course, collaborating with Synopsys, teaching 271 participants from 13 countries
- [Overwhelmingly positive feedback](https://github.com/skillsurf/systemverilog\#feedback-from-the-participants) from undergraduate & industry professionals
- (Content)[https://github.com/skillsurf/systemverilog]:
  - Hands-on examples: Basics (full adder, counter) to complex (AXI-Stream [Parameterized Matrix Multiplier](https://github.com/SkillSurf/systemverilog/blob/master/rtl/matvec_mul.sv) with UART I/O)
  - Testing with [randomized transactional testbenches](https://github.com/SkillSurf/systemverilog/blob/master/tb/mvm_uart_system_tb.sv)
  - FPGA implementation & testing with Python
  - ASIC flow with Synopsys DesignCompiler & IC Compiler.

   
## Other Projects & Initiatives

- Missing Semester:
  - An initiative I have started at my department, to conduct hands-on webminars to familarize students with tools and languages.
  - Free and open to anyone willing to learn
  - SystemVerilog webminar (above) was part of it.
- [SoC Design for Vision Based Traffic Control](https://aba-projects.blogspot.com/2019/10/2019-vision-based-traffic-sensing-and.html) 
  - Undergraduate thesis project
  - Patent under review - private repo 
  - Tensorflow 1.x, Keras, Python, C++, SystemVerilog, ZYNQ 
- Vision Based Traffic Analytics
  - Commercializing - private repo
  - Group work
  - Python, Tensorflow 2.x, AWS, Node.js
- [AbruTech Processor](https://aba-projects.blogspot.com/2018/01/2018-custom-processor-design-and.html)
  - My first big project in digital design
  - A custom processor on FPGA with our own architecture, ISA, assembler and simulator
  - Algorithms implemented: Downsampling, Upsampling RGB images, applying filters, prime finding with eratosthenes sieve
- Digital Graphic Equalizer
  - 3 bands, built for 5 extra marks
  

<!--**abarajithan11/abarajithan11** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
