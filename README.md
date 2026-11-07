# Digital_Queue_Management_System
A Verilog-based digital queue management system with automatic token generation and priority handling.
# Verilog-Based Digital Queue Management System with Automatic Token Generation and Priority Handling

## Project Overview
This project implements a digital queue management system using Verilog HDL. It automatically generates tokens for customers and manages them using the First-In-First-Out (FIFO) method. It also supports priority handling, where priority requests are served before normal requests.

The design is simulated using EDA Playground with the Riviera-PRO simulator.

## Features
- Automatic token generation.
- FIFO-based normal queue management.
- Priority request handling.
- Priority tokens are served before normal tokens.
- Queue full and queue empty detection.
- Rejection of new requests when the queue is full.
- Reset functionality.
- Simultaneous token request and service operation.

## Tools Used
- **Verilog HDL** – RTL design.
- **EDA Playground** – Online simulation platform.
- **Riviera-PRO** – Verilog simulation.
- **Cadence** – Simulation and synthesis.

## Project Files
- `design.v` – Main Verilog design module.
- `testbench.sv` – Testbench for verifying the design.
- `Simulation_Screenshots/` – Simulation output and waveform screenshots.
- `Cadence_Screenshots/` – Cadence screenshots.

## Simulation
The testbench verifies:
- Normal token generation.
- Priority token generation and serving.
- FIFO serving order.
- Queue full condition.
- Rejection of requests when the queue is full.
- Reset operation.
- Simultaneous request and service operation.

## Conclusion
The project demonstrates a simple digital queue management system using Verilog HDL. It combines automatic token generation, FIFO queue management, and priority handling through RTL design and simulation.
