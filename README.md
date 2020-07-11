# rdma-server-client
RDMA based simple server client application using rsockets from librdmacm library

## Compile the scripts using:

g++ server.cpp -o server -libverbs -lrdmacm <br>
g++ client.cpp -o client -libverbs -lrdmacm <br>

## Run the executables using:

./server PORT
  
./client SERVER-IP SERVER-PORT
