#OSI Model
Layer                   Purpose

Application            Browser,HTTP       Provides a direct interface between network services and end-user applications.
Presentation           Encryption         Translates, encrypts, and compresses data
Session                Session Management Establishes, maintains, and terminates connections between applications.
Transport              TCP/ UDP           Ensures reliable, end-to-end data delivery (e.g., TCP and UDP).
Network                IP Routing         Routes data across different networks (e.g., using IP addresses).
Data Link              Mac Address        Transfers data between adjacent network nodes (e.g., using MAC addresses).
Physical               Cable              Manages raw hardware, cabling, and physical signals.

#TCP/IP Model (Transmission control Protocol/Internet protocol)
   It is a set of protocols, which supports network communication. TCP breaks the data into small data units segments and hands them off to IP, then it completes     the routing, TCP Module in the reciver combines the message segments to origional message.
TCP/IP Layer         
Application          Applictaion,Presentation,Session
   List of protocols provided by appliation layer
   DNS- Domain name system trnslates IP address to Domain names and vice versa.
   DHCP- Dynamic host configuration protocol autpomatically assign IP address to computer present in your network.
   FTP- File transfer protocol is used to trnsport files to internet.
   HTTP- Hyper text transfedr protocol is used to send or recieve web pages.
   IMAP- Intyernet mail access protocol used to email messages in internet.
   IRC-  Intyernet relay chat protocol used for internet chat
   POP3- Post office protocol version 3 used by email clients to retyrive messages from remote server.
   SMTP- Simple mail transfer protocol used  to email messages in internet.
Transport            Transport Dat transfer, ACK & Connection termination(Sender TCP sends finished message to Reciever TCP. the other end acknowdges the message.    That is called two way handshake process, so the connection termination follows 4 way hand shake process)
Network              is resonsible for logical addressing, routing and path determination.
Data Link            Ethernet  (Medium access control-MAC Sub layer) (Logical link control-LLC Sub layer)
    MAC Sub layer responsible for data encapsulation and accessing the media.
    Data encapsulation: header- mac address, IP Packet, Trailer-Error checking data
    Access method: Carrier sense multiple access / colloison detection. CSMA/CD
    LLC Sub layer is responsible for flow control and error control and sizing of the packets. Automatic reapet request (ARQ) , LLC Can resize the data packet         recived from the network layer to fit them into data link layer frame.
Physical             Ethernet
#TCP vs UDP (User Datagram Protocol)
TCP- slow but more Reliable, Ordered,Connection oriented
    Error free data transfer
    ordered data transfer
    Retransmission of lost data
    Discarding duplicate data
    congestion throttling or Flow control
UDP-It's connectionless means it does not esatablish a session, it does not guarentee data delivery.When a computer send data it does not really cares the data has been recieved at other end. It's known as fire and forget protocal.Fast, no guarantee,Connectionless
E.G.-TCP,HTTP,HTTPS,SSH,FTP,SMTP,UDP,DNS,VoIP,Gaming,Video Streaming
#Common Ports and Common Protocols
Port is a logical connection that is used by programs and services to exchange information.
System/ well known ports- 0-1023
User/Registrated ports-   1024-49151
Dynamic/private ports-49152-65535
Port          Protocol
20/21           FTP
22              SSH
23              Telnet
25              SMTP
53              DNS
80              HTTP
110             POP3
143             IMAP
443             HTTPS
3306            MySQL
3389            RDP
#TCP three way Handshake
First a computer will send a message called SYN, then the reciever computer will send back an acknowedgement message SYN ACK, telling the sender that it has recieved the message, then finally the sender computer sends another acknowedgement message back to the reciever.Once this takes place data will be delivered.
Client->SYN->Server->SYN ACK->Client->ACK->Connection established. (FIN,ACK,FIN,ACK)
#Packet flow
Packet flow in networking is the step by step joureny of data broken into small chunks(packets) from source to destination. As a packet travels intermideate devices like switches, roters analyse, encapsulate and forwad the packet based on mac address, IP Address and routing tables.
#Wireshark Introduction
Wireshark is the open source, free, industry standard network protocol analyser. It is essentially a digital microscope (packet snipper) that intyersepts and displayes network traffic in real time, allows it professional to troubleshoot network issues, analyse protocols and conduct cyber security forensics. 
