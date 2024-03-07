Meeting Held on: 27/02/2024

The C code should undergo the simulation of normal GCC X86 Compiler and riscv compiler (SPIKE Simulation)

AS PER THE REQUIREMENT OUTPUT OF GCC (F1) SHOULD BE EQUAL = TO OUTPUT OF RISCV GCC (F2)
![image](https://github.com/sripadma19/sripadmach/assets/161410141/b1223b5b-f4b6-41bf-9880-369d6ade797a)
Step - 1:Run the code in the normal GCC Compiler To compile the code: gcc sum1ton.c -o sum1ton To Get the output use "./a.out" : Here the output finds to be -Sum of numbers from 1 to 50 is 125250

Step - 2: To Run the code in the RISC-V GCC Compiler

To compile the code: riscv64-unknown-elf-gcc -o sum1ton sum1ton.c To Get the output use "./a.out" : Here the output finds to be -Sum of numbers from 1 to 50 is 125250
![image](https://github.com/sripadma19/sripadmach/assets/161410141/cd4800cf-85e2-43f5-b964-14fafeddb5f2)
![image](https://github.com/sripadma19/sripadmach/assets/161410141/d9b4232c-2678-4b9b-80a3-4b3abbe82ae9)
![image](https://github.com/sripadma19/sripadmach/assets/161410141/a88c36c1-05d0-4852-ba89-fb76adfcd95a)

