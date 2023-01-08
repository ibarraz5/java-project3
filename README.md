# Assignment 5: Distributed Algorithms

## Description:
#### Activity: Simplified Concesus Algorithm 
This program runs the concesus algorithm and uses a client that inputs data. The nodes in this case which are 2 of them, act a bank each. The client has two options here, to ask the banks for a credit of money or to pay them back money owed. The leader in this program is able to handle the requests from the client and then take the balance of the nodes to decide whether the nodes will approve or deny a credit request. The client is able to make any payment to the nodes but the payment won't exceed what is owed. Once the payment is made it is split 50/50 between the 2 nodes. 
#### Activity: Distributed Algorithm Sorting (group chat)
This program works as a group chat. Multiple users can be created and they can talk under a chat. The screencast shows how to run the program and the programming running with multiple users using the chat. The chat also does not breakdown when a user decides to exit the chat. 

## Screencast Links:
#### Activity: Simplified Concesus Algorithm
https://youtu.be/FAWqybZL2hk
#### Activity: Distributed Algorithm Sorting (group chat)
https://youtu.be/-hFjTGPb3SE

### How to run the programs
#### Activity: Simplified Concesus Algorithm
- cd Assignment5/Leader/
- For optimal results please run them in the order they are below. Leader, node1, node2, client.
- To run leader: gradle leader --console=plain -q
- To run node1: gradle node1 -Pmoney=1000 --console=plain -q
- To run node2: gradle node2 -Pmoney=2000 --console=plain -q
- To run client: gradle client --console=plain -q
#### Activity: Distributed Algorithm Sorting (group chat)
- cd Assignment5/Peer2Peer/
- 1st user: gradle runPeer --args "A 7000" --console=plain -q
- 2nd user: gradle runPeer --args "B 7001 7000" --console=plain -q
- 3rd user: gradle runPeer --args "C 7002 7000" --console=plain -q

-Ivan
