# AXI Streaming IP Core – Vivado Block Design Project

This repository contains an AXI4-Stream FIFO design implemented and exported from **Xilinx Vivado** using the **IP Integrator (Block Design)** flow.

## Project Overview

The project implements an **AXI4-Stream FIFO** IP core designed for high-throughput streaming data applications in FPGA systems. It uses **asynchronous FIFO logic** to decouple AXIS master and slave clock domains.

>  **Note**: The Verilog files included in this repository (such as `axis_fifo_v1_0.v`) are **wrapper files auto-generated** by Vivado as part of the IP packaging process.

##  Vivado IP Packaging Flow

This project was built using:

- **Vivado 2024.2**
- **Create and Package IP** workflow
- A **Block Design**-based approach (IP Integrator)

The actual logic and AXI interfaces were defined in the block design environment. After packaging, the IP was exported and integrated into other designs via the IP catalog.



