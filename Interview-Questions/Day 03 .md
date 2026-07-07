# Day 3 Interview Questions:-
##Explain HTTP?
  Answer:HTTP (Hypertext Transfer Protocol) is the foundational set of rules that governs how data—like text, images, and video—is exchanged across the World Wide Web. It  operates on a client-server model, where a web browser (the client) sends a request, and the server returns the requested resources.
##Difference between HTTP and HTTPS?
  Answer:
  Feature                               HTTP                                              HTTPS
  Fullform                    HyperText Transfer Protocol                   HyperText Transfer Protocol Secure
  Security                    None; data is sent in plain text               Encrypted using SSL/TLS protocols (Secure sockets Layer/Transport Layer Security)
  Default Port                           80                                               443
  Url Prefix                           http://                                           https://
##Difference between GET and POST?
  Answer:GET retrieves data from a server without modifying it, while POST sends data to a server to create or update a resource.
##Difference between PUT and PATCH?
  Answer:PUT replaces an entire resource, whereas PATCH applies partial modifications to a resource.
##What is Cookie?
  Answer:HTTP Protocol is a stateless protocol, it constantly forgets what user has done on the site unless we have a way to remember.
Internet cookies are small text files websites save on your device. They act as a website's memory, holding unique data that helps servers recognize you upon return. Cookies remember login credentials, maintain items in your shopping cart, and save personal preferences to make browsing smoother and more personalized.
##What is Session?
  Answer:A session in networking is a temporary, interactive conversation between two or more communicating devices or applications. It encompasses the entire duration from the initial "handshake" and data exchange until the connection is officially closed or times out.
##Difference between Cookie and Session?
  Answer:cookies store data on the client side (browser), while sessions store data on the server side. Because HTTP is stateless, both mechanisms are used together to track user state and remember information across different webpage requests.
##Why is HTTPS more secure?
  Answer:HTTPS (HyperText Transfer Protocol Secure) is the secure version of HTTP. It is the foundation of data communication for the World Wide Web, ensuring that the connection between your web browser and the website you are visiting is encrypted, authenticated, and protected from interception.
  In a standard HTTP connection, data is transmitted in plain text. This means anyone intercepting your network traffic (like a hacker on a public Wi-Fi network) can read your passwords, messages, and credit card details.
HTTPS fixes this by adding a layer of security using SSL (Secure Sockets Layer) or, more commonly today, TLS (Transport Layer Security).
##What is HTTP only Cookie?
  Answer:An HttpOnly cookie is a secure type of web cookie assigned an HttpOnly flag. It restricts client-side scripts (like JavaScript) from reading or modifying the cookie via APIs like document.cookie, meaning it can only be transmitted directly to the server during HTTP(S) requests
##What is same site Cookie?
  Answer:A SameSite cookie is a security attribute in HTTP cookies that tells the browser whether to restrict a cookie to first-party contexts or send it alongside cross-site requests. It is primarily used to protect websites from Cross-Site Request Forgery (CSRF) attacks.
##Explain status code 401 vs 403?
  Answer: 401:Unauthorized, we are missing the right credentials.
          403:Forbidden, your request is forbidden to see the content.(trying to enter VIP area with general ticket.)
##Difference between 301 and 302?
  Answer:301:Moved permanently
         302:Found(or previously "Moved Temporarily")
##What is content-type?
  Answer:The HTTP Content-Type representation header explicitly indicates the original media type (format) of the resource being transmitted in the message body. It tells the recipient (a browser or server) exactly how to interpret, parse, and render the data being exchanged.
##Why can Burp suite intercept traffic?
  Answer:Burp Suite acts as a Man-in-the-Middle (MitM) proxy. By routing your device’s network traffic through it, you authorize Burp to decrypt, view, and modify requests. To handle encrypted HTTPS, Burp uses its own self-signed certificate, which decrypts data for inspection and then re-encrypts it to communicate with the target server.
##Why can't be passwords be safely sent over HTTP?
  Answer:In a standard HTTP connection, data is transmitted in plain text. This means anyone intercepting your network traffic (like a hacker on a public Wi-Fi network) can read your passwords, messages, and credit card details.
##Which HTTP method should never modify the server data?
  Answer:Get Method
##Which response tells the browser to save the cookie?
  Answer: set cookie in Response Header
##Why does browsers automatically sends cookies?
  Answer:Browsers automatically send cookies with every request because the foundational protocol of the internet (HTTP) is "stateless"—meaning it forgets who you are the second you load a new page. Sending cookies automatically allows servers to remember your identity and settings.
##Difference between authorization and authentication?
  Answer:Authentication verifies who you are, while authorization determines what you are allowed to do.
##Why is same site cookie important?
  Answer:SameSite cookies are a critical security mechanism that prevents web browsers from automatically sending cookies with cross-site requests. Their primary importance lies in defending users against Cross-Site Request Forgery (CSRF) attacks, preventing unauthorized data leakage, and controlling user privacy across domains
##Why every Application Secutrity tester master HTTP before learning Burp suite?
  Answer:An Application Security (AppSec) tester must master HTTP before learning Burp Suite because Burp Suite is simply a tool that displays, intercepts, and manipulates raw HTTP traffic. Without a deep understanding of HTTP, a tester is essentially flying blind—looking at a screen full of text without understanding what the variables mean, what the server expects, or where vulnerabilities actually hide.
