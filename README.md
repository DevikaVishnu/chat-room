# Chat Room

This project is a chat room application make up of server program capable of handling multiple clients.

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
