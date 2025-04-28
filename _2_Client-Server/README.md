# Client-Server Computing

## COMMUNICATION MODELS
1. **Communication Models**
2. **Blocking vs Non-blocking Message-Passing**
   - 2.1 Message-passing
   - 2.2 Latency
   - 2.3 Pipelining

## SOCKET-BASED COMMUNICATION
3. **Classic View of Network API**
4. **Sockets**
   - 4.1 Datagram Sockets
5. **Simple Message Passing (Java)**
6. **Client-Server (Java)**
   - 6.1 Network Addresses in Java
   - 6.2 Datagram Packets in Java
   - 6.3 Datagram Sockets in Java

## STREAM SOCKETS
7. **Stream Sockets**
   - 7.1 Stream Sockets (Java)
   - 7.2 Client Stream Sockets in Java
   - 7.3 Server Stream Sockets in Java
   - 7.4 Extended Server Sockets

## FTP EXAMPLE
8. **FTP: File Transfer Protocol**
   - 8.1 FTP Data Transfer
   - 8.2 Creating the Data Connection: Active Mode
   - 8.3 Creating the Data Connection: Passive Mode
   - 8.4 Active vs Passive Mode
   - 8.5 Server File Transfer
   - 8.6 Client File Transfer

## REMOTE PROCEDURE CALL
9. **RPC as a Programming Abstraction**
10. **The Basic RPC Protocol**
11. **RPC Binding**
12. **Request Marshalling**
    - 12.1 Data in Messages
    - 12.2 Fancy Argument Passing

## RPC WITH LOST MESSAGES
13. **RPC Semantics in the Presence of Failures**
    - 13.1 Client is Unable to Locate Server
    - 13.2 Messages Lost
    - 13.3 Lost Request Message
    - 13.4 Overcoming Lost Packets
    - 13.5 Costs in Fault-tolerant Version?
    - 13.6 Big Packets
    - 13.7 Lost Reply Message

## RPC WITH CRASHES
14. **Server Crashes**
15. **Impossibility of Exactly Once Semantics**
16. **Client Crashes**
    - 16.1 Client Crashes: Possible Solutions

## FALLACIES IN DISTRIBUTED COMPUTING
17. **The Network is Reliable**
18. **Latency is Zero**
19. **Bandwidth is Infinite**
20. **The Network is Secure**
21. **Topology Doesn't Change**
22. **There is One Administrator**
23. **Transport Cost is Zero**
24. **The Network is Homogeneous**
25. **Broad Comments on RPC**

## JAVA RMI
26. **Java Remote Method Invocation (RMI)**
    - 26.1 Defining Remote Interfaces
    - 26.2 Defining a Remote Implementation
    - 26.3 RMI Registry
    - 26.4 Factory Objects
    - 26.5 Example Server
    - 26.6 Example Client
    - 26.7 Putting it All Together
    - 26.8 Dynamic Stub Loading

## LOCAL RPC
27. **RPC versus Local Procedure Call**
28. **RPC Costs in Case of Local Destination Process**
29. **RPC Example**
30. **RPC in Normal Case**

## Important Optimizations: LRPC
31. **LRPC (Lightweight RPC)**
    - 31.1 LRPC Performance Impact
32. **FBUFS**
    - 32.1 Fbufs
    - 32.2 Where are Fbufs Used?
