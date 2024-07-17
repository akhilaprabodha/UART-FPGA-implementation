# UART Module on FPGA Platform 🚀

This repository contains the implementation of a Universal Asynchronous Receiver/Transmitter (UART) module on an FPGA platform. This project was undertaken as part of the EN2111 - Electronic Circuit Design module at the Department of Electronic & Telecommunication Engineering, University of Moratuwa, Sri Lanka.

## Project Overview 📚

The goal of this project was to design and implement a UART communication system using an FPGA. The system facilitates serial communication between the FPGA and external devices, following the UART protocol standards. The project was carried out in four distinct phases:

### Phase 1: Requirement Analysis 📝

- Identified the key requirements for the UART module.
- Defined the communication parameters such as baud rate, data bits, parity bits, and stop bits.
- Established the criteria for error detection and handling.

### Phase 2: Design and Simulation 🛠️

- Developed the initial design using VHDL/Verilog.
- Created testbenches to simulate the UART module functionality.
- Verified the design through extensive simulation to ensure accurate operation.

### Phase 3: Synthesis and Implementation 💻

- Synthesized the VHDL/Verilog code using FPGA development tools.
- Implemented the design on an FPGA development board.
- Conducted hardware testing to validate the functionality of the UART module.

### Phase 4: Testing and Validation ✅

- Performed comprehensive testing with various baud rates and frame formats.
- Ensured reliable data transmission with error detection mechanisms.
- Documented the results and prepared the final project report.

## Team Members 👥

- [Akhila Prabodha]()
- [Shemal Perera]()
- [Dineth Perera]()

## Features ✨

- **Baud Rate Control**: Configurable baud rate for versatile communication speed.
- **Data Framing**: Supports different frame formats including start, stop, and parity bits.
- **Error Detection**: Implements parity checking for reliable data transmission.
- **Hardware Implementation**: Fully synthesized and tested on FPGA hardware.

## Getting Started 🚀

### Prerequisites

- **FPGA Development Board**: Ensure you have access to a compatible FPGA board.
- **Development Environment**: Use tools like Xilinx Vivado or Altera Quartus for synthesizing and programming the FPGA.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/akhilaprabodha/UART-FPGA.git
    ```
2. Open the project in your preferred FPGA development environment.
3. Synthesize and implement the design on your FPGA board.

## Usage 📖

1. Connect the FPGA to your computer using a serial cable.
2. Open a terminal program (e.g., PuTTY, Tera Term) and configure the serial connection parameters.
3. Program the FPGA with the synthesized bitstream.
4. Begin communication by sending and receiving data through the terminal.

## Contributing 🤝

We welcome contributions to enhance the UART module. Feel free to fork the repository and submit pull requests.

## Acknowledgments 🙏

We would like to thank our lecturer, [Lecturer's Name], for the guidance and support throughout this project.
