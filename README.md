# TCP-Project

*Development of File Repository System using Client-Server TCP/IP Model

File repository system is used for user file storage. User (Client) will connect with the file server using socket connection. The server should be able to handle multiple client connection requests at any particular time. Client can send file to the server, and server will automatically store the file in specific user’s directory.  Client could also perform other tasks, e.g. create, copy, and delete directory. Client could also request for files to be downloaded from the server. During data transmission, the program should be clear of any interruption. 

User manual:

1. Compile client.c and server.c 
2. Run both files on different terminal/pc (Server.c first)

For example:

Terminal 1:

gcc server.c -o server

./server <port>


Terminal 2:

gcc client.c -o client

./client <serverHostName> <port>



