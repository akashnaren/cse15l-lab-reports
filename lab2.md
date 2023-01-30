# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 2: Servers and Bugs 
---
Objective: Write code for a web server
---
**Part 1**
---
So before I delve into the steps of the assignment, I want to preface that there will be uses of files from the wavelet github files. Particularly the Server.java file. This file sets up an HTTP server in Java using Java's built-in HttpServer. The code creates a class "Server" which starts the HTTP server on the specified port and has a single endpoint, "/", handled by the "ServerHttpHandler" class. The "ServerHttpHandler" class takes in an implementation of the "URLHandler" interface and uses it to handle incoming HTTP requests. The "URLHandler" interface defines a single method, "handleRequest", which takes a URI and returns a string. The returned string is then sent as a response to the HTTP request. 

Back to the assignment though, the main goal in Part 1 is to Write a web server called StringServer that supports the path and behavior as described in the lab write up. 
---
**Step 1:**

