TRACING 
1) You press enter on http://tyler.test:8000
2) The resolver checks /etc/hosts for the domain name
3) The resolver translates the cached domain name into the IP address (127.0.0.1)
3.5) The browser connects to 127.0.0.1 on port 8000
4) The computer then does a GET HTTP/1.1 with Host: tyler.test:8000 to the server
4.5) The server finds index.html
5) The server responds with content that have specific feilds such such as status codes
and content types
6) The computer recieves the rresponse  and renders it acccordingly 
7) Any extra things the computer needs to properly render the page, it request
