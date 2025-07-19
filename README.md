UART Transmitter using Verilog
This project implements a UART Transmitter using Verilog HDL. The design uses a Finite State Machine (FSM) to transmit 8-bit serial data over a single line at a baud rate of 9600.

📁 Files Included
uart_tx.sv – Main UART Transmitter module

testbench_uart_tx.sv – Testbench to simulate transmission

uart_tx_output_waveform.png – Simulation waveform output

🧪 Simulation
The transmitter is tested using a SystemVerilog testbench. It simulates data transmission with proper start, data, and stop bits. The waveform shows the transmission behavior and tx_busy signal status.

💡 Tools Used
Language: SystemVerilog

Simulator: EDA Playground / ModelSim

Waveform Viewer: GTKWave

📸 Screenshot
uart_tx_output_waveform.png


🔖 Tags
#UART #Verilog #FSM #VLSI #DigitalDesign #MiniProject
