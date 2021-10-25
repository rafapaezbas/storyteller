# Storyteller

Storyteller is a minimal interactive fiction engine for the [uxn](https://wiki.xxiivv.com/site/uxn.html) virtual machine.

## How does it work?

Storyteller takes up to 99 nodes. Each node is a file with the text to show and its connection to the other nodes. 

File 01

```
This is the text of this node. 

If you press 1, it will take you to node 30
If you press 2, it will take you to node 44

#30
#44
```

File 30

```
This is node number 30. It has no connections, so its an endpoint.
```

Each node can have up to 9 connections. One connection for numbers 1-9.

The default node is 01.
