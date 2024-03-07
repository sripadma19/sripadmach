functional Simulation. Veriog code is being executed and the waveforms are generated using the gtkwave Aim: To verify the Functional Simulation:- Table of contents 1.RISC-V RV32I

2.BLOCK DIAGRAM OF RISC-V RV32I

3.INSTRUCTION SET OF RISC-V RV32I

4.FUNCTIONAL SIMULATION

4.1 About iverilog and gtkwave 4.2 Installing iverilog and gtkwave 4.3 The output waveform

RISC-V RV32I This project provides an insight into the working of a few important instructions of the instruction set of a Single cycle Reduced Instruction Set Computer - Five(RISC-V) Instruction Set Architecture suitable for use across wide-spectrum of Applications from low-power embedded devices to high-performance Cloud-based Server processors. The base RISC-V is a 32-bit processor with 31 general-purpose registers, so all the instructions are 32-bit long. Some Applications where the RISC-V processors have begun to make some significant threads are in Artificial intelligence and machine learning, Embedded systems, ultra-low power processing systems, etc.

BLOCK DIAGRAM OF RISC-V RV32I 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/97e19623-c7d3-46d5-9904-1742d1159628)
INSTRUCTION SET OF RISC-V RV32I 





![image](https://github.com/sripadma19/sripadmach/assets/161410141/dff82442-57a7-4dba-9e4b-1ded6bca5cf5)

![image](https://github.com/sripadma19/sripadmach/assets/161410141/b687a06c-e3b5-463f-8016-3248303d9c99)



FUNCTIONAL SIMULATION 4.1 About iverilog and gtkwave Icarus Verilog is an implementation of the Verilog hardware description language. GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing

4.2 Installing iverilog and gtkwave For Ubuntu Open your terminal and type the following to install iverilog and GTKWave

$sudo apt get update $ sudo apt get install iverilog gtkwave

![image](https://github.com/sripadma19/sripadmach/assets/161410141/b40038c3-9829-4e2a-929a-e1d9c9ee0243)

To clone the repository and download the netlist files for simulation, enter the following commands in your terminal. $ git clone https://github.com/sripadma19/sripadmach
![image](https://github.com/sripadma19/sripadmach/assets/161410141/c8f232af-1544-44a7-880f-d0b06791963e)
4.3 The output waveform The output waveform showing the instructions performed in a 5-stage pipelined architecture.

Instruction 1:add r6,r2,r1
![image](https://github.com/sripadma19/sripadmach/assets/161410141/d5fb6c5f-3b2b-44ca-89d9-4ba408ca083a)
Instruction 2:sub r7,r1,r2
![image](https://github.com/sripadma19/sripadmach/assets/161410141/dd408711-c17d-4de4-8422-cfb73dbcae20)
Instruction 3:and r8,r1,r3

![image](https://github.com/sripadma19/sripadmach/assets/161410141/ab1b6873-b25a-4bb8-abbc-b1735099281e)
Instruction 4:or r9,r2,r5

![image](https://github.com/sripadma19/sripadmach/assets/161410141/e7a9492f-5ef7-4866-858d-425462ff93f3)
Instruction 5:xor r10,r1,r4 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/6f27e3bb-49ec-4934-af8d-ecad1596c767)
Instruction 6:slt r11,r2,r4 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/de69ae02-c550-4e86-9113-1e18ff8fe9d4)
Instruction 7:addi r12,r4,5 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/91029556-bf72-4eb9-9d9e-2efb5751b804)
Instruction 8:sw r3,r1,2 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/b1f5ffa2-6628-4d24-8371-f06f83fdfd5b)
Instruction 9:lw r13,r1,2

![image](https://github.com/sripadma19/sripadmach/assets/161410141/16374fe7-66c5-43e8-a25e-821b026f8742)
Instruction 10:beq r0,r0,15 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/b88f5c0d-5ffe-4c04-8215-9311f8b8df16)
After branching, performing Instruction 11:add r14,r2,r2 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/16ee8caa-7ccd-426b-9e7f-11154851f955)
Full 5-stage instruction pipeline and pc-increment description Waveform 

![image](https://github.com/sripadma19/sripadmach/assets/161410141/ec4f4c14-cf3a-41d6-abfb-bd2648f04fb9)

![image](https://github.com/sripadma19/sripadmach/assets/161410141/dd300224-cd0a-4a4b-91df-66770fae5144)

![image](https://github.com/sripadma19/sripadmach/assets/161410141/c2ae1098-0755-41c1-8891-ff2d7a333978)

















