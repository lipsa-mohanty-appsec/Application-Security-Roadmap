#Browser Architecture
Checks cache
Resolve DNS
Create TCP Connection
Performs TLS Handshakes
Sends HTTP Requests
Recives HTTP response.
Download HTML
Download CSS
Download Java script
Renders the Page
#Chrome DevTools
F12
Elements
Console
Network
Application
Sources
#Network Tab
Open https://github.com
Press F12
Go to Network
Refresh
Observe Method,Status, Domain,Type, Size, Time
Click any request and Study General, Request Headers, Response Headers,Cookies,Preview,Reponse, Timing
#Headers
##Request Headers
Host, User-Agent,Accept,Accept-Encoding,Autheroziation, cookie, refer,Origin
##Response Headers
Content-Type,Server,Cache-Control,Set cookies,Location,Strict-Transport-Security
#Cookies and Storage
Go to any application cookies
Observe the Name, value,Domain,Path,Expires,Secure,HTTP Only,SameSite
#Local Storage                          vs                  Session Storage
Persists after browse restarts.                     Cleared when tab/browser closes.
Larger Storage                                      Smaller Storage
Accessiable via JavaScript                          Accessiable via JavaScript    
#Practical Labs
