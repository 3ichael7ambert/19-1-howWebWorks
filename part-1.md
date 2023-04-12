## **Part One: Solidify Terminology**

In your own terms, define the following terms:

- What is HTTP?
HTTP stands for Hypertext Transfer Protocol. It is used for transmitting data over the internet. 
It is the foundation of the World Wide Web.

- What is a URL?
URL stands for Uniform Resource Locator. It is the address that identifies a web page on the internet. 
It contains information about the protocol to be used, the server name, and the path to the resource.

- What is DNS?
DNS stands for Domain Name System.
Its the system that translates the domain name into an IP address

- What is a query string?
A query string is a part of a URL that contains additional information that the server can use to respond to a request. 
It normally has a ? in the url link that is used to query and search a database on a server.

- What are two HTTP verbs and how are they different?
Two HTTP verbs are GET and POST. GET is used to retrieve data from the server, while POST is used to submit data to the server for processing.

- What is an HTTP request?
An HTTP request is a message sent by a client to a server, asking it to perform an action. 
It contains a URL, and some additional information such as values entered in a search form client side to retrieve data from the host or server.

- What is an HTTP response?
An HTTP response is a message sent by a server to a client in response to an HTTP request.
if the search (request) was 'potatoes' on the google image search, the response would be a series of potatoe pictures (unless a timeout occured then a 404 would be the response).

- What is an HTTP header? Give a couple examples of request and response headers you have seen.
An HTTP header is a part of an HTTP message that provides additional information about the message. 
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers


- What are the processes that happen when you type “[http://somesite.com/some/page.html](http://somesite.com/some/page.html)” into a browser?
When you type "http://somesite.com/some/page.html" into a browser, the browser sends an HTTP GET request to the server specified in the URL (GET or Requesting the page.html in the 'some' directory on the IP address/server of somesite.com), asking for the resource at the specified path. The server will either respond with page.html and load it into the DOM or we will get a 404 error if anything about the url is wrong (DNS/URL,directory, filename/type)