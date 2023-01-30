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
In Step 1, I want to first show the code that I ended up making for my `StringServer`. I want to explain my code to make sure that as future readers, you will be able to understand the components that make up my code as you see my code. 

Here is my code for the StringServer.java file:
```
import java.io.IOException;
import java.net.URI;

class Handler implements URLHandler {
    // The one bit of state on the server: a number that will be manipulated by
    // various requests.
    String message = "";

public String handleRequest(URI url) {
    if (url.getPath().contains("/add-message"))  {
        String[] parameters = url.getQuery().split("=");
        if (parameters[0].equals("s")) 
        {
            message += parameters[1] + "\n";
            return message;
        } 
    } 
        return "404 Not Found!";
    }
}


class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new Handler());
    }
}

```

Here is my code and if it looks confusing, here is a little breakdown to clear anything up. 

First, this code sets up a simple string server using the HTTP server created in the previous code. The "Handler" class implements the "URLHandler" interface and defines the "handleRequest" method. This method checks if the path of the incoming URI contains "/add-message", and if it does, it splits the query part of the URI into key-value pairs and adds the value to a "message" string if the key is "s". Finally, it returns the updated "message" string. If the path does not contain "/add-message", the method returns a "404 Not Found!" error message.

The "StringServer" class takes the first command line argument as the port number, starts the server using the "Server.start" method, and passes in a new instance of the "Handler" class as the URL handler. If the port number is not provided as a command line argument, it prints a message to provide one.


As stated in the next step of the lab, here are two screenshots of using `/add-message`, 
