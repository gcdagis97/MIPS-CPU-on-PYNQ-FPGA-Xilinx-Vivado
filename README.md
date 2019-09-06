# MIPS-CPU-on-PYNQ-FPGA-Xilinx-Vivado

This project outlines the bottom-up design of a MIPS processor as well as its
implementation onto a PYNQ-Z1 board. The MIPS processor discussed within the project is
designed in verilog and has been simulated on EDA Playground in order to test functionality
prior to implementing onto the PYNQ board. After debugging the processor, it was then
implemented onto the PYNQ board using Xilinx Vivado Design Suite 2018.3. The MIPS
processor code was altered in order to light up LEDs corresponding to certain values outputted
by the ALU. The Software Development Kit (SDK) was used in order to create an First
Stage Boot Loader (FSBL) which allowed for the code to run off an SD card rather than through
the USB port.
