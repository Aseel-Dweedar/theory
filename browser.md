- **What happens when you type a site in the browser and hit enter**

  https://aws.amazon.com/blogs/mobile/what-happens-when-you-type-a-url-into-your-browser

- **What devtools do you use in the browser; what do you do with them?**

  console, network, … etc(the default ones not the installed)

- **What is the “same-origin policy”?**

  a web browser permits scripts contained in a first web page to access data in a second web page, but only if both web pages have the same origin

- **What are sockets?**

  A socket is one endpoint of a two way communication link between two programs running on the network.

  [sockets](https://docs.oracle.com/javase/tutorial/networking/sockets/definition.html)

- **How does the server differ between requests from two different clients? or multiple connections from a single client?**

  **_Two requests cannot use the same port._**

  When the client connects with an unbound socket, the TCP stack will choose a port number that's not currently in use, and assign it to that connection. When it sends a request to the server, the server will reply to the port number that got assigned. On the client-side, the TCP stack will look at the port number in the packet, and route it to whichever process was assigned that port number.
