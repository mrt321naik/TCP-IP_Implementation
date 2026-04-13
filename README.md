# TCP-IP_Implementation

A project to display my implementation of an TCP/IP web server. Entirely written in C++. 

## Socket programming:

Socket programming is a way for two computers or programs to talk to each other over a network
        -> There are two main types of Sockets **TCP/IP** then then **UDP**. 

    1. **TCP/IP**

            - It stands for Transmission Control Protocol / Internet Protocol. 

            - It is connection based with a more reliable communication.

            - The stack guarantees data arrives in order without loss or duplication.

            -  Used for web browsing, email, and file transfers.

2. **UDP**

            - UDP stands for Unified Datagram Protocol.

            - Connectionless, unreliable communication.

            - Faster but does not guarantee delivery or order.

            - Used for video-streaming, online-gamine, and voice calls.



####By Compiling the code in the repo we would get the following outupt

    -> first run server.cpp, by doing this the server program is listening for the client, 

    - > Then run the client.cpp, the client will send the message we sent to the server at             port 8080 and the message is revived and printed by the server.

`

![](/home/abhaynaik/.var/app/com.github.marktext.marktext/config/marktext/images/2026-04-13-16-56-36-Screenshot1.png)

![](/home/abhaynaik/.var/app/com.github.marktext.marktext/config/marktext/images/2026-04-13-16-56-47-Screenshot2.png)

![](/home/abhaynaik/.var/app/com.github.marktext.marktext/config/marktext/images/2026-04-13-16-56-55-Screenshot3.png)
