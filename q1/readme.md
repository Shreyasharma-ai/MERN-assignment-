When we type a URL (Uniform Resource Locator) into a web browser and press Enter, several steps take place before the webpage appears on the screen.

1. URL Entry:
The process begins when the user enters a URL, such as https://www.example.com, into the browser's address bar and presses Enter.

2. Browser Cache Check:
The browser checks its cache to see whether it already has the required resources stored locally. If the resources are available and valid, the browser may reuse them.

3. DNS Lookup:
The browser uses the Domain Name System (DNS) to translate the domain name into an IP address so that it can locate the web server.

4. Establishing a Connection:
The browser establishes a connection with the web server. For HTTPS websites, it also performs a TLS handshake to establish secure, encrypted communication.

5. Sending an HTTP Request:
The browser sends an HTTP request to the server, asking for the required webpage and its resources.

6. Server Response:
The server processes the request and sends an HTTP response containing a status code, such as 200 OK, along with the requested content, usually HTML.

7. Parsing HTML and CSS:
The browser reads the HTML document and creates the Document Object Model (DOM). It also processes CSS to create the CSS Object Model (CSSOM). During this process, it discovers additional resources, such as images, fonts, stylesheets, and JavaScript files, and requests them when needed.

8. Creating the Render Tree:
The browser combines the DOM and CSSOM to create a render tree, which contains the visible elements and their styles.

9. Layout and Painting:
The browser calculates the size and position of elements on the page. It then paints the text, images, colors, and other visual elements onto the screen.

10. JavaScript Execution:
Finally, JavaScript executes as required to make the webpage interactive. It can also modify the page's content and appearance.

Conclusion

When we type a URL and press Enter, the browser performs several steps involving DNS, network connections, HTTP requests, server responses, and page rendering. These processes work together to display the requested webpage on the screen