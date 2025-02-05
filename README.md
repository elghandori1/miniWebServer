Steps to Run :

1 ------ Clone the repository :

 + git clone <your-repo-link>
 + cd <your-repo-name>

2 ------ Compile the server :

 + using command :  make && ./web_server

3 ------ Open in browser :

 + Visit http://localhost:8080 to view the served pages.

--------------------------------------------------------

! --- Important Considerations:

Security: This is a very basic server and is not suitable for production use. It lacks many security features.
Error Handling: The error handling is basic. More robust error checking is needed in a real-world application.
HTTP Parsing: The server does not fully parse the HTTP request. It simply receives the request and sends back the HTML file. 
              A real web server would need to parse the request to handle different HTTP methods (GET, POST, etc.), headers, and other features.
Concurrency: This server handles one client at a time. For handling multiple clients concurrently, you would need to use threads,
             processes, or asynchronous I/O.

------------------------------------------------------------------------------------------------------------------------------------------------
