##Install Burp Suite Community Edition.
##Learn Burp Suite Interface
  #Dashboard
  #Proxy
  #HTTP History
  #Target
  #Reapeater
  #Intruder
  #Decoder
  #Comparer
##Configure Browser Proxy  
  #Setup Browser Proxy
  #Verify that requests appear in HTTP History.
  #You can intersept traffic.
##Proxy Intercept
  #Turn intersept on
  #visit https: //httpbin.org
  #Observe the request
  #Forwad it
  #Turn intersept off
  #Browse normally
  Intercept – if intercept is on, all the request between the web browser and web server will be passing through the proxy only. When you request from web        browser, the request will be hold at proxy, once you forward the request then it will be sent to web server. Then only the web page will be loaded.
##HTTP History
  #GET Requests-  Get should be used only to retrieve data.
  #POST Requests- To upload any type of data it is used.
  #HEAD Requests- Similar to Get method, but it is without Response Body.
  #PUT Requests- To update any type of data.
  If we try to login any web application by using the credentials with Get method, the credentials are visible in URL but if we use post method for login, the       credentials remain in body.
  #DELETE   Requests- To delete any type of recourse.
  #CONNECT Requests- To connect with any target recourse.
  #OPTIONS Requests- To tell to the target that which all kinds of options do we support.
  #TRACE Requests- For Loop back method testing, we use trace method.
  #Requests contains:-
  Method, path, Version of protocol
  Headers
  #Response Contains:-
  Version of protocol, Status Code, Status Message
  Headers
  #Status codes
  Informational Response 100–199
  (Request was received and the process is continuing)
  Successful Response 200–299
  (Action was successfully received, understood and accepted.)
  Redirection Response 300–399
  (Further action must be taken in order to complete the request.)
  Client error response 400–499
  (Request contains incorrect syntax or can not be fulfilled)
  Server Error Response 500–599
  (Server failed to fulfil, apparently valid request)
  #Cookies
  #Response Headers
  HTTP/HTTPS – HTTP – 80 Port, HTTP – 443 Port.
##Installation of OWASP JUICE SHOP
  From Source → Deploy on Heroku → Sign up → Create account → Verify through email id → Log in to Heroku → Go back to the GitHub page → Click on Deploy → Give any   application name → Click on Deploy → Click on view
##Reapeater
  #Send request to Reapeater
  #Experiment by changing harmless values such as  User-Agent & Accept-Language
  #Observe how the reponse changes.
  Open testphp.vulnweb.com
  Put the request in repeater, it helps to repeat your request multiple times.
