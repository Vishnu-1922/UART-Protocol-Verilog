# UART-Protocol-Verilog
**UART Protocol Design and Verification**

Project Overview:
This project implements a UART (Universal Asynchronous Receiver Transmitter) communication system in Verilog HDL.

The design includes:
UART Transmitter,
UART Receiver,
Baud Rate Generation,
Loopback Verification Environment,
Functional Simulation.

Features:
FSM-Based UART Design,
Configurable Baud Rate (9600 bps),
Start Bit Detection,
Stop Bit Detection,
Serial Data Transmission,
Serial Data Reception,
Loopback Testing.

Architecture:

UART TX ---> Serial Line ---> UART RX

Verification:
Test Pattern:
Transmit Data = 0xA5,
Receive Data  = 0xA5.

Verification confirms:
Correct transmission,
Correct reception,
tx_busy operation,
newrx indication.

Tools Used:
Verilog HDL,
Vivado Simulator.

Skills Demonstrated:
RTL Design,
FSM Design,
Digital Design,
Functional Verification,
UART Protocol.
