# Dual-Clock-Asynchronous-FIFO
. Designed an asynchronous dual-port FIFO using double flop synchronizers to avoid metastability issues
◦ Incorporated Gray encoding for inter clock domain control data transfer to avoid multi-bit signal transitions
◦ Verified the Verilog RTL design for write full and read empty test cases in Xilinx Vivado tool

![image](https://github.com/chetan1107/Dual-Clock-Asynchronous-FIFO/assets/138870448/1b1995ed-0e6a-457a-97c9-19863dbe840a)

![image](https://github.com/chetan1107/Dual-Clock-Asynchronous-FIFO/assets/138870448/42b2d768-d545-48ea-a7b7-fd45cbc651c2)

  **Dual n-bit Gray code counter block diagram**

                                           **Vivado Project** 
![image](https://github.com/chetan1107/Dual-Clock-Asynchronous-FIFO/assets/138870448/ed4db163-c4d3-4b20-beb8-e6369f93c875)

                       
![image](https://github.com/chetan1107/Dual-Clock-Asynchronous-FIFO/assets/138870448/40ef06ab-7a33-4a51-8b33-02d4a882e086)
 **Behavioural  Simulation Result for the Testbench attached**


***Results***:
◦ Designed Asynchronous FIFO in Verilog, synthesised & verified the design in Xilinx Vivado.
◦ Synchronization of FIFO pointers is accomplished using Gray Code to avoid multi-bit signal transitions.
◦ Implemented 2 Flip-Flop Synchronizer to avoid meta-stability issues in CDC


***Reference*** - Simulation and Synthesis Techniques for Asynchronous FIFO Design ,Clifford E. Cummings, Sunburst Design, Inc. 
