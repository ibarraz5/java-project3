# Activity Distributed Algorithm: Sorting (group chat)
Assignment 5

### Description:
This program works as a group chat. Multiple users can be created and they can talk under a chat. The screencast shows how to run the program and the programming running with multiple users using the chat. The chat also does not breakdown when a user decides to exit the chat. 

### How to run it

Arguments are name and port. Start 2 to many peers each having a unique port number. For the username you can only use a single letter username. Open the Peer2Peer folder first before starting. 

- cd Assignment5/Peer2Peer/
- 1st user: gradle runPeer --args "A 7000" --console=plain -q
- 2nd user: gradle runPeer --args "B 7001 7000" --console=plain -q
- 3rd user: gradle runPeer --args "C 7002 7000" --console=plain -q


## ScreenCast:
https://youtu.be/-hFjTGPb3SE

