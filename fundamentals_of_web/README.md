# Introduction to the web

![image info](https://static.studytonight.com/servlet/images/client-server-architecture.jpg)

<b>
The Web consists of billions of clients and servers connected through wires and wireless networks. The web clients make requests to web servers. The web server receives the request, finds the resources, and return the response to the client. When a server answers a request, it usually sends some type of content to the client. The client uses a web browser to send requests to the server. The server often sends responses to the browser with a set of instructions written in HTML(HyperText Markup Language). All browsers know how to display HTML page to the client.
</b>

#

### Web Application

A website is a collection of static files (webpages) such as HTML pages, images, graphics etc. A Web Application is a website with dynamic functionality on the server. Google, Facebook, Twitter are examples of web applications.

### HTTP (Hypertext Transfer Protocol)

HTTP is a protocol that clients and servers use on the web to communicate.
It is similar to other internet protocols such as SMTP (Simple Mail Transfer Protocol) and FTP (File Transfer Protocol) but there is one fundamental difference.
HTTP is a stateless protocol - i.e, HTTP supports only one request per connection. This means that with HTTP the clients connect to the server to send one request and then disconnects. This mechanism allows more users to connect to a given server over a period of time.
The client sends an HTTP request and the server answers with an HTML page to the client, using HTTP.

![image info](https://static.studytonight.com/servlet/images/http-request-response.jpg)

#

### HTTP Methods

HTTP request can be made using a variety of methods, but the ones you will use most often are Get and Post. The method name tells the server the kind of request that is being made, and how the rest of the message will be formated.

- [OPTION] -> Request for communication options that are available on the request/response chain.

- [GET] -> Request to retrieve information from server using a given URI
- [HEAD] -> Identical to GET except that it does not return a message-body, only the headers and status line.
- [POST] -> Request for server to accept the entity enclosed in the body of HTTP method.

- [DELETE] -> Request for the Server to delete the resource.
- [CONNECT] -> Reserved for use with a proxy that can switch to being a tunnel.

- [PUT] -> This is same as POST, but POST is used to create, PUT can be used to create as well as update. It replaces all current representations of the target resource with the uploaded content.

For more info

[WikiPedia](https://en.wikipedia.org/wiki/World_Wide_Web#:~:text=The%20World%20Wide%20Web%20(WWW,the%20world's%20dominant%20software%20platform.)
