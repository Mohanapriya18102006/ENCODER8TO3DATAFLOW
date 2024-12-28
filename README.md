### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3



**PROGRAM**

Developed by:MOHANA PRIYA R   Register number:24900710

![Screenshot (219)](https://github.com/user-attachments/assets/45615572-e3cd-4d2b-a00a-b6a11a4d558f)


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**


![Screenshot (220)](https://github.com/user-attachments/assets/c1024dd0-e79e-4302-927c-83493fef010b)



**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**


![Screenshot (221)](https://github.com/user-attachments/assets/a896a992-0e6b-4888-87bf-bb7a84ef42d4)

**RESULTS**


Thus the encoder 8:3 dataflow has studied and verified successfully using quartus software.



