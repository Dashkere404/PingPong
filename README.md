Implementation of the interaction between the client and the server using FIFO as a messaging channel.
The server receives messages from the client, processes them, and sends responses. It is also possible to request a message history.

## Installing and assembling the project
1. Cloning the repository
git clone https://github.com/MariaYazikova/PingPong.git 
2. cd your-folder
3. mkdir build
4. cd build
5. Run the CMake command:
cmake .. 
6. Build the project:
cmake --build . 
7. ./server 
8. ./client

### Client commands 
* history - request history 
* exit - exit

