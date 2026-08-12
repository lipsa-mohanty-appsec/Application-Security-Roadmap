# Day 6 Interview Questions:-
##What is Burp suite?
  Answer: Burp Suite is a tool which is used to do security scanning for mobile application, web application , API Testing and to perform penetration testing for web applications. 
##Why do AppSec Engineers use Burp Suite instead of browser DevTools?
  Answer: AppSec engineers use Burp Suite instead of browser DevTools because Burp Suite acts as an intercepting proxy that lets them view, modify, and replay any HTTP/S traffic between an app and server, whereas DevTools only inspects what a single local browser renders or sends.
##Difference between Dev Tool and Burp Suite?
  Answer: Feature                    Browser Dev Tool                                                             Burp Suite
      Primary Purpose          Website building, UI styling, and front-end debugging          Security auditing, hacking, and vulnerability scanning
      How it Operates          Built inside the browser engine                                Acts as a separate proxy server intercepting network traffic
      Traffic Interception     Cannot easily pause traffic before it leaves the browser       Can intercept traffic, change it mid-air, and then send it
      Automation               Highly manual; built for one-off request replays               Highly automated; scans, brute-forces, and fusses endpoints
##What is intersepting Proxy?
  Answer: An intercepting proxy is a specialized middleman server that sits between a client device (like a web browser or mobile app) and a target web server. It captures network traffic—typically HTTP or HTTPS—allowing a user to inspect, pause, change, or drop data packets in real time before they reach their destination.
##What is HTTP History and why it is useful?
  Answer: History tracks how web communication evolved from a simple 1991 text-transfer method into modern, fast, and secure versions like HTTP/2 and HTTP/3. Knowing this history helps engineers fix network slow-downs, secure user data, and build better web apps.
  HTTP history is useful because 
  Performance Tuning: Knowing how multiplexing (HTTP/2) fixes head-of-line blocking helps you design fast-loading sites.
  Troubleshooting: Tracing how errors or headers changed from 1.0 to modern standards helps debug network traffic.
  Security Awareness: Understanding how plain-text HTTP grew into encrypted HTTPS protects users from data theft.
##What is Repeater?
  Answer: Burp Repeater is a manual testing tool in Burp Suite that lets you capture, modify, and resend individual HTTP or WebSocket requests as many times as you want. It helps you see how a server responds to different changes without intercepting live browser traffic every time.
##What types of request do you expect to see after logging into a web application?
  Answer: After logging into a web application, you send and receive requests to manage your session, load data, and perform actions. The application uses secure cookies, tokens, and API calls to keep you verified and load your dashboard.
##How would you verify the authentication is working correctly?
  Answer:To verify that user authentication is working properly, test positive login flows with valid credentials, negative flows with invalid passwords or expired tokens, session persistence, and security edge cases like rate limiting.
##Why understanding of HTTP impopratant before using Burp?
  Answer: Understanding HTTP is essential before using PortSwigger's Burp Suite because Burp Suite is fundamentally an HTTP/HTTPS interception proxy. Without a solid grasp of HTTP, you cannot interpret or manipulate the data Burp Suite captures.Burp Suite intercepts and displays raw network traffic. If you do not understand HTTP components, you will see a wall of meaningless text. You must know how to read.
##Why do Appsec engineers map an application before testing it?
  Answer: Mapping an application before security testing helps the tester find hidden entry points, understand data flow, and spot weak areas. This step builds a complete picture of the target. It makes sure no hidden pages or forgotten features get missed during the scan.
##What information do you collect during reconnaissance?
  Answer: During reconnaissance, security professionals and threat actors collect intelligence about a target's digital footprint, network infrastructure, and personnel to map out the attack surface. This phase involves gathering both public data and technical system details to identify potential entry points.
##Why shouldn't you immediately start running scanners?  
  Answer:
##Why Burp Suite is the most important tool for web application testing?
  Answer: Burp Suite is the top choice for web testing because it acts as an easy-to-use middleman between your browser and the web app. It lets you catch, change, and test web traffic in real time. It mixes manual tools with smart automated scanners to find hidden security holes fast
##Difference between proxy and repeater?
  Answer: A proxy sits in the middle of live traffic as a gateway to intercept, inspect, or change requests and responses in real-time. A repeater is a manual testing tool used to take a captured request, change it, and send it over and over again to see how a server reacts.
##If a login page is found, what would you test next?
  Answer: When you find a login page, test next for authentication flaws, input validation issues, and session management weaknesses to see if an attacker can bypass controls or gain unauthorized access.
