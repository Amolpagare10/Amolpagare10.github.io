---
layout: single
title: "Courses"
permalink: /courses/
author_profile: true
classes: wide
custom_css: courses.css
---

<div class="tech-bg"></div>
<div class="circuit-lines"></div>

<div class="tech-wrapper">

<div class="tech-hero">
  <h1 class="tech-title">📘 Courses & <strong>Academic Work</strong>
  </h1>
  <p class="tech-subtitle">
    A curated collection of coursework at <strong>IIT Bombay</strong>, covering  
    <span class="chip-tag">Computer Architecture</span>
    <span class="chip-tag">VLSI Design</span>
    <span class="chip-tag">CAD Tools</span>
    <span class="chip-tag">Embedded Systems</span>
    <span class="chip-tag">DSP & ML</span>
  </p>
</div>

## <span class="section-title">EE 451 — Supervised Research (Autumn ’25)</span>
<div class="tech-card">
  <p><strong>Advisor:</strong> Prof. Laxmeesha Somappa</p>
  <ul>
    <li>Implemented a full <strong>RISC-V SoC</strong> with KianV core on FPGA.</li>
    <li>Designed FPGA top-level, constraints, bitstream generation.</li>
    <li><strong>Successfully booted Linux</strong> on the SoC running on Pynq-Z2.</li>
  </ul>
</div>

## <span class="section-title">EE 669 — VLSI Technology (Autumn ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Anil Kottantharayil</p>
  <ul>
    <li>Simulated oxidation, diffusion & implantation using <strong>Sentaurus</strong>.</li>
    <li>Analyzed Deal–Grove/Massoud models & dopant junction behavior.</li>
    <li>Optimized lithography (standing waves, proximity effects, PEB/ARC tuning).</li>
    <li>Explored CMOS integration: STI, gate-stack, high-k/metal gate flows.</li>
    <li>Studied fabrication of <strong>FinFET & GAAFET</strong> at advanced nodes.</li>
  </ul>
</div>

## <span class="section-title">EE 709 — Testing & Verification of VLSI Circuits (Autumn ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Madhav Desai</p>
  <ul>
    <li>Modeled Boolean functions & FSMs using <strong>cmubdd</strong>.</li>
    <li>Built optimized Mealy machines with don’t-care propagation.</li>
    <li>Performed structured <strong>ROBDD traversal</strong> for invertibility analysis.</li>
    <li>Ran <strong>SAT-based ATPG</strong> using Minisat to generate test vectors.</li>
    <li>Conducted deductive fault simulation for stuck-at defects.</li>
  </ul>
</div>

## <span class="section-title">EE 748 — Advanced Topics in Computer Architecture (Autumn ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Virendra Singh</p>
  <ul>
    <li>Characterized <strong>SPEC2006</strong> workloads via MPKI/APKI/IPC/LLC sensitivity.</li>
    <li>Developed custom <strong>LLC replacement policies</strong> (LRU-slow, LRU-6).</li>
    <li>Designed guided branch prediction using RVCF-style hints.</li>
    <li>Proposed GPU performance improvements via NL-DWF + register prefetching.</li>
  </ul>
</div>

## <span class="section-title">EE 789 — Algorithmic Design of Digital Systems (Spring ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Madhav Desai</p>
  <ul>
    <li>Implemented matrix multiplication variants in <strong>Algorithmic Assembly</strong>.</li>
    <li>Designed multipliers, dividers, sqrt units & parallel arithmetic modules.</li>
    <li>Built a <strong>4×4 output-queued switch</strong> supporting fair arbitration.</li>
    <li>Used Aa → hardware compilation (elastic pipelines, guarded actions).</li>
    <li>Generated cycle-accurate <strong>VHDL</strong> using the AHIR toolchain.</li>
  </ul>
</div>

