
## UART Transmitter using Verilog

This project implements a Finite State Machine (FSM) based UART Transmitter using Verilog HDL. It simulates the transmission of serial data (8-bit) over a single line with proper start and stop bits at a baud rate of 9600.

---

### 📁 Files Included

- `uart_tx.sv` – Main UART transmitter module  
- `testbench_uart_tx.sv` – Testbench to simulate the transmitter  
- `uart_tx_output_waveform.png` – Simulation waveform output  

---

### 🧪 Simulation

The transmitter is tested using a SystemVerilog testbench. The simulation includes sending a data byte, and visualizing start bit, 8-bit data, stop bit, and `tx_busy` signal. It ensures proper timing and bit serialization.

---

### 💡 Tools Used

- Language: SystemVerilog  
- Simulator: EDA Playground / ModelSim  
- Waveform Viewer: GTKWave  

---

### 📸 Screenshot

uart_tx_output_waveform.png

---

### 🔖 Tags  
#UART #Verilog #FSM #VLSI #DigitalDesign #MiniProject  
