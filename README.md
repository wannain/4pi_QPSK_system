# QPSK Full Duplex Communications System

The design of this research project takes the design and implementation of QPSK modulation system on FPGA as the research direction, and establishes a complete communication system with transmitter and receiver. Here are the details in this system.

## How to design this system

- Transimitng Part

![image-20220902155042706](https://raw.githubusercontent.com/wannain/image/main/2022/09/upgit_20220902_1662105042.png)

- Receiving Part

  <img src="https://raw.githubusercontent.com/wannain/image/main/2022/09/upgit_20220902_1662105208.png" alt="image-20220902155328785" style="zoom:80%;" />

## How to run this project in simulink

This instruction is this communications system experiment by text demonstration. 

The total project is code by Matlab, I only use `slprj` to generarte cource control in different service time and arrive time. So if you want to run this project, you have to make sure you have placed `slprj` package into right location. 

And then you just run the `QPSK_system.m` to transimit the `test_input.txt`, and then wait the `QPSK_system.m` to receive the signal from QPSK system , and print the result into `test_out.txt` .

![image-20220902161633323](https://raw.githubusercontent.com/wannain/image/main/2022/09/upgit_20220902_1662106593.png)

In the simulation time frame,we set the simulation time as inf. Then, we just stick the Run button to start the software link, and wait a moment, click the Stop button or wait for the simulation to end. At last, double-click the Scope block to observe the waveform.

## Conclusions

- Based on FPGA platform,combined with QPSK principle,this communication system supports both compressed file and full duplex voice transmission. 
- A system that supports both compressed file and full duplex voice transmission leveraging MatLab on FPGA platform.
- Set up communication simulation leveraging MatLab on FPGA platform and actual link, including receiving and transmitting antenna.





