# OpenSource_Physical_Design
  This repository contains all the information studied and created during the [Advanced Physical Design Using OpenLANE / SKY130](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/) workshop.

# Table of Contents
  - [Introduction To RISC-V ISA](#Introduction-to-risc-v-isa)
  - [Compiler Toolchain](#compiler-toolchain)
  - [Application Binary Interface](#application-binary-interface)
  - [RTL Design Using TL-Verilog and MakerChip](#rtl-design-using-tl-verilog-and-makerchip)
      - [Designing a Simple Calculator](#designing-a-simple-calculator)
      - [Pipelining the Calculator](#pipelining-the-calculator)
      - [Adding Validity to Calculator](#adding-validity-to-calculator)
  - [Basic RISC-V Core](#basic-risc-v-core)
      - [Program Counter and Instruction Fetch](#program-counter-and-instruction-fetch)
      - [Instruction Decode and Read Register File](#instruction-decode-and-read-register-file)
      - [Execute Instruction and Write Register File](#execute-instruction-and-write-register-file)
  - [Pipelined RISC-V Core](#pipelined-risc-v-core)
  - [Final 4-Stage RISC-V Core](#final-4-stage-risc-v-core)
      - [Final RISC-V Core](#final-risc-v-core)
      - [Code Comparison](#code-comparison)
  - [Future Work](#future-work)
  - [References](#references)
  - [Acknowledgement](#acknowledgement)
 
# List of All Open-Source Tools Used:
  | Name of Tool | Application / Usage |
  | --- | --- |
  | Yosys | Synthesis of RTL Design |
  | ABC | Mapping of Netlist |
  

# References
  - RISC-V ISA Manual: https://github.com/riscv/riscv-isa-manual/
  - RISC-V: https://riscv.org/
  - VLSI System Design: https://www.vlsisystemdesign.com/

# Acknowledgement
  - [Kunal Ghosh](https://github.com/kunalg123), Co-founder, VSD Corp. Pvt. Ltd.
  
