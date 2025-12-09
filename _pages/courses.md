---
layout: archive
title: "Courses"
permalink: /courses/
author_profile: true
---
These are my **courses and projects** taken by me.
<!-- 
Below is a curated selection of my **academic projects, lab work, and coursework** across **Computer Architecture, VLSI Design, CAD tools, Digital Systems, Signal Processing, and Computational Biology** — completed as part of my B.Tech + M.Tech Dual Degree at **IIT Bombay**. -->

---

# 🚀 Key Projects & Coursework

---

## **EE 451 — Supervised Research Exposition (Autumn ’25)**  
**Guide:** Prof. Laxmeesha Somappa, IIT Bombay  
**Topic:** *Full RISC-V SoC & Linux Boot Flow*

- Built a complete **RISC-V SoC** around the *KianV (RV32IMA)* core: UART, GPIO, SDRAM, SPI-NOR flash, CLINT timer  
- Implemented multicycle FSM CPU, **RISC-V privileged modes**, SV32 virtual memory  
- Designed FPGA top-level, generated bitstream, deployed on hardware  
- **Successfully booted the Linux kernel** on FPGA, demonstrating scheduling + peripheral I/O  

---

## **EE 669 — VLSI Technology (Autumn ’25)**  
**Guide:** Prof. Anil Kottantharayil  
**Topic:** *CMOS Fabrication, Simulation & Process Engineering*

- Simulated silicon oxidation, diffusion, implantation using **Sentaurus**, NanoHUB & PV Lighthouse  
- Analyzed Deal–Grove/Massoud models, dopant diffusion, junction behavior  
- Lithography optimization: standing-wave, proximity effects, PEB/ARC tuning  
- Explored CMOS process integration: trench isolation, gate-stack, shallow junctions  
- Investigated **FinFET & GAAFET** fabrication at 3nm scale  

---

## **EE 709 — Testing & Verification of VLSI Circuits (Autumn ’25)**  
**Guide:** Prof. Madhav Desai  
**Topic:** *ROBDDs, SAT-based ATPG, Fault Simulation*

- Modeled Boolean functions & FSMs using **cmubdd** for equivalence verification  
- Built optimized Mealy machines with don’t-care utilization  
- Explored invertibility & impossible outputs via structured **ROBDD traversal**  
- Performed **ATPG using Minisat**, generating distinguishing test vectors  
- Conducted **deductive fault simulation** for stuck-at analysis  

---

## **EE 748 — Advanced Topics in Computer Architecture (Autumn ’25)**  
**Guide:** Prof. Virendra Singh  
**Topic:** *Microarchitecture, Memory Systems & GPU Optimizations*

- Characterized **SPEC2006** workloads: MPKI, APKI, LLC sensitivity, IPC trends  
- Designed custom **LLC replacement policies** (LRU-slow, LRU-6)  
- Implemented guided branch prediction using **RVCF-style core hints**  
- Proposed GPU optimizations combining **NL-DWF + register prefetching**  

---

## **EE 789 — Algorithmic Design of Digital Systems (Spring ’25)**  
**Guide:** Prof. Madhav Desai  
**Topic:** *Algorithmic Assembly (Aa), Hardware Compilation & Digital Systems*

- Implemented matrix multiplication variants in **Algorithmic Assembly**  
- Designed shift/add multipliers, parallel multipliers, dividers, sqrt units  
- Built a **4×4 output-queued switch** with fair arbitration & structured queues  
- Applied Aa → hardware compilation (elastic pipelines, guarded statements)  
- Generated cycle-accurate **VHDL** via AHIR toolchain  

---

## **EE 705 — VLSI Design Lab (Spring ’25)**  
**Guide:** Prof. Laxmeesha Somappa  
**Topic:** *FPGA Systems, Arithmetic Blocks & RISC-V SoC Integration*

