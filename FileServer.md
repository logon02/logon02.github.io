[Back to Portfolio](./)

File Share Server
===============

-   **Class:** CSCI 332
-   **Grade:** A
-   **Language(s):** C and C++
-   **Source Code Repository:** [CSCI 332](https://github.com/logon02/CSCI-332-FileServer)
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is my final project for CSCI 332: Applied Networking. This is a file share server and client program and it has the ability to send text files to another computer on the same network. It uses the IP address and a port number of the destination computer to send the file.

## How to compile and run the program

To compile this project you will need gcc installed on your system, which works best in Linux or Windows. Once you have gcc installed on your system use these commands:

```bash
cd ./CSCI 332 Final Project
gcc Client.cpp -o Client.out
./Client.out
```

Now the client should be running.

In another terminal, enter these commands to run the server:

```bash
cd ./CSCI 332 Final Project
gcc Server.cpp -o Server.out
```
Once you have both programs running at the same time, follow the prompts to test the file share server.

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
