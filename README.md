# Hi, I'm Minseo Kim

Electrical Engineering & Physics student at Sogang University.

I am interested in hardware-software co-design for efficient computing systems, with a foucs on FPGA accelerators, embedded platforms, and system-level performance analysis.

---

## Featured Projects

### FPGA Systolic Array AI Accelerator

INT8 systolic-array accelerator implemented on a Xilinx Zynq SoC.

- Designed a systolic-array architecture in Verilog for matrix-multiplication workloads
- Implemented HW-SW co-design using AXI DMA on Zynq platform
- Performed Roofline modeling and runtime analysis
- Identified memory- and host-bound bottlenecks limiting system performance
- Integrated INT8 quantization (PTQ, selective QAT) for MobileNetV2 deployment, analyzing the trade-off between accuracy and hardware efficiency

### STM32 Real-Time Embedded System

Multi-peripheral embedded system implemented on STM32F103RB with an interrupt-driven architecture.

- Designed an interrupt-based firmware architecture coordinating GPIO, ADC (DMA), USART, and timers
- Implemented a state-machine-based user interface for clock, temperature monitoring, and passcode doorlock
- Separated keypad input and main logic using USART-based dual-board communication
- Used ADC + DMA for non-blocking temperature sampling
- Implemented flash memory storage for persistent password management
- Focused on real-time system design, avoiding blocking delays and ensuring responsive user interaction

---

## Interests

- FPGA & Hardware Acceleration
- Embedded Systems
- Edge AI Deployment
- System Performance Analysis
