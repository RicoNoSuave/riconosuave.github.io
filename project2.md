[Back to Portfolio](./)

UDP Client/Server
===============

-   **Class: CSCI 330 - Applied Networking** 
-   **Grade: 100** 
-   **Language(s): C++** 
-   **Source Code Repository:** [CSCI 330 - Applied Networking](https://github.com/RicoNoSuave/CSCI330_Applied_Networking)  
    (Please [email me](mailto:Ricardo.E.Harris@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This project is divided into a client and server that communicate over a network using a UDP connection to transfer text files from the client to the server. Text files have the transfer time and date appended to the name of the file.

## How to compile and run the program

To compile and run this project, make sure that you use two separate terminals when operating on the same device, and that there is a .txt file on the device running the Client program.

```bash
g++ Client.cpp -o Client;
./Client;
```

```bash
g++ Server.cpp -o Server;
./Server;
```

## UI Design

Begin by launching the Server, providing a port to communicate through (see Fig 1). Then launch the Client, providing the Server port and IP address, followed by the .txt file that you wish to transfer (see Fig 2). Afterwards, note that a new .txt file is located in the same directory as the Server with the same contents as the text file from the Client, as well as a new title including the date and time transferred (see Fig 3 and 4).

![screenshot](/images/Networking_UDP/Server.jpg)  
Fig 1. Server initialization.

![screenshot](/images/Networking_UDP/Client.jpg)  
Fig 2. Client setup.

![screenshot](/images/Networking_UDP/Initial.jpg)  
Fig 3. Directory before transfer.

![screenshot](/images/Networking_UDP/New_File.jpg)  
Fig 3. Directory after transfer.

[Back to Portfolio](./)
