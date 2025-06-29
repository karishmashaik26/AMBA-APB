# AMBA-APB
# 🚀 AMBA APB Interface – Verilog Implementation

This repository contains the Verilog HDL implementation and simulation of an **AMBA APB (Advanced Peripheral Bus)** compliant interface module suitable for low-frequency domain applications.

## 📘 Project Title

**Implementation of an AMBA APB Compliant Interface Module for Low Frequency Domains**

> Submitted in partial fulfillment of the requirements for the B.Tech degree in **Electronics and Communication Engineering**, CMRCET.

---

## 👨‍💻 Team Members

- Shaik Karishma (23H55A0426)  
- MD. Faisal (22H51A0442)  
- A. Srihitha (22H51A04D0)  
- M. Likitha (22H51A04P3)  
- S. Harish (22H51A04R2)  

Under the guidance of **Mrs. V. Anusha**, Assistant Professor, ECE Dept.

---

## 📂 Contents

- `apb_dut.v` – Verilog code for APB-compliant slave
- `apb_tb.v` – Testbench to verify APB module functionality
- `report.pdf` – Complete project report (literature, architecture, FSM, waveforms)
- `README.md` – Project overview
- *(Optional)* `apb_interface.slx` – Simulink design file (if used)

---

## 📌 Features

- Implements IDLE, SETUP, ACCESS states as per AMBA APB protocol
- Synchronized with rising edge of `PCLK`
- Supports read/write operations with `PREADY`, `PSLVERR` signaling
- Testbench with realistic simulation scenario
- FPGA synthesizable (low resource footprint)

---

## 🧪 Simulation Results

Testbench validates:
- Write and read transactions with correct address/data handling
- Protocol compliance through PSEL, PENABLE, and control signals
- Zero error conditions and stable operation in low-frequency domain

---

## 📈 Future Enhancements

- Add clock gating for low-power operation
- Support multiple slaves via APB decoder
- Implement UVM-based advanced verification
- Upgrade to APB v5 / bridge to AHB/AXI master

---

## 📎 References

- [ARM AMBA APB Specification](https://developer.arm.com/documentation/ihi0033)
- Michael D. Ciletti – *Advanced Digital Design with Verilog HDL*
- IEEE 1800-2017 SystemVerilog Standard
- [ASICWorld – AMBA Tutorial](http://www.asic-world.com/verilog/amba3.html)

---
