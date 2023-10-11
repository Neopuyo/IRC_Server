# IRC Server

## A server for IRC from ...



The executable takes two arguments, the port and the password for the server.
to launch the server, run the following commands:

```bash
make
./ircserv 6667 test
```

To connect to the server, you can use an IRC client like Hexchat.
Or directly using netcat command in a terminal:

```bash
nc localhost 6667
```