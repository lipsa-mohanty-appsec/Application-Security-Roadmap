#OSI Model
Layer                   Purpose

Application            Browser,HTTP
Presentation           Encryption
Session                Session Management
Transport              TCP/ UDP
Network                IP Routing
Data Link              Mac Address
Physical               Cable

#TCP/IP Model
TCP/IP Layer         Maps to OSI

Application          Applictaion,Presentation,Session
Transport            Transport
Internet             Network
Network Access       Data Link, Physical

#TCP vs UDP
TCP- Reliable, Ordered,Connection oriented
UDP-Fast, no guarantee,Connectionless
E.G.-TCP,HTTP,HTTPS,SSH,FTP,SMTP,UDP,DNS,VoIP,Gaming,Video Streaming
#Common Ports and Common Protocols
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
Client->SYN->Server->SYN ACK->Client->ACK->Connection established. (FIN,ACK,FIN,ACK)
Packet flow
Wireshark Introduction

