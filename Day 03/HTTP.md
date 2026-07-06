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

#HTTP Request
Headers
Body
#HTTP Response
Headers
Body
#HTTP Methods
GET
POST
PUT
PATCH
DELETE
OPTIONS
HEAD
##Status Codes
200
201
301
302
400
401
403
404
500
503
##Headers
##Cookies
##Sessions
##Brower Developer Tools / Chrome Dev. Tools Practice

