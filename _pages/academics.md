---
layout: single
permalink: /academics/
title: ""
author_profile: true
classes: wide
custom_css: academics.css
---

<div class="tech-bg"></div>      
<div class="circuit-lines"></div> 

<!-- <div class="tech-wrapper"> -->

<!-- <div class="tech-hero"> -->
  <!-- <h1 class="tech-title"><strong>Courses</strong> & <strong>Academic Work</strong> 📘</h1> -->

# Courses & Academic Work 📘

  <p class="tech-text">
    A curated collection of my coursework at <strong>IIT Bombay</strong>.
  </p>

  <ul class="tech-text">
    <!-- EE 789 -->
    <li><strong>EE 789 — Algorithmic Design of Digital Systems</strong><br>Introduced to Petri Nets and their advantages over traditional FSMs, followed by a detailed study of AHIR’s dataflow-based design model. Explored AHIR building blocks, their VHDL realizations, and applied them to digital system design through practical examples.</li>
    <details class="gh-collapse">
      <summary><strong>EE 789 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains all coursework for <strong>EE789: Algorithmic Design of Digital Systems</strong> 📘, including the Final Project, Midsem Assignment, and Mini Project.<br>  
            The Final Project implements three matrix multiplication architectures ⚙️—unrolled dot product, block-parallel computation, and rank-1 decomposition—using Algorithmic Assembly with detailed analysis.<br>  
            The Midsem Assignment focuses on VHDL-based arithmetic units ➗ such as multipliers, dividers, and square-root units, complete with Vivado testbenches and reports.<br>  
            The Mini Project builds a <strong>4×4 Output-Queued Switch</strong> 🔀 featuring fair arbitration, packet routing, and structured queuing using AHIR dataflow principles.<br>  
            Each module includes source code, architecture diagrams, simulation results, and documentation 📄.<br> 
            Toolchain includes Vivado, VHDL, GTKWave, and Algorithmic Assembly 🛠️.
          </p>
          🔗 <a href="https://github.com/Amolpagare10/EE789_Algorithmic_Design_of_Digital_Systems" target="_blank">GitHub Link</a>
        </div>
      </div>
    </details>
    <!-- EE 748 -->
    <li><strong>EE 748 — Advanced Topics in Computer Architecture</strong><br>This research-intensive course builds on SMT and GPGPU architecture, diving into advanced topics such as heterogeneous ISAs, reconfigurable CMPs, TLB prefetching, fault-tolerant redundant execution, and look-ahead architectures through discussions of ISCA and MICRO papers. 
    </li>
    <details class="gh-collapse">
      <summary><strong>EE 748 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains all coursework for <strong>EE748 — Advanced Topics in Computer Architecture</strong> 🧠, including assignments, research paper reviews, gem5 experiments, and a superscalar processor project.<br>  
            Assignments cover SPEC benchmark analysis 📊, LLC sensitivity studies, and custom cache replacement policy design.<br>  
            Further work explores RVCF-guided branch prediction 🔍 using leading/trailing core simulations in gem5 to improve accuracy and IPC.<br>  
            The superscalar project implements an out-of-order processor in Verilog ⚙️ with register renaming, ROB, reservation stations, and full pipeline evaluation.<br>  
            The course project proposes GPU optimizations by combining NL-DWF with register prefetching 🚀 to reduce RF conflicts and improve SIMD efficiency.<br>  
            A comprehensive set of research paper reviews 📚 spans heterogeneous ISAs, fault tolerance, branch prediction, secure architectures, and cache innovations.<br>  
            Together, this repository demonstrates extensive architectural analysis, simulation, and hardware-software co-design skills.<br>  
          </p>
          <a href="https://github.com/Amolpagare10/EE_748_Advanced_Topics_in_Computer_Architecture" target="_blank">🔗 https://github.com/Amolpagare10/EE_748_Advanced_Topics_in_Computer_Architecture</a>
        </div>
      </div>
    </details>
    <!-- EE 739 -->
    <li><strong>EE 739 — Processor Design</strong><br>Covers the evolution of computers, microprocessor architecture, instruction execution (FSMs, pipelines), memory systems, caching, branch prediction, and superscalar/VLIW execution. Also includes virtual memory, process scheduling, cache behavior, parallelism, and multithreading for modern high-performance processor design.
