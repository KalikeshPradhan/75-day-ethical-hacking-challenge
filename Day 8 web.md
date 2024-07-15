# HTML (HyperText Markup Language)

HTML is the standard language for creating web pages. It describes the structure of a web page using a series of elements and tags. Each element represents a different part of the content, such as headings, paragraphs, links, images, and more.

## Basic Structure of an HTML Document

An HTML document has a specific structure, which includes the following components:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
  <h1>This is a Heading</h1>
  <p>This is a paragraph.</p>
</body>
</html> 

# Components of an HTML Document

## `<!DOCTYPE html>`
This declaration defines the document type and version of HTML. It ensures that the browser interprets the document correctly.

## `<html>`
This tag is the root element of an HTML page. It wraps all other elements in the document.

## `<head>`
The head section contains meta-information about the document, such as the title, character set, styles, scripts, and more.

## `<title>`
The title tag sets the title of the web page, which is displayed in the browser's title bar or tab.

## `<body>`
The body section contains the actual content of the web page, such as text, images, links, tables, and more.

# Common HTML Elements

## Headings
Headings are defined with the `<h1>` to `<h6>` tags. `<h1>` defines the most important heading, while `<h6>` defines the least important heading.

html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
# HTML Elements

## Paragraphs
Paragraphs are defined with the `<p>` tag.

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

# HTML Elements

## Links
Links are defined with the `<a>` tag. The `href` attribute specifies the URL of the page the link goes to.

```html
<a href="https://www.example.com">This is a link</a>

##Images
Images are defined with the <img> tag. The src attribute specifies the path to the image, and the alt attribute provides alternative text for the image.

!Description of the image

##Lists
There are two types of lists in HTML: ordered lists (<ol>) and unordered lists (<ul>). List items are defined with the <li> tag.

#Ordered List:

1. First item
2. Second item
3. Third item

#Unordered List:

- First item
- Second item
- Third item

##Tables
Tables are defined with the <table> tag. A table is divided into rows (<tr>), and each row is divided into cells (<td>). Table headers are defined with the <th> tag.

| Header 1    | Header 2    |
|-------------|-------------|
| Row 1, Cell 1 | Row 1, Cell 2 |
| Row 2, Cell 1 | Row 2, Cell 2 |

##Attributes
HTML elements can have attributes, which provide additional information about the element. Attributes are always specified in the start tag and usually come in name/value pairs like name="value".

#Common attributes include:

id: Specifies a unique id for an element.
class: Specifies one or more class names for an element.
style: Specifies an inline CSS style for an element.
src: Specifies the source file for media elements like images, videos, and audio.
href: Specifies the URL for a link.
Example:

<p id="unique-id" class="text-class" style="color:blue;">This is a styled paragraph.</p>




# Load Balancer

A load balancer distributes network or application traffic across multiple servers. This improves the responsiveness and increases the availability of applications.

## Example Configuration (Nginx)
```nginx
http {
    upstream backend {
        server backend1.example.com;
        server backend2.example.com;
    }

    server {
        location / {
            proxy_pass http://backend;
        }
    }
}


### 3. CDN (Content Delivery Network)

```markdown
# CDN (Content Delivery Network)

A CDN is a network of servers that delivers content to users based on their geographic location, improving load times and availability.

## Benefits
- Reduced Latency
- Improved Load Times
- Scalability
- DDoS Protection

## Example (Using Cloudflare)
1. Sign up for Cloudflare.
2. Point your DNS to Cloudflare.
3. Configure caching rules.


# Databases

Databases store, manage, and retrieve data efficiently. Common types include relational (SQL) and non-relational (NoSQL).

## Example (Using PostgreSQL)
```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100) UNIQUE
);

INSERT INTO users (name, email) VALUES ('Alice', 'alice@example.com');


# What is a Web Server?

A web server is a software or hardware system that serves content to clients over the internet. It handles HTTP requests and responses.

## Popular Web Servers
- Apache
- Nginx
- Microsoft IIS


# Virtual Hosts

Virtual hosting allows a single server to host multiple domains or websites. This enables efficient use of resources.

## Example (Using Apache)
```apache
<VirtualHost *:80>
    ServerName example.com
    DocumentRoot /var/www/example.com
</VirtualHost>

<VirtualHost *:80>
    ServerName example.org
    DocumentRoot /var/www/example.org
</VirtualHost>
