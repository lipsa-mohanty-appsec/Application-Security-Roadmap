#Authentoication behavior
#Login Requests
Session/ token handling
Logout behavior
Password reset concept
Authentication Bypass concept
Token manupulation basic
Rste limiting concept
Error message information leakage
##Authentication(Who are you)
Username + Password
        |
Authentication
        |
User Identified
##Authorization(What are you allowed to)
       |
User->view own profile
Admin->Manage Users
##Session
How application remembers that you have authenticated.
##Token
A value used by the client or server to maintain authentication state.
##Logout
The application should invalidate or otherwise terminate the authenticated session according to it's design.
                             OPEN
Burp->Proxy->HTTP History
Request:
Method
URL
Content Type
Request Body
Headers
Response:
Status code
Response Body
Set-Cokkies, is present
Authorization / token information
Other security- Relevant headers
                             REPEATER
Righr click on the login request and send to Repeater.
Repeater-> Send
"This request authenticates the user and the tresponse establishes the authenatication state".
                   TEST INVALID AUTHENTICATION
#TEST-1-Correct email + incorrect poassword
Observe the status code,error message and response behavior.
#TEST-2-Invalid email + invalid poassword
Observe the status code,error message and compare the response behavior.
#TEST-3-Empty username / Password
#TEST-4- Empty poassword
#TEST-5- Missing required parameter 
                    AUTHENTICATION TOKEN ANALYSIS
After sussesful login, find arequest that requries authentication.
Authorization: Bearer <token> or session cookie
                                 LOGOUT
Login-> Capture authentication request-> Logout
Take the previously captured authentication request and resend it, observe whether the server still considers the session valild. 
Don't automatically assume the result is a vulnerability ; session behavior depends on the application's architecture and token design.











