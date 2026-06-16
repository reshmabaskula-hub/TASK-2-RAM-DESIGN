# TASK-2-RAM-DESIGN
# Abstract
Random Access Memory (RAM) is an essential component of digital systems used for temporary storage of data. RAM allows data to be written into memory locations and read back whenever required. In this project, a simple synchronous RAM module is designed using Verilog HDL. The RAM supports both read and write operations controlled by a clock signal. The design is verified using a testbench and simulation results are analyzed to confirm proper memory functionality.
The developed RAM consists of 16 memory locations with each location capable of storing 8-bit data. Read and write operations occur synchronously with the clock, making the design suitable for digital systems such as processors, controllers, and embedded applications.
# Introduction
Memory plays a vital role in modern digital systems. Processors require memory to store instructions, variables, and intermediate results during execution. RAM is a type of volatile memory that allows fast access to stored information.
A Synchronous RAM performs all operations in synchronization with a clock signal. Unlike asynchronous memory, where outputs can change immediately with input changes, synchronous RAM updates its contents only at clock edges. This provides improved timing control and reliability in digital circuits.
In this project, a simple synchronous RAM is designed and implemented using Verilog HDL. The RAM supports both writing data into memory and reading data from memory using a common address bus.
# Objectives
The objectives of this project are:
• To understand the architecture and operation of Random Access Memory.
• To design a synchronous RAM using Verilog HDL.
• To implement read and write operations.
• To understand clock-controlled memory behavior.
• To develop a testbench for verification.
• To simulate and analyze RAM functionality.
• To gain practical knowledge of memory design in digital systems.
# Problem Statement
Design a simple synchronous RAM module with the following features:
• 16 memory locations.
• Each location stores 8-bit data.
• Supports write operation.
• Supports read operation.
• Operates synchronously with the clock signal.
• Verify functionality through simulation.
# Theory
# What is RAM?
Random Access Memory (RAM) is a storage device that allows direct access to any memory location. Unlike sequential storage devices, RAM provides equal access time to all locations.
RAM is commonly used for:
• Temporary data storage
• Program execution
• Buffer memory
• Cache memory
• Embedded system applications
# Synchronous RAM
In synchronous RAM, all operations are performed on the active edge of the clock signal.
Advantages include:
• Predictable timing
• Reliable operation
• Easy integration with processors
• Better synchronization
# RAM Architecture
The RAM consists of:
# Memory Array
Stores data values
Memory[0]
Memory[1]
Memory[2]
...
Memory[15]
Each location stores 8 bits.
# Address Bus
Used to select a specific memory location.
For 16 locations:
Address Width = 4 bits
Because:
2^4 = 16
# Data Input
Used to write data into memory.
din[7:0]
# Data Output
Used to read stored data.
dout[7:0]
Write Enable Signal
Controls writing operation.
we = 1 → Write
we = 0 → Read
# Result Analysis
The simulation confirms correct RAM operation.
During the write phase:
• Data AA is stored at address 1.
• Data 55 is stored at address 2.
During the read phase:
• Address 1 returns AA.
• Address 2 returns 55.
This verifies successful read and write functionality.
# Applications
• Microprocessors
• Cache Memory
• Embedded Systems
• FPGA Designs
• Digital Signal Processing
• Communication Systems
• Industrial Controllers
• Computer Memory Systems
# Advantages
• Simple architecture
• Fast memory access
• Clock synchronized operation
• Reliable performance
• Easy FPGA implementation
• Scalable design
# Limitations
• Volatile memory
• Limited memory size
• Data lost after power-off
# Future Scope
• Increase memory size
• Dual-port RAM design
• Add reset functionality
• Implement FIFO memory
• Design high-speed memory architecture
• Integrate with processor systems
# Conclusion
A 4-tap Finite Impulse Response (FIR) filter was successfully designed and simulated using Verilog HDL. The filter processed digital input samples using predefined coefficients and generated filtered outputs through weighted summation. Simulation results verified correct filter operation and demonstrated the effectiveness of FIR filtering techniques. The project provided practical experience in digital signal processing, hardware description language design, and simulation-based verification. The knowledge gained from this project can be extended to advanced DSP systems, FPGA implementations, and communication applications.
