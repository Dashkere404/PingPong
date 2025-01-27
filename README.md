Implementation of the interaction between the client and the server using FIFO as a messaging channel.
The server receives messages from the client, processes them, and sends responses. It is also possible to request a message history.

## Installing and assembling the project
1. Cloning the repository:
git clone https://github.com/Dashkere404/PingPong.git
3. cd your-folder
4. mkdir build
5. cd build
6. Run the CMake command:
cmake .. 
7. Build the project:
cmake --build . 
8. ./server 
9. ./client

### Client commands 
* history - request history 
* exit - exit

