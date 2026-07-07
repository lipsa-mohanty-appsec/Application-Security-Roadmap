##HTTP:
HTTP (Hypertext Transfer Protocol) is the foundational set of rules that governs how data—like text, images, and video—is exchanged across the World Wide Web. It operates on a client-server model, where a web browser (the client) sends a request, and the server returns the requested resources.
#HTTPS:
HTTPS (HyperText Transfer Protocol Secure) is the secure version of HTTP. It is the foundation of data communication for the World Wide Web, ensuring that the connection between your web browser and the website you are visiting is encrypted, authenticated, and protected from interception.
In a standard HTTP connection, data is transmitted in plain text. This means anyone intercepting your network traffic (like a hacker on a public Wi-Fi network) can read your passwords, messages, and credit card details.
HTTPS fixes this by adding a layer of security using SSL (Secure Sockets Layer) or, more commonly today, TLS (Transport Layer Security).
Key mechanics of this secure connection include:Encryption: Scrambles the transferred data so that even if it is intercepted, it is unreadable to eavesdroppers.Authentication: Uses digital certificates verified by trusted third parties (Certificate Authorities) to ensure you are actually communicating with the legitimate website and not an imposter.Data Integrity: Ensures that the data sent between your browser and the web server has not been tampered with or altered in transit.
#HTTP vs HTTPS
Feature                               HTTP                                              HTTPS
Fullform                    HyperText Transfer Protocol                   HyperText Transfer Protocol Secure
Security                    None; data is sent in plain text               Encrypted using SSL/TLS protocols (Secure sockets Layer/Transport Layer Security)
Default Port                           80                                               443
Url Prefix                           http://                                           https://
Request->Server->Response
#HTTP Request
Request Lines
Headers
Body
Cookies
Authorization
#HTTP Response
Status Lines
Headers
Response Body
#HTTP Methods
GET
POST
PUT
PATCH
DELETE
OPTIONS
HEAD
##Status Codes
200-OK, Successful HTTP Request
201-Created, New copntent is created, and it's now live.
204-No content, when you send a delete request, it's done, but don't have any content to send back.
301-Moved permanently
302-Found(or previously "Moved Temporarily")
304-Not Modified
400-Bad Request, check again what you have sent.
401-Unauthorized, we are missing the right credentials.
403-Forbidden, your request is forbidden to see the content.(trying to enter VIP area with general ticket.)
404-Not Found , your requested file is not present.
405-Method not allowed
429- Too many requests, server's way of saying hey slow down.
500-Internal Server error
502-Bad Gateway
503-Service Unavailable
504-Gateway Timeout
##HTTP Headers
  General
                         Request Header format                                                   Response Header Format
                         Request Line                                                            Status Line
                         Header fields                                                           Header fields                         
                         Blank line                                                              Blank line
                         Message Body                                                            Message Body
                         
                         
  
##Cookies
HTTP Protocol is a stateless protocol, it constantly forgets what user has done on the site unless we have a way to remember.
Internet cookies are small text files websites save on your device. They act as a website's memory, holding unique data that helps servers recognize you upon return. Cookies remember login credentials, maintain items in your shopping cart, and save personal preferences to make browsing smoother and more personalized.
##Sessions
A session in networking is a temporary, interactive conversation between two or more communicating devices or applications. It encompasses the entire duration from the initial "handshake" and data exchange until the connection is officially closed or times out.
##Brower Developer Tools / Chrome Dev. Tools Practice


