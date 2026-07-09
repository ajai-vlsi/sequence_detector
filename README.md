# sequence_detector
# Sequence Detector using Verilog HDL

## Overview

This project implements a **Sequence Detector** in **Verilog HDL** and verifies its functionality using **QuestaSim (Intel FPGA Edition)**. The design detects a predefined input bit sequence and generates an output pulse whenever the target sequence is recognized.

This project was developed as part of my learning journey in **Digital Electronics** and **Verilog HDL**. During the process, I learned how to write RTL code, create a testbench, simulate the design, analyze waveforms, and debug common simulation issues in QuestaSim.

---

## Project Objectives

* Design a sequence detector using Verilog HDL.
* Develop a testbench to verify the functionality.
* Simulate the design using QuestaSim.
* Analyze simulation waveforms to confirm correct sequence detection.

---

## Tools Used

* **Verilog HDL**
* **QuestaSim (Intel FPGA Edition)**
* **Intel Quartus Prime Lite** (Project Management)

---

## Project Files

* `seq_det.v` – Sequence Detector RTL design
* `tb_seq_det.v` – Testbench for functional verification
* `waveform.png` – Simulation waveform
* `README.md` – Project documentation

---

## Simulation

The design was compiled and simulated successfully in **QuestaSim**. The waveform confirms that the output is asserted whenever the required input sequence is detected.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Writing synthesizable Verilog code
* Creating Verilog testbenches
* Clock and reset generation
* Running simulations in QuestaSim
* Reading and interpreting timing waveforms
* Debugging compilation and simulation errors
* Understanding the behavior of sequential logic circuits

---

## Future Improvements

* Implement overlapping sequence detection.
* Parameterize the sequence for greater flexibility.
* Verify the design using SystemVerilog assertions.
* Extend the project using Finite State Machine (FSM) implementation.

---

## Author
**Ajai A.**
Final Year B.Tech – Electrical and Electronics Engineering (EEE)
Interested in **VLSI Design**, **RTL Design**, and **Design Verification**.
Thank you for visiting this repository. Feedback and suggestions are always welcome.
