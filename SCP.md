[Back to Portfolio](./)

Single Cycle Processor
===============

-   **Class:** CSCI 330: Computer Architechure
-   **Grade:** A
-   **Language(s):** Verilog and Assembly
-   **Source Code Repository:** [CSCI 330](https://github.com/logon02/CSCI330-SCP/tree/main)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is an implementation of a 32-bit MIPS (Microprocessor without Interlocked Pipeline Stages) single cycle processor that completes specific instructions such as lw, sw, add, nor, noop, beq, etc.

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

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
