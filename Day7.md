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

#### HTTP (Hypertext Transfer Protocol)
- **What is HTTP?**: It's the foundation of data communication on the web. It defines how clients (like browsers) request resources from servers and how servers respond.
- **What is HTTPS?**: An encrypted version of HTTP, secured using SSL/TLS certificates.
- **URL (Uniform Resource Locator)**: A web address that specifies the protocol (HTTP/HTTPS), domain, and resource path (e.g., https://example.com/page).
- **Making a Request**: Browsers send HTTP requests (GET, POST, etc.) to servers.
- **HTTP Methods**: Common methods include GET (retrieve data), POST (send data), PUT (update data), DELETE (remove data).
- **HTTP Status Codes**: Numeric codes (e.g., 200 OK, 404 Not Found) indicating the server's response.
- **Cookies**: Small pieces of data stored by browsers to remember user sessions.



