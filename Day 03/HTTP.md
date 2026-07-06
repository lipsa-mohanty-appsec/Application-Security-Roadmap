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
200-OK
201-Created
204-No content
301-Moved permanently
302-Found(or previously "Moved Temporarily")
304-Not Modified
400-Bad Request
401-Unauthorized
403-Forbidden error
404-Not Found
405-Method not allowed
429- Too many requests
500-Internal Server error
502-Bad Gateway
503-Service Unavailable
504-Gateway Timeout
##HTTP Headers
##Cookies
##Sessions
##Brower Developer Tools / Chrome Dev. Tools Practice

