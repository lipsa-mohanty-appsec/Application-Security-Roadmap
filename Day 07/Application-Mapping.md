##Application Mapping + Burp Target + Authentication Flow
#Learn Burp Target
Burp → Target
Site map
Scope
Hosts
URLs
Request/response
#Configure Burp Scope
Add only the Juice Shop target to scope.
Turn on filtering for scoped traffic where appropriate.
Scope = what you're authorized to test.
#Map the Application
Start browsing Juice Shop normally.
Don't attack anything yet.
Pretend your manager gave you this assignment:
"Perform a web application security assessment."
#Your first job is:
Understand the application.
Browse:
Home page
Login
Registration
Search
Products
Basket/cart
User profile
Orders
Feedback
#Other visible functionality
Proxy → HTTP history
Target → Site map
#Authentication Flow
Go to the Juice Shop login page.
Create/use a training account as appropriate.
Observe the login request in Burp.
#Request
Method
URL
Headers
Body
Content-Type
#Response
Status code
Response body
Token/cookie
Headers
#Authentication Testing Mindset
#Security mindset:
"Can someone bypass login?"
"Can User A access User B's information?"
"What happens with an invalid token?"
"What happens when the token is removed?"
"Can a normal user access an administrative function?"
#Send Login Request to Repeater
Find the login request.
Right-click:
Send to Repeater
Then send it without changing anything.
#Record:
Request
Response
Status
Token/session information

#Build Your First Real Pentest Deliverable
