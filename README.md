# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

Open Quartus Prime software.

Create a new project and include a Verilog file for the 4-bit ripple counter.

Write the Verilog code for the 4-bit ripple counter using T flip-flops.

Compile the project to check for errors.

Simulate the design to observe the waveform outputs.

Compare the output against the truth table to verify functionality.

Generate the RTL schematic and timing diagrams.



**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.
![Screenshot 2024-12-18 153843](https://github.com/user-attachments/assets/3f60d9a7-363a-4183-b5c7-4ba21d5e48c4)

 Developed by:THAMIZH.S RegisterNumber:24900483
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-18 153711](https://github.com/user-attachments/assets/6f726067-3bfd-491a-9e88-bc9517859bd9)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-18 153827](https://github.com/user-attachments/assets/4a6eb076-a4bd-4fe4-9010-11be23df0287)
**RESULTS**

