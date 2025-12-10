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

<div class="tech-wrapper">

<div class="tech-hero">
  <h1 class="tech-title"><strong>Courses</strong> & <strong>Academic Work</strong> 📘</h1>
  <p class="tech-subtitle">
    A curated collection of my coursework at <strong>IIT Bombay</strong>.
  </p>

  <ul class="tech-subtitle">
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
          <a href="https://github.com/Amolpagare10/EE789_Algorithmic_Design_of_Digital_Systems" target="_blank">🔗 https://github.com/Amolpagare10/EE789_Algorithmic_Design_of_Digital_Systems</a>
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
    <li><strong>EE 705 — VLSI Design Lab</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 705 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE705" target="_blank">🔗 github.com/.../EE705</a>
        </div>
      </div>
    </details>
    <!-- EE 678 -->
    <li><strong>EE 678 — Wavelets & Multirate DSP</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 678 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE678" target="_blank">🔗 github.com/.../EE678</a>
        </div>
      </div>
    </details>
    <!-- EE 677 -->
    <li><strong>EE 677 — VLSI CAD</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 677 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE677" target="_blank">🔗 github.com/.../EE677</a>
        </div>
      </div>
    </details>
    <!-- EE 671 -->
    <li><strong>EE 671 — VLSI Design</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 671 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE671" target="_blank">🔗 github.com/.../EE671</a>
        </div>
      </div>
    </details>
    <!-- EE 669 -->
    <li><strong>EE 669 — VLSI Technology</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 669 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE669" target="_blank">🔗 github.com/.../EE669</a>
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
    <li><strong>EE 344 — Electronic Design Lab</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>EE 344 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/EE344" target="_blank">🔗 github.com/.../EE344</a>
        </div>
      </div>
    </details>
    <!-- EE 309 -->
    <li><strong>EE 309 — Microprocessors (CISC & RISC)</strong><br>Short course summary here.</li>
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
    <li><strong>DH 607 — Introduction to Computational Multi-Omics</strong><br>Short course summary here.</li>
    <details class="gh-collapse">
      <summary><strong>DH 607 — Repository Info</strong></summary>
      <div class="collapse-outer">
        <div class="gh-box gh-info collapse-body">
          <p><strong>📦 Repository:</strong></p>
          <p>Description of repo + main work done.</p>
          <a href="YOUR_GITHUB_LINK/DH607" target="_blank">🔗 github.com/.../DH607</a>
        </div>
      </div>
    </details>
  </ul>
</div>
</div> <!-- tech-wrapper -->
