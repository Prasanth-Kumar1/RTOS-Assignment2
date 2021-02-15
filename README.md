# RTOS-Assignment2

Run the following commands.

Terminal 1
gcc group_server.c -o server -lpthread
./server 8001

Terminal 2
gcc group_client.c -o client -lpthread
./client 4 127.0.0.1 8002
