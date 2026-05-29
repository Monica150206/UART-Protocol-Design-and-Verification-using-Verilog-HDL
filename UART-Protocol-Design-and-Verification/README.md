UART Protocol Design and Verification using Verilog HDL

This project implements a Universal Asynchronous Receiver Transmitter (UART) communication system using Verilog HDL. The design consists of a Baud Rate Generator, UART Transmitter, and UART Receiver modules. Finite State Machines (FSMs) are used to control serial data transmission and reception.

The transmitter converts parallel input data into serial format and sends it through the TX line, while the receiver reconstructs the serial data back into parallel form. A baud rate generator is used to synchronize data transfer timing between transmitter and receiver.

The complete design was verified using a Verilog testbench and simulated in EDA Playground with waveform analysis in EPWave. The simulation successfully demonstrated accurate UART communication by transmitting and receiving 8-bit data.

Features:
• Baud rate generation
• UART serial communication
• FSM-based transmitter and receiver
• Start and stop bit handling
• Waveform verification using EPWave
• Verilog HDL implementation and simulation

Tools Used:
• Verilog HDL
• EDA Playground
• EPWave

Applications:
• Embedded systems
• FPGA communication
• Microcontroller interfaces
• Serial communication systems
• IoT devices