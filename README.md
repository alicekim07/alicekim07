# Hi, I'm Minseo Kim

Electrical Engineering & Physics student at Sogang University.

I focus on understanding and optimizing system-level behavior in complex HW-SW integrated systems. 
My work centers on identifying performance gaps between theoretical compute capability and real-world execution, and analyzing how data movement, memory hierarchy, and system architecture impact overall performance.

Through FPGA-based AI accelerator design and embedded system development, I have built a strong foundation in system-level analysis, bottleneck identification, and HW-SW co-design.

---

## Featured Projects

### FPGA Systolic Array AI Accelerator

Designed and analyzed an INT8 systolic-array accelerator on a Xilinx Zynq SoC targeting MobileNetV2 workloads.

- Implemented a Verilog-based systolic array architecture and AXI DMA-based HW-SW interface
- Achieved high compute efficiency (~38× theoretical speedup), but observed limited end-to-end performance (~2.4×)
- Developed a runtime analysis framework with cycle-level instrumentation and Roofline modeling
- Identified that system performance was fundamentally limited by memory bandwidth and host-side overhead (memory/host-bound)
- Quantified the relationship between arithmetic intensity and performance scaling
- Explored INT8 quantization (PTQ and selective QAT), analyzing trade-offs between model accuracy and hardware efficiency

This project emphasized that system performance is not determined by compute throughput alone, but by the interaction between computation, memory, and data movement.

### STM32 Real-Time Embedded System

Developed an interrupt-driven embedded system on STM32F103RB.

- Designed a modular firmware architecture integrating GPIO, ADC (DMA), USART, and timers
- Implemented a state-machine-based control system for real-time interaction
- Used DMA-based ADC sampling for non-blocking data acquisition
- Built a dual-board communication system using USART

This project strengthened my understanding of how software interacts with hardware in real-time systems.

---

## Interests

- System-Level Performance Analysis in HW-SW Integrated Systems  
- Hardware-Software Co-Design for Efficient Computing  
- FPGA-Based Acceleration and Dataflow Architecture  
