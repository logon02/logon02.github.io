[Back to Portfolio](./)

Single Cycle Processor
===============

-   **Class:** CSCI 330: Computer Architecture
-   **Grade:** A
-   **Language(s):** Verilog and Assembly
-   **Source Code Repository:** [CSCI 330](https://github.com/logon02/CSCI330-SCP/tree/main)  
    (Please [email me](mailto:lcferguson@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is an implementation of a 32-bit MIPS (Microprocessor without Interlocked Pipeline Stages) single-cycle processor that completes specific instructions such as lw, sw, add, nor, noop, beq, etc.

## How to compile and run the program

In order to run my code with the main test bench that tests all the main instructions of the processor, follow the steps below:
In the mips32_scp directory use this command:

```bash
iverilog -o processor testbench.v
```

(This compiles the processor and creates the executable file “processor”)

Run the executable:

```bash
vvp processor
```

This will run the testbench file and complete all the instructions.

## UI Design

The UI for this project is very simple. This single-cycle processor uses the command line to print out the results of the testbench file and display when all the instructions are completed successfully. For each register change, the contents of that register are printed so the user can see what is happening in the background. See examples below.

![image](https://github.com/logon02/logon02.github.io/assets/85260424/2cffeee3-c5f1-4a5c-afe2-57ae1c1a7972)

Fig 1. The launch screen

![image](https://github.com/logon02/logon02.github.io/assets/85260424/61113f89-c6be-4018-a1a5-9361949b82cd)
 
Fig 2. Example output after input is processed.

## 3. Additional Considerations

This program can be resource-demanding on some computers, so be aware that if there are issues with the execution of the project, it may be due to older components or an old kernel version of Linux. Linux is the easiest way to execute this program, but if there are issues please contact me.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
