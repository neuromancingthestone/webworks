- What is HTTP?
Hypertext transfer protocol - it's the protocol that serves web pages
- What is a URL?
Uniform resource locator - it's the entire web site string that serves to find a web site and data
- What is DNS?
Domain Name System - a series of servers that parse a web site name/URL to provide the IP address.
- What is a query string?
Allows data to be passed with a URL
- What are two HTTP verbs and how are they different?
GET - serves a request for a site with no changes
POST - serves a site request with changes
- What is an HTTP request?
A server request on a specific port to get web site data
- What is an HTTP response?
The servers response to that request
- What is an HTTP header? Give a couple examples of request and response headers you have seen.
Passes data along with a HTTP request
Request URL:
https://developer.mozilla.org/en-US/
Request Method:
GET
Status Code:
304 Not Modified
Remote Address:
34.111.97.67:443
Referrer Policy:
strict-origin-when-cross-origin

Request URL:
https://icanhazdadjoke.com/
Request Method:
GET
Status Code:
200 OK
Remote Address:
172.67.198.173:443
Referrer Policy:
strict-origin-when-cross-origin

- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
A ton of stuff happens. HTTP request sent over web. DNS breaks it down to IP. Sent to actual server. The server breaks down the URL into the headers, data, everything it needs. It begins to serve the page using that data. Sends back the formed page.
