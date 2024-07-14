#### What is DNS?
The Domain Name System (DNS) acts like the phonebook of the Internet. Here's how it works:

1. **Human-Friendly Names**: When you type a website address  into your browser, you're using a human-friendly domain name.

2. **Translation to IP Addresses**: Behind the scenes, DNS translates that domain name into an **IP address** (e.g., 192.0.2.1). Computers use IP addresses to find each other on the network.

3. **Hierarchy**: DNS is organized hierarchically:
   - **Root Servers**: At the top are the **root servers**, which know about all top-level domains (TLDs).
   - **TLD Servers**: Below them are TLD servers (like ".com" or ".org").
   - **Authoritative Servers**: Finally, there are **authoritative servers** for specific domains (e.g., "example.com").

!DNS Hierarchy
#### Domain Hierarchy
- **Domain**: The broadest level in the hierarchy .
- **Subdomain**: A subdivision of a domain (e.g., blog.example.com).
- **TLD (Top-Level Domain)**: The last part of a domain (e.g., .com, .org).

!Domain Hierarchy
#### TLD (Top-Level Domain)
A TLD is the last segment of a domain name (e.g., .com, .org). It helps categorize websites based on their purpose, owner, or geographical area. Examples:
- `.com`: Commercial websites
- `.org`: Non-profit organizations
- `.net`: Network infrastructure
#### Subdomain
A subdomain is a prefix added to a domain name, creating a separate section within the main website. Examples:
- `blog.example.com`: Subdomain for a blog
- `store.example.com`: Subdomain for an online store

!Subdomain Example
#### DNS Record Types
1. **A Record (Address)**: Maps domain names to IPv4 addresses.
2. **AAAA Record**: Similar to A records but for IPv6 addresses.
3. **CNAME Record (Canonical Name)**: Creates an alias for a domain (e.g., maps www.example.com to example.com).
4. **MX Record (Mail Exchange)**: Specifies mail servers for a domain.
5. **TXT Record**: Holds arbitrary text data (often used for SPF records or domain verification).

# HTTP (Hypertext Transfer Protocol)
HTTP is the foundation of data communication on the web. It defines how clients (like browsers) request resources from servers and how servers respond.

## What is HTTP?
HTTP stands for Hypertext Transfer Protocol. It's a set of rules for transferring files (like text, images, and videos) on the web. When you click a link or type a web address, your browser uses HTTP to communicate with the website's server and fetch the content.

## What is HTTPS?
HTTPS is the secure version of HTTP. The "S" stands for "Secure." It uses SSL/TLS certificates to encrypt the data sent between your browser and the server, keeping it safe from eavesdroppers. You'll see HTTPS in the web address bar when a website is secure.

## URL (Uniform Resource Locator)
A URL is a web address. It tells your browser where to find a resource on the internet. A typical URL looks like this: `https://example.com/page`. It includes:
- **Protocol**: (`http` or `https`)
- **Domain**: (`example.com`)
- **Resource Path**: (`/page`)

## Making a Request
When you visit a website, your browser sends an HTTP request to the server. There are different types of requests, such as:
- **GET**: Retrieve data from the server.
- **POST**: Send data to the server.
- **PUT**: Update existing data on the server.
- **DELETE**: Remove data from the server.

## HTTP Methods
Here are some common HTTP methods:
- **GET**: Used to fetch data from the server. Like asking for a web page.
- **POST**: Used to send data to the server. Like submitting a form.
- **PUT**: Used to update existing data on the server.
- **DELETE**: Used to remove data from the server.

## HTTP Status Codes
When a server responds to an HTTP request, it sends a status code to indicate the result. Some common status codes include:

- **200 OK**: The request was successful, and the server is sending the requested data.
- **201 Created**: The request was successful, and a new resource was created on the server.
- **204 No Content**: The request was successful, but there's no content to send back.
- **301 Moved Permanently**: The requested resource has been permanently moved to a new URL.
- **302 Found**: The requested resource is temporarily located at a different URL.
- **304 Not Modified**: The resource hasn't changed since the last request, so the client can use the cached version.
- **400 Bad Request**: The server couldn't understand the request due to invalid syntax.
- **401 Unauthorized**: The request requires authentication. The client must log in.
- **403 Forbidden**: The server understands the request but refuses to authorize it.
- **404 Not Found**: The server couldn't find the requested resource.
- **405 Method Not Allowed**: The request method is not allowed for the requested resource.
- **408 Request Timeout**: The server timed out waiting for the request.
- **429 Too Many Requests**: The client has sent too many requests in a given amount of time.
- **500 Internal Server Error**: The server encountered an unexpected condition that prevented it from fulfilling the request.
- **501 Not Implemented**: The server doesn't support the functionality required to fulfill the request.
- **502 Bad Gateway**: The server received an invalid response from an inbound server.
- **503 Service Unavailable**: The server is currently unable to handle the request due to temporary overload or maintenance.
- **504 Gateway Timeout**: The server, acting as a gateway, didn't receive a timely response from an upstream server.


## Cookies
Cookies are small pieces of data stored by your browser. They help websites remember things like your login status, preferences, and other session information. For example, when you log into a website, a cookie is often used to keep you logged in as you navigate the site.