- Designed + verified: **32-bit Brent–Kung adder**, **Dadda multiplier**, **barrel shifter**  
- Built arithmetic subsystems using controllers, BRAM, VIO on PYNQ FPGA  
- Implemented **ALU DECODE** for RISC-V 32IM  
- Built full **RISC-V SoC** with ALU, decode, LSU, CSR, AXI, UART, GPIO  

---

## **EE 739 — Processor Design (Spring ’25)**  
**Guide:** Prof. Virendra Singh  
**Topic:** *Superscalar Out-of-Order Processor*

- Designed a pipelined **OoO superscalar processor** with ALU/LSU pipelines  
- Implemented stages: fetch → decode → issue → execute → writeback  
- Built hazard detection, stall/flush logic, forwarding  
- Developed **ARF/RRF-based register renaming** + ROB for in-order commit  
- Verified scheduling & execution using reservation stations + load buffers  

---

## **EE 344 — Electronic Design Lab (Spring ’25)**  
**Guide:** Prof. Siddharth Tallur  
**Topic:** *Embedded Sensing, PCB Design & Ultrasonic SHM System*

- Built **EcoSync 8X**, a dsPIC33A-based ultrasonic SHM platform  
- Implemented 100 kHz excitation & sensing with instrumentation-grade amplification  
- Integrated dsPIC33 + ESP32 for control, data capture & wireless communication  
- Designed PCB in KiCAD + fabricated custom enclosure  

---

## **EE 671 — VLSI Design (Autumn ’24)**  
**Guide:** Prof. Laxmeesha Somappa  
**Topic:** *Physical Design & GDS-II Generation*

- Built Laplacian filter accelerator using Verilog for 16×16 edge detection  
- Designed Kogge-Stone adder, multiplexer blocks, pixel clipping logic  
- Completed full **OpenLane flow**: synthesis → PnR → CTS → STA → DRC/LVS  
- Generated final **GDS-II**, liberty & LEF files  

---

## **EE 677 — VLSI CAD (Autumn ’24)**  
**Guide:** Prof. Virendra Singh  
**Topic:** *Reversible Logic & CAD Algorithms*

- Implemented reversible logic synthesis using **PPRM expansions** + Toffoli networks  
- Used priority-based search trees & heuristics to minimize expansions  
- Designed Verilog/EDIF-compatible circuit simulator  

---

## **EE 678 — Wavelets & Multirate DSP (Autumn ’24)**  
**Guide:** Prof. Vikram Gadre  
**Topic:** *Wavelet-Enhanced U-Net Segmentation*

- Integrated **DWT/IDWT** into U-Net for high-frequency feature retention  
- Built dual DWT-IDWT pathways at deep blocks, improving DICE & precision  
- Experimented with wavelet bases & tuned under compute constraints  

---

## **EE 309 — CISC & RISC Processor Design (Spring ’24)**  
**Guide:** Prof. Virendra Singh  
**Topic:** *16-bit RISC Processor in VHDL*

- Designed pipelined processor with stalling, forwarding & branch prediction  
- Executed 26 instructions across six pipeline stages  
- Built decoders, hazard detection, and FPGA demo on Intel Max-10  

---

## **DH 607 — Computational Multi-Omics (Autumn ’25)**  
**Guide:** Prof. Saket Choudhary  
**Topic:** *Sequence Analysis, Algorithms & Structural Bioinformatics*

- Implemented core algorithms: **BWT**, Needleman–Wunsch, suffix structures  
- Built multi-omics pipelines for genomic + miRNA network analysis  
- Modeled mutation impacts via **Boltz docking**  

---

# 📘 Summary

Across these courses, I have worked extensively on:

- **RISC-V processors & microarchitecture**  
- **FPGA systems & embedded hardware**  
- **VLSI design, CAD tools & process engineering**  
- **Digital system design & hardware compilation**  
- **DSP, machine learning & computational biology**

This page highlights the breadth and depth of my **hardware–systems–VLSI skillset**, built through rigorous IIT Bombay coursework and hands-on projects.


