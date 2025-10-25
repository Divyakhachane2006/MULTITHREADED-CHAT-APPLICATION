# MULTITHREADED-CHAT-APPLICATION

    Name:- DIVYA JAYANT KHACHANE 
    COMPANY:- CODETECH IT SOLUTION 
    DOMAIN:- JAVA PROGRAMMING 
    TASK3:- MULTITHREADED CHAT APPLICATION 
    DURATION:- 4 WEEKS 
    MENTOR:- NEELA SANTHOSH KUMAR 
    ID:-CTO4DR697
    
# BUILD A CLIENT-SERVER CHAT APPLICATION USING JAVA SOCKETS AND MULTITHREADING TO HANDLE MULTIPLE USERS

  DESCRIPTION": 
      I HAVE USE VS-CODE BUT CHECKED MY OUTPUT IN MY WINDOWS TERMINAL THIS CODE IS FOR A SIMPLE CHAT SERVER APPLICATION USING JAVA SOCKETS AND MULTITHREADING. IT ALLOWS MULTIPLE USERS TO CONNECT TO THE SERVER AND SEND MESSAGES TO EACH OTHER IN REAL-TIME.THE CHAT SERVER LISTENS FOR INCOMING CONNECTIONS ON A SPECIFIED PORT NUMBER. WHEN A CONNECTION IS ESTABLISHED, THE SERVER CREATES A NEW INSTANCE OF THE CLIENTHANDLER CLASS TO HANDLE COMMUNICATION WITH THE CONNECTED CLIENT.
      
      THE CLIENTHANDLER CLASS IS RESPONSIBLE FOR READING MESSAGES FROM THE CLIENT AND BROADCASTING THEM TO ALL OTHER CONNECTED CLIENTS. IT ALSO HANDLES DISCONNECTIONS AND EXCEPTIONS.
      THE CHAT CLIENT IS A SEPARATE PROGRAM THAT CONNECTS TO THE CHAT SERVER AND ALLOWS USERS TO SEND AND RECEIVE MESSAGES. IT USES THE JAVA SOCKET API TO ESTABLISH A CONNECTION TO THE SERVER AND EXCHANGE ESSAGES.
      THE CHAT SERVER USES MULTITHREADING TO HANDLE MULTIPLE CLIENT CONNECTIONS CONCURRENTLY. EACH CLIENTHANDLER INSTANCE RUNS IN ITS OWN THREAD, ALLOWING THE SERVER TO HANDLE MULTIPLE MESSAGES SIMULTANEOUSLY.
      THE CODE IS WRITTEN IN JAVA AND USES THE JAVA SOCKET API TO ESTABLISH NETWORK CONNECTIONS. IT ALSO USES THE JAVA MULTITHREADING API TO HANDLE MULTIPLE THREADS CONCURRENTLY.
      
      HERE ARE THE MAIN FEATURES OF THE CODE:
      
      MULTIPLE CLIENT SUPPORT
      REAL-TIME MESSAGING
      MULTITHREADING
      JAVA SOCKET API
      JAVA MULTITHREADING API
      
  OUTPUT: 
          <img width="1290" height="568" alt="Image" src="https://[github](url).com/user-attachments/assets/29fe1673-2e73-48a7-846e-70084de04407" />

# DELIVERABLE: A FUNCTIONAL CHAT APPLICATION WITH A SERVER AND MULTIPLE CLIENTS COMMUNICATING IN REAL TIME.

 This real-time chat application is developed using Java, enabling seamless communication between multiple users. It uses socket programming and multithreading to ensure efficient message delivery and responsiveness.

    Key Features:
    
        Multi-User Chat: Supports multiple clients connecting to the server and exchanging messages simultaneously.
        Server-Client Architecture: A central server manages all communication between clients, ensuring real-time message exchange.
        Private & Group Chats: Users can send private messages or join group chats visible to all connected clients.
        Real-Time Messaging: Instant message delivery ensures a smooth chatting experience.
        Simple Text-Based Interface: Easy-to-use and intuitive interface for users to interact.
    
    Technical Overview:
    
        Server: The server uses multithreading to handle multiple client connections, broadcasting messages to the correct recipients without delays.
        Client: Each client connects to the server to send and receive messages in real time.
        
    Technologies Used:
    
        Java: Used for developing both server and client-side applications.
        Socket Programming: Facilitates network communication between clients and the server.
        Multithreading: Ensures the server can manage multiple users concurrently without performance issues.
        
    Getting Started:
    
        Clone the repository:
        git clone https://github.com/prabal-17/realtime-chat-app.git
        
        Compile the Java code:
        javac *.java
        
        Start the server:
        java Server
        
        Connect the client:
        java Client
    
    Future Enhancements:
        Implementing user authentication for secure access.
        Adding file sharing capabilities.
        Saving and retrieving chat history.
