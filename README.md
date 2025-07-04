COMPANY: CODTECH IT SOLUTIONS

NAME: GOVINDA MAHARANA

INTERN ID: CT04DF2309

DOMAIN: VLSI

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

# DESCRIPTION OF TASK 2

Develop a Simple Synchronous RAM Module with Read and Write Operations
In the second task, the objective was to design a Synchronous RAM (Random Access Memory) module in Verilog, with both read and write capabilities. RAM is a vital part of any computing system, as it stores both data and instructions temporarily while the system is powered on.

For this project, I used Verilog for implementation and ModelSim for simulation. The editor used was Visual Studio Code, where I managed all .v files (Verilog source files) and .tb.v testbench files. The RAM module was designed as a synchronous system, meaning all operations (reads/writes) occur on the rising edge of the clock signal.

The module accepts inputs like:

address: to point to the memory location

data_in: data to be written

we: write enable signal

clk: clock signal

data_out: output from the addressed memory location

To simulate memory behavior, I used an array to represent memory cells (e.g., reg [7:0] mem[0:15]; for 16 memory locations of 8 bits). The read and write operations were handled inside an always @(posedge clk) block to ensure clock-synchronized access.

A testbench was written to verify functionality. I tested various scenarios like:

Writing to different memory locations

Reading back data from the same addresses

Checking whether write operations overwrite previous values correctly

Ensuring reads do not affect memory content

This task holds immense relevance in modern electronics. RAM modules are essential in FPGAs, microcontrollers, and SoC (System on Chip) designs. Understanding how synchronous memory works is crucial for designing reliable systems with predictable timing behavior.

By completing this task, I gained knowledge about:

Memory architecture

Clock synchronization

Data flow control

Use of conditional statements and timing control in Verilog

The task can be applied to create larger memory modules (like SRAM blocks), which are used in high-speed cache memories inside CPUs, GPUs, and embedded systems. This also serves as a stepping stone to understanding and implementing more advanced memory concepts like DRAM, FIFO buffers, and even memory-mapped I/O systems.

#OUTPUT 

![Image](https://github.com/user-attachments/assets/228708fc-06d6-4382-b9b5-4755f98b5b4b)
