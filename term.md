# What is HTTP?
Hypertext transfer protocol is how clients get data from a server or send data to a server.

## What is a URL?
Uinform Resources Locator,is the address of a unique resource on the internet. It is one of the key mechanisms used by browsers to retrieve published resources, such as HTML pages, CSS.

### What is DNS?
Domain Name System associate names like www,mike.com with a corresponding address the computer uses the DNS to lookup domain names and get the  domain names and get the assigned IP address which is used to connect  your computer to the destination on the internet.

### What is a query string?
A query string  allows you to pass additional information to a web application or backend database. The query string contains key-value pairs separated by ampersands (&).

- What are two HTTP verbs and how are they different?
-Get: Retriving data from the server such as clicking a link and seaching forms submission without side effect

- POST - send some data to the server such as email, charging credit cards and with side effect.

- What is an HTTP request?
get request is sometimes use to send request from web browser to servers without side effect(www.facebook.com)

#### What is an HTTP response?
post request is with side effect usually from server to browser.(HTML,JS & CCS)

#### What is an HTTP header? Give a couple examples of request and response headers you have seen.
- Headers provide additional information about the request or the response. 
the examples are stated below
- Request headers: Host, User-Agent, Accept, Cookie, Cache-Control
- Response headers: Content-Type, Last-Modified, Set-Cookie, Cache-Control


#### What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?What is HTTP?
1. Your browser “resolves” the name into an IP address using DNS
2. Your browser makes a request to that IP address, including headers info about browser.
3. The server sends a response  with a status code such as: 200 if it was sucessful, 301 if request is elsewher, 404 if request isn't found and 500 when the server has internal problem.
4. The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
5. The browser makes separate HTTP requests for those resources and receives response from the server for each