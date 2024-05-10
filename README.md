# VHDL UART Implementation

This repository contains VHDL code for UART (Universal Asynchronous Receiver/Transmitter) communication. The code implements UART transmitter (TX), receiver (RX), and a sender module.

## Introduction

This VHDL code provides a complete implementation of UART communication, featuring a transmitter, a receiver, and a sender module. UART is a widely used asynchronous serial communication protocol, commonly used for interfacing microcontrollers with peripherals, such as sensors, displays, and other devices.

### Features

- UART transmitter (TX) module
- UART receiver (RX) module
- Sender module for transmitting data over UART

## Usage

To use this VHDL code, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using `git clone https://github.com/yourusername/your-repository.git`.

2. **Open in a VHDL IDE**: Open the VHDL files in your preferred VHDL integrated development environment (IDE) such as Xilinx ISE, Vivado, or Quartus Prime.

3. **Simulate (Optional)**: Optionally, simulate the design to verify its functionality before synthesis and implementation on a target FPGA (ZYBO Board) / You can modify sender to change what ascii data you want to send.

4. **Synthesize and Implement**: Synthesize and implement the design on your target FPGA platform.
   
5. **Hardware Testing**: Connect your FPGA board to the UART peripheral you wish to communicate with, and verify the UART communication using appropriate testing methods using terminal command (-minicom -b 15200 -D /dev/ttyUSB). You can figure out what device your USB corresponds to using
   (dmesg grep | ttyUSB). 
   