</li>
    <details class="gh-collapse">
      <summary><strong>EE 739 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository for <strong>EE739 — Processor Design</strong> contains complete implementations of both an Out-of-Order and an In-Order Superscalar Processor, built using Verilog and VHDL 🚀.<br>  
            The OoO design features reservation stations, ROB, unified register file, ALUs, LSUs, hazard control, and dual-issue execution, supporting in-order commit and broadcast forwarding.<br>  
            The repository includes full datapaths, controller logic, fetch/decode stages, register files, load/store buffers, and testbenches 📁.<br>  
            The In-Order superscalar processor implements parallel pipelines, scoreboard-based hazard detection, modular execution stages, and ISA-compliant components 🔧.<br>  
            Together, these designs demonstrate strong understanding of pipelined execution, register renaming, scheduling, hazard management, and ILP in modern processor architectures 🧠.
          </p>
          <a href="https://github.com/Amolpagare10/EE739_Processor_Design" target="_blank">🔗 https://github.com/Amolpagare10/EE739_Processor_Design</a>
        </div>
      </div>
    </details>
    <!-- EE 709 -->
    <li><strong>EE 709 — Testing & Verification of VLSI Circuits</strong><br>Covers Boolean algebra, VLSI design flow, formal verification, BDD/SAT-based reasoning, equivalence checking, and fault modeling for testing digital circuits. Focuses on automated techniques that ensure correctness and reliability of combinational and sequential hardware designs.</li>
    <details class="gh-collapse">
      <summary><strong>EE 709 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains all assignments for EE 709: Testing & Verification of VLSI Circuits, focusing on ROBDD-based modeling and ATPG workflows.<br>  
            It includes state-machine encoding, Boolean function analysis, output-space feasibility checking, and ROBDD-driven equivalence verification.<br>  
            The ATPG section features fault equivalence classification, SAT-based test pattern generation, and deductive fault simulation for stuck-at defects.<br>  
            Problems cover invertibility checks, impossible-output detection, and analysis of structural faults using Minisat.<br>  
            Overall, the repository demonstrates formal verification methods and automated testing techniques used to validate and ensure correctness of digital hardware.
          </p>
          <a href="https://github.com/Amolpagare10/EE_709_Testing_and_Verification_of_VLSI_Circuits" target="_blank">🔗 https://github.com/Amolpagare10/EE_709_Testing_and_Verification_of_VLSI_Circuits</a>
        </div>
      </div>
    </details>
    <!-- EE 705 -->
    <li><strong>EE 705 — VLSI Design Lab</strong><br>EE705 focuses on practical VLSI design through Verilog-based implementation of arithmetic units, memory systems, and a complete RISC-V processor pipeline. The course emphasizes full RTL-to-FPGA flow, including simulation, synthesis, debugging, and SoC integration using Vivado and PYNQ hardware.</li>
    <details class="gh-collapse">
      <summary><strong>EE 705 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains all Verilog-based assignments and projects from EE 705: VLSI Design Lab, covering arithmetic units, memory subsystems, and a complete RISC-V 32IM processor implementation. ⚙️💻<br>  
            It includes designs such as Brent–Kung adders, Dadda multipliers, barrel shifters, and custom I-/D-cache architectures, all validated through simulations and FPGA runs. 🔧📐<br>  
            The RISC-V subsystem integrates ALU decode logic, execution pipelines, LSU/CSR modules, and cache hierarchies, culminating in a full AXI4-Lite based SoC. 🚀  
            Each assignment is backed by detailed reports, testbenches, Vivado projects, and hardware debugging via VIO/ILA. 📑📊<br>  
            Overall, the repository demonstrates complete RTL-to-FPGA design flow and hands-on SoC development experience. 🖥️✨
          </p>
          <a href="https://github.com/Amolpagare10/EE705_VLSI_Design_Lab" target="_blank">🔗 https://github.com/Amolpagare10/EE705_VLSI_Design_Lab</a>
        </div>
      </div>
    </details>
    <!-- EE 678 -->
    <li><strong>EE 678 — Wavelets</strong><br>Introduces the fundamentals of wavelet transforms, key families like Haar and Daubechies, the uncertainty principle, and comparisons with STFT. Covers multilevel decomposition using high/low-pass filters and perfect reconstruction of signals from wavelet coefficients.</li>
    <details class="gh-collapse">
      <summary><strong>EE 678 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains coursework deliverables for EE678 Wavelets, focusing on applying wavelet transforms to medical image analysis and MRI-based tumor detection. 🧠📊 <br>
            The mid-semester work integrates wavelet features into CNN pipelines for improved tumor detection, supported by Python code and a detailed report. <br>
            The end-semester project explores wavelet-based deep learning architectures for MRI segmentation, enhancing feature extraction and boundary precision. <br>
            Both code modules include preprocessing scripts, wavelet utilities, model architectures, and complete training and evaluation workflows. 💻🔍 <br>
            Comprehensive reports document the methodology, results, and comparisons across both stages of the course. 📑✨  
          </p>
          <a href="https://github.com/Amolpagare10/EE678_Wavelets" target="_blank">🔗 https://github.com/Amolpagare10/EE678_Wavelets</a>
        </div>
      </div>
    </details>
    <!-- EE 677 -->
    <li><strong>EE 677 — VLSI CAD</strong><br>Covers the full VLSI design flow including logic minimization, fault detection algorithms, and physical design steps such as partitioning, placement, and routing. Emphasizes practical heuristics and fault-modeling techniques used to optimize circuit correctness, testability, and layout efficiency.</li>
    <details class="gh-collapse">
      <summary><strong>EE 677 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            EE677 VLSI CAD involves building CAD tools for digital and quantum circuits, including data-flow graph generation, fault detection through time unrolling, and reversible circuit synthesis.<br>
            The repository contains Python implementations for parsing netlists, analyzing circuit structure, and evaluating fault detectability in sequential logic.<br>
            Assignments focus on understanding circuit dependencies, modeling stuck-at faults, and automating verification workflows used in practical VLSI CAD systems.<br>
            The course project applies Positive Polarity Reed-Muller (PPRM) logic to synthesize reversible circuits, supporting quantum and low-power design methodologies.<br>
            These tools demonstrate foundational concepts in graph analysis, fault modeling, Boolean algebra, and algorithmic circuit synthesis.<br>
          </p>
          <a href="https://github.com/Amolpagare10/EE677_VLSI_CAD" target="_blank">🔗 https://github.com/Amolpagare10/EE677_VLSI_CAD</a>
        </div>
      </div>
    </details>
    <!-- EE 671 -->
    <li><strong>EE 671 — VLSI Design</strong><br>This course covers CMOS device fundamentals, logic gate design, latches/flip-flops, arithmetic units, FSM-based control paths, and memory architectures ranging from ROMs to SRAM/DRAM. It also introduces multi-stage logic optimization, semi-custom VLSI design styles (PLAs, FPGAs), I/O circuits, packaging, and testing methodologies.</li>
    <details class="gh-collapse">
      <summary><strong>EE 671 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository documents the complete EE671 VLSI Design coursework, covering CMOS inverter design, standard-cell layout, RTL synthesis, and full physical design using SkyWater 130A PDK, NGSpice, Magic, Netgen, and OpenLane.<br>
            It includes simulations of inverter behavior, DRC/LVS/PEX-verified INVX1 layouts, and synthesis of a 16-bit Wallace Tree adder with functional verification and area/timing reports.<br>
            The physical design flow for a 16-bit Brent–Kung adder is captured end-to-end, including CTS, routing, parasitic extraction, and signoff checks with final GDSII outputs.<br>
            Project 1 involves developing and characterizing custom standard cells with schematic, layout, LEF/Liberty files, and timing/power analysis.<br>
            Project 2 implements a Laplacian edge-detection filter in Verilog, integrating arithmetic blocks and taking the design from RTL to layout with waveform and performance analysis.<br>
            Together, these works demonstrate proficiency across device-to-system VLSI workflows, from transistor-level design to full SoC-ready physical implementations.<br>
          </p>
          <a href="https://github.com/Amolpagare10/EE671_VLSI_Design" target="_blank">🔗 https://github.com/Amolpagare10/EE671_VLSI_Design</a>
        </div>
      </div>
    </details>
    <!-- EE 669 -->
    <li><strong>EE 669 — VLSI Technology</strong><br>This course covers the complete VLSI process flow—from wafer cleaning, oxidation, diffusion, implantation, lithography, CVD/PVD deposition, plasma/RTP processing, interconnect fabrication, to full NMOS/CMOS/Bipolar process integration. It also explores advanced device technologies including high-k/metal-gate stacks, multi-level metallization, and modern nanoscale architectures such as FinFETs and GAAFETs down to 3 nm.</li>
    <details class="gh-collapse">
      <summary><strong>EE 669 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
          This repository documents my coursework for EE669 VLSI Technology, covering foundational and advanced semiconductor process engineering.<br>  
          It includes simulations and analysis of oxidation, diffusion, ion implantation, lithography, deposition, etching, and thermal/plasma processing.<br>  
          Assignments explore crystal anisotropy, Deal–Grove/Massoud oxidation models, dopant diffusion behavior, and lithography artifacts such as standing waves and proximity effects.<br>  
          The TCAD section features Sentaurus-based simulations for oxide growth, diffusion, trench processes, and ion implantation using SRIM and SProcess.<br>  
          The repo emphasizes process integration, device scaling trends, and modern device technologies such as FinFETs and GAAFETs.<br>  
          Together, these works demonstrate hands-on modeling and deep understanding of VLSI fabrication workflows from wafer to device.
        </p>
          <a href="https://github.com/Amolpagare10/EE_669_VLSI_Technology" target="_blank">🔗 https://github.com/Amolpagare10/EE_669_VLSI_Technology</a>
        </div>
      </div>
    </details>
    <!-- EE 451 -->
    <li><strong>EE 451 — Supervised Research Exposition</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 451 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE451" target="_blank">🔗 github.com/.../EE451</a>
        </div>
      </div>
    </details>
    <!-- EE 344 -->
    <li><strong>EE 344 — Electronic Design Lab</strong><br>Projects in this lab course span various areas within the electrical engineering domain such as electronic systems, computational processing, IOT, power systems, control systems with the objective of delivering a working prototype by the semester end</li>
    <details class="gh-collapse">
      <summary><strong>EE 344 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            The EcoSync 8X repository showcases a dsPIC33A-based ultrasonic guided-wave structural health monitoring system with an 8-channel configurable Tx/Rx interface and wireless acquisition using ESP32.<br>
            It contains complete firmware for signal generation, command protocols, and Wi-Fi communication, along with full PCB schematics, layouts, component libraries, and laser-cut enclosure files.<br>
            The system supports high-voltage Hanning-windowed pulse generation, precision sensing with instrumentation amplifiers, and real-time visualization through a custom GUI.<br>
            The documentation includes the bill of materials, step-by-step programming instructions, hardware design workflow, and integration details.<br>
            Challenges such as incomplete ADC functionality and partial Wi-Fi–MCU interfacing are described, alongside future plans for GUI enhancements, DI-map improvements, SRAM expansion, and full wireless pipeline completion.<br>
            Overall, it demonstrates a complete embedded hardware–software development cycle from concept to prototype.  
          </p>
          <a href="https://github.com/Amolpagare10/EE344_Electronic_Design_lab" target="_blank">🔗 https://github.com/Amolpagare10/EE344_Electronic_Design_lab</a>
        </div>
      </div>
    </details>
    <!-- EE 309 -->
    <li><strong>EE 309 — Microprocessors (CISC & RISC)</strong><br>The course covered instruction set architectures, 8085/8051 microprocessors, assembly programming, timers, interrupts, delays, and peripheral interfacing. It also explored RISC vs. CISC architectures, multi-cycle and single-cycle CPUs, pipelining, and cache memory.</li>
    <details class="gh-collapse">
      <summary><strong>EE 309 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE309" target="_blank">🔗 github.com/.../EE309</a>
        </div>
      </div>
    </details>
    <!-- DH 607 -->
    <li><strong>DH 607 — Introduction to Computational Multi-Omics</strong><br>The course bridges biology, statistics, and computing to teach how modern sequencing technologies generate high-dimensional genomic data and how mathematical models help extract meaningful biological insights. It covers sequence alignment, gene expression analysis, dimensionality reduction, statistical modeling of multi-omics data, and practical skills for exploratory analysis, visualization, and reproducible bioinformatics workflows.</li>
    <details class="gh-collapse">
      <summary><strong>DH 607 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>
            This repository contains assignments and a final project for DH 607, covering probability, statistics, alignment algorithms, HMMs, and RNA-Seq quantification for analyzing real biological datasets.<br>
            The coursework builds core skills in quantitative biology through topics such as PCR modeling, BLAST scoring, BWT and suffix structures, and transcript-level expression analysis.<br>
            Assignments include probabilistic reasoning, sequence alignment, string algorithms, hidden Markov models, and normalization methods like RPKM and TPM.<br>
            The final project performs a multi-omics investigation of Mycobacterium tuberculosis, integrating genomic, transcriptomic, and miRNA data to study disease mechanisms.<br>
            It analyzes host immune activation signatures, MTB drug-resistance mutations, and structural modeling of KatG and EmbB variants to explain phenotype-level antibiotic resistance.<br>
            Overall, the repository demonstrates a full pipeline of computational biology techniques, from raw sequencing concepts to advanced multi-omics interpretation.
          </p>
          <a href="https://github.com/Amolpagare10/DH_607_Intro_to_Computational_Multiomnics" target="_blank">🔗 https://github.com/Amolpagare10/DH_607_Intro_to_Computational_Multiomnics</a>
        </div>
      </div>
    </details>
  </ul>
<!-- </div> -->
