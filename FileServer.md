[Back to Portfolio](./)

File Share Server
===============

-   **Class:** CSCI 332
-   **Grade:** A
-   **Language(s):** C and C++
-   **Source Code Repository:** [CSCI 332](https://github.com/logon02/CSCI-332-FileServer)

    (Please [email me](mailto:lcferguson@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is my final project for CSCI 332: Applied Networking. This is a file share server and client program and it has the ability to send text files to another computer on the same network. It uses the IP address and a port number of the destination computer to send the file.

## How to compile and run the program

To compile this project you will need gcc installed on your system, which works best in Linux or Windows. Once you have gcc installed on your system use these commands:

```bash
> cd ./CSCI 332 Final Project
> g++ server.cpp -o server -lws2_32
> server.exe
```

Now the server should be running.

In another terminal, enter these commands to run the client:

```bash
> cd ./CSCI 332 Final Project
> g++ client.cpp -o client -lws2_32
> client.exe
```
Once you have both programs running simultaneously, follow the prompts to test the file share server. The text file that can be shared is test.txt, but feel free to try it with any text file!

## UI Design

This project uses the command line as the front end to give the user options and feedback. Ensure that the IP addresses and the port numbers are consistent between the client and the server. The file share requires two projects to be running simultaneously, so the user must use two terminal windows on the machine. See the screenshots below for details:

![image](https://github.com/logon02/logon02.github.io/assets/85260424/ae3e4fa3-f1d3-4879-89c1-67c1512427a6)
Fig 1. The launch screen

![image](https://github.com/logon02/logon02.github.io/assets/85260424/7a5a6009-bb81-4962-9cc4-35b5c42f4c1d)
Fig 2. Example output after input is processed.

![image](https://github.com/logon02/logon02.github.io/assets/85260424/3b3e2b73-83c1-48e6-95f9-8c6967835ef1)
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

I highly recommend using Ubuntu 20.04 or later because the gcc compiler comes pre-installed. This can be done in Windows, however there are more steps involved when installing and using gcc.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
