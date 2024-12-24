# Chat Room

This project is a chat room application consisting of a server program capable of handling multiple clients, and a client program that can connect to the server.

## Compilation:
Server:
```
gcc -Wall -g TCPEchoServer.c HandleTCPClient.c DieWithError.c -o echo-server
```

Client:
```
gcc -Wall -g TCPEchoClient.c DieWithError.c -o echo-client
```

## Usage:
Server:
```
Usage: ./echo-server <Server Port>
```

Client:
```
Usage: ./echo-client <Server IP> <Echo Word> [<Echo Port>]
```