## <span class="section-title">EE 705 — VLSI Design Lab (Spring ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Laxmeesha Somappa</p>
  <ul>
    <li>Designed & verified: Brent–Kung adder, Dadda multiplier, barrel shifter.</li>
    <li>Built arithmetic subsystems using BRAM, controllers, VIO.</li>
    <li>Implemented <strong>ALU DECODE</strong> for RISC-V 32IM.</li>
    <li>Built full <strong>RISC-V SoC</strong> with AXI, CSR, GPIO & UART subsystems.</li>
  </ul>
</div>

## <span class="section-title">EE 739 — Processor Design (Spring ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Virendra Singh</p>
  <ul>
    <li>Designed pipelined <strong>OoO superscalar processor</strong>.</li>
    <li>Implemented rename, issue, execute, commit with ROB.</li>
    <li>Designed hazard detection, stall/flush mechanisms, forwarding paths.</li>
    <li>Verified scheduling using reservation stations & load buffers.</li>
  </ul>
</div>

## <span class="section-title">EE 344 — Electronic Design Lab (Spring ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Siddharth Tallur</p>
  <ul>
    <li>Built <strong>EcoSync-8X</strong>, a dsPIC33A-based ultrasonic SHM platform.</li>
    <li>Developed 100 kHz excitation & sensing pipelines.</li>
    <li>Integrated dsPIC33 + ESP32 for wireless communication.</li>
    <li>Designed PCB using KiCAD & fabricated custom enclosure.</li>
  </ul>
</div>

## <span class="section-title">EE 671 — VLSI Design (Autumn ’24)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Laxmeesha Somappa</p>
  <ul>
    <li>Built Laplacian filter accelerator in Verilog.</li>
    <li>Designed Kogge-Stone adder, mux networks & clipping logic.</li>
    <li>Completed full <strong>OpenLane flow</strong>: synth → PnR → STA → DRC/LVS.</li>
    <li>Generated GDS-II, liberty & LEF views.</li>
  </ul>
</div>

## <span class="section-title">EE 677 — VLSI CAD (Autumn ’24)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Virendra Singh</p>
  <ul>
    <li>Built reversible logic circuits using <strong>PPRM</strong> expansions & Toffoli nets.</li>
    <li>Used priority-based heuristics for expansion minimization.</li>
    <li>Developed Verilog/EDIF-compatible logic simulator.</li>
  </ul>
</div>

## <span class="section-title">EE 678 — Wavelets & Multirate DSP (Autumn ’24)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Vikram Gadre</p>
  <ul>
    <li>Integrated <strong>DWT/IDWT</strong> into U-Net for sharper edge retention.</li>
    <li>Built dual wavelet pathways improving DICE & precision.</li>
    <li>Experimented with wavelet bases under compute constraints.</li>
  </ul>
</div>

## <span class="section-title">EE 309 — CISC & RISC Processor Design (Spring ’24)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Virendra Singh</p>
  <ul>
    <li>Designed a pipelined RISC processor with hazards & forwarding.</li>
    <li>Executed 26 instructions across six stages.</li>
    <li>Built decoders, hazard logic & FPGA prototype on Max-10.</li>
  </ul>
</div>

## <span class="section-title">DH 607 — Computational Multi-Omics (Autumn ’25)</span>
<div class="tech-card">
  <p><strong>Instructor:</strong> Prof. Saket Choudhary</p>
  <ul>
    <li>Implemented BWT, Needleman–Wunsch & suffix-based algorithms.</li>
    <li>Built multi-omics pipelines (variants + miRNA networks).</li>
    <li>Used <strong>Boltz docking</strong> to model mutation impacts.</li>
  </ul>
</div>


# <span class="tech-title">📚 Summary</span>
<div class="tech-card">
  <p>
    My coursework builds a strong foundation across:
  </p>
  <ul>
    <li><strong>Computer Architecture & RISC-V processors</strong></li>
    <li><strong>VLSI design, CAD flows & semiconductor process engineering</strong></li>
    <li><strong>FPGA systems & digital hardware design</strong></li>
    <li><strong>DSP, ML-based architectures & computational biology</strong></li>
  </ul>

  <p>
    These courses collectively shape my hardware–systems–VLSI skillset  
    and complement my research & project work.
  </p>
</div>

</div> <!-- tech-wrapper -->
