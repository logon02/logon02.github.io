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
$ cd ./CSCI 332 Final Project
$ gcc Client.cpp -o client.out
$ ./client.out
```

Now the client should be running.

In another terminal, enter these commands to run the server:

```bash
$ cd ./CSCI 332 Final Project
$ gcc Server.cpp -o server.out
$ ./server.out
```
Once you have both programs running at the same time, follow the prompts to test the file share server. The text file that can be shared is the one called test.txt, but feel free to test it with any text file!

## UI Design

This project uses the command line as the front end to present the user with options and feedback. Ensure that the IP addresses and the port numbers are consistent between the client and the server. The file share requires two projects to be running at once, so the user must use two terminal windows on the machine. See the screenshots below for details:

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

I highly recommend using Ubuntu 20.04 or later because the gcc compiler comes pre-installed. This can be done in Windows, however there are more steps involved when installing and using gcc.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
