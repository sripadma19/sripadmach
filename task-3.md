
By Referring to C-based Lab videos and RISC-V-based lab videos

Snapshots of the compiled C code and RISC-V

Step 1: check whether the leafpad is installed in ur machine by using the commands leafpad sum1ton.c& (sum1ton.c is the file name) If the leafpad editor is opened without any errors then type the C code. **If the leafpad is not installed in ur machine then install by using the following command


sudo snap install leafpad**
![image](https://github.com/sripadma19/sripadmach/assets/161410141/1fcae12a-dead-4108-9305-caccad174706)

**Step 2: Writing the C code in the leafpad editor using the following command

leafpad sum1ton.c&
![image](https://github.com/sripadma19/sripadmach/assets/161410141/16e439f1-c928-4dbf-ae97-080bc7a4c2c4)
Step 3: After writing the C code save the editor by Ctrl+s

Step 4: Check for the errors by using the following command(compilation step) gcc sum1ton.c
![image](https://github.com/sripadma19/sripadmach/assets/161410141/b0a97733-ec41-41a3-86ba-55b6c4006a7c)
Step 5: Check the output by using the command

./a.out
![image](https://github.com/sripadma19/sripadmach/assets/161410141/11668a8f-cc54-43a5-af66-fdab13278648)
The results will be displayed as

Sum of numbers from 1 to 500 is 125250

***RISCV Compilation and Execution

Step 1: View the C Code in the editor window using the following command

cat sum1ton.c
![image](https://github.com/sripadma19/sripadmach/assets/161410141/31f4ef05-3e15-47af-a433-762d1222f1a3)
Step 2: Compile the code in riscv using the following command

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
![image](https://github.com/sripadma19/sripadmach/assets/161410141/7dff20cc-e4b4-444d-aede-048def6445d0)



Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.
use the command ls -ltr sum1ton.c
![image](https://github.com/sripadma19/sripadmach/assets/161410141/d9baff9e-a8d8-4bfb-9cec-cc21dd675e69)




Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution
![image](https://github.com/sripadma19/sripadmach/assets/161410141/65c5cfe7-5515-4d60-93c9-1fe74a41893d)

![image](https://github.com/sripadma19/sripadmach/assets/161410141/da59eaec-abf6-44be-a486-677d1415ab76)
Step 4:

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
![image](https://github.com/sripadma19/sripadmach/assets/161410141/c735df6b-d51f-49be-b989-1e9d02ed3b19)

![image](https://github.com/sripadma19/sripadmach/assets/161410141/b1780140-226e-4fa3-8277-aec3f1a02937)





















