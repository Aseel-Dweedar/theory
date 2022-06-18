- **What happens when you type a site in the browser and hit enter**

  https://aws.amazon.com/blogs/mobile/what-happens-when-you-type-a-url-into-your-browser

- **What devtools do you use in the browser; what do you do with them?**

  console, network, … etc(the default ones not the installed)

- **What is the server side rendering and a single web page app** (Diversity group interview)

  https://www.youtube.com/watch?v=Kg0Q_YaQ3Gk&t=318s

- **What is the “same-origin policy”?**

  URL-originn (protocol, (sublevel , domain name, toplevel), port).
  
  ![url-origin](/img/url.png)

  same-origin policy: a web browser permits scripts contained in a first web page to access data in a second web page, but only if both web pages have the same origin

- **What is CORS?**

  Cross-origin resource sharing (CORS) is a mechanism that allows restricted resources on a web page to be requested from another domain.
  
  [CORS](https://www.youtube.com/watch?v=tcLW5d0KAYE&t=500s)

- **what is local storage ?**

  properties allow to save key/value pairs in a web browser with no expiration date. The data will not be deleted when the browser is closed. The localStorage property is read-only.

- **What are sockets?**

  A socket is one endpoint of a two way communication link between two programs running on the network.

  [sockets](https://docs.oracle.com/javase/tutorial/networking/sockets/definition.html)

- **How does the server differ between requests from two different clients? or multiple connections from a single client?**

  **_Two requests cannot use the same port._**

  When the client connects with an unbound socket, the TCP stack will choose a port number that's not currently in use, and assign it to that connection. When it sends a request to the server, the server will reply to the port number that got assigned. On the client-side, the TCP stack will look at the port number in the packet, and route it to whichever process was assigned that port number.

- **Mention some of web APIs**

  ![web-API](/img/webAPI.png)