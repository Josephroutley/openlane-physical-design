# OpenLane Physical Design & DFT

## Project Overview
This project takes the RTL from the `systolic-array-accelerator` and pushes it through the **OpenLane** open-source ASIC flow to generate a manufacturable GDSII layout.

It focuses on the "Back-End" of chip design: Synthesis, Floorplanning, Placement, Routing, and Sign-off.

## Learning Objectives (NVIDIA Target Skills)
* **DFT (Design For Test):** Inserting Scan Chains to make the chip testable.
* **Physical Design:** Floorplanning, Clock Tree Synthesis (CTS), and Routing.
* **STA (Static Timing Analysis):** Analyzing Setup and Hold time violations.
* **Tcl Scripting:** Automating the flow using Tcl scripts.

## Tools & Tech Stack
* **Flow:** OpenLane (based on OpenROAD)
* **PDK:** SkyWater 130nm (open source Process Design Kit)
* **Scripting:** Tcl, Python

## Roadmap
- [ ] Configure OpenLane for the Systolic Array design.
- [ ] **DFT:** Enable Scan Chain insertion in the synthesis configuration.
- [ ] **Floorplanning:** Define core area and IO pin placement.
- [ ] Run the flow to GDSII.
- [ ] **Analysis:** Review Timing (STA) and Power reports.
- [ ] **Failure Analysis:** Fix any setup/hold violations by adjusting constraints.
