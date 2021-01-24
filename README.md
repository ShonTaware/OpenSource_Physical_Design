# OpenSource Physical Design
  This repository contains all the information studied and created during the [Advanced Physical Design Using OpenLANE / SKY130](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/) workshop.

# Table of Contents
  - [Introduction To RTL to GDSII](#introduction-to-rtl-to-gdsii)
  - [Setting Up Environment](#setting-up-environment)
  - [Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK](#day-1-inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [Basics of Physical IC Design](#basics-of-physical-ic-design)
      - [Basic IC Terminologies](#basics-ic-terminologies)
      - [Introduction To RISC-V](#introduction-to-risc-v)
    - [SoC Design and OpenLANE](#soc-design-and-openlane)
    - [Open-Source EDA Tools](#open-source-eda-tools)
      - [OpenLANE Setup](#openlane-setup)
      - [Design Preparation](#design-preparation)
      - [Design Synthesis and Results](#design-synthesis-and-results)
  - [Day 2 - Good floorplan vs bad floorplan and introduction to library cells](#day-2-good-floorplan-vs-bad-floorplan-and-introduction-to-library-cells)
  - [Day 3 - Design library cell using Magic Layout and ngspice characterization](#day-3-design-library-cell-using-magic-layout-and-ngspice-characterization)
  - [Day 4 - Pre-layout timing analysis and importance of good clock tree](#day-4-pre-layout-timing-analysis-and-importance-of-good-clock-tree)
  - [Day 5](#day-5)
  - [Future Work](#future-work)
  - [References](#references)
  - [Acknowledgement](#acknowledgement)
 
# List of All Open-Source Tools Used:
  | Name of Tool | Application / Usage |
  | --- | --- |
  | [Yosys](https://github.com/YosysHQ/yosys) | Synthesis of RTL Design |
  | ABC | Mapping of Netlist |
  | [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) | Static Timing Analysis |
  | [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) | Floorplanning, Placement, CTS, Optimization, Routing |
  | [Magic VLSI](http://opencircuitdesign.com/magic/) | Layout Tool |
  

# References
  - RISC-V: https://riscv.org/
  - VLSI System Design: https://www.vlsisystemdesign.com/
  - Digital Integrated Circuits: A Design Perspective by Jan M. Rabaey, Anantha P. Chandrakasan

# Acknowledgement
  - [Kunal Ghosh](https://github.com/kunalg123), Co-founder, VSD Corp. Pvt. Ltd.
  - [Nickson Jose](https://github.com/nickson-jose)
  
