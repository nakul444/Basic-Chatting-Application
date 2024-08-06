# Basic-Chatting-Application

Description

The basic chatting application is a desktop application built using Java, Java Swing for the graphical user interface (GUI), and socket programming for real-time communication. This application allows multiple users to connect to a server and exchange messages in real time. It serves as an excellent project to understand the fundamentals of networking and GUI development in Java.

Key Components

1.Server: Manages connections from multiple clients, receives messages from one client, and 
  broadcasts them to all connected clients.

2.Client: Allows users to connect to the server, send messages, and receive messages from other 
  clients.

3.GUI: Built using Java Swing, it provides a user-friendly interface for sending and receiving 
  messages.

Features

* Multi-client support: Multiple users can connect to the server simultaneously.
  
* Real-time messaging: Messages are exchanged in real time between connected clients.
* User-friendly interface: Java Swing is used to create an intuitive and responsive chat window.
  
* Server-side broadcasting: The server broadcasts messages from one client to all connected clients.
  
Implementation Details

1. Server:
The server listens on a specified port for incoming client connections. It uses multithreading to handle multiple clients simultaneously. Each client connection is managed by a separate thread.

2. Client:
The client connects to the server and allows the user to send and receive messages. It has a simple Swing-based GUI for user interaction.

How to Run

1.Start the Server:
  * Compile and run the Server.java class.
  * The server will start listening on port 6001 for incoming connections.
    Start the Client:

2.Compile and run the Client.java class.
  *A chat window will appear where the user can enter their messages.
  
3.Connect Multiple Clients:
  * Run multiple instances of the Client.java class to simulate multiple users.
  * Each client can send messages which will be broadcast to all connected clients.
    
Conclusion

This basic chatting application demonstrates the use of Java Swing for GUI development and socket programming for network communication. It provides a foundation for building more advanced chat applications with features like user authentication, private messaging, and message history.
