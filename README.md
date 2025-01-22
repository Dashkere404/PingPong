Implementation of interaction between client and server using FIFO as a channel for messaging.
The server receives messages from the client, processes them and sends responses. It is also possible to request message history.

### Project files
- client.cpp — client source code.
- server.cpp — server source code.
- CMakeLists.txt - file for building a project using CMake.

## Installing and assembling the project

**1. Cloning the repository**

git clone https://github.com/MariaYazikova/PingPong.git 

**2. Go to your project folder** 

cd your-folder

**3. Create a build folder and go to it**

mkdir build

cd build

**4. Run the CMake command** 

cmake .. 

**5. Build the project** 

cmake --build . 

**6. First start the server**  

./server 

**7. Then the client** 

./client

### Client commands 
* history - request history 
* exit - exit

(Second year university)
