## Building Webserver using Nodejs

### Which of the following statement(s) are true about the C10M problem?

    I. It can be solved using nodejs as a webserver. 
    II. App developer has to optimize the code, even if nodejs is used as a server.
    III. Only one machine is enough to handle the request, we can scale it vertically.
    IV. Multiple machines sitting behind a load balancer is required, we scale it horizontally.

    a. All the statements are true
    b. I, II
    *c. II, IV
    d. IV

### Which statement is true about a Web Server?

    a. It communicates over HTTP protocol.
    b. Nodejs alone can be used as a web server in production deployment.
    c. Web server is used to serve static resources (HTML, pdf, images)
    d. b and c are true
    *e. only b is false, rest are true

### A web page keeps on loading, without any end, then the request times out, what could be the reason. Assume, there is no network error.

    a. There is some internal server error.
    *b. Request - Response cycle in not ended. (res.end is not called explicitly)
    c. Database connection error.
    d. None of the above

### What does the status code 500 signify?

    a. Route not found
    b. Network error
    *c. Internal server error
    d. Unauthorized access

### What is true about a Request Handler?

    a. It's a middleware function
    b. It bootstraps the server to listen on a particular port
    c. It has access to the request and the response objects
    d. All the correct
    e. Only a and c

### How to handle errors when starting a node server? 

    a. Using try/catch blocks
    b. Using Error callbacks
    c. By listening to 'error' event on server
    d. By listeining to 'connection' event on server

### Which npm module in Nodejs is used to test server response?

    a. mocha
    b. superagent 
    c. supertest
    d. chai

### Given a url, http://www.my-awesome-webapp/myfiles?name=abcd&city=xyz, and nodejs url module, how'll you get hold of query strings, name and city?

    a. url.parse(req.url, true).query
    b. url.parse(req.url, false).query
    c. url.parse(req.url, true).pathname
    d. url.parse(req.url, false).pathname





